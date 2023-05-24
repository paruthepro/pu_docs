---
description: This page describes how phone notifications are handled
---

# Phone Notifications

### Client

Below is the exact contents of the Client notify.lua file of which custom phone notifications can be used, take note of the initial notification followed by the small, medium and large notifications.

These will require additional custom code from the customer however we cannot provide support for your custom phone(s), we can however guarantee that the original QB Notifications within the script will work for the following phones - `qb-phone, Renewed-Phone`

```
-- Add your custom phone notifications below for notifying players of job start, location, Police Dispatch etc

RegisterNetEvent('pu-bt:client:dispatch', function()
exports["ps-dispatch"]:VanRobbery() -- Add your code here (REMOVE ME)
end)

RegisterNetEvent("pu-bt:client:phonenotify", function() -- Phone Notification (Email, text etc)
-- Add your code here (REMOVE ME)
end)

RegisterNetEvent("pu-bt:client:smallnotify", function() -- Small Bank Truck
-- Add your code here (REMOVE ME)
end)
RegisterNetEvent("pu-bt:client:mediumnotify", function() -- Medium Bank Truck
-- Add your code here (REMOVE ME)
end)
RegisterNetEvent("pu-bt:client:largenotify", function() -- Large Bank Truck
-- Add your code here (REMOVE ME)
end)
```

### Server

Below is the exact contents of the Server notify.lua file of which custom phone notifications can be used, take note of the initial notification followed by the small, medium and large notifications.

These will require additional custom code from the customer however we cannot provide support for your custom phone(s), we can however guarantee that the original QB Notifications within the script will work for the following phones - `qb-phone, Renewed-Phone`

```
RegisterServerEvent('pu-bt:server:notify', function()
-- Add your code here (REMOVE ME)
end)
```
