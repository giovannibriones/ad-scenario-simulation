<p align="center">
<img alt="1" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/682741e6-6b28-4cc1-aea7-c39b5c242018"/>

</p>

<h1> On-premises Active Directory Deployed in the Cloud (Azure) (Part 4) </h1>


<p>In this fourth and final part of this tutorial, various situations will be simulated to enhance understanding of user provisioning, administration, and problem-solving within Active Directory.</p>

<h2>Prerequisites</h2>

- <a href="https://github.com/giovannibriones/ad-and-azuresetup"> On-premises Active Directory Deployed in the Cloud (Azure) (Part 1) </a>
- <a href="https://github.com/giovannibriones/ad-deployment-configuration"> On-premises Active Directory Deployed in the Cloud (Azure) (Part 2) </a>
- <a href="https://github.com/giovannibriones/ad-user-generation">On-premises Active Directory Deployed in the Cloud (Azure) (Part 3) </a>

<h2>Main Objectives</h2>

<h4>Situation Simulation</h4>

- Participate in practical simulations of a variety of situations, such as password resets, group membership changes, and account deactivations.

<h4>Troubleshooting Situations</h4>

- Develop troubleshooting skills by simulating situations where users are confronted with access issues, and learn to identify and resolve these challenges effectively.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (22H2)



<h1>Situations</h1>

<h3>&#9312; User Account Creation </h3>

<h4>Background:</h4>

<p>A new software developer, John Smith, has been hired to join the IT department at your company. As part of the onboarding process, the IT help desk needs to create a new user account for John in Active Directory.</p>

<p><strong>First, create a new user account named "John Smith" with the username "john_smith" and a temporary password.</strong></p>

<img width="324" alt="2" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/218dba86-c290-49ba-9f8c-42839329bf0b">


<p><strong>NOTE: Set the account to require a password change at the next login.</strong></p>


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong> Assign John to the "Developers" security group in Active Directory.</strong></p>

<img width="340" alt="3" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/152726a4-49a0-44d0-b190-f381b23177dd">


<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Then make sure that John's account is found in the proper Organizational Unit (OU) for IT staff.</strong></p>

<img width="340" alt="4" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/5df07577-bc88-40c3-b964-54f86246c627">

<br>
<br>

- Communicate the login credentials and temporary password to John through a secure channel.
- Record the date and time of account creation for auditing purposes.
  
<h4>Considerations:</h4>

- The temporary password should meet the company's password policy standards.
- Make sure that John has the necessary permissions and group memberships to obtain the resources required for his role.

<h3>&#9313; Password Reset </h3>

<h4>Background:</h4>

<p> Sarah Thompson, a marketing executive, contacts the IT help desk reporting that she has forgotten her password and is not able to enter into her computer and email. The help desk needs to help Sarah in resetting her password in Active Directory.</p>

<p><strong> Find Sarah's user account and start a password reset.</strong></p>

<img width="383" alt="5" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/cfaa21b5-0c19-4422-bf9e-958f5baa44ba">



<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Set a temporary password for Sarah that follows the company's password standards.</strong></p>

<img width="383" alt="6" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/24babf1d-94fb-4dd2-8295-84a26d5558a7">


<p><strong>NOTE: Make sure to choose the highlighted boxes to make sure the user’s account is unlocked and cause them to be able to set their own password. </strong></p>

- Communicate the temporary password to Sarah through a secure channel and instruct her to change it immediately after logging in.
- Guide how to change the password using the company's self-service password reset tool if available.
- Record the date and time of account creation for auditing purposes.

<h4>Considerations:</h4>

- Make sure that the chosen temporary password is strong and follows the company's password standards.
- Remind Sarah to update the password on any additional devices or applications where the old password was saved.

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>&#9314; Group Membership Update </h3>

<h4>Background:</h4>

<p>Emma Rodriguez, a systems analyst, has recently been promoted to a managerial role within the IT department. As part of her new responsibilities, Emma now requires access to specific network resources and project folders. The IT help desk needs to update Emma's group memberships in Active Directory accordingly.</p>

<p><strong>Locate Emma's user account and review her current group memberships.</strong></p>

<img width="304" alt="7" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/aa94a703-8dcd-4def-9074-f83f008e98e9">


