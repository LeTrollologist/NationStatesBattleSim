# Fork Notice
I am not continuing the development of NationStates BattleSimulator/NSBS. I have forked this repository purely to research things for Drumfire, my spiritual successor to Forrest's NSBS that was written in Java. Drumfire is written in Rust, and will feature many new and unique features than NSBS had.

# Why Not Continue NSBS?
Because while I have loved working with Java, the last time I worked with it was to make Minecraft plugins for a now largely dead Minecraft server. Since then I've returned to coding in Rust, and making my own programming language named Morrow. Both have made me realized how much I despised coding in Java. Also, I don't feel like updating all of the code and it runs poorly, along with the on-going issues. I think the standard of 2013-2015 that it was innovative, especially to the community of NationStates, but I don't think it has aged well to the standards of of the 2020s.

# What happened to NSBS: Online?
NSBS: Online, a mobile successor to NSBS: Java, was canceled more than once by myself. I always found myself worrying about security, and furthermore, forking over real money to maintain it with no possibility of requesting donations. With that being said, killed the drive on working on it.

# Why now? 
I feel like it. I also think it can benefit the NationStates community, a community I've been a part of off and on since 2013.

# What will Drumfire achieve that NSBS cannot?
Compile, run fast, and add the ability to have modes, updates, and many QoL features while using similar mathmatics that the original NSBS did, but more fleshed out, modernized, and needless to say the rustic line, **faster**.

# Where is Drumfire?
Drumfire can be located here: https://github.com/LeTrollologist/Drumfire/tree/main

A support/development/community Discord server will be created at a later date when I am satisfied with the progress of Drumfire and am ready to release it in a substantial manner, now is not that time.

---
# Original README for NSBS below

# NationStatesBattleSim
NationStates Battle Simulator is a roleplaying supplement and Battle Simulator for Nation States.  It's designed to take input from the user for different factors of battle: Force Count, Morale, Technology, Training, Combat Experience, Logistics, and Intel, and simulate the outcome of a skirmish to be roleplayed out after.  This allows for constructive roleplay, as the outcome of the battle isn't decided by story arc alone.  



# How to use
There are many, many factors to war.  Often in roleplaying, it's difficult to fairly decide the outcome of a battle.  
Enter me, with an idea.  The program is packaged in an executable JAR, so just run it like anything else. The Jar is in the root directory.
The program calculates different factors, physical force count, troop morale, level of technology, the level of training, troop combat experience, logistics, intel, and supplies.  Enter the two sets of values for each team, then hit Run Simulation.  

#Calculating your Forces
This doesn't mean your total entire military.  Simply put, it's how many troops you're throwing at the specific battle.
#Calculating Morale
Your troops need to have hope.  If they've been on a constant losing streak, they'll be less likely to fight their best.  Each division/squad/etc starts at 100 Morale.  With each loss, subtract 10.  With each victory, add 10.  

#Calculating everything else
Everything else is treated on a scale of 1-10.  Now, before you go and ask questions, pay attention.  I made this for people who awant to act like adults for roleplaying.  Quantifying arbitrary values is hard, so what I'll summarize describe what each parameter represents.  It's up to you and your enemy to decide the actual values.


Technology:
This value is how technologically advanced your country is.  Here's a few examples:

WWII:
Russia - Tech 3
'Murica - Tech 7
Britain - Tech 5
Germany - Tech 9


Medieval:
England - Tech 7
Chinese - Tech 9
Vikings - Tech 2

Hope that makes sense

Training Rating:
This value is how well trained your fighting force is.  If your soldiers are hyper-elite, near-super humans that have undergone years of training, they'll be higher on the scale than a bunch of kids thrown into battle.

Combat Experience:
This value is similar to the training value, but vastly different.  This value relies on hoe battle-hardened your forces are.  Nations with more wars in their history should have higher values, while newer nations would have lower.


Logistics:
This value is the ability for the non-combat personnel's ability to move supplies to and from the front line.  

Intel:
How much the intelligence the nation has over the other.  If one country has been flying spy planes over the other for years, they'd have the higher value.  Can also be measured by how much crtical information you know about the enemy or the battlefield.

Home Team Advantage:
Fighting on your home soil gives you an advantage.  


#Reading the Output
Now, battles are dynamic.  This is shown in the simulator by the intermittent outcome screen, then "Continue?/Retreat?" dialouges.  If you're losing too many forces, you can leave.  

As I've been reading it, the Score value is based on per hour of fighting, so each intermittent "Win" is basically dominating the fight for that one hour.

#Download from GitHub 
Most recent version:
GitHub https://github.com/GhostlyBanjo/NationStatesBattleSim/blob/master/NationStatesBattleSim.jar?raw=true

#Download from DropBox
Updated less:
Dropbox https://www.dropbox.com/s/om0buzhkhmmqias/NationStatesBattleSim.jar?dl=0


#FAQ

Q: Why can't I use the Nation States stats?

A: The reason the NS values aren't compatible with this version is that Nation States is a country simulator,  not a military simulator.  Almost all of the values on Nation States have nothing to do militaries, which is why it's set up as such.  Maybe later, a version will be release that has integration with the NS stats, but for now, this is a roleplaying supplement, not an extension of NationStates itself.


#Contact

Questions or Comments? Direct them to ghostlyBanjo@gmail.com

I'm also online most of the day on #NSBS at webchat.esper.net
