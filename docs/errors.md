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
**Description:** Failed to hook into Vault. </br>
**Cause:** Vault was not installed/enabled or your permissions plugin is non-existing/disabled.</br>
**Effect:** Plugin will disable.</br>
**Fix:** Install Vault and a supported permissions plugin or fix the plugins, and restart.

## Code 4
**Description:** Grant/expiry/revoke commands not set. </br>
**Cause:** The "commands-executed-on" section in your settings.yml is not set up.</br>
**Effect:** Plugin will disable.</br>
**Fix:** Install a stable permissions plugin such as LuckPerms, UltraPermissions, or PermissionsEx and restart, or set up the commands manually and restart.

## Code 6
**Description:** Failed to send title. </br>
**Cause:** Unsupported server version or corrupt server JAR. </br>
**Effect:** Title will not be shown, or will be partially shown to the player.</br>
**Fix:** Contact Demeng7215 with the stack trace (error).

## Code 7
**Description:** Missing configuration values. </br>
**Cause:** Something is missing in one of your configuration files. Perhaps you mispelled a key or deleted one by accident? </br>
**Effect:** Plugin breaks. Things don't function like they supposed to, messages are deformed, errors spamming everywhere.</br>
**Fix:** Undo your changes, fix your errors, or reset configurations back to defaults.

## Code 8
**Description:** Failed to log information. </br>
**Cause:** One of your log files have been deleted or cannot be accessed. </br>
**Effect:** Information will not be logged. </br>
**Fix:** Restart the server or (if applicable) fix permissions so that GrantX can access the files.

## Code 9
**Description:** Online player returned offline. </br>
**Cause:** Someone logged out, crashed, or could not be found unexpectedly. </br>
**Effect:** Nothing. Can be ignored. </br>
**Fix:** Ignore.

## Code 10
**Description:** Failed to connect to MySQL. </br>
**Cause:** GrantX couldn't access your database. Incorrect credentials? Permissions issue? </br>
**Effect:** Plugin will be disabled. </br>
**Fix:** Fix your database or try again later.

## Code 11
**Description:** Failed to save data. </br>
**Cause:** Your data storage system is experiencing an issue. Could be a connection issue for SQL? Missing file for flat? </br>
**Effect:** Data will not save, or will save in a corrupt format. </br>
**Fix:** Fix your database if using MySQL and make sure your data.yml is fine.

## Code 12
**Description:** Failed to establish connection. </br>
**Cause:** Invalid/blocked internet connection whilst performing external tasks (checking for updates). </br>
**Effect:** Nothing, just no update notifications. </br>
**Fix:** Ignore or fix internet.

## Code 14, 15, 16, 17
**Description:** You either know why this happened or you don't. </br>
**Effect:** Plugin will be disabled. </br>
**Fix:** If you don't know why this happened, contact Demeng7215 ASAP.

## Code 18
**Description:** Invalid license key.</br>
**Cause:** Your license key has expired, been revoked, or is no longer valid.</br>
**Effect:** Plugin will be disabled. </br>
**Fix:** If you don't know why this happened, contact Demeng7215 ASAP.
