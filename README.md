# ToontownCalculator

## Background 

Toontown Rewritten (TTR) is a turn-based Massively Multiplayer Online Role-Playing Game (MMORPG) based on Disney’s now-defunct Toontown Online, which ran from 2002 to 2013.
TTR takes place in the fictional world of Toontown, where wacky and colorful cartoon characters called ‘Toons’ reside. 
In the game, an army of dull corporate robots known as ‘Cogs’ attack the town to put an end to their fun. 
Lucky for toons, the Cogs can’t take a joke, so Toons fight the Cogs by using gags. 
Toons fight the cogs by defeating them on the streets, in cog buildings (which were originally toon buildings), and in the Cog Headquarters.

There are four types of Cogs invading Toontown: `Bossbots`, `Lawbots`, `Cashbots`, and `Sellbots` **(see table below)**. 
Each of the different Cog types have their own respective headquarters, and each headquarter contains different cog facilities where Toons may go to fight cogs. 
One major feature of Toontown is the ability to go fight the Cogs’ boss battles; 
Each cog type has their own version of a boss battle: `Sellbots have the VP`, `Cashbots have the CFO`, `Lawbots have the CJ`, and `Bossbots have the CEO`. 
In order to go fight any of these big bosses, Toons must acquire a cog disguise and earn enough ‘points’ to be ‘Ready for a Promotion!’ 
so they can sneak inside the Cog Boss facilities. 
These points each have a different name for each Cog Type: `Bossbots must earn Stock Options`, `Lawbots must earn Jury Notices`, 
`Cashbots must earn Cogbuck`s, and `Sellbots must earn Merit`s; all of these can be obtained by fighting enough Cogs. 
After defeating the Cog Boss, the Toon’s suit disguise earns a promotion, they must fight more Cogs to earn more points to be ready for another promotion, 
and the process continues to repeat.


| Cog Type | Cog Facility Name                | Cog Facility Types                                 | Cog Boss Name                    | Name of Points  to be earned |
|----------|----------------------------------|----------------------------------------------------|----------------------------------|------------------------------|
| Bossbot  | Cog Golf  Courses                | "The Front Three" "The Middle Six" "The Back Nine" | C.E.O. (Chief Executive Officer) | Stock Options                |
| Lawbot   | DA Offices  (District  Attorney) | A Office, B Office, C Office, D Office             | C.J.(Chief  Justice)             | Jury Notices                 |
| Cashbots | Cog Mints                        | Coin Mint,  Dollar Mint, Bullion Mint              | C.F.O (Chief Financial Officer)  | Cogbucks                     |
| Sellbot  | Sellbot  Factory                 | Short, Long*                                       | V.P. (Vice  President)           | Merits                       |

_Note: The Sellbot Factory is the only Cog Facility in Sellbot HQ, but Toons will typically either take a “short” or “long” route in the factory, depending on how many Merits or Cogs a toon may need to fight._ 

## So what's the issue?
The problem every toon in Toontown faces is knowing exactly how many cog facilities they need to earn a promotion, 
which is where this app comes in: to help toons automatically calculate how many facilities they need based on what suit level they are. 
Using the app, all you need to input is how many points you need, how many you’ve already obtained, and what cog suit type you are calculating. 
The app will output a string of exactly how many facilities they need.

## Technical Notes

This program is a mobile Application designed for Android. The front-end is written in Kotlin, and the
back-end calculator is written in Java which uses an `abstract superclass` and an `interface` 
to make the calculations and optimize code sharing.
