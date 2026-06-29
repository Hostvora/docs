---
icon: puzzle-piece-simple
---

# Plugin Installer

## Installing Plugins Using the Plugin Installer

Hostvora provides an easy-to-use **Plugin Installer** inside the Pterodactyl panel, allowing you to install Spigot, Paper, and Purpur plugins automatically without needing to upload files manually.

***

### 1. Access the Plugin Installer

1. Log in to the panel: [**https://panel.hostvora.com**](https://panel.hostvora.com/)
2. Select your Minecraft server.
3. In the left-hand menu, click **“Plugin Installer”**.

Here you will find a library of available plugins that you can install with just one click.

***

### 2. Browse or Search for Plugins

Inside the Plugin Installer, you can:

* Browse the full list of available plugins
* Use the search bar to find a specific plugin
* View plugin descriptions, versions, and compatibility

The system automatically selects the correct plugin version for your server's Minecraft version when available.

***

### 3. Install a Plugin

1. Click on the plugin you want to install.
2. Review the plugin details.
3. Press the **“Install Plugin”** button.

The panel will:

* Download the plugin
* Place it into the `plugins` folder
* Handle the correct file naming
* Prepare it for the next server restart

No manual file uploads are required.

***

### 4. Restart Your Server

Once installation is complete:

1. Go to **Console**
2. Restart the server using the **Restart** button or by typing:

```
restart
```

After the reboot, the plugin will load and create its configuration files.

***

### 5. Managing Plugin Files

To edit or configure plugins:

1. Go to the **Files** tab
2. Open the `plugins` folder
3. Each installed plugin will have:
   * A `.jar` file
   * A folder containing configuration files

You can edit `.yml` or `.json` configs directly in the panel.

***

### 6. Removing Plugins

To remove a plugin:

1. Go to the `plugins` folder
2. Delete the plugin `.jar` file and its configuration folder
3. Restart the server