<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Remove Emma from the "Systems Analysts" group and add her to the "IT Managers" group.</strong></p>

<img width="303" alt="8" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/77a72de0-687e-4813-b491-e278dc4b581b">


<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Make sure that Emma now has the necessary access rights to project folders and relevant network resources.</strong></p>

<img width="600" alt="9" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/e43a00de-6f50-4e00-928a-1ce9cd9ea70f">


- Communicate the group membership update to Emma, along with any additional instructions or changes in access.
- Record the whole process


<h4>Considerations:</h4>

- Make sure that Emma's new group memberships coincide with her managerial responsibilities.
- Communicate the changes to other relevant parties, such as the IT security team, to maintain awareness.
- Make sure that Emma's access permissions are correctly set after the group membership update.

<h3>&#9315; Account Deactivation </h3>

<h4>Background:</h4>

<p>Mark Johnson, a network administrator, has recently resigned from the company. The IT help desk needs to deactivate Mark's user account in Active Directory to prevent unauthorized access and make sire the company resources are secured.</p>

<p><strong>Find Mark's user account and start the account deactivation process.</strong></p>

<img width="421" alt="10" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/052df505-133e-45a0-93e4-9477144cb3ed">


<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Disable Mark's account to prevent further logins while keeping the account details for reference.</strong></p>

<img width="470" alt="11" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/76f7e808-fbb6-4120-bd49-851655c1007c">


<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>You may receive a confirmation dialog; click "Yes" to make sure of the disabling of the user account.</strong></p>

<img width="223" alt="12" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/664127cd-c1bf-4141-92e5-b844b3613b8b">


<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Remove Mark from all security groups to take away his access to network resources.</strong></p>

<img width="295" alt="13" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/d7a8062f-b30a-4551-92cd-be65fe0341c6">


<br>
<br>

<p><strong> Make sure with other relevant departments (e.g., HR) that Mark's departure aligns with company standards and record the whole process.</strong></p>

<h4>Considerations:</h4>

- Ensure a smooth transition of Mark's responsibilities to other team members.

-  Communicate the account deactivation to other departments, such as HR and security, for coordinated efforts.

-  Retain Mark's user account details for historical records and potential future reference.
   
-  Conduct a review of Mark's access rights to identify and update any shared resources associated with his account.

<h3>&#9316; Organizational Unit (OU) Management </h3>

<h4>Background:</h4>

<p>The Sales department has recently went through a reorganization, resulting in the creation of a new team focused on international sales. The IT help desk needs to reflect this change in the Active Directory structure by creating a new Organizational Unit (OU) for the International Sales team and moving relevant user accounts into the new OU.
</p>

<p><strong>Create a new Organizational Unit named "International Sales" within the Sales department's organizational structure.</strong></p>

<img width="323" alt="14" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/f96451e6-d948-44fd-bc62-3079a2b08a55">


<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Transfer the user accounts of team members, such as Alex Turner and Maria Sanchez, to the newly created OU.</strong></p>

<img width="307" alt="15" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/5cb8d6b4-7b29-4379-87f3-6b1df5510ea9">


<img width="305" alt="16" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/c8c73606-a0cb-4db9-8312-52b6c216991d">


<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong> Make sure that the users now appear under the "International Sales" OU in Active Directory.
</strong></p>

<img width="296" alt="17" src="https://github.com/giovannibriones/ad-scenario-simulation/assets/163789590/04aa6c1a-9aab-4398-87ee-e3c1c1617994">


<br>
<br>

<p><strong>Communicate the organizational change to relevant stakeholders, such as department heads and team leaders.
</strong></p>

<h4>Considerations:</h4>

- Make sure that the new OU structure coincides with the company's organizational hierarchy.

- Make sure that the appropriate Group Policy settings apply to the users within the new OU.
  
- Communicate any changes in access permissions or policies resulting from the OU reorganization to the IT security team.



<h2> In Conclusion </h2>

<p>
In summary, Active Directory is essential for managing user accounts and network resources. The situations provided cover common IT help desk tasks, such as creating user accounts, resetting passwords, updating group memberships, and handling account deactivation. These situations serve as practical exercises for training IT personnel and highlight the importance of Active Directory in maintaining a secure and organized digital environment. </p>
