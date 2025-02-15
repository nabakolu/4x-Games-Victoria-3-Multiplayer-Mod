#######################
### Integrated Mods ###
#######################
- Sustainable Resource Buildings Expansion (SRBE) - https://steamcommunity.com/sharedfiles/filedetails/?id=3324172660
- 1.8.6 Unofficial Hotfix Mod (UHM) - https://steamcommunity.com/sharedfiles/filedetails/?id=3274932837
- Ultra Historical Demography (UHD) - https://steamcommunity.com/sharedfiles/filedetails/?id=3041693269
- Lump Sum Transfer (LST) - https://steamcommunity.com/sharedfiles/filedetails/?id=3245710931
- GDP Ownership Display - https://steamcommunity.com/sharedfiles/filedetails/?id=3290552216
- GDP Plotline Plus - https://steamcommunity.com/sharedfiles/filedetails/?id=3190466673
- PDXRP Updated GM Tool - https://steamcommunity.com/sharedfiles/filedetails/?id=3369619242
- Global Stats (GDP and POP) - https://steamcommunity.com/sharedfiles/filedetails/?id=3312478537
- Great Game For Sandbox - https://steamcommunity.com/sharedfiles/filedetails/?id=3274667739

#######################
### Building Groups ###
#######################
- Building Group Ports:
    - Economy of Scale enabled
- SRBE buildings added

#################
### Buildings ###
#################
- Mod New Buildings:
    - Coal Liquefaction Plant added
- Reworked Vanilla Buildings:
    - Port:
        - Building Group changed from Public Infrastructure to Port
        - Can no longer be downsized/deleted
- SRBE New Buildings:
    - Coal Mining Center
    - Iron Metallurgical Center
    - Lead Metallurgical Center
    - Sulfur Mining Center
    - Oit Exploration Center
    - Oceanic Fishery Port
    - Composite Wood Factory
    - Synthetics Rubber Plants
- UHM:
    - AI UK Indian subjects now build more plantations if they have the British Dictate Plantations Journal Entry

##############################
### Character Interactions ###
##############################
- UHM:
    - Moderate characters who are exhiled should now adopt a more interesting ideology

###########################
### Character Templates ###
###########################
- Sweden:
    - Oscar Bernadotte
        - Culture changed from French to Swedish

#########################
### Combat Unit Types ###
#########################
- All infantry unit types can be upgaded into any other infantry combat unit types
- All artillery unit types can be upgraded into any other artillery combat unit types
- All cavalry unit types can be upgraded into any other cavalry combat unit types
- All light ship unit types can be upgraded into any other light ship combat unit types
- All flagship unit types can be upgraded into any other flagship combat unit types
- All support ship unit types can be upgraded into any other support ship combat unit types

#################
### Companies ###
#################
- Reworked Vanilla Companies:
    - Egyptian National Railways:
        - Land Trade Capacity increased from 10 to 100
    - São Paulo Railway Co. Ltd:
        - Land Trade Capacity increased from 10 to 100
    - Căile Ferate Române:
        - Land Trade Capacity increased from 15 to 150
    - Də Afḡān Nasājī Šerkat:
        - Land Trade Capacity increased from 5 to 50
    - Turkish Petroleum Company:
        - Land Trade Capacity increased from 5 to 50
    - United Construction Company:
        - Construction throughput reduced from 20% to 5%
    - Imperial Tobacco Corporation of Persia, Limited
        - Now requires the country to have any of the following primary cultures:
            - Persian
            - English
            - Scottish
    - Nam Định Textile Factory:
        - Now requires the country to have any of the following primary cultures:
            - Vietnamese
    Sunhwaguk:
        - Now requires the country to have any of the following primary cultures:
            - Korean
    Kaiping Mining Company:
        - Now requires the country to have any of the following primary cultures:
            - Han
            - Manchu

#####################
### Country Ranks ###
#####################
- All migration attraction buffs and debuffs removed from all country ranks
- Prestige average threshold for Major Powers reduced from 2.5 down to 2

#################
### Decisions ###
#################
- Game Master (GM) system added
- Moderator funny decision added for Switzerland to RP Swiss Bank

###############
### Decrees ###
###############
- Game Master (GM) system added

###############
### Defines ###
###############
- NGame:
    - Number of autosaves increased from 5 to 12
