---
description: >-
  Within this page will be a brief breakdown of the Config options and what they
  do
---

# Config File

### Config File breakdown

Below is a breakdown of the configuration file labeled `config.lua` which is within the script/resource root (inside the pu-bt folder)

```lua
Config.Phone = 'qb'
```

The `Config.Phone` option has two inputs for it, either `qb` which will utilise the default QB Phone notifications for the default QB Phone **or** `custom` which will utilise two extra files within the `client` and `server` folder called `notify.lua` refer to the [Phone Notifications](phone-notifications.md) page for more information about that.

Both of these files have 1 event in them that is triggered if the `custom` option is used instead of the default QB Notifications,&#x20;

**NOTE:** that these events MUST exist at all times otherwise the script will error out and no support will be given.

```
Config.Target = vec3(0, 0, 0)
```

The `Config.Target` option is the placement of the Target for the 3 types of Bank Truck job that can be done, to configure this simply paste the chosen coordinates for your desired location within this config option, the rest is handled by the script. (Requires Ox\_Target)

All other configuration options are explained briefly within the `config.lua` file
