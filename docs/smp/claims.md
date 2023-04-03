# Claims
Lost Lands uses a custom Claim plugin. Please read the below information carefully as some functionality may be different than
what you are used to!

## Selecting a Region
Start by obtaining a wand (wooden axe) using `/claim tool`. If you are familiar with WorldEdit selections, you can proceed using that knowledge. 
If not, the objective is to create a cube using two selections at the foremost positions of your build. Using your wand, create your 2 selections
by right clicking and left clicking the blocks on each end of your build. Remember, you want to cover your entire build, so make one selection 
high above on one end, and another at a low level at the opposite. If you wish to not use the wand and instead make selections with commands,
use `//pos1` and `//pos2`. A more detailed video on WorldEdit selections can be [found at this link](https://www.youtube.com/watch?v=lzB0l5ZJGH8).

### Verifying your Selection
If you've successfully created a selection, you can run `//size` to get the amount of blocks in that section.

## Creating a Claim
Once you have created a selection, simply run the command `/claim create <name>`, where name is what you want to call it.

## Deleting a Claim
`/claim delete <name>`

## Trusting others with your Claim
Trusting players gives them access to build on your claim.

### Trust Player
`/claim trust add <claim> <player>`

### Revoking Trust
`/claim trust remove <claim> <player>`

## Claim Flags
At its core, our custom claim plugin uses WorldGuard for region protection. Therefore, claim owners can take advantage of setting WorldGuard region flags on their
claims (note: not all flags are available, and some flags are only available with higher ranks). A full list of flags can be found 
[here on the WorldGuard website](https://worldguard.enginehub.org/en/latest/regions/flags/). 

### Set a flag
`/claim flag <claim> <flag> <value>`

### Remove a flag
`/claim flag <claim> <flag>`
<br />
*The command is the same for setting a flag, just omit the value*