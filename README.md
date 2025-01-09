# Osticket_WorkFlow
This repository provides detailed workflows and guides for using and managing osTicket. It includes  instructions for user account creation, ticket management, and admin tasks

## Prerequisites
 If you have not installed osTicket, click, click [here](https://github.com/ccastro25/Setting_up_osTicket/blob/main/README.md) to get started. 
 If you have not set up roles and the internal hierarchy, click [here](https://github.com/ccastro25/Configuring_osTicket_System/blob/main/README.md) to get started


## Creating a User Account
1. Go to [http://localhost/osTicket/login.php](http://localhost/osTicket/login.php)
2. Click **Create Account**
3. Fill in:
   - Email
   - Full Name
   - (Optional) Phone Number
4. Create a password
![creating user accoutn](https://github.com/user-attachments/assets/b0d814e7-1f4b-47d4-b726-20fbf855e922)

## Admin Giving Access to User
1. Log in as admin
2. In the admin panel, go to the **Users** tab
3. Select the user
4. In the pop-up box, select the **Manage Access** tab
5. Fill in their information
6. Select **Password Reset Required** input
7. Save changes
![admin giving access to user](https://github.com/user-attachments/assets/34caf7f5-ee76-4d9a-8ee0-6713f2530c60)

## User Resetting Password
1. Click **Sign In**
2. Sign in with current credentials
3. Enter current password
4. Enter new password and confirm it
![User resetting passwrod](https://github.com/user-attachments/assets/e53b28ff-ab5e-405a-ba6a-abf07abc59b5)

## User Creating Ticket
1. Under Help Topic select **PC Issues**
2. Enter issue summary
3. Enter message
4. Click **Create Ticket**
![usercreating tickect](https://github.com/user-attachments/assets/ffd489d9-00cd-4715-a3b0-647155c17a4d)

## Assigning Ticket and Changing SLA
1. As an admin, make sure you are in the admin panel
2. Select the **Tickets** tab and then select the ticket
3. View the ticket number and title
4. Below the ticket title, select and change the **SLA Plan** if needed
5. A window will appear
6. Under **SLA Plan**, select the drop-down menu and pick the severity
7. Click **Update**
8. Select **Unassigned**
9. A window will appear
10. Under **Assignee**, select the drop-down menu and pick the agent
11. Click **Assign**
![Assing ticket and changing SLA](https://github.com/user-attachments/assets/1f496ced-6438-4562-832d-d1959df4689e)

## Agent Responding to Ticket Assignment
1. Go to the **Tickets** tab
2. Select the user
3. Respond to the message
4. Post note (note will only be visible to internal members)
![Agent responding to ticket assignment](https://github.com/user-attachments/assets/1488aa47-8656-4bbb-aafe-e0cc97aa6213)

## Admin Responding to Agent and User
1. Admin logs in
2. By default, logged into the Admin panel with the **Tickets** tab selected
3. Click on the corresponding ticket
4. Scroll down and reply to both agent and user
![Admin responding to agent and user](https://github.com/user-attachments/assets/4e4efba6-0df4-442d-85e0-5babe53d167c)

## Agent Giving User Item
1. After giving the user the item
2. Agent logs in
3. By default, the agent is in the **Tickets** tab
4. Select the ticket by clicking on the subject title
5. Enter title for internal note
6. Enter message
7. Click **Post Note**
![agent gave user item](https://github.com/user-attachments/assets/e2432ac3-3c8e-42df-9ce1-f8f8fbeb3811)

## User Received Item
1. User logs in
2. Directed to the **Tickets** tab
3. Reply “Thank you” to the thread
![User recieved Item](https://github.com/user-attachments/assets/30edbe86-480b-40f3-a341-6c083192272d)

## Admin Resolving Ticket
1. Admin logs in
2. Go to the admin panel
3. Select the **Tickets** tab
4. Click on the corresponding ticket
5. Go to **Status** under the ticket title
6. Click **Open**, then select **Resolve**
7. Status window appears
8. Ensure **Resolved** is selected
9. Click **Close**
![Admin resolving ticket](https://github.com/user-attachments/assets/c95cb35a-df95-4e3b-b7a6-51fbed16fe5f)
