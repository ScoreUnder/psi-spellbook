# My personal Psi spellbook

This repository is a spellbook with all the [Psi][psi] spells I use. Spells in
the root directory are ones I have written myself, while those in the "others"
directory are ones I have found online and are not authored by me. I have made
effort to credit the original authors.

## Spells cast from the rod

### [Break 1](break-1.txt)

Breaks a single block that the caster is looking at.

### [Bridge](bridge.txt)

Loopcast spell. Conjures a bridge of blocks in the direction the caster is
looking. Creates 2 rows of 3, so fast enough to run with, but might be a little
power hungry and doesn't make an active attempt to make sure there's ground
under your feet.

### [Farm with ruler](farm-with-ruler.txt)

Loopcast spell. Use a vector ruler to mark out one corner of your farm
(shift-right click on the crop itself), then move one block outside of your
farm and cast while standing perfectly still. It will farm your farm for you,
replanting with the seeds in the slot to the right of your rod.

### [Item attract](item-attract.txt)

Dead simple, just pulls the items where the spell lands towards you.

### [Loop smelt](loop-smelt.txt)

Loopcast spell. Smelts the item stack the caster is looking at. The spell will
gracefully end once there is no more to smelt, or when the user's Psi energy is
low.

### [Mine this way!](mine-this-way.txt)

Magic circle spell. The caster must first create a direction vector using the
vector ruler, by shift-right-clicking any block on the floor, then
right-clicking the one next to it in the direction you wish this spell to mine.
Then the spell should be cast on the floor immediately next to a wall, which it
will mine out in huge vertical columns.

Warning: This spell will use all your Psi energy at once even at endgame and it
is very easy to go from full HP to zero by mis-casting this spell.

### [Place invis](place-invis.txt)

Simple block conjuring spell, which places a block on the surface the caster is
looking at. Useful if you're using another mod like Astral Sorcery to grind
away all the cobblestone and you find yourself totally lacking in blocks to
build platforms with.

### [EXPLOSION!!!!](safe-explosion.txt) ("Safe explosion")

Explodes an enemy you are looking at (or if you aren't looking at one directly,
any enemy close enough to your line of sight). Places water before explosion
and creates a temporary block after explosion, so that the terrain and user are
not damaged. Kills groups of endermen in one shot lol

The spell will refuse to detonate if it can't create the water. Better to be
unable to blow up that annoying skeleton than succeed and have it take out most
of your base too.

### [Slow regen](slow-regen.txt)

Another dead simple spell. Creates a long slow regeneration effect on the user.

### [Square me](square-me.txt)

Messing around with particle effects. This draws a 5x5 square around the caster
on the XZ plane.

### [Tree feller](tree-feller.txt)

Magic circle spell. Simply mines upweards from the circle.

## Spells to put on tools

### [Break forwards](break-forwards.txt)

Used with the psimetal pickaxe. Breaks a whole row of blocks in the direction
that the caster is mining.

### [Column and replace](column-and-replace.txt)

Used with any psimetal mining tool, but intended for the axe. Breaks a large
vertical column above the broken block and then replaces (re-plants) the
original broken block with the item to the right of your rod.

## Spells to put on the sword

### [Throw and ignite](throw-and-ignite.txt)

Used with the psimetal sword. Launches the target into the air and ignites them
at about the time they're due to fall. With luck, you might get some cooked
meat out of it or something. Most of the damage by far comes from the
launching, so it works best in open-air environments.

### [Trismite](trismite.txt)

Used with the psimetal sword. Smites the target with lightning 3 times. Not
recommended for use on creepers.

[psi]: https://psi.vazkii.net/
