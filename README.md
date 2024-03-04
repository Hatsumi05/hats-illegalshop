# hats-illegalshop
Illegal Blackmarket QBCore Fivem Script with item

Credits for the original script: https://github.com/MT-Scripts/mt-blackmarket
I only changed the code

You need to add this to qb-core/server/player.lua
    PlayerData.metadata['blackmarketlevel'] = PlayerData.metadata['blackmarketlevel'] or 0
Also For Logs, you need to add this in qb-smallresources/server/logs.lua
    ['blackmarket'] = '',
