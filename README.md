<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Lifecycle</h1>
This lab is a showcase of a day-to-day basis osTicket life cycle and what happends on an average work day.<br/>
* This lab is done using a virtual machine in Azure. Here are my <a href="google.com" styl>lab</a> showcases *

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Prerequisites</h2>

- osTicket Installation (my <a href="https://github.com/tonideeprai/osticket-prereqs">guide</a>.)
- osTicket Configuration (my <a href="https://github.com/tonideeprai/osticket-prereqs">guide</a>.)

<h2>URL (optional)</h2>

These will help you go back and forth between diffferent pages quicker.<br>
- Admin/Analyst Login Page:<br>
<a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a>
- End User osTicket:<br>
<a href="http://localhost/osTicket">http://localhost/osTicket</a>

<h2>Let's get started!</h2>
<h3>Users</h3>
<b>Toni</b>
<ul>
  <li>The Admin user</li>
  <li>Has all authorities and permissions</li>
</ul>
<b>Agents</b>
<ul>
<li>Jane Doe (Dept: SysAdmins, Role: Supreme Admin, Team: Online Banking)</li>
<li>Alex Blues (Dept: Support, Role: Help Desk, Team: no team (he'll be an IT help desk support)</li>
</ul>
<b>Customers</b>
<ul>
  <li>Sarah</li>
  <li>Coby</li>
</ul>
<hr>

<h3>Scenario 1</h3>
<p>Sarah submits a ticket about the entire mobile online banking is down. Alex as a helpdesk will assign the ticket to help Sarah with the problem. </p>

- Sarah submitting the ticket throught the end user site
<p>
  <img width="90%" alt="Screenshot 2024-10-28 at 1 50 59 PM" src="https://github.com/user-attachments/assets/9e8ccf42-45a0-4b9b-8cdc-9c93a619cafa">
  <img width="90%" alt="Screenshot 2024-10-28 at 1 58 19 PM" src="https://github.com/user-attachments/assets/96cd3575-8a5e-4dbd-ab42-9e2e270726c4">
</p>

- Alex observing and assigning ticket's properties (Priority, Department, SLA, Assign to)
<p>
  <img width="90%" alt="Screenshot 2024-10-28 at 3 44 54 PM" src="https://github.com/user-attachments/assets/03c3d9c2-4547-4a9d-bbeb-bebc55f4cf15">
  <img width="90%" alt="Screenshot 2024-10-28 at 3 56 12 PM" src="https://github.com/user-attachments/assets/e297be18-9bc2-4761-9b39-92e1c55346e4">
  <img width="90%" alt="Screenshot 2024-10-28 at 4 07 58 PM" src="https://github.com/user-attachments/assets/2883fd94-6b56-47eb-824e-aafb092e37d5">
</p>

- Working as Jane in Online Banking team to solve the problem
<p>
  <img width="90%" alt="Screenshot 2024-10-28 at 4 14 15 PM" src="https://github.com/user-attachments/assets/2aab888a-bd4f-4331-91b4-53eb9dc628d5">
  <img width="90%" alt="Screenshot 2024-10-28 at 4 18 20 PM" src="https://github.com/user-attachments/assets/19997d09-5386-40ca-a70a-62717d8e6a4a">
</p>

- Jane solving and closing the ticket
<p>
  <img width="90%" alt="Screenshot 2024-10-28 at 4 22 58 PM" src="https://github.com/user-attachments/assets/57906dd8-1817-46bd-8533-812412a0a58c">
  <img width="90%" alt="Screenshot 2024-10-28 at 4 25 28 PM" src="https://github.com/user-attachments/assets/6be42ee4-e20f-44b8-80ed-10f96df1a2d0">
</p>

- Observing the closed ticket with Toni's Admin account
<p>
  <img width="90%" alt="Screenshot 2024-10-28 at 4 31 30 PM" src="https://github.com/user-attachments/assets/996468f9-55dc-493e-813e-1756dcb69d94">
  <img width="90%" alt="Screenshot 2024-10-28 at 4 32 11 PM" src="https://github.com/user-attachments/assets/30e45f9f-7206-405d-9c06-c24beafce028">
</p>
<h3>Scenario 2</h3>
<p>Coby submits a ticket about having problem with Adobe software access. Alex as a helpdesk will support Coby to gather more information and solve the problem.</p>

- Coby submitting the ticket (with little to no information about the problem)
<p>
  <img width="90%" alt="Screenshot 2024-10-28 at 1 50 59 PM" src="https://github.com/user-attachments/assets/751bbdc5-7759-4a1c-a0a6-ac0d89c0ed39">
<img width="90%" alt="Screenshot 2024-10-29 at 9 28 32 AM" src="https://github.com/user-attachments/assets/76b47988-1114-4613-b001-9fb6f71cf4f6">
</p>

- Alex observing and assigning ticket's properties (Priority, Department, SLA, Assign to)
<p>
  <img width="90%" alt="Screenshot 2024-10-29 at 9 29 44 AM" src="https://github.com/user-attachments/assets/ff20ce2c-e862-4878-a54c-ff6fa7cedf73">
  <img width="90%" alt="Screenshot 2024-10-29 at 9 33 01 AM" src="https://github.com/user-attachments/assets/2f133275-a4d0-421d-932f-ad2ef9327833">
</p>

- Alex reaching out to the customer to gather more information about the problem
<p>
  <img width="90%" alt="Screenshot 2024-10-29 at 9 35 39 AM" src="https://github.com/user-attachments/assets/817c8626-5db9-4869-a082-61b399a1ea8a">
</p>

- Alex solving the problem and closing the ticket
<p>
  <img width="90%" alt="Screenshot 2024-10-29 at 9 40 40 AM" src="https://github.com/user-attachments/assets/62dcfa3c-743a-46ff-9df2-635320f89342">
  <img width="90%" alt="Screenshot 2024-10-29 at 9 42 05 AM" src="https://github.com/user-attachments/assets/6a2767fa-d8d0-4741-b29d-14ddb60213bd">
</p>

- Observing the closed ticket with Toni's Admin account
<p>
  <img width="90%" alt="Screenshot 2024-10-29 at 9 44 35 AM" src="https://github.com/user-attachments/assets/da747952-b0d9-4aa2-8a49-71e9aaffb704">
  <img width="90%" alt="Screenshot 2024-10-29 at 9 45 20 AM" src="https://github.com/user-attachments/assets/89d0a386-dd76-46f1-8a70-10706b68d65e">
</p>


