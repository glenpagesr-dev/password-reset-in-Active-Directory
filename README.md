# Watch Me Build The Lab Here

https://www.loom.com/share/67e9403709dd4626ab02b9ee67819859

# password-reset

A hands-on lab demonstrating the setup and configuration of a Password Reset in Active Directory

# Step 1: Open Active Directory Users and Computers
![image alt](https://github.com/glenpagesr-dev/password-reset/blob/9fbd9ce03be85219cbbc30396b75f17ef9cf7483/Pass%20AD%20users.png)
1. From the virtual machine, open the Start Menu.

2. Navigate to Windows Administrative Tools → Active Directory Users and Computers

# Step 2: Locate the User Account
![image alt](https://github.com/glenpagesr-dev/password-reset/blob/54c2d48972d42a0e7667d4fd08a18258f363dbda/user%20account.png)
1. In the ADUC console, browse to the appropriate Organizational Unit (OU).

2. Locate and select the target user account.

# Step 3: Reset the User Password
![image alt](https://github.com/glenpagesr-dev/password-reset/blob/8dbc50ce38dcf2d927b173159880169961a1715b/reset%20password.png)
1. Right-click the selected user account.

2. Select Reset Password from the context menu.

# Step 4: Set the New Password

1. Enter the new password in the New password field.

2. Re-enter the password in the Confirm password field.

3. Ensure both entries match and comply with the organization’s password complexity policies.

# Step 5: Unlock the User Account (If Applicable)

1. If the user account is locked out, select the option to Unlock the user’s account.

2. This step is typically required when multiple failed authentication attempts have triggered an account lockout.

# Step 6: Confirm and Apply Changes

1. Click OK to apply the changes.

   The password reset is processed immediately.

   Outcome

   The user’s password has been successfully reset.

   If selected, the account lockout has been cleared.

   The user can now authenticate using the new credentials.
