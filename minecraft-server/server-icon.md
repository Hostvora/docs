---
icon: image
---

# Server Icon

## Setting a Server Icon

You can customize your Minecraft server by adding a server icon, which appears in the multiplayer server list for all players. Hostvora makes this process simple with an automatic icon upload tool.

***

### 1. Open the File Manager

1. Log in to the Pterodactyl panel: [**https://panel.hostvora.com**](https://panel.hostvora.com/)
2. Select your Minecraft server.
3. Navigate to the **Files** tab.

At the top of the file list, you will see a button labeled **“Set Icon”**.

***

### 2. Upload Your Icon

1. Click **“Set Icon”**.
2. Choose any image from your device (PNG or JPG recommended).
3. The panel will automatically:
   * Convert the image to the correct file type
   * Resize it to **64x64 pixels** (Minecraft’s required size)
   * Save it as `server-icon.png` in your server files

No manual resizing or renaming is needed.

***

### 3. Restart Your Server

For the icon to appear for players:

1. Go to the **Console**
2. Click **Restart** or run:

```
restart
```

After the restart, your server icon will be visible in the Minecraft server list.

***

### 4. Tips for Best Results

* Choose a clear and simple image — small details may not be visible at 64×64.
* Bright colors often look better in the server list.
* If the icon doesn’t show:
  * Clear your Minecraft client cache
  * Try a full server restart
  * Ensure the icon is named `server-icon.png` (the panel handles this automatically)
