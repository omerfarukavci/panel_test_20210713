# User Panel:
User information will be displayed, when the new user button is clicked, the user registration window will open, and the information will be saved when entered.

![Interface](https://lists.office.com/Images/969df1bb-97b6-44ef-9108-dc18a5fd96c2/298428f6-6729-4501-a9de-dcaf554877fe/T1RGZ5H7YQMWKPQXFLFIUG5UQ1/c2f1cb7e-5022-433a-93a2-1ac0b6ec1015)


## Interface:

### 1. New User Button:
When clicked, the user list will scroll to the left and the registration form will open on the right. With the 'New User' header, the following information will be retrieved:
- **Username:** String of max. 10 characters
- **Display Name:** String of max. 20 characters
- **Phone:** String of 10 digits
- **Email:** String separated by '@', ending with '.com', '.net', '.edu' extensions
- **User Roles:** A selectable list
  - **Guest:** Limited authorization
  - **Admin:** Authority to edit users
  - **SuperAdmin:** Access to all panels
- **Enabled:** Checkbox
- **Save User button:** Saves the user

### 2. Hide Disabled User Checkbox:
It will be blank by default. If clicked, disabled users will not be listed.


### 3. User List:
- **ID:** Autoincrement integer
- **User Name:** (Saved)
- **Email:** (Saved)
- **Enabled:** Boolean value will be displayed (Saved) 

