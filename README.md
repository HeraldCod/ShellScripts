# ShellScripts
Shell scripts that automate Linux system administration tasks

Script 1 (addusers.sh)
Goal:- Create a shell script that adds users to the same Linux system as the script is executed on.

1. Enforces that it be executed with superuser (root) privileges.  If the script is not executed with superuser privileges it will not attempt to create a user and        returns an exit status of 1.

2. Prompts the person who executed the script to enter the username (login), the name for person who will be using the account, and the initial password for the account.

3. Creates a new user on the local system with the input provided by the user.

4. Informs the user if the account was not able to be created for some reason.  If the account is not created, the script is to return an exit status of 1.

5. Displays the username, password, and host where the account was created.  This way the help desk staff can copy the output of the script in order to easily deliver the information to the new account holder.

6. Expires the password and prompts for the new password creation at the first login itself.

Script 2 (add_local-user_with_password.sh)
- Feature added - Automatic password generation

Script 3 (add_local-user_with_redirection.sh)
- Feature added - redundant output redirected using the pipe ampersand syntax

Script 4 (disable-local-user.sh)
- Disables local users automatically and archives the home directory

Script 5 (show-attackers.sh)
- Inspects the log files and blocks the IP address with maximum number of failed attempts

Script 6 (run-everywhere.sh )
- Script runs the specified command at a time on all list of servers
