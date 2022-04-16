# Fivem-Acid-Trip
Reworked Acid Trip - Original - https://github.com/meta-hub/fivem-acidtrip


**How to install:**

- Drop the acidtrip.lua into your client side folder in qb-smallresources.
- Copy/paste the client and server side info into your qb-smallresources consumables client and server side.
- Drop the lsd.png into your inventory.

**Add this to your core:**

```["lsd"] 	= {["name"] = "lsd", 	["label"] = "LSD", 	["weight"] = 100, 	["type"] = "item", 	["image"] = "lsd.png", 		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = false,   ["combinable"] = nil,   ["description"] = "Have fun!"},```

--------------------------------

I've taken the original Fivem-Acid-Trip and modified it for better performance.

This script allows you to make acid a consumable item. I've included the small resources events needed to make the item usable, and the event to start the trip.

This DOES NOT spawn another entity of yourself and chase you, I noticed that code can be very buggy.

No longer experience random screen blackouts due to screen shake and other visual effects being too high.

Spawns 2 Marios around you.

--------------------------------

The trip last a total of 4mins. This can be changed.

![image](https://user-images.githubusercontent.com/101474430/163679322-622adf71-3a14-49cc-af5b-274949176ad0.png)
![image](https://user-images.githubusercontent.com/101474430/163679343-0778d496-ba86-4f3b-b1f2-10761acf4acf.png)

