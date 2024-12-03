# Help Desk Ticket: Active Directory Background Lock

<h2>Description</h2>
In this help desk ticket: I was asked to use Active Directory to prevent employees from the engineering department from changing their background image without affecting other departments.   
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows GUI</b>

<h2>Environments Used </h2>

- <b>Windows Server 22</b> 
- <b>Windows 11 Enterprise</b> 
<br />
<br />
Help desk ticket.

![1) TICKet](https://github.com/user-attachments/assets/ad31c214-ae84-49e7-a084-9c5205394b1f)

<br />
<br />
Create new Group Policy Object.

![2) create new GPO in engineering](https://github.com/user-attachments/assets/19cc8c0e-360b-4139-940e-79ba74813236)

<br />
<br />
Edit Lock Desktop Background GPO.

![3) created GPO name and edit](https://github.com/user-attachments/assets/89ccd5fa-6a1e-44dc-9751-6f38db2f6ed7)

<br />
<br />
In GPO editor for Lock Desktop Background, navigate to User Config...>Policies>Adminstrative Temp...>Personalization>Prevent changing desktop abckground> right click edit. 

![4) navigate to prevent changing desktop background](https://github.com/user-attachments/assets/f6a5a49e-b838-4d04-b4d6-49461aa6cff9)

<br />
<br />
Select enabled and apply. 

![5) enable and apply](https://github.com/user-attachments/assets/201a4262-86e7-4e95-aae2-e8da53a99b4a)

<br />
<br />
Logged into Engineering User to change background. Settings are locked. 

![6)checked background settings is locked](https://github.com/user-attachments/assets/73bae484-b7ed-45b1-a10c-176772d4de56)

<br />
<br />
