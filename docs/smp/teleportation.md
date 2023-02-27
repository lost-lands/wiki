# Teleportation

## Teleporting & Movement
Players must not move for 5 seconds while attempting to teleport. A countdown will display on the action bar with the amount of seconds left until they are teleported. If they move at all (including being pushed), the teleport is canceled. This is implemented as a feature to prevent people from teleporting out of situations where they might be fighting someone or running from a mob. 

## Teleport Requests
Players can request to teleport to a player using the `/tpa <player>` command. That player will receive a notification in chat indicating a player would like to teleport to them, and they can either click [ACCEPT] or [DENY]. Requests are valid for 30 seconds. If accepted, the player will be immediately queued for a teleport, and must wait the period stated above without moving. If denied, the player will be notified in chat.

### Handling Multiple Requests
If you have multiple incoming requests, or chat has been so busy that you cannot click the request message, you can use the `/tpaccept` command which will bring up a book listing all of the players requesting to teleport to you. From there, you can click a player's name to accept their teleport. If you wish to deny a request, simply wait for the request to timeout. 

## Warps

### Teleporting to Warps
Players can teleport to a warp using the `/warp <name>` command. If no name is supplied, the command will output a list of available warps. You can either copy a name from that list and use the same command, or simply click the name to teleport. 

### Creating Warps
Players can create global warps using the `/setwarp <name>` command. These warps will be available to anyone to teleport to, and will show up on the [world map](https://map.lostlands.org). The amount of warps a player can create is based on their rank. These limits are:

| Rank   | Warp Limit |
|--------|------------|
| Player | 3          |
| OG     | Unlimited  |

### Warp Info
Interested in learning about who created a warp, or what the coordinates of the warp may be? Use the `/warpinfo <name>` command to learn more. 

## Other Commands
### Spawn
`/spawn`


