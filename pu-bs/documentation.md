---
description: >-
  This page will demonstrate usage of ox_inventory for developers to setup
  crafting stations and storage for the PU-BS Job (Burgershot)
---

# Documentation

### Below is the crafting to be added to ox\_inventory/data/crafting.lua

Make sure you add your own craftable items to the items table within each Crafting Table.

```
{
	items = {},
	points = {
		vec3(-1185.9948730469, -899.62396240234, 13.548998832703),
	},
	groups = {['burgershot'] = 0},
	zones = {
		{
			coords = vec3(-1185.9948730469, -899.62396240234, 13.548998832703),
			size = vec3(1, 1, 1),
			distance = 2,
			rotation = 70.0,
		},
	},
},
Fries Crafting
{
	items = {},
	points = {
		vec3(-1188.1883544922, -901.14605712891, 13.688589096069),
	},
	groups = {['burgershot'] = 0},
	zones = {
		{
			coords = vec3(-1188.1883544922, -901.14605712891, 13.688589096069),
			size = vec3(1, 1, 1),
			distance = 2,
			rotation = 70.0,
		},
	},
},
Drinks Crafting
{
	items = {},
	points = {
		vec3(-1191.3488769531, -898.02728271484, 14.071642875671),
	},
	groups = {['burgershot'] = 0},
	zones = {
		{
			coords = vec3(-1191.3488769531, -898.02728271484, 14.071642875671),
			size = vec3(1, 1, 1),
			distance = 2,
			rotation = 70.0,
		},
	},
},
Patty Crafting (Cooking Station)
{
	items = {},
	points = {
		vec3(-1187.2214355469, -900.86828613281, 13.759497642517),
	},
	groups = {['burgershot'] = 0},
	zones = {
		{
			coords = vec3(-1187.2214355469, -900.86828613281, 13.759497642517),
			size = vec3(1, 1, 1),
			distance = 2,
			rotation = 70.0,
		},
	},
},
```

### Below is the Storage which is to be placed within ox\_inventory/data/stashes.lua

```
Storage
{
	coords = vec3(-1184.1459960938, -900.87158203125, 13.94385433197),
	target = {
		loc = vec3(-1184.1459960938, -900.87158203125, 13.94385433197),
		length = 1.0,
		width = 1.0,
		heading = 214.73,
		minZ = 13.7,
		maxZ = 13.9,
		label = 'Open Storage'
	},
	name = 'bs_storage2',
	label = 'Burgershot Front Storage',
	owner = false,
	groups = {['burgershot'] = 0},
	slots = 50,
	weight = 1000000,
},
Tray 1
{
	coords = vec3(-1187.9656982422, -894.03924560547, 14.025440216064),
	target = {
		loc = vec3(-1187.9656982422, -894.03924560547, 14.025440216064),
		length = 0.5,
		width = 0.5,
		heading = 32,
		minZ = 13.7,
		maxZ = 13.9,
		label = 'Open Tray 1'
	},
	name = 'bstray1',
	label = 'Burgershot Tray 1',
	owner = false,
	slots = 10,
	weight = 50000,
},
Tray 2
{
	coords = vec3(-1189.4934082031, -895.05255126953, 14.008352279663),
	target = {
		loc = vec3(-1189.4934082031, -895.05255126953, 14.008352279663),
		length = 0.5,
		width = 0.5,
		heading = 32,
		minZ = 13.7,
		maxZ = 13.9,
		label = 'Open Tray 2'
	},
	name = 'bstray2',
	label = 'Burgershot Tray 2',
	owner = false,
	slots = 10,
	weight = 50000,
},
Tray 3
{
	coords = vec3(-1191.1195068359, -896.12878417969, 14.020124435425),
	target = {
		loc = vec3(-1191.1195068359, -896.12878417969, 14.020124435425),
		length = 0.5,
		width = 0.5,
		heading = 32,
		minZ = 13.7,
		maxZ = 13.9,
		label = 'Open Tray 3'
	},
	name = 'bstray3',
	label = 'Burgershot Tray 3',
	owner = false,
	slots = 10,
	weight = 50000,
},
```

