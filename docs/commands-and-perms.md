# Commands and Permissions

## Commands
### /grantx
**Description:** Displays plugin information.</br>
**Aliases:** /grantx info

### /grantx help
**Description:** Shows a list of commands.

### /grantx reload
**Description:** Reloads configuration files.</br>
**Permission:** grantx.reload

### /grantx save
**Description:** Forcibly saves grants data.</br>
**Permission:** grantx.save

### /grantx import
**Description:** Imports ranks from your permissions plugin into GrantX's ranks.yml.</br>
**Permission:** grantx.import

### /grant {player}
**Description:** Grants the specified player a rank.</br>
**Permissions:** grantx.grant</br>
**Parameters:**
- *player* : Any player that has joined the world before.

### /grants {player}
**Description:** View the grant history of the player.</br>
**Permissions:** grantx.grants.view</br>
**Parameters:**
- *player* : Any player that has joined the world before.
</br>

## Standalone Permissions

### grantx.grants.revoke
**Description:** Ability to revoke grants in /grants.
</br>

## Custom Permissions
Players may need to require other permissions to do things. Refer to your configuration files to see the custom permissions for durations, reasons, etc.
