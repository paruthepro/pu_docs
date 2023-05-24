---
description: >-
  Within this page a breakdown of the config options will be presented for your
  needs.
---

# Config

Below is the configuration option for the "job" used to utilise the script's core functions, including access to the target's for clocking in and out as well as utilising the billing system for the registers.

```
Config.JobName = 'burgershot'
```

Below is the setup for the phone of which has two options, `qb` and `custom` if custom is used then custom billing code must be placed within the phone.lua file in the server folder

```
Config.Phone = 'qb'
```

Below is the setup displayed for the billing/register locations there are four to be used however if needed they can be removed, there is an allowed maximum of four locations for billing players.

```
Config.Registers = {
    [1] = vec3(-1190.4847412109, -895.76062011719, 14.042953491211),
    [2] = vec3(-1188.9637451172, -894.76477050781, 14.041003227234),
    [3] = vec3(-1187.4822998047, -893.70434570313, 14.042896270752),
    [4] = vec3(-1194.7612304688, -905.09448242188, 13.874839782715)
}
```

Below is the Target sizing for the billing targets, if you find it difficult to hit the target locations within your `Config.Registers` portion of the config file.

```
Config.TargetSize = vec3(0.5, 0.5, 0.5)
```

Below contains the Duty location within the Config File of which players can utilise to toggle their duty state to true or false.

```
Config.Duty = vec3(-1177.1368408203, -896.86315917969, 13.953170776367)
```
