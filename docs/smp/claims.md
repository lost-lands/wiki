# Claims

## Selecting a Region
Start by obtaining a wand (wooden axe) using `/claim tool`. If you are familiar with WorldEdit selections, you can proceed using that knowledge. 
If not, the objective is to create a cube using two selections at the foremost positions of your build. Using your wand, create your 2 selections
by right clicking and left clicking the blocks on each end of your build. Remember, you want to cover your entire build, so make one selection 
high above on one end, and another at a low level at the opposite. If you wish to not use the wand and instead make selections with commands,
use `//pos1` and `//pos2`. A more detailed video on WorldEdit selections can be [found at this link](https://www.youtube.com/watch?v=lzB0l5ZJGH8)

### Verifying your Selection
If you've successfully created a selection, you can run `//size` to get the amount of blocks in that section.

## Creating a Claim
Once you have created a selection, simply run the command `/claim create <name>`, where name is what you want to call it.

## Deleting a Claim
To delete a claim, run the command `/claim delete <name>`

## Trusting Players
Trusting players gives them full access to your claim, apart from [locked items](https://wiki.lostlands.org/smp/locking/). To trust a player, run the command
`/claim trust add <claim> <player>` where claim is your claim name, and player is the player you want to trust. If you wish
to remove a player from your claim, run `/claim trust remove <claim> <player>`.