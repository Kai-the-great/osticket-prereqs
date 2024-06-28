# osticket-prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services (IIS)
- Install Web Platform 
- Install MYSQL (set up useranme and password)
- Install C++
- Configure Permissions, Install OS Ticket

<h2>Installation Steps</h2>




 <p>
<img width="482" alt="Screenshot 2024-06-26 at 12 17 38 PM" src="https://github.com/Kai-the-great/osticket-prereqs/assets/173731770/48f763f1-81f2-423b-987b-2ae241dd1210">

<img width="482" alt="Screenshot 2024-06-26 at 12 18 27 PM" src="https://github.com/Kai-the-great/osticket-prereqs/assets/173731770/9db55a23-ee1d-4513-b6d7-4d72ddf8a403">

</p>
<p>
CGI and Common HTTP Features
World Wide Web Services -> Application Development Features ->
[X] CGI
[X] Common HTTP Features
AND IIS Management Console
Internet Information Services -> Web Management Tools -> IIS Management Console
	[X] IIS Management Console
</p>
<br />




<p><img width="482" alt="Screenshot 2024-06-26 at 12 29 27 PM" src="https://github.com/Kai-the-great/osticket-prereqs/assets/173731770/5ca1fa80-6759-4dc6-97e3-a33f3a1a1c4e">

</p>
<p>
Install PHP Manager for IIS AND IIS Rewrite Moduel 2 Setup in order to establish the web platform. Follow the promts and agree to services and agreements.  
</p>
<br />




<p>
<img width="480" alt="Screenshot 2024-06-26 at 12 42 29 PM" src="https://github.com/Kai-the-great/osticket-prereqs/assets/173731770/3e1efd12-5e14-4e83-bf66-b061429ae251">
<img width="500" alt="Screenshot 2024-06-26 at 12 43 43 PM" src="https://github.com/Kai-the-great/osticket-prereqs/assets/173731770/cd52788b-878c-4a83-9dc3-9c877b1506f7">
<img width="500" alt="Screenshot 2024-06-26 at 12 44 02 PM" src="https://github.com/Kai-the-great/osticket-prereqs/assets/173731770/cbd6babd-0154-4ecf-b24f-ed7c1fffc119">



</p>
Download MYSQL and follow these steps; Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->
*Password*





</p>
<img width="464" alt="Screenshot 2024-06-26 at 12 41 17 PM" src="https://github.com/Kai-the-great/osticket-prereqs/assets/173731770/274ef080-46a8-49e0-b784-bdf56fb5d549">

Install Microsoft C++, complete setup wizard.
</p>



<img width="1057" alt="Screenshot 2024-06-26 at 12 49 56 PM" src="https://github.com/Kai-the-great/osticket-prereqs/assets/173731770/2f31dad5-b0c7-47c5-b9f5-ecd0b7897e0e">
<img width="1045" alt="Screenshot 2024-06-26 at 12 59 52 PM" src="https://github.com/Kai-the-great/osticket-prereqs/assets/173731770/ddd4e67f-25c1-473f-99fc-65314a2e94de">

Go back to IIS, sites -> Default -> osTicket
Enable: php_imap.dll
Enable: php_intl.dll
Enable: php_opcache.dll
Refresh the osTicket site in your browser



<br />