- NDiplomacy:
    - Abandon support relations impact reduced from 50 to 0
    - Diplomatic Pact cost multiplier from infamy doubled
        - Infamous level of infamy: 50% increase
        - Notorious level of infamy: 100% increase
        - Pariah level of infamy: 200% increase
    - Diplomatic play opening phase ends at 31 days, up from 21 days
    - Diplomatic play closing phase starts at 90 days, up from 80 days
- NEconomy:
    - Maximum Trade Route level increased to 250
    - Trade route economy of scale Cap increased to 61
    - Auto downsize building months to wait decreased from 12 down to 3
    - Building timed modifier weeks increased from 52 to 104
    - Trade route auto increase employment threshold decreased from 0.9 to 0.5
    - Trade route auto increase very low productivity threshold decreased from 3 to 2.9
    - Trade route auto increase low productivity threshold decreased from 6 to 3
    - Trade route auto increase high productivity threshold decreased from 10 to 3.1
    - Trade route auto reduction employment threshold decreased from 0.75 to 0.1
- NMilitary:
    - Army unit upgrade rate decreased from 10% to 2% (Takes 1 year to upgrade all units in an army)
    - Fleet unit upgrade rate decreased from 5% to 1% (Takes 2 years to upgrade all units in a fleet)
    - General travel auto reassign instantly increased from 15 to 120
- NPops:
    - Migration pull from available arable land employment increased from 0.5 to 0.75
    - Migration pull from available arable land employment cap increased from 30 to 60
    - Birth rate and mortality rate have been modified to be more in line with the UHD mod
        - Birthrate slightly increases until 10 SoL, to allow for historical massive population growth during industrial revolution
        - High plateau but with both birthrate and mortality decreasing between 10 SoL and 14 SoL
        - Slow decrease until stabilization at 20 SoL
    - High pop modifier now applies to states with 500000 pops and more, raised from 100000 pops and more
    - States with less than 50000 pops will not get emigration, raised from 20000 pops
    - States with less than 250000 pops have reduced market emigration numbers to avoid total depopulation, raised from 100000 pops

##########################
### Diplomatic Actions ###
##########################
- All diplomatic actions between players have no relations requirement
- Rivalries can be established between the following power ranks:
    - Great Powers can rival:
        - Great Powers
        - Major Powers
        - Unrecognized Major Powers
    - Major Powers can rival:
        - Great Powers
        - Major Powers
        - Unrecognized Major Powers
        - Minor Powers
    - Minor Powers can rival:
        - Major Powers
        - Minor Powers
        - Insignificant Powers
    - Insignificant Powers can rival:
        - Minor Powers
        - Insignificant Powers
    Unrecognized Major Powers can rival:
        - Great Powers
        - Major Powers
        - Unrecognized Major Powers
        - Unrecognized Regional Powers
    - Unrecognized Regional Powers can rival:
        - Major Powers
        - Unrecognized Major Powers
        - Unrecognized Regional Powers
        - Unrecognized Powers
    - Unrecognized Powers can rival:
        - Unrecognized Regional Powers
        - Unrecognized Powers

########################
### Diplomatic Plays ###
########################
- All diplomatic plays & actions between players have no relations requirement when starting them. Relation requirements still apply in joining an active diplomatic play
- AI no longer erroneously desires to reduce the autonomy of charter companies
- States can be traded between players while at war (Note: Players exploiting this will be punished)

###############
### History ###
###############
- Countries:
    - Hudson Bay Company:
        - Now starts with Extraction Economy economic system law due to being Chartered Company subject type
- Power Blocs:
    - Russia:
        - Core power bloc principle changed from Vassalisation Level 1 to Exploitation of Members Level 1
        - Second starting power bloc principle changed from Defensive Co-Operation Level 1 to Food Standardization Level 1 
    - Austria:
        - Second starting power bloc principle changed from Defensive Co-Operation Level 1 to Police Coordination Level 1
    - Ottomans:
        - Second starting power bloc principle changed from External Trade Level 1 to Transportation Infrastructure Level 1

##################
### Ideologies ###
##################
- Modified Vanilla Ideology:
    - Scholar Gentry Ideology:
        - Opinions on the economic system law group has been added
            - Agrarianism = Approve
            - Industy Banned = Disapprove
            - Traditionalism = Strongly Approve
            - Interventionism = Neutral
            - Co-Operative Ownership = Strongly Disapprove
            - Laissez-Faire = Strongly Disapprove
            - Command Economy = Strongly Disapprove
            - Extraction Economy = Disapprove

