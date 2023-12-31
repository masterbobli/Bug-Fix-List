# Issues Fixed
Note: the presence of "?" in some entries indicates that there is code implemented to address the reported issue, but it has not been thoroughly tested yet.

## General
- Various formable nations fix, including
    - Cannot form Gran Colombia as Crucao and Guyana.
    - Cannot form Central America as Belize.
    - Decisions to form new countries do not add core to some states split from a later update.
    - Greater Lithuania and Greater Commonwealth don't have cores in Balta-Tiraspol.
- Ship Designer's "Upgrade All Modules" functionality only upgrades Anti-air to Level 3. [Link](https://forum.paradoxplaza.com/forum/threads/ship-designers-upgrade-all-modules-functionality-only-upgrades-anti-air-to-level-3.1590434/)
- AI will ignores all subsequent modifiers when setting the `ai_chance` value to be `factor = 0`. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-setting-factor-0-in-ai_chance-ignores-the-modifiers-1-10-5-502a.1468930/)
- German civil war overrides the play-set AI behavior of the UK and Italy to follow the historical path. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-german-civil-war-overrides-the-play-set-ai-behavior-of-uk-and-italy-to-follow-the-historical-path.1561968/)
- Some intended permanent move of capitals could move back to the former location after recapturing the former capital.
- ? Decision "Industrial Land Appropriation" pops up when no slots can actually be added. [Link](https://forum.paradoxplaza.com/forum/threads/industrial-land-appropriation-pops-up-if-you-have-no-states-with-5-5-infra-but-only-takes-stab-and-ws-adding-no-slot.1583429/)
- Doctrine "Naval Strike Torpedo Tactics" in the Operational Integrity tree is miscategorized as a doctrine from the Battlefield Support tree. [Link](https://forum.paradoxplaza.com/forum/threads/doctrine-cost-bonus-from-theorist-not-applied.1590381/)
- Non-existent dynamic tags can be valid collaboration government targets.
- Collaboration government creates a dynamic tag even when the original tag can be released.
- Releasing collaboration governments will give your core states to the collaboration government. [Link](https://forum.paradoxplaza.com/forum/threads/why-do-collaboration-governments-take-your-core-states.1358376/)
- State ownership changes cause loss of extra building slots. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-building-slots-and-buildings-getting-destroyed-when-releasing-a-nation-and-created-nation-not-inheriting-tech-v1-12-6-beta.1557693/)
- Trigger `is_controlled_by_ROOT_or_subject` doesn't have a loc key.
- Typo in spirit of the airforce "Industry Liaisons".
- Slovenia has an incorrect capital. [Link](https://forum.paradoxplaza.com/forum/threads/some-emergent-countries-have-incorrect-capitals.1578066/)
- Event "treaty_org.4" does not have a title.
- Spirit of the Academy "Embrace the future" gives new officers Panzer Leader instead of Armor Officer. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-embrace-the-future-spirit-of-the-academy-in-officer-corps-usually-gets-you-panzer-leader-and-not-panzer-officer-barbarossa-v1-11-12-82b4.1538946/)
- Several news events about the capture/liberation of states don't fire properly. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-the-news-of-the-fall-of-singapore-has-ceased-to-appear-1-9-0-last.1341120/)
- Some state modifiers are added to the country scope, and vice versa.
- AI is unlikely to invest in Greece or Turkey unless they have unused civilian factories. [Link](https://forum.paradoxplaza.com/forum/threads/greek-foreign-investment-decisions.1442150/)
- Several AI factors that demand other countries to be puppeted/annexed from Poland/Baltics are incorrectly written.
- AI does not hire advisors who possess the traits of communist revolutionary, democratic reformer, or fascist demagogue even when specifically instructed to do so most of the time.
- Fascist Occitania does not have small or medium flags. [Link](https://forum.paradoxplaza.com/forum/threads/fascist-occitania-wrong-flag.1596087/)
- Fixed several misspellings of "snorkol" in the English localisation.
- Decision "Dismantle the maginot line" does not dismantle forts in Picardy if France extended the maginot line.
- Generic decision to purchase Soviet Ships don't work. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-ethiopia-cant-purchase-soviet-ships.1554391/)

## Australia
- Australia Support Indonesian Uprising does not make Indonesia an Australian puppet. [Link](https://forum.paradoxplaza.com/forum/threads/australia-support-indonesian-uprising.998864/)

## Baltic
- "Forest Brothers" divisions don't spawn in Baltic shared communist civil war. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-steam-v1-11-4-e26e-b22c-blatic-shared-communist-civil-war-not-working-as-intended.1505469/)
- Incorrect Annexation of Belarus in the Belarussian Civil War. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-launching-civil-war-in-belarussian-states-with-high-claims-results-in-winner-directly-annexing-the-soviet-belarus-without-getting-cores.1502952/)
- Communist Baltic countries keep generals with anti-bolshevism traits in civil war. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-communist-baltic-countries-keeps-generals-with-anti-bolshevism-traits-in-civil-war.1502948/)
- Lithuania's Baltic Entente decision has a few TODO effects.

## China
- Dali doesn't have the state modifier "Densely Populated Rural Area". [Link](https://forum.paradoxplaza.com/forum/threads/code-error-in-hearts-of-iron-iv-history-countries-chi-china-txt.1584851/)
- Decisions "Evacuating Factories" don't work. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-evacuating-factories-china-decisions-still-dont-work-windows-steam-1-11-11-2eb0-8e75.1530192/)
- Focus "Dominate Japan" and "Integrate Tibet" can still be taken when being a puppet.

## Communist China
- The hidden event that ages Mao Zedong doesn't work. [Link](https://forum.paradoxplaza.com/forum/threads/cant-get-the-people-have-stood-up-achievment.1580470/)
- Warlords cannot bypass focuses in the communist tree that has no effects.
- Parts of China Mao received after the Chinese United Front is disbanded contain no states.

## Estonia
- National Focus "Unite the Finnic Identity" doesn't give cores on some states.

## Ethiopia
- Decision "Invite Foreign Prospectors" is not visible sometimes. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-ethiopia-focus-and-decision-bugged-invite-foreign-prospectors.1546224/)
- The effect to add VP to the city in Begemder targets a province in Afghanistan. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-the-effect-to-add-vp-to-city-in-begemder-targets-a-province-in-afghanistan.1560699/)
- AI Italy never agrees to Ethiopian territorial compensation. [Link](https://forum.paradoxplaza.com/forum/threads/ai-italy-never-agrees-to-ethiopian-territorial-compensation.1547749/)
- Dynamic modifier "Ethiopia Airforce" doesn't have a correct icon when upgraded.
- Ethiopia doesn't use the unique electrify state icon.
- Event "Economic Boom in (State)" does not increase building slot factor.
- Ethiopia led by Haile Selassie will also transfer states to Italy after winning the fascist civil war.
- The event to inform Ethiopia that Italy starts major offensive/build up does not trigger.
- Event "Major Italian Offensive" is triggered when Italy decides to build up.

## France
- Focus "Disunite Germany" does not release Austria as a puppet. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-hoi4-v-1-11-4-b22c-taking-the-focus-disunite-germany-as-france-fails-to-release-austria-as-a-puppet.1504136/)
- Focus "Grow the Empire" only gives parts of Belgian Congo to France. [Link](https://forum.paradoxplaza.com/forum/threads/national-focus-grow-the-empire-now-only-gives-parts-of-belgian-congo-to-france.1587416/)
- ? AI behavior "Democratic - Alternate" is not working. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-french-ai-behavior-democratic-alternate-little-entente-is-not-working.1556634/)
- National spirit "Disjointed government" cannot be removed if focus "Force the Issue" is bypassed. [Link](https://forum.paradoxplaza.com/forum/threads/france-flipping-ideology-through-election-prevent-the-removal-of-disjointed-government-national-spirit.1595383/)
- Richelieu Class is considered to be a battlecruiser instead of a battleship. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-windows-10-v-1-12-4-aefa-f96e-richelieu-battleship-class-considered-as-a-battlecruiser.1549761/)
- ? Free France intervention decisions may transfer states not owned by Vichy. [Link](https://forum.paradoxplaza.com/forum/threads/free-france-intervention-focuses-decisions-dont-check-that-states-are-owned-by-vichy.1594800/)
- AI France is more likely to cede Indochina to Japan if its at war with a minor country.
- ? Decision to directly intervene Spanish civil war have no effect if France is communist and AI Spain chooses the anti-stalinist path.

## Germany
- Reinstated fascist generals have incorrect portraits. [Link](https://forum.paradoxplaza.com/forum/threads/incorrect-portraits-for-reinstated-nazi-germany-unit-leaders.1592764/)
- Democratic Germany cannot protect the state Gydinia when Poland is attacked by the Soviet Union.
- National Focus "Alliance with Spain" does not remove all 3 versions of "Recovering From Civil War" national spirits from Spain. [Link](https://forum.paradoxplaza.com/forum/threads/german-focus-alliance-with-spain-does-not-remove-recovering-from-civil-war-for-spain.1588838/)
- Decision category "Reichskommissariats" uses a generic icon.
- RK Ukraine does not require Germany controlling Balta-Tiraspol.
- Günther von Kluge may not be the country leader if Wehrmacht is asked to restore order in the SS civil war.
- Germany doesn't receive the correct cosmetic tag in SS civil war.
- Freeing Wilhelm II from the Netherlands gives Wilhelm III as country leader. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-as-germany-freeing-wilhelm-ii-from-the-netherlands-gives-wilhelm-iii-as-country-leader.1553489/)
- Typo in event option `wtt_germany.20.a`.
- National Focus "Operation Tannenbaum" cannot be bypassed due to a broken trigger. [Link](https://forum.paradoxplaza.com/forum/threads/german-focus-tree-oversight-tannenbaum.1598180/)
- National Focus "Befriend Poland" cannot be bypassed due to a broken trigger.
- ? Decision "Dismantle the Maginot Line" does not remove forts in Picardy if France extended the Maginot Line.

## Greece
- Decision "Form Greater Greece" is available when Adolfos I becomes the leader.
- Various fixes to the Heraklion Convention. (Credit to Mefisto1029)
- Event "Communists Seize Power in Greece" is incorrectly sent to the Soviet Union. [Link](https://forum.paradoxplaza.com/forum/threads/event-communists-seize-power-in-greece-incorrectly-sent-to-soviet-union.1594907/)
- AI Greece always arrests the king with historical AI focuses off.
- "Edirne" does not get renamed to "Thracia" when forming Byzantium.
- "Balıkesir" does not get renamed to "Palaeokastron" when forming Greater Greece. [Link](https://forum.paradoxplaza.com/forum/threads/greater-greece-decision-renaming-cities.1596368/)

## Hungary
- Focus "Reclaim the Empire" cannot be taken if Hungary already controls one of the required states.

## Italy
- Fascist Italy is unable to progress in focus tree after the anti-fascist civil war. [Link](https://forum.paradoxplaza.com/forum/threads/fascist-italy-unable-to-progress-in-focus-tree-after-anti-fascist-civil-war.1590660/)
- The civil war triggered from BOP doesn't switch RDS to the correct ideology.
- The "Lost Cores" modifier does not get removed after recapturing the state. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-hoi-iv-italian-balance-of-power-lost-core-modifier-bug-1-12-11-checksum-66ce.1572437/)
- Focus "Flotta d'Evasione" is always locked with MtG DLC enabled. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-1-12-11-italian-focus-flotta-devasione-not-possible-with-mtg.1572710/)
- Modifier "Mafia on the Rise" is added to the country scope and cannot be removed. [Link](https://forum.paradoxplaza.com/forum/threads/mafia-on-the-rise-doesnt-go-away.1586525/)
- Anarchists respond to themselves when communist Italy wants to cooperate with them. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-hoi-4-anarchists-responds-to-themselves-when-communist-italy-want-to-cooperate-with-them.1546020/)
- Cannot release Ethiopia (and its constituents) with 70% compliance. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-italy-cant-release-ethiopia-even-with-the-required-compliance.1551526/)
- Kingdom of Bosporus cannot be established if Crimea controls one of the required states.
- Duplicate bonus for the production cost of heavy tanks in the Italian focus tree. [Link](https://forum.paradoxplaza.com/forum/threads/missing-bonuses-for-italian-military-industry.1592898/)
- Focus "Corpo di Truppe Volontarie" can be bypassed before the Spanish civil war begins. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-ita-corpo-di-truppe-volontarie-bypasses-if-the-focus-foreign-affairs-has-been-completed-before-the-spanish-civil-war.1562143/)
- Mussolini can come to power again after being deposed through focus.
- Greece/Turkey fails to join the Italian faction in the trade of Dodecanese islands. [Link](https://forum.paradoxplaza.com/forum/threads/greece-turkey-fails-to-join-italian-faction-in-the-trade-of-dodecanese-islands-with-solution.1590557/)
- Local Ethiopian rulers don't become country leaders if Italy attempts to release subject countries when Ethiopia goes into exile. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-pc-v1-12-2-9ebb-e45c-s-ethiopian-sub-nations-dont-use-unique-portraits.1545774/)
- Gasperi, the Pope, and king Umberto does not have the balance of power changed in focus Proclaim the Italian Empire.

## India
- The strength of the Indian civil war does not properly scale with autonomy level.

## Japan
- Focus "Approach the Young Officers" only gives 1 communist general. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-hoi-4-v1-11-3-b175-33b6-possible-communist-japan-bug.1503098/)

## Lithuania
- Focus "Request Polish occupation" transfers ownership of occupied Polish states while transferring the occupation of owned Polish states.
- Bolesław Piasecki doesn't become the country leader of Lithuanian Poland.

## Latvia
- "Ignite the [Country] Civil War" decision only targets Poland. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-latvias-ignite-civil-war-decisions-do-not-work-v1-11-2-a194-7844.1499979/)
- AI always picks the non-aligned side of the fascist civil war even when the AI is set to take the fascist path.

## Manchukuo
- Aisin Gioro Puyi loses the Nationalist Symbol trait when the Chinese Empire is formed. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-aisin-gioro-puyi-loses-nationalist-symbol-trait-when-chinese-empire-is-formed.1574405/)

## Poland
- Free City of Danzig loses core on Danzig when they rise up against Poland. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-free-city-of-danzig-looses-core-on-danzig-when-they-rise-up-against-poland.1561972/)
- Focus "Enforce Baltic Socialism" triggers events demanding Poland to become a puppet of itself. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-doing-enforce-baltic-socialism-while-owning-latvia-results-in-poland-demands-submission-from-itself-1-11-1-bf90.1499394/)
- Many triggers and effects in focus "Enforce Baltic Socialism" and "Commonwealth of Socialist Republics" don't work.
- ? Event to demand the return of Otto von Habsburg only removes one variant of the Hungarian Monarchy national spirit.
- ? AI Germany is more likely to accept alliance request from Poland if they have a wargoal against Poland

## South Africa
- Four national focuses on autonomy progress have no requirements. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-focus-south-africa-first-enables-south-africa-to-declare-independence-regardless-of-autonomy.1548439/)

## Soviet Union
- Various issues in the Soviet Civil War, including
    - The Stalinist Soviet Union spawned from the civil war is unable to continue the focus tree.
    - The Stalinist Soviet Union spawned from the civil war still keeps the opposition strategy plan.
    - Limited variation in AI's pre-Soviet civil war base of operation selection. [Link](https://forum.paradoxplaza.com/forum/threads/limited-variation-in-ais-pre-soviet-civil-war-base-of-operation-selection.1590269/)
    - National spirit "Anti-Soviet Thinking" cannot be removed after the right opposition coup. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-impossible-to-get-rid-of-anti-soviet-thinking-for-bloodless-coup-right-opposition.1539444/)
    - Design bureaus cannot be reinstated immediately after the right opposition coup.
    - The Soviet civil war pauses the Communist Baltic civil war.
    - Stalinist Soviet Union doesn't keep the negative great purge modifiers.
    - Unit leaders promoted to country leader in the uprising side may side with Stalin sometimes. [Link](https://forum.paradoxplaza.com/forum/threads/soviet-opposition-may-have-generic-leader-during-civil-war.1592951/)
    - States targeted by right opposition uprisings don't align with the right opposition at the start of the civil war.
    - Decision "The Head of the NKVD - Yezhov" references Yagoda in the description instead of Yezhov.
- Sakhalin and the Kuril Islands are not cored by the USSR. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-sakhalin-and-the-kuril-islands-dont-cored-by-ussr-v1-12-13-e502.1500386/)
- Event "Promise of Peace Broken" fires to the wrong country when declaring war on the Soviet Union. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-promise-of-peace-broken-event-fires-to-the-wrong-country-when-declaring-war-on-soviet-union.1547603/)
- Decision "Demand Increased Tribute" does not reduce the decision cost for the "Direct Rule from Moscow" decision. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-demand-increased-tribute-doesnt-reduce-the-decision-cost-for-decision-direct-rule-from-moscow.1508444/)
- The Right Opposition can lock itself out of its focus tree. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-right-opposition-can-lock-itself-out-of-its-focus-tree.1545180/)
- The Soviet Union has a visible operation to infiltrate its own atomic program.
- The Soviet Union cannot release any country that is not a constituent of the Soviet Union.
- Soviet unit leaders may accuse themselves of treason.
- Yakovlev designer always becomes the first aircraft designer being targeted in a great purge. [Link](https://forum.paradoxplaza.com/forum/threads/fixed-rng-causing-yakovlev-design-bureau-to-be-consistently-targeted-in-the-great-purge.1590971/)
- ? Russia will not receive an event if the fascist American country refuses to join the faction through focus Intervention in the Americas.
- Soviet Union is twice as likely to pick "Right Opposition Cooperative" path in ahistorical mode.
- Random purges can still be triggered if a great purge is already going to be triggered from Stalin's counter-measure missions.
- ? Focus "Regional Development" add building slots to Qingdao instead of Dushanbe.
- ? Khakassia is not considered as a Soviet Republic.

## Spain
- Various issues in the Spanish Civil War, including
    - Carlist Spain has a duplicate Carlism national spirit. [Link](https://forum.paradoxplaza.com/forum/threads/carlist-spain-have-a-duplicate-carlism-national-spirit.1589990/)
    - Franco may die if the focus "Caudillo of Spain" is completed twice.
    - Spain with a dynamic tag does not display advisors correctly. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-rebel-tag-republican-spain-cannot-start-enlist-the-carabineros-focus-1-11-1f6bd-bf90.1499282/) [Link](https://forum.paradoxplaza.com/forum/threads/triggers-and-tooltips-involving-characters-are-broken-in-spanish-civil-war.1589975/)
    - Characters now go to the correct countries.
 - Province modifier "Autonomous State" doesn't get removed when countries are released as free. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-sakhalin-and-the-kuril-islands-dont-cored-by-ussr-v1-12-13-e502.1500386/)
- Global Defence Council has a duplicate decision to core Balearic Islands and Canary Islands. [Link](https://forum.paradoxplaza.com/forum/threads/duplicate-coring-decisions-for-islas-baleares-and-islas-canarias.1595410/)
- National spirit "Popular Front" does not update properly sometimes.

## Switzerland
- President initiatives modifies stability and war support factor instead of stability and war support.
- ? Decision "Seize Fascist Gold" does not appear. [Link](https://forum.paradoxplaza.com/forum/threads/there-is-a-problem-with-the-available-of-the-decision-swi_seize_fascist_gold.1599765/)

## Turkey
- Can't remove the negative Turkish/Ottoman national spirit "Sectarian Woes." (Note: Only a partial fix for Kurdistan is implemented) [Link](https://forum.paradoxplaza.com/forum/threads/cant-remove-negative-turkish-ottoman-national-spirit-sectarian-woes.1577414/)
- Turkey's alternate history strategy plan is enabled for all countries.
- The US receives resource rights in Antalya instead of Afyon in the Chester concession. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-us-receive-resource-right-in-antalya-instead-of-afyon-in-chester-concession.1558082/)
- Setting Turkish AI behavior to Ottoman may not work sometimes. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-setting-turkish-ai-behavior-to-ottoman-may-not-work-sometimes-1-10-5-502a.1468899/)
- Missing description for the national spirit "Sectarian Woes" in Turkey. [Link](https://forum.paradoxplaza.com/forum/threads/missing-description-for-national-spirit-sectarian-woes-in-turkey.1590972/)
- A few issues with the mission "Kurdish Resistance Escalates Anti-Government Efforts." [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-a-few-issues-with-the-mission-kurdish-resistance-escalates-anti-government-efforts-1-10-5-052a.1471676/)
- Focus "The Pontic Redoubt" appears twice in the Turkish alternate fascist plan. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-focus-tur_the_pontic_redoubt-appeared-twice-in-the-turkish-alternate-fascist-plan-1-10-5-502a.1474310/)
- Austro-Hungarian Empire does not form or join the faction after completing the focus "Press the Austro-Hungarian Claim". [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-turkish-focus-press-the-austro-hungarian-claim-not-working.1438077/)
- Ataturk will may die twice. [Link](https://forum.paradoxplaza.com/forum/threads/turkish-focus-tree-nation-bugs.1592046/)
- Unable to removenational spirit "Disorganised Armed Forces" through decisions as Turkey. [Link](https://forum.paradoxplaza.com/forum/threads/unable-to-remove-disorganised-armed-forces-national-spirit-through-decisions-as-turkey.1593204/)
- ? Ataturk may still be the leader of CHP after passing away. [Link](https://forum.paradoxplaza.com/forum/threads/zombie-ataturk.1591982/)
- Focus "Reclaim the Makedonyalı Sanjak" cannot be bypassed due to a broken trigger.
- Focus "Reinstate the Darülfünûn-u Şahâne" can be bypassed if you're not in a faction.

## United Kingdom
- The portrait of Winston Churchill is abnormal in non-Latin alphabet-based localisation. [Link](https://forum.paradoxplaza.com/forum/threads/protrait-of-winston-churchill-is-abnormal-in-non-latin-alphabet-based-localisation.1586877/)
- ? The United Kingdom will not have cores on the US states if it reclaimed Canada through an imperialist civil war after forming the Imperial Federation with the North America dominion established. [Link](https://forum.paradoxplaza.com/forum/threads/no-cores-from-imperial-federation.1455596/)
- Focus "Secure the Italian alliances" will bypass if BBA is not enabled. [Link](https://forum.paradoxplaza.com/forum/threads/the-focus-secure-the-italian-alliance-appears-to-bypass-no-matter-the-status-of-italy.1597338/)

## USA
- Conflicting plans prevent the AI United States from changing ideology. [Link](https://forum.paradoxplaza.com/forum/threads/conflicting-plans-prevent-ai-united-states-from-changing-ideology.1590275/)
- Chromium mines in Alaska can be expanded indefinitely. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-infinite-chromium-in-alaska-1-12-6-46b6-a6ba.1559922/)
- ? Non-MTG naval OOB starts with duplicate submarines. [Link](https://forum.paradoxplaza.com/forum/threads/hoi-4-usa-starts-with-extra-submarines-without-mtg.1574789/)
- ? Decision "Homeland Defense Emergency Act" and both events for the US to return to democracy only remove the initial version of the great depression.
- Philippines does not have the correct party popularity set. [Link](https://forum.paradoxplaza.com/forum/threads/fix-the-incorrect-display-of-the-popularity-of-philippine-parties.1594613/)
