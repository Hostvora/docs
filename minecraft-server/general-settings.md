---
icon: earth-europe
---

# General Settings

## Basic Minecraft Server Management

This section covers the most common tasks for managing your Minecraft server on Hostvora, including giving players OP permissions, enabling the whitelist, and using essential commands.\
All actions can be performed through the Pterodactyl console at [**https://panel.hostvora.com**](https://panel.hostvora.com/).

***

### 1. Giving a Player OP (Administrator Rights)

OP (Operator) status allows a player to execute admin commands such as banning players, changing weather, managing game rules, and more.

#### How to Add OP

1. Open your server in the Pterodactyl panel.
2. Go to the **Console** tab.
3. Enter the following command:

```
op <playername>
```

Example:

```
op Steve
```

#### How to Remove OP

```
deop <playername>
```

***

### 2. Managing the Whitelist

The whitelist allows only specific players to join your server. All other players will be blocked.

#### Enable the Whitelist

In the console, run:

```
whitelist on
```

#### Disable the Whitelist

```
whitelist off
```

#### Add a Player to the Whitelist

```
whitelist add <playername>
```

Example:

```
whitelist add Alex
```

#### Remove a Player from the Whitelist

```
whitelist remove <playername>
```

#### View Whitelisted Players

```
whitelist list
```

***

### 3. Common Minecraft Server Commands

Here are some useful administrative commands you can run in the Pterodactyl console:

*   **Restart the server**

    ```
    restart
    ```
*   **Stop the server**

    ```
    stop
    ```
*   **Ban a player**

    ```
    ban <playername>
    ```
*   **Unban a player**

    ```
    pardon <playername>
    ```
*   **Set the game mode**

    ```
    gamemode <mode> <playername>
    ```

    Modes: survival, creative, adventure, spectator
*   **Change server time**

    ```
    time set day
    time set night
    ```
*   **Change weather**

    ```
    weather clear
    weather rain
    weather thunder
    ```

***

### 4. Accessing and Editing Server Files

You can manage and edit server files directly in the panel:

1. Go to the **Files** tab.
2. Open or edit files such as:
   * `server.properties`
   * `whitelist.json`
   * `ops.json`
3. Save changes and restart the server to apply them.

#### Important Settings in `server.properties`

| Setting        | Description                                       |
| -------------- | ------------------------------------------------- |
| `gamemode=`    | Default game mode for new players                 |
| `difficulty=`  | Peaceful, Easy, Normal, Hard                      |
| `online-mode=` | Should be **true** unless running cracked servers |
| `pvp=`         | Enable/disable player vs. player combat           |
| `white-list=`  | Should be **true** to enable whitelist            |
| `max-players=` | Maximum number of players allowed                 |

***

### 5. Restarting the Server After Changes

Any major settings change (gamemode, whitelist, properties, mods/plugins) should be followed by a restart.

To restart:

1. Go to **Console**
2.  Run:

    ```
    restart
    ```

    or click the **Restart** button in the panel.

***

### 6. Need More Help?

If you run into problems or need help with commands, plugins, mods, or configuration, you can open a support ticket anytime in the Hostvora billing panel.