#######################
### Journal Entries ###
#######################
- Meiji Economy Journal Entry:
    - Complete requirement now requires having 70% or more states with railways built, not more than 70% of states with railways
- Warlord China:
    - China having either having a foreign investment agreement or granting foreign investment rights will change the fragile china counter by 1
- Great Game:
    - Great Game journal entries and content are now playable in sandbox mode for multiplayer
    - Won't fail if UK or Russia disband their power bloc. Only if they drop below Great Power rank or any other vanilla fail conditions
- Purveyor of Progress (India Railway):
    - Jounral entry criteria now matches what is said in the tooltip
-
- Opium Wars:
    - Opium Wars journal entries were allowed to be completed in the wrong order, which could cause Qing to not fail the journal entries even though they should
- Americas Migration (Central, South, American West):
    - Protectorates are now also allowed to use the journal entry
- Lobby Demands:
    - Time limit increased from 5 years to 10 years
- German Unification:
    - 30 year timer added to the Schleswig-Holstein journal entry
    - Negative prestige modifier for failing the Schleswig-Holstein journal entry added (-15% prestige for 10 years)
- SRBE Journal Entries:
    - Added journal entries for all SRBE buildings

############
### Laws ###
############
- Health System:
    - Private Health Insurance:
        - State mortality from wealth modifier added (UHD)
    - Public Health Insurance:
        - State mortality from wealth modifier added (UHD)

####################
### Miscellanous ###
####################
- AI UK no longer erroneously hates Indian Democracy
- Insurrections and Secessions now get disbanded when they literal 0 support
- Money can now be sent between countries with exact amounts, to the nearest £1000 (LST)

###################################
### Mobilization Options Groups ###
###################################
- Added option for rifles used to make use of military techs, called Main Rifles

############################
### Mobilization Options ###
############################
- Main Rifles added:
    - Rifles: +5 offense, +5 defense
    - Repeaters: +10 offense, +10 defense, +1 small arms upkeep
    - Bolt-Action: +15 offense, +15 defense, +2 small arms & +1 ammunition upkeep
- Chemical Weapons reworked:
    - Unit kill rate bonus increased from 50% to 100%
    - +200% devastation has been added

###########################
### Political Movements ###
###########################
- Communist movements no longer incorrectly prefers states with high urbanization

##################
### Power Bloc ###
##################
- Power Bloc mandate generation changed. New values are:
    - Great Power: +10
    - Major Power: +4
    - Unrecognized Major Power: +2
    - Minor Power: +1
    - Unrecognized Regional Power: +0.5
- Principle Slots:
    - 3rd slot can be unlocked by having either:
        - Power bloc is 5th or higher in the power bloc ranking
        - Power bloc has 5 or more members
    - 4th slot can be unlocked by having either:
        - Power bloc is 3rd or higher in the power bloc ranking
        - Power bloc has 10 or more members
    - 3rd and 4th power slots will be removed if power bloc doesn't meet either of the requirements (if it works as expected)

#############################
### Power Bloc Identities ###
#############################
- Trade Leagues:
    - Bloc Members:
        - Bloc members cannot embargo each other
        - Increased leverage from economic dependence
    - Bloc Members (Not Bloc Leader):
        +20% convoy contribution to power bloc leader
        -20% Influence
    - Bloc Leader:
        - Has foreign investment rights in power bloc members of lower power rank
        - Can enforce a change in the trade policy law of power bloc members
        - +10% Influence
        - +10% Trade route volume
- Soverign Empires:
    - Bloc Members (Not Bloc Leader):
        - Will become the Bloc Leader's subject upon joining the Power Bloc
    - Bloc Leader:
        - New members will become their subject upon joining the Power Bloc
- Ideological Union:
    - Bloc Leader:
        - Can enforce a change in the economic system law of power bloc members
        - Can enforce a change to the land reform law of power bloc members
        - Can enforce a change to the free speech law of power bloc members
        - Can enforce a change to the slavery law of power bloc members
- Military Treaty:
    - Bloc Leader:
        - Can enforce a change in the army model law of power bloc members
        - +50% weekly unit experience gain for armies and navies
        - -10% Military Goods cost
    - Bloc Members (Not Bloc Leader):
        - +25% weekly unit experience gain for armies and navies
        - -5% Military Goods cost
- Religious Convocation:
    - Bloc Leader:
        - Can enforce a change to the church and state law of power bloc members
        - Clergymen have +50% investment pool contribution efficiency
    - Bloc Members (Not Bloc Leader):
        - Clergymen have +25% investment pool contribution efficiency

