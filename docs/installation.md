# Installation

## Prerequisites
* Java 8 or above.
* Spigot or a Spigot-forked JAR such as Paper/TacoSpigot running anywhere between MC 1.8.x-1.16.x.
* Basic knowledge on how to operate Minecraft servers.

## Dependencies
* [Vault](https://dev.bukkit.org/projects/vault)
* A permissions plugin supporting Vault, such as [LuckPerms](https://www.spigotmc.org/resources/28140/) (recommended).

## Instructions
1. Download GrantX [here](https://demeng.dev/grantx) after purchasing if you haven't already.
2. Move the JAR file to your server's "plugins" directory.
3. Install all dependencies and configure your groups in your permissions plugin if you haven't already.
4. Restart your server.
5. Several files will be generated in the "GrantX" directory, including a logs folder, settings.yml, messages.yml, style.yml, ranks.yml, durations.yml, reasons.yml, and data.yml.
6. If you DID NOT buy from SpigotMC, you must set the "license-key" field in settings.yml. Join our [Discord](https://demeng.dev/discord) and create a ticket if you don't have a key.
7. Go to settings.yml's "commands-executed-on" section and set everything up. Comments explain what to do.
8. Input your MySQL credentials and information in data.yml if you would like to use MySQL storage, or skip this step if you would like flat file storage.
9. Restart your server.
10. After making sure GrantX enables successfully at least once, go to ranks.yml and follow the example rank format to make your own ranks, or run */grantx import* to import the ranks from your permissions plugin automatically.
11. Make any other changes in other configuration files (optional).
12. Restart or run the */grantx reload* command to activate your changes.
13. Enjoy! Need more help? Join our [Discord](https://demeng.dev/discord).
