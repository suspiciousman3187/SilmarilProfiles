# Omen Profiles
For Omen, since there are no enrage or hard DPS checks, I run a mostly defensive setup focused around slow but stable and consistent kills with defensive support and lots of backup healing.

PLD/RDM - For tanking/healing. You can also run /SCH or /BLU if you want.
MNK/DRG - Main DPS. Useful for tanking Unfaltering Bravado with Mantra.
COR/DNC - Defensive support with Gallant's Roll and backup healing with Waltz.
GEO/WHM - Defensive support with Indi-Barrier & backup healing with Curaga III.
RDM/WHM - Buff/Debuff support and backup healing with Cure/Curaga III.
BRD/WHM - Defensive support and backup healing with Curaga III.

## Encounter Auto-switching Triggers
I run a set of triggers on the Paladin which automatically moves to the next profile set as I run. This lets me not worry about manually switching profiles throughout the run. Here is an example flow with my setup.

### Gin Run Example
1. Load Omen/Trash, clear the first two rooms.
2. Enter first Midboss, the Omen/Trash profile will automatically switch to the Craver/Gorger/Thinker profiles upon engaging them.
3. After beating the boss, move to the next trash room. While still in the midboss profile, engaging any Sweetwater mob triggers a profile load back to Omen/Trash.
4. After clearing the trash and reaching Gin, I engage Gin and the trigger automatically loads the Gin profile.
5. (EXTRA) While still in the Gin profile and starting a new run, engaging any Sweetwater mob will again switch back to the Omen/Trash profile.

This works for all bosses EXCEPT Ou, which requires some specific setup. Explanation below.

# Profile Notes
Here are some short notes on how to use the profiles.

## Trash
Used for clearing the trash rooms. Use Aeolian Edge and cleave all the mobs down.

## Craver
I stack defensive buffs and then facetank his primary mechanic (View Sync+Carousel) since it is only plain damage.

## Gorger
Straightforward fight. I let him use Blessing Sync as much as he wants and just tank him on Paladin while DPSing him down slow and steady.

## Thinker
The key is to have a trigger to disengage on Pain Sync cast to prevent the reflect damage. After that, I have triggers to WS on all other TP moves and turn normal Weaponskill off, decreasing the chances of WSing by accident during Pain Sync.

NOTE: Sometimes the Pain Sync disengage trigger is slow and doesn't work properly. I haven't found out why it does this. I suggest just keeping Reraise on your healers to be safe. Most of the time there are no issues though.

## Kin
Like Glassy Thinker, it is a simple fight using Triggers. I use triggers to WS on any Spell cast to prevent WSing into an absorb, and just build TP between spellcasts. I ignore Target since if you push him quick enough from Target to Target you can just skip Eleventh Dimension.

## Gin
Straightforward fight, just run in and kill him. Use Paladin to tank and keep everyone healed through Zero Hour.

## Kyou
NOTE: I use the same profile for Gin AND Kyou.
Another straightforward fight. Just make sure to position everyone INFRONT of Kyou at all times. After that make sure Monk uses Mantra and keep party topped off with Paladin to survive Unfaltering Bravado.

## Kei
I use Monk to do a 4 step skillchain with Godhands+Hoxne Ampulla. Make sure Bard sings double marches to keep Haste capped as Gin can cancel Haste with his slow aura. Other than that, I use triggers to run to 10-12y to avoid Dancing Fullers and then just kill him slow and steady.

## Fu
NOTE: I don't know if I'm doing this right. 

I basically just run in and let him absorb all my buffs and kill him anyways. I use Invincible and Intervene to make sure he doesn't one-shot the Paladin since he hits like a truck with all the absorbed buffs. There is probably a better way to handle this fight but I am lazy.

# Ou
Requires special setup. There are three profiles based on the "phases" of the Ou fight.

1. OuStart - Used at the start. I only activate this profile with Monk to bring him down to 95%. After Ebullient Nullifcation finishes, my trigger has everyone run in and then loads the OuMid profile.
2. OuMid - Used for the middle of the fight up to Dancing Fullers cast. A standard profile focused on setting up buffs/debuffs & Monk using Mantra to prepare for Unfaltering Bravado. Includes a trigger to run away to avoid Dancing Fullers.
3. OuZerg - After Dancing Fullers, the trigger will load this last profile. At this point, I basically just zerg him down and ignore the rest of the mechanics.

## Fight Instructions
1. Load at the start, make sure the party is positioned 21y+ away to avoid Ebullient Nullification. Run in and engage with ONLY Monk and bring him down to 95%. Silmaril should be on ONLY for the Monk.
2. After Ebullient Nullification, the trigger will switch to OuMid, causing the party will run in and start setting up buffs/debuffs. Make sure to use Mantra on Monk and prepare for Unfaltering Bravado.
3. After Unfaltering Bravado, DPS him down until he does Dancing Fullers.
4. After Dancing Fullers, trigger will switch to OuZerg and finish the fight.

## Other Notes
I run a Counter build with Monk and find that it helps with the 100-95% push. See https://www.bg-wiki.com/ffxi/Community_Monk_Guide#Other_Miscellaneous_Sets for options on how to stack Counter.

For the OuZerg phase, depending on how strong your party is and how strong your monk is, you may want to tweak it to enable Weaponskills for everyone. 

My Monk is fairly geared and uses Hoxne Ampulla so I found that just having the Monk DPS and repeatedly SC Light did more damage overall, but if your entire party is geared, the damage from everyone WSing constantly could overtake it.

There is a trigger to use Super Jump on the Monk when Ou uses Target. This is only required if you are running low-man (without the Paladin). Otherwise you can disable it if you are running with the full party.