#############################
### Power Bloc Principles ###
#############################
- Restrictions:
    - External Trade is restricted to Trade Leagues only
    - Internal Trade is restricted to Trade Leagues only
    - Vassalization is restricted to Soverign Empires only
    - Exploitation of Members is restricted to Soverign Empires only
    - Creative Legislature is restricted to Ideological Unions only
    - Ideological Truth is restricted to Ideological Unions only
    - Defensive Co-operation is restricted to Military Treaties only
    - Aggressive Co-ordination is restricted to Military Treaties only
    - Sacred Civics is restricted to Religious Convocations only
    - Divine Economics is restricted to Religious Convocations only
    - Soverign Empires can only take either Vassalization or Exploitation of Members, not both

- Foreign Investments:
    - Has been removed
    - Been merged into the Market Unification principle

- Market Unification:
    - Level 1:
        - Bloc members cannot embargo each other
        - Increased leverage from economic dependence
    - Level 2:
        - Foreign investment rights in power bloc members of lower power rank
    - Level 3:
        - Power Bloc becomes a customs union

- Advanced Research:
    - Level 1:
        - +25% institution size change speed for education institution
        - -10% bureaucracy cost of education institution
        - Cannot have the No Schools law
        - Bloc Leader can enforce a change in the education system law of power bloc members
    - Level 2:
        - +15% institution size change speed for research institution (+40$ total)
        - -15% bureaucracy cost of education institution (-25% total)
        - +1% education access per institution level
    - Level 3:
        - +10% institution size change speed for research institution (+50% total)
        - -25% bureaucracy cost of education institution (-50% total)
        - +2% education access per institution level (+3% total education access per institution level)

- Food Standardization:
    - Level 1:
        - +10% Agriculture throughput
    - Level 2:
        - Unlocks production method "Efficient Vacuum Canning Practices" for Food Industries
    - Level 3:
        - -5% Pop mortality

- Construction:
    - Level 1:
        - -50% infrastructure usage for construction sectors
    - Level 2:
        - +5% state construction efficiency
    - Level 3:
        - United Construction Conglomerate comany unlocked
            - +5% construction efficiency (down fom +20%)

- Freedom of Movement:
    - Level 1:
        - +20% Migration Quota
    - Level 2:
        - Migration allowed within Power Bloc
    - Level 3:
        - +50% Mass Migration attraction

- Vassalization:
    - Level 1:
        - +2% authority added per subject (changed from +25 authority per allowed subject type)
    - Level 2:
        - +1% authority added per subject (+3% total)
        - Power Bloc Leader gets +25% subject income transfer modifier
    - Level 3
        - +1% authority added per subject (+4% total)
        - Power Bloc Leader can enact decrees in subjects

- Exploitation of Members:
    - Level 1:
        - +20% Power Bloc Leader authority
        - -20% Bloc Member (Not Leader) authority
        - -5 Power Bloc Cohesion
    - Level 2:
        - -5 Power Bloc Cohesion (-10 total)
        - +20% Power Bloc Leader Influence
        - -20% Bloc Member (Not Leader) Influence
        - +10% Power Bloc Leader authority (+30% total)
    - Level 3:
        - -10 Power Bloc Cohesion (-20 total)
        - +10% Power Bloc Leader Authority (+40% total)
        - 5% income transfer from Power Bloc Members to Power Bloc Leader
    
- External Trade:
    - Level 2:
        - Influential Trade Center PM:
            - Influence per level reduced from 2 down to 1
            - Migration attraction bonus removed

- Militarized Industry:
    - Level 2:
        - Miltarg goods cost reduced from -15% down to -10%

- Sacred Civics:
    - Level 1:
        - Higher diplomatic proposal acceptance for countries with same religion
        - -5% morale loss
        - +5% morale recovery
    - Level 2:
        - Reduced liberty desire for subjects with same religion

- Divine Economics:
    - Level 2:
        - New Ownership PM (Clergy Oversight) is now used by requirement in Financial Districts and Manor Houses

- Transportation Infrastructure:
    - Level 1:
        - +33% state infrastructure from population
        - +33% maximum state infrastructure from population
    - Level 2:
        - +250 land trade capacity
    - Level 3:
        - Unlocks the Joint Steam Trains PM for Railways
        - Unlocks the Joint Electric Trains for Railways
        - Unlocks the Joint Diesel Trains for Railways

