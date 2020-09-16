# User As Teams Owner
# Description:
 Script will provide the teams details where user as owner for the team in your organization. 
1. As an Administrator, type PowerShell in the start menu. Right-click Windows PowerShell, then select Run as Administrator.
Click Yes at the UAC prompt.

2. Type the following within PowerShell and then press Enter:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**`Install-Module MicrosoftTeams`**
  
3. Type Y at the prompt.Press Enter.

4. If you are prompted for an untrusted repository,then type A (Yes to All) and press Enter.The module will now install. 

Run the script please provide the global administrator credentials or Teams admin credentials.
- script will prompt you for input user,provide the input to proceed.
- to connect to microsoftteams provide the administrative credentials.
-script will get the teams details where user as owner for the team in your organization. 
-exports details to a output.csv file.

# Example 
if a user is associated to a team as owner, this script will get that team details and export it in .csv file.
# Parameters
1. User : the user whom you want to get the data.
# Output
 The details of teams will stores in output.csv file.

