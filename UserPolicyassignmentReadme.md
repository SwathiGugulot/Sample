# User Policy Assignment
# Description:
UserPolicyAssignment script will work for assigning custom user policies for N no.of users.\
To run the script first you need to install the [SFB online connector](https://www.microsoft.com/en-us/download/details.aspx?id=39366)
- import the Module into windows powershell 
- get the script from the 'UserPolicyAssignment.ps1' file and paste it in windows powershell, then run the script.
- Script has all the avaialble policies to user listed below, please provide the requried input from 1 to 12 to apply the policy. 

                      1- TeamsAppSetupPolicy 
                      2- TeamsMeetingPolicy 
                      3- TeamsCallingPolicy
                      4- TeamsMessagingPolicy 
                      5- BroadcastMeetingPolicy
                      6- TeamsCallParkPolicy
                      7- CallerIdPolicy 
                      8- TeamsEmergencyCallingPolicy 
                      9- TeamsEmergencyCallRoutingPolicy
                      10-VoiceRoutingPolicy 
                      11-TeamsAppPermissionPolicy 
                      12-TeamsDailPlan
- select one policy from the above list to assign the user.

# Example
In the list of policies ,if you select one policy that will assign to provided user.
# Input 
 provide the UserPricipleName in Input.Csv file.
# Output
The selected policy will assigned to the user.








