# 4x-Games-Victoria-3-Multiplayer-Mod
Victoria 3 mod for use in the 4x Games Discord community for Victoria 3 multiplayer games & campaigns.

Invite link: https://discord.gg/8CNwKHpHWh

### Features List ###
#### AI Strategies ####
- Bugfix: AI countries will not actively befriend other larger nations (Confirmed by Paradox and planned for patch 1.7.4: https://forum.paradoxplaza.com/forum/threads/mistakes-found-in-ai_default_strategies.1694358/)
#### Building Groups ####
- Shipyards: Parent group changed from heavy industry to light industry
- Ports: Economy of Scale enabled

#### Buildings ####
- Coal Liquefaction Plant added: Converts coal into oil and oil into rubber
- Port: Building Group changed from Public Infrastructure to Port

#### Character Templates ####
- Sweden: Oscar Bernadotte's culture changed from French to Swedish

### Country Ranks ###
- Migration attraction buffs and debuffs removed from all country ranks
- Prestige average threshold for Major Powers reduced from 2.5 down to 2

#### Defines ####
- NGame: Number of autosaves increased from 5 to 12
- NDiplomacy: Abandon support relations impact reduced from 50 to 0
- NEconomy:
    - Maximum Trade Route level increased to 250
    - Trade route economy of scale Cap increased to 61
- NPops:
    - Migration pull from available arable land employment increased from 0.5 to 0.75
    - Migration pull from available arable land employment cap increased from 30 to 60

#### Diplomatic Actions ####
- All diplomatic actions between players have no relations requirement
- Foreign Investment Agreement Opportunity System bug fixed
- Bug where Overlords couldn't give their own states to their own subjects unless the state in question is both not incorporated and not primary homeland. Changed to be that primary homeland states can't be given away unless they are incorporated
- Bug where Overlords could erroneously enforce military access on their own subjects who are at war with said Overlord

#### Diplomatic Plays ####
- All diplomatic plays between players have no relations requirement. Relation requirements still apply in joining an active diplomatic play

#### Ideologies ####
- New Ideologies added:
    - Colonial Government: Has opinions on Governance Principles, Distribution of Power, Bureaucracy, Policing, Economic System, Trade Policy, Taxation

#### Interest Groups ####
- Landowners:
    - British East India Company: Paternalistic ideology replaced with Colonial Government ideology
    - Dutch East Indies: Paternalistic ideology replaced with Colonial Government ideology
- Rural Folk:
    - British East India Company: Agrarian ideology replaced with Colonial Government ideology
    - Dutch East Indies: Agrarian ideology replaced with Colonial Government ideology

#### Journal Entries ####
- Meiji Economy Journal Entry: Complete requirement now requires having 70% or more states with railways built
- Sick Man of Europe (Education): Required goal removed and the Literacy rate requirement changed from 20% to 32%, to take into account the 20% increase originally required by the journal's required goal

#### Mobilization Options Groups ####
- Added option for rifles used to make use of military techs, called Main Rifles

#### Mobilization Options ####
- Main Rifles added:
    - Rifles: +5 offense, +5 defense
    - Repeaters: +10 offense, +10 defense, +1 small arms upkeep
    - Bolt-Action: +15 offense, +15 defense +2 small arms & +1 ammunition upkeep

### Power Blocs ###
- Leverage Threshold to invite reduced to 100 for power blocs lead by any country that doesn't have the Great Power rank. Leverage Threshold to invite remains at 200 for Great Powers

### Power Bloc Principles ###
- Freedom of Movement: All bonuses reduced by 50%

#### Production Method Groups ####
- Coal-Liquefaction Plant:
    - Coal to Oil PMs added (Levels 1-5)
    - Oil to Rubber PMs added (Levels 1-5)

#### Production Methods ####
- Added timed modifiers for PM Changes:
    - Change in primary PM grants a decaying -20% throughput
	  - Change in secondary PM grants a decaying -10% throughput
- Added production methods for Coal-Liquefaction Plant
    - Coal to Oil: 5 Coal --> 1 Oil
    - Oil to Rubber: 5 Oil --> 1 Rubber
- Convoys supplied by Ports increased:
    - Anchorages: Amount of Convoys increased from 20 to 50
    - Industrial Ports: Amount of Convoys increased from 175 to 250
    - Modern Ports: Amount of Convoys increased from 200 to 400
- Influence provided by Power Block Principle External Trade II & III reduced from 2 to 1
- Production methods using Transportation as an input good are blocked until the building has access to Transportation
- Freedom of Movement Principle Production Method migration bonus reduced from 20% down to 10%
- Gold output from using the nitroglycerin production method in gold mines reduced from 5 to 2.5. This brings it inline with the dynamite production method which outputs 5 gold, as the nitroglycerin production method should output half the gold output of the dynamite production method
- Canals now employ 500 bureaucrats instead of 500 capitalists, so the capitalists don't end up starving as they were before.

#### Static Modifiers ####
- Base Government Dividends efficiency increased from 25% to 35%
- Recently adjusted primary production method timed modifier added
- Recently adjusted secondary production method timed modifier added
- Power bloc cohesion penalty for power blocs lead by countries that don't have the Great Power rank is reduced from 50% down to 25%

#### Technologies ####
- Production:
    - Synthetic Strategic Resources (Era 5): Unlocks Coal-Liquefaction Plant, Coal --> Oil Production Methods, Oil --> Rubber Production Methods
- Society:
    - Pan-Nationalism: Added Identification Documents as an unlocking technology requirement
    - Great War Diplomacy (Era 5): Adds 1375 maneuvers to diplomatic plays, reduces war exhaustion from casualties by 65%

#### GUI ####
- GDP Graph: Size increased from 280 x 100 to 1400 x 500