- Defense Co-operation:
    - Level 2:
        - +10% unit defense

################################
### Production Method Groups ###
################################
- Coal-Liquefaction Plant:
    - Coal to Oil PMs added (Level 1, Level 2, Level 3, Level 4, Level 5)
    - Oil to Rubber PMs added (Level 1, Level 2, Level 3, Level 4, Level 5)

##########################
### Production Methods ###
##########################
- Added timed modifiers for PM Changes:
    - Change in primary PM grants a decaying -20% throughput
	- Change in secondary PM grants a decaying -10% throughput
- Added production methods for Coal-Liquefaction Plant
    - Coal to Oil: 5 Coal --> 1 Oil
    - Oil to Rubber: 5 Oil --> 1 Rubber
- Convoys supplied by Ports have been increased:
    - Anchorages:
	    - Amount of Convoys increased from 20 to 50
    - Industrial Ports:
	    - Amount of Convoys increased from 175 to 250
    - Modern Ports:
        - Amount of Convoys increased from 200 to 400
- Influence provided by Power Block Principle External Trade II & III reduced from 2 down to 1
- Production methods that use Transportation as an input good are blocked until the building has access to Transportation
- External Trade Principle Levels 2 & 3 Trade Center PM now has clerks working. Was 0 clerks per trade center level, now 250 clerks per trade center level (UHM)

########################
### Scripted Buttons ###
########################
- Americas Migration Button Cost:
    Target Countries:
        - Power Rank requirement removed
        - Number of states requirement removed
        - Target state needs to have 250000 state population or higher
        - Target state needs to be in a country that has a total population of 3 million or greater
    Cost of Use:
        - -25% influence cost
        - -10% authority cost
        - Weekly cost of £ equal to 0.025% of GDP, rounded to nearest 100


########################
### Scripted Effects ###
########################
- UHM:
    - Diplomatic Pact Opportunity system for investment rights/agreement fixed

########################
### Static Modifiers ###
########################
- Base Government Dividends efficiency increased by 10%, from 25% to 35%
- Recently adjusted primary production method timed modifier added
- Recently adjusted secondary production method timed modifier added
- Tech spread from literacy doubled, from 75 at 100% literacy to 150 at 100% literacy
- Excess innovation into tech spread reduced from 20% down to 2%
    - Before change, 20% of excess innovation would be added to tech spread
    - After change, 2% of excess innovation would be added to tech spread
- India Company Rule modifier:
    - Industrialist IG Political Strength increased from 200% bonus to 300% bonus

####################
### Technologies ###
####################
- Production:
    - Synthetic Strategic Resources:
        - Era 5
        - Unlocks Coal-Liquefaction Plant
        - Unlocks the Coal --> Oil Production Methods
        - Unlocks the Oil --> Rubber Production Methods

- Society:
    - Pan-Nationalism:
        - Added Identification Documents as an unlocking technology requirement
    - Great War Diplomacy:
        - Era 5
        - Adds 1375 maneuvers to diplomatic plays
        - Reduces war exhaustion from casualties by 65%
    - Medical Degrees:
        - -0.0005% morality per level of wealth
    - Pharmaceuticals:
        - -0.0005% morality per level of wealth
    - Antibiotics:
        - 0.001% morality per level of wealth
    - Urbanization:
        - Land trade capacity increased from 50 to 200
    - Urban Planning:
        - Land trade capacity increased from 10 to 150
    - Modern Sewerage:
        - Land trade capacity increased from 10 to 150
    - Steel-Frame Buildings:
        - Land trade capacity increased from 10 to 150
    - Elevator:
        - Land trade capacity increased from 10 to 150
    - Paved Roads:
        - Land trade capacity increased from 20 to 200

- Military:
    - Gantry Cranes:
        - Now increases the max level of ports by 8 instead of 4
    - Concrete Dockyards:
        - Now increases the max level of ports by 10 instead of 4

###########
### GUI ###
###########
- GDP Graph:
    - Size increased from 280 x 100 to 1400 x 500
- GDP Ownership:
    - UI and tooltip can show how much of a country's economy is owned by foreign investors
    - UI and tooltip can show how much foreign investment a country has in other countries
- Global GDP and POP Stats:
    - Country's percentage of global GDP and POP added to the country's GDP and population tooltip

##############
### Events ###
##############
- Paris Commune:
    - Truce length reduced from 24 months (2 years) down 2 months
- Krakatoa:
    - Krakatoa no longer kills Asia