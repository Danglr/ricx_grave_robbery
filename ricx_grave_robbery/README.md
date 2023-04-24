# ricx_grave_robbery
RedM Script for Grave Robbery Activity - RedEM:RP &amp; VORP & QBR Core


Players can dig different (configured in config) graves to get reward item (configured in config).
Players can also pray (animation) at graves.
One grave can be robbed only once per server/script restart.

https://www.youtube.com/watch?v=DpX_Uguh1I4



Insert into rsg-core/shared/items.lua 

```-- Graverobbing
    ["golden_ring"]  = {["name"] = "golden_ring",  ["label"] = "Golden Ring",  ["weight"] = 100, ["type"] = "item", ["image"] = "golden_ring.png", ["unique"] = false, ["useable"] = true,  ["shouldClose"] = true, ["combinable"] = nil, ["description"] = ""},
    ["golden_nugget"]  = {["name"] = "golden_nugget",  ["label"] = "Golden Nugget",  ["weight"] = 100, ["type"] = "item", ["image"] = "golden_nugget.png",  ["unique"] = false, ["useable"] = true,  ["shouldClose"] = true, ["combinable"] = nil, ["description"] = ""},
    ["rock"]  = {["name"] = "rock",  ["label"] = "Rock",  ["weight"] = 100, ["type"] = "item", ["image"] = "rock.png",  ["unique"] = false, ["useable"] = true,  ["shouldClose"] = true, ["combinable"] = nil, ["description"] = ""},```