# Difficulty-and-AI
EU4 mod. https://steamcommunity.com/sharedfiles/filedetails/?id=2453967654

Content:
- Added 10 Idea slots in a balanced way.
- Tweaks to ideas and policies, to make more idea groups relevant.  
- 2 New Estates; City States, Nomadic Aristocracy. ( Mamluks, Janissaries, Ghulam's were cut )
- Added optional Auto Development decision, that develops the cheapest province at monarch point cap. Works for both the Players and AI. Big thanks to LoStack for implementing it. ( https://github.com/stackpoint/Dev-Click )
- Added 5 terrain types to the game, replacing most of the vanilla ones, reworking problem areas of the map. The source of the Images is CK3 and I:R.
- Small map & trade region changes. For example CoT and starting Fort in Paris.
- Monarch point bonus from Consort if consort skills are higher.

Republic Election Changes:
- Elections Candidates will have randomized above average stats.
- Reelecting the same candidate will increase random stat by 1. Reelection cost increases over time.
- Enabling estates for Trade republics.

Nomads:
- Adding 2 new estates for Nomads and Nomads like government types and cultures. City States and Nomad Aristocracy.
- Enabling Clergy for Hordes that have organized religion.
- Nomads or Tribal Federations always have access to Tribes estate. Steppe cultures still can get access to Tribes estate as long as they own steppe provinces.    
- Removing banners reinforcement speed penalty, mainly for gameplay reasons. Reducing the amount of available banners.
- Hordes combat bonus in plains is reduced to 10% shock damage, and penalty to -10% shock damage.
- Horde unity should be easier to maintain.
- Adding Dzungar khanate as possible formable for Oirats with unique NI’s.

Asia:
- Changes to Mandate reforms to make taking Mandate more desirable. By Svatopluk1.
- Celestial Empire will lose 5 Mandate for losing a war.
- Adding 2 more Important Chinese Cities, and corresponding penalties for not controlling them.
- Limiting tributary interactions, monarch point tribute is capped at 6.
- Laying down ground work for AI to form Qing and fully conquer China.
- Changing names for several countries in the region to more appropriate historical counterparts.
- Decision to reform Shogunate to simulate centralized nature of Tokugawa Shogunate a bit better.

Middle East:
- Tribal Governments and Ardabil are getting access to Tribe estate.
- Reducing requirements for Unite Islam decision, turning it on for AI with  exceptions of Ottomans and Mamluks.    



Buildings:
- Regimental Camp and Conscription Center no longer give a flat amount of force limit, now it's +50%, +100% to local force limit. Meaning they give more benefit in high development provinces.
- Ramparts and State House are no longer considered as manufactories. Both have a limit per state and no special bonus from trade goods.
- Ramparts gives 1 fort level and 15% for defense. Defence edict was nerfed a bit to compensate.    
- Reducing flat manpower from Soldiers Households from 750 to 600.
- Naval Battery provides Statewide Block on Slave Raids, but can only be built in a province with Fort. In addition Provides a minor amount of fort defense 10-15%.
- University provides Statewide -10% to local development cost, in addition to provincial -10% to local base development cost. Limited to 1 per state, building cost incised to 500.



Gameplay and Balance changes:
- Added 10 Idea slots in a balanced way.
- Tweaks to ideas and policies, to make more idea groups relevant.
- Major reduction of the amount of Discipline, Force limit and Manpower in the game. For performance and gameplay reasons.
- Small adjustment to cavalry pips, mostly adding defensive pips in a late game.
- More meaningful advisers, weaker Advisers have more to offer.
- Major Mercenary company Rebalance. Adding additional requirements to most unique mercenary companies and making them stronger. Adding new mercenary companies.  
- Light tweaks to Basic Government reforms.
- Effect of corruption was reduced to 1/5 of original game values, and AI is less willing to use debase currency.
- Increased base supply limit by 2, AI tends to have more troops with this mod.
- Custom Ruler traits. Restricting Ruler traits distribution, rulers with high stats are less likely to get negative traits.
- Reducing the price of Coal, getting Coal in a province should automatically delete existing outdated manufactory.
- Fixes and tweaks to Hegemon’s. Preventing AI from claiming Eco hegemon after getting some cash in a peace deal.
- Small touch to Muslim faith, reworking old convert decisions and enabling it for AI.
- Increasing duration of Muslim Schools bonuses by 10 years.
- Removing shock damage taken penalty from Marines, Marines take 50% less attrition at sea.
- Small changes to trade regions, Bordeaux is an end node, White sea flows into Novgorod.
- Nerf to trade propagation, from 20% to 10%. It makes Inland trade nodes much more viable.
- Land and naval maintenance increase from technology is nearly 3 times higher in the mod. This is done for balance reasons, as AI is much better at managing its economy and it affects the game world as a whole. More income can be made from trade etc.
- Removing build cost and build time reduction from Expand infrastructure.
- Doubling duration of Supply Depot interaction.
- Reducing prestige hit from changing secondary religion from -50 to -25.
- Aggressive Expansion, Removing Province from HRE, Annex Vassal opinion penalty is capped at 100.
- Capital bonuses for governing costs are reduced from -100% to -25%. 
- Bigger penalties from Overextension and not accepted cultures. Mainly unrest.
- Gentler terms that the victor doesn't directly benefit from are changed to have a significantly lower cost.
- Various small exploits and bug fixes. If we know about it, it can be fixed.




Everything AI:
- Added difficulty scaling and settings screen.
- AI is more aggressive on higher difficulties.  
- Stopping AI from debasing currency.
- Restricting AI army movements a bit, AI should behave more defensively.
- Improved AI building logic, AI should build manufactory in every province.
- More aggressive AI logic for new Estates, the bottom line for AI is 10% crown land.
- Making sure that AI will take all possible Privileges that give monarch points.
- Monarch point Privileges are disabled for AI OPM's for balance reasons.  
- Fix for logic behind Religious interaction. Orthodox Icons and Anglican aspects.
- Increased AI budget fraction for missionary maintenance.
- Lowering early game cannons ratio for AI.
- Lowering AI transport ship ratio.
- AI should use guarantees less often.
- Humiliate option in peace offer is more desirable for AI.  
- Changed AI reasons for giving subsidies, AI will prioritize sending it to Allies in debt.
- Increasing AI score for accepting cultures.
- Reducing bonuses for Lucky nations, mainly 25% manpower recovery was changed to 10%.
- Increased Autonomy and Harsh treatment interactions are disabled for AI.
- Random events that generate Generals with high army tradition would have lower outcomes for AI.
- AI is blocked from taking the mandate of heaven in a war. There are no checks or logic in peace options for AI unfortunately. AI will take it via separate decision once it fulfills the requirements.
- Preventing AI Hordes from forcing tributary status in a peace deal. 
- Enabling various decisions for AI.
- Various small AI fixes.

AI specific scripting:
- AI building script, takes over if AI is spazzing out.
- AI scripting that upgrades Forts and deletes redundant Forts.
- AI expansion planner, AI specific agendas that generate claims.
- A way for AI to Expand infrastructure, Raze Provinces, Decrease autonomy.
- Ability for some AI personalities to dev push institutions. Only works if AI Auto Dev is On.
- AI Pope can now use the Investigate Heresy button, with 10 years duration on it.
- AI events that disband Mercenary Companies.


Known problems
- AI doesn't like using Edicts, same issues as in 1.30.
- Weird edge cases where AI will start deleting all their forts. Restarting the game might help.  
- AI attitudes can no longer be locked. 


Special thanks to ppl who helped us test development build and provided feedback along the way: 
Atwix
Derrurak
