# Tableau_ServerBackup - Powershell Script to do some Housekeeping Job
Hi All, Hope the below-mentioned steps will help you to set up the tableau Server Back up and HOuse cleaning activity. Code involves the below activity:
1. Run script to collect Daily Backup
2. Store a copy of the backup file to Network location (another Server)
3. Delete the Historical file (Older than 4 days) to save the space
4. Send a completion mail to intended audience 
Save the script named as Server_Backup.ps1 (Powershell script) and scheduled it to run during off-peak hours
