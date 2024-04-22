This script is designed to be used on untamed animals. The script uses a min/max stat calculation to determine the percentile of the analyzed mob. This script does not take into account overcapped skills, it only looks at stats + resists.

Once the calculation is done the details are displayed on screen for a short period of time, as well as posted in your Journal in game.

To calculate the min and max values for an animal, if you wish to add your own you need to look up what the minimum and maximum values for whatever animal you're interested in. Once you have the min and max values you can add that to the script in a new line along with the other animals listed. Please note that if the name of the animal you're inspecting is not typed exactly as it appears in game you will get an error.

A example of the min/max calculation is as follows for a nightmare " https://www.uoguide.com/Nightmare "

Attributes

Strength	496-525

Hit Points	298-315

Dexterity	86-125

Stamina	86-105

Intelligence	86-125

Mana	86-125

Resists and Damage

Types	      		Physical	      Fire	      Cold	      Poison	      Energy

Resistances			55-65	          30-40	      30-40	      30-40	        20-30

Min calculation: 496+298+86+86+86+86+55+30+30+30+20 = 1303

Max calculation: 525+315+125+105+125+125+65+40+40+40+20 = 1535

So our new pet entry would look as follows
'a nightmare': { min: 1303, max: 1535 },

This was designed for use on OSI so I can't vouch for it working anywhere else.

Happy hunting!
