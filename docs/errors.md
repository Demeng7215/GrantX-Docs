# Error Codes

## Code 1
**Description:** Failed to load files. </br>
**Cause:** A YAML formatting error in one of your files, or a tampered data.yml file. </br>
**Effect:** Plugin will disable. </br>
**Fix:** Run your configurations through a parser and fix the issues or delete + restart to get back defaults.

## Code 2
**Description:** Configuration files are outdated. </br>
**Cause:** One or more of your configuration files are outdated for your current GrantX version. </br>
**Effect:** Plugin will disable.</br>
**Fix:** Delete + restart to get new defaults or compare the new config to the old and make changes accordingly.

## Code 3
**Description:** Log files could not be created. </br>
**Cause:** The log file for the session could not be created. </br>
**Effect:** Plugin will disable.</br>
**Fix:** Make sure file permissions on your server allow GrantX to access its logs folder and create writeable + readable files.

## Code 4
**Description:** Failed to save data. </br>
**Cause:** Your data storage system is experiencing an issue. Could be a connection issue for SQL? Missing file for flat? </br>
**Effect:** Data will not save, or will save in a corrupt format. </br>
**Fix:** Fix your database if using MySQL and make sure your data.yml is fine.

## Code 5
**Description:** Grant/expiry/revoke commands not set. </br>
**Cause:** The "commands-executed-on" section in your settings.yml is not set up.</br>
**Effect:** Plugin will disable.</br>
**Fix:** Set up your permission plugin's group set/add/remove commands in settings.yml, in the commands-executed-on section.

## Code 6
**Description:** Invalid material name.</br>
**Cause:** A material representation or button icon in ranks.yml or style.yml is invalid. </br>
**Effect:** GUI will not be shown, item will be missing, and/or additional errors.</br>
**Fix:** Check the configuration section of the wiki to see a list of valid material names. Make sure all your materials are available on your server version.

## Code 7
**Description:** Failed to hook into Vault. </br>
**Cause:** Vault was not installed/enabled or your permissions plugin is non-existing/disabled.</br>
**Effect:** Plugin will disable.</br>
**Fix:** Install Vault and a supported permissions plugin or fix the plugins, and restart.

## Code 8
**Description:** Invalid title format. </br>
**Cause:** The custom title(s) you provided in messages.yml are invalid.</br>
**Effect:** Title will not display.</br>
**Fix:** Make sure the title and subtitle are split by a colon (:) like Title:Subtitle.

## Code 9
**Description:** Failed to send title. </br>
**Cause:** Unsupported server version or corrupt server JAR. </br>
**Effect:** Title will not be shown, or will be partially shown to the player.</br>
**Fix:** Contact Demeng7215 with the stack trace (error).

## Code 10
**Description:** Failed to log information. </br>
**Cause:** One of your log files have been deleted or cannot be accessed. </br>
**Effect:** Information will not be logged. </br>
**Fix:** Restart the server or (if applicable) fix permissions so that GrantX can access the files.

## Code 11, 12, 13
**Description:** Rank, duration, or reason not found. </br>
**Cause:** A rank, duration, or reason has has been used before to grant could no longer be found in ranks.yml or style.yml. </br>
**Effect:** Plugin will disable.</br>
**Fix:** Add the rank/duration/reason back to ranks.yml, durations.yml, or reasons.yml and set the slot to -1 to create the entity but not display it in the GUI.

## Code 14
**Description:** Failed to parse default duration. </br>
**Cause:** The default duration you have provided in settings.yml could not be parsed properly. </br>
**Effect:** Plugin will disable.</br>
**Fix:** Make sure the custom duration is in proper format.

## Code 15
**Description:** Invalid license key.</br>
**Cause:** Your license key has expired, been revoked, or is no longer valid.</br>
**Effect:** Plugin will be disabled. </br>
**Fix:** If you don't know why this happened, contact Demeng ASAP.

## Code 16, 17
**Description:** Failed to establish connection with authentication servers. </br>
**Cause:** Invalid/blocked internet connection whilst performing security checks. </br>
**Effect:** Plugin will disable or keep running depending on the situation. </br>
**Fix:** Ignore (if possible) or fix internet.

## Code 18
**Description:** Your plugin/file/account/server has been blacklisted from using GrantX. </br>
**Effect:** Plugin will be disabled. </br>
**Fix:** Usually re-downloading will fix the issue, but if it doesn't, contact Demeng.

## Code 19
**Description:** Failed to check for updates </br>
**Cause:** Invalid/blocked internet connection whilst checking for updates </br>
**Effect:** Nothing, the issue is ignored. </br>
**Fix:** Ignore (not recommended) or fix internet.
