# TERA-92.03-GM-Commands
Here's the GM commands for TERA 92.03 Retail

## Arbiter Server GM Commands

```
/@add_card_collection_point [point] //Add card book score
/@add_city_war_guild_ban [leagueId][guildDbId] //Add Battle Battle Guild Ven List
/@add_citywar_taxpot [taxId][taxMoney] //add tax
/@add_dungeon_abnormality [continentId] [abnormalId] [startTime] [endTime] //Add Dungeon Abnormality Event
/@add_event_system [Condition Minimum Level][Condition Maximum Level][Condition Class][Event Type][TargetTemplateId][Number of Achievements] //Add event system event
/@add_friend [userName] //add friend
/@add_friendship [userName] [point] //Increase friendship with the friend
/@add_friendship_party [point] //Add friendliness to friends among party members
/@add_guild_contribution_point [point] //Acquisition of guild contribution (weekly repayment cannot be exceeded)
/@add_guild_exp [exp] //Acquire Guild EXP
/@add_guild_money [coin] //Acquisition of guild funds
/@add_guild_point [point] //Get points
/@add_guild_quest [questTemplateId] //Add guild quest to the list
/@add_guild_this_week_play_time [guildName] [addTime(unit:sec)] //Add thisweekplaytime to a specific guild
/@add_item_period [itemTemplateId] [eventStartTime] [eventEndTime] [itemPeriodTime] //Add period item information
/@add_many_friends [count (1~50)] //Create multiple users and add friends
/@add_namepreempt_event [event class][time interval] //Add nickname preemption event
/@add_package [PackageId] [ExpireSecond] {[UserName]} //Account Trait Package setting
/@add_vip_game_exp [exp] //Vip system game experience
/@add_vip_pub_exp [exp] //Vip system publisher experience acquisition
/@number of add_vip_token //Increase VIP Token
/@addawakenchange [scrollTID] [scrollCount] [materialCount] //Add awakening transformation data (1 day)
/@addawakenenchant [scrollTID] [scrollCount] [materialCount] [enchantStep] [combatRank] [combatType(1,3,4,5)] //Added awakening enhancement data (1 day)
/@addstyleshop [itemTid] or [itemTid] [saleStart] [saleEnd] [previewStart] [previewString] [price] //Add style shop sale item
/@apply_party //party support
/@assign_floating_castle Floatability ID //Floating payment
/@assign_guild_emblem Emblem Type, Emblem Id //Giving Guild Emblem
/@auto_recalc_tb_avg [on/off] //Automatically calculate the average transaction price of the trading agency on/off
/@battlefield [battleFieldId other-username] //enter the battlefield
/@blocklist_max [count] //Change the number of users that can be blocked
/@BOT_check //
/@BOT_recvmsg //
/@calc_guild_level_ranking //recalculate guild level ranking status
/@card_collection_level [level] //Change card encyclopedia level
/@cc [Args..] //Client command (QA)
/@change_achievement_season [Season ID] //Change achievement season
/@change_date [date] //Change server date
/@change_deco_ui [decoUIId] //Change deco ui
/@change_guild_member_count [Guild name] [Number of guild members to change] //Adjust the number of guild members in a specific guild
/@change_loading_screen_status [Loading Screen Control Status] //Loading Screen Control
/@change_pr //Change PR text
/@change_shop_status //change shop status
/@change_time [time] // change server time
/@change_voice //
/@char_record character recording //character recording
/@char_record_end Stop character recording // Stop character recording
/@check_premium_slot_reset_time //Check premium slot reset time
/@check_simple_tip simpleTipId // Check with this simple tip
/@chnage_city_war_interestOnly [leagueId][on/off] //Stakeholder position setting function
/@chrono_debug [mode] //chronoscroll debug mode
/@clear_achievement_season //Initialize achievement season DB (requires server restart)
/@clear_all_item_period //Batch deletion of fixed-term item information
/@clear_all_pverank //PVE dungeon record and ranking are all reset
/@clear_all_pvprank //PVP battlefield record, reset all ranking
/@clear_all_serverachievement // Initialize all server achievements
/@clear_bf_cool //Clear all battlefield cooldown and entry count
/@clear_board //Climbing bulletin board writing [id] [content] [number]
/@clear_friend_request //reset friend request restrictions
/@clear_inven // clear all inventory
/@clear_level_reward Delete level event rewarded record //
/@clear_package {[UserName]} //Account Trait Package initialization
/@clear_parcel [character name] // empty the parcel of the target character
/@clear_pverank [continentId] //Remove all season records of the dungeon
/@clear_pverank_player [continentId] //Clear his dungeon record
/@clear_recipe // clear RECIPE
/@clear_saevent // Delete all cumulative attendance events
/@clear_serverachievement [id] // Initialize server achievement
/@clear_simple_tip //initialize simple tip check information
/@clear_tb_avg_price // Clear all average transaction price of the trading agency
/@clear_vip_reward_recv // Reset VIP reward information
/@clear_vip_token_recv // Reset VIP Token acquisition information
/@clear_vote_cool // Clear all voting cooldown
/@clear_wanted_writing // Completely initialize the guild request system (until each cooldown)
/@clientCommand [Args..] //Client command (QA)
/@collect_floating_castle Float ID //Float recovery
/@collect_guild_emblem Emblem Type, Emblem Id //Giving Guild Emblem
/@connection //close connection
/@consoleprint_commandlist // List all admin commands ConsoleLog output
/@crash_arbiter // crash the arbiter
/@create_bill_account // create account
/@create_guild [guild-name] [first-username] //Create a new guild
/@create_many_guilds [count:1~99] //Create a lot of guilds (Give basic guild membership conditions)
/@create_many_guilds_and_users [guild count:1~99] [user count:2~60] //Create a lot of guilds (randomly grant guild registration conditions) and randomize the number of users
/@create_many_guilds_for_invite_user_to_guild [count:1~20] // Create (many) guilds and send me guild invitations
/@create_many_guilds_random_condition [count:1~99] //Create a lot of guilds (random guild registration conditions)
/@create_many_users_and_apply_guild [count:1~20] //Create (many) users and apply to join the guild
/@create_many_users_for_guild_wanted_writing [count:1~20] //Creates (many) users and registers a guild wanted article
/@create_many_users_to_my_account [count] //Create a lot of users in my account
/@create_many_users_to_my_guild [count:1~50] //Join many users in my guild
/@create_user [username] // create a new character
/@dailyevent [dayOfWeek] //Change the date of the day of the week (0:None 1:Sun 2:Mon ... 7:Sat)
/@dbg_break //debug-Force break point exception
/@del_city_war_guild_ban [leagueId][guildDbId] //Addition of Guild Ven List for Battle
/@del_city_war_rank [leagueId][SeasonId][guildDbId] //Delete ranking
/@delete_all_event_system //Event Remove all system events
/@delete_all_parcels // Delete all mail information from DB (requires server restart)
/@delete_friend [userName] //Delete friend
/@delete_friend_limit_off //Set unlimited friend deletion
/@delete_item_period [itemTemplateId] //Delete item information for a period
/@deleteawakenchange [eventId] // Delete awakening data
/@deleteawakenenchant [eventId] // Delete awakening data
/@dis // just disconnect the client test
/@dungeon_log [on/off] //Enable dungeon log
/@escape character name //Move to somewhere
/@friendlist_max [count] //Change the number of users who can register friends
/@fund_coin [Funding acmount] //Cash charge
/@gara_pub_exp [on/off] //Acquire publisher experience through fake in-game store
/@get_bf_result_resettime //find the last rating reset time
/@getplaytime //PC room access time Promotional access time information
/@give_guild_incentive [incentiveRate] //Guild rewards are paid by mail
/@gmevent_change_maxjoincount // Change the maximum number of GM events per day
/@gmevent_notice [Notice] //Notice of GM event operator
/@guild_cooltime on/off // Guild joining cooltime OnOff
/@guild_join_cooltime //Set the guild re-join cooltime
/@guild_level [level] //Change level
/@guild_quest_add_limit_time [addMin] //Increase or decrease the remaining time limit of the guild quest in progress
/@guild_quest_clear [questTemplateId] //Clear guild quest progress information
/@guild_quest_complete [questTemplateId] // Guild Quest Complete
/@guild_quest_start [questTemplateId] //Start guild quest
/@guild_quest_usable [on/off] //Guild mission available on/off, guild membership is modified
/@Guildaddmax [amount] //100 is the maximum number of guild members up to 100, 0 is the original
/@guildwar_cancel [Guild name] //Withdrawal of declaration of guild war
/@guildwar_cooltime [minute] //Proclamation, withdrawal, surrender cooltime applied
/@guildwar_declare [Guild Name] //Declaration of Guild Wars
/@guildwar_immediate //Start immediately with all guild wars waiting to be progressed
/@guildwar_surrender [guild name] // surrender in guild war
/@help [keyword] //Search QA command
/@huntingevent_add [type] [hz] [val] [duration] //Add hunter event
/@huntingevent_remove [event id] //remove hunter event
/@import_characters //
/@increase_guild_reward_point [point] // Update guild mission points
/@info_dungeon //Display the output contents of [Basic information]>[Indones]
/@init_awesomium // Initialize Awesomium
/@init_battlefield_season //Reset the battlefield season
/@init_dungeon_season //Dungeon season reset
/@init_guild_wanted_writing_rewrite_time //Remove re-registration time for guild wanted
/@init_limited_gacha [gachaId] //init LimitedGacha
/@insert_floating_castle_parts PartId //Add parts to parts inventory
/@join_guild [guildName] //Join a guild
/@limited_gacha_go_next_bucket [gachaId] [1/0] //go next bucket
/@load_gmevent // Load GM event datasheet
/@load_saevent // Add cumulative attendance event for test defined in datasheet
/@logout // logout test
/@lord_behavior [behavior-type-id] //Send lord achievement behavior test message
/@makeitem_mprate [luxury magnification] //Fix luxury magnification when using makeItem command
/@makeuser_pverank [ContinentId][StageLevel][UserCount:1~100] //Register dungeon ranking after creating user
/@makeuser_pvprank [UserCount:1~100][BattleFieldId] // Register battlefield ranking after user creation
/@masterpiece //
/@nexus_broadcast //
/@nexus_bypass //
/@observer_mode [on/off] //enable/disable observer mode
/@open_awesomium [URL] //Awesomium dialog open & navigate
/@open_identify [on/off] //Unconditionally unsealing when item is created
/@parcelreturn Parcel return time // Parcel return time
/@party [userName] //Create a party
/@pchannel_max [count] // Change the number of users who can enter the private chat channel
/@perfect_card_collection // collect all cards
/@phaselevel [continentId] [phaseLevel] //set dungeon phase level
/@pk_section [area id] [section id] [on/off] //Pk OnOff for each section
/@profile //Profiling
/@ps_activate_election //Activate the permanent system
/@ps_add_point [point] //Add competitive point
/@ps_calc_tax // Compulsory tax settlement / Permanent residents only
/@ps_candidacy_membercount [member-count] //Adjust the number of guild members required for candidate registration
/@ps_clear_election //initialize permanent residence and election information
/@ps_com_window [continent number] [0:voting 1: battlefield] //View the lord competition window
/@ps_go_next //Forcing the next permanent residence election stage
/@ps_guard_info [guardId] //View guard information
/@ps_guard_window //Open guard info window
/@ps_gw_point [Point] //Change the competition point for the permanent guild battle
/@ps_gw_reset //Reset the limit for acquiring competitive points in the permanent guild battle
/@ps_gw_time [Hour] //Change the reset time limit for acquiring competitive points in the permanent guild battle
/@ps_im_king [guardId] //Roman crowned
/@ps_maketax [value] // Change the total tax amount
/@ps_period_minute [minute] //Replace the permanent election period in minutes
/@ps_planet_vote on/off // 1 vote for 1 account on all servers
/@ps_policy_point [point] //Change policy point / Only permanent residents
/@ps_reg_window //Open the registration window for permanent residence candidates
/@ps_vote_count [count] //manipulate the number of votes
/@ps_vote_window //Open the voting window for permanent residence
/@ps_world_tick [sec] //Change world tick
/@publisher [publisher name] //Change publisher
/@purchase_prod [ProductID] //Purchase product
/@qatest on/off //
/@query_point //Search Cash point
/@raid [Raid number] //Organize a raid party
/@rank_next_season [dungeonId id] // Record Competition Pass the dungeon season
/@rank_sort //Calculate the ranking of the record competition immediately
/@refresh_inven //
/@reg_party //Register party match
/@reload_datasheet // reload data sheet
/@reload_ir //InputRestrictionData.xml Reload
/@reload_netm //NetModeratorConfig.xml Reload
/@reload_shop_data //Reload shop data
/@remove_package [PackageId] {[UserName]} //Account Trait Package setting
/@reserve_festival [EventId] [StartTime] [EndTime] //Reserve world event
/@reset_admin_reward // Reset admin reward record
/@reset_all_phaselevel Reset all user dungeon phase levels (Arbiter) //
/@reset_attendance_event_reward // Initialize the information received from the attendance check event
/@reset_bf_result //Reset Battleground Rating
/@reset_buymenu //Reset store purchase limit (World unit)
/@reset_buymenu_limit //Reset store purchase limit (by world)
/@reset_card_collection // reset card encyclopedia
/@reset_charsock // Initialize character socket extension
/@reset_dungeon //reset all indnes
/@reset_event_mail [event ID] //reset event mail
/@reset_floating_castle_parts_cooltime Reset floating parts cool time //Reset floating parts cool time
/@reset_guild_quest //Refresh daily quota and guild mission list
/@reset_guild_reward //Guild reward points and guild reward history reset
/@reset_guildwar_toggle_cool //Toggle Guild War Allowed Status Reset Cooldown
/@reset_invitecode //Initialize the number of in-game invitation codes used
/@reset_premium_slot //reset premium slot
/@reset_profile //reset profile data
/@reset_returnuser //Set as the first returning user (return customer guide only) (reconnect required)
/@reset_styleware //Initialize style warehouse slot expansion
/@reset_ware //reset warehouse
/@reset_ware_slot //Initialize warehouse slot expansion
/@reset_weekly_contribution_point // Reset weekly guild contribution
/@resetplaytimereward //Reset PC room access time promotion reward
/@resettime_saevent // Update reset time to current time
/@send_mass_parcel //For testing sending large mail to me
/@send_mass_parcel_n //For testing sending mail to me (n: specifying a number)
/@set_account_res_level [level] //Set the limit account level
/@set_admin_level character name level //for debug/admin commands
/@set_arbiter_worldparam [param-name] [param-value] //Modify WorldParam
/@set_awesomium_debug_mode [on/off] //Sets awsomium DebugMode
/@set_awesomium_web_url [url] //Set awsomium URL
/@set_bf_result [Battlefield ID] [Win] [D] [L] [Personal Rating] //
/@set_bf_result_resettime [yyyy] [mm] [dd] [h] //Set the last battlefield ranking initialization time (enter in utc)
/@set_board_clear_time //Set the reset time for the number of creations of the climbing board [hour/minute]
/@set_bypass on/off // turn off and on bypass
/@set_card_preset_amount [point] //Adjust the number of card presets
/@set_chat_ban [set_chat_ban] //set_chat_ban
/@set_city_war_open_time [leagueId][day][hour][playTime] //Change the battle open time
/@set_dg_result_resettime [yyyy] [mm] [dd] [h] //Set the last dungeon ranking initialization time (enter in utc)
/@set_dungeoncool [dungeonId] [minutes] //Set the dungeon cooldown
/@set_escrow_return_wait // Set the escrow return waiting time
/@set_floating_castle_coin Additional Points //Add Parts Shop Coin
/@set_go on/off //GO character set
/@set_guild_play_time_next_week //go over one week to calculate the logic for playtime (use for guild search)
/@set_guild_rec //Adjust the number of guild recommendations
/@set_logout_time character name year month day // designate logout time
/@set_max_recv_mail_cnt // Set the maximum number of inboxes
/@set_max_send_mail_cnt //Set the maximum number of sent mail
/@set_new_member [on/off] //Set whether a new user is
/@set_pcbang [on/off] //Set whether you are a pcbang user
/@set_play_limit limit //Maximum to create queue
/@set_referer [RefererName] [RefereeName] //Refer-A-Friend set inviter
/@set_returnuser //set as the first returning user (returning customer guide only) (reconnect required)
/@set_tax_config [taxId][tradeTax][storeTax][payRate][serverAdjust] //Set tax rate
/@set_tb_avg_price [tid] [enchant] [masterpiece] [avgPrice] //Set the average transaction price of a specific item at the trading agency
/@set_trade_broker_remain_hours //Set the remaining expiration time for items registered in the trading agency
/@set_vip_level [level] //Vip system level adjustment
/@setplaytime [Daily cumulative (minutes)] [Total cumulative (minutes)] //PC room access time Promotion access time setting
/@show_cand //View applicant list
/@show_friendship_info [on/off] // Display reason for acquiring friendship and score system message
/@show_guild_week_play_time [guildName] //Show the weekplaytime of a specific guild
/@show_party //View party match list
/@skill_cheater_arbiter [on/off] [termSeconds(int)] [countThreashold(int)] [kick/nokick] //Change skill cheater settings
/@start_festival [EventId] //start world event
/@start_rookie_event [continentId] [hour] [rewardItem] [amount] // Start mentoring event (time is added from the present and the end time is set)
/@sticktogether //
/@stop_festival [EventId] //World event ends
/@store_changeinfo_add random [amount] (buylist/buylistrange) 
[listid...] (item/itemrange) [templateId...] //add store item edits
/@store_changeinfo_arbiter [index] //Show changes to store item sales (ArbiterServer)
/@string [string name] [string ID] //display string
/@sub_parcel_days [days] [title] //Manipulate all parcels with the title @title back to the past as much as @[I][B][URL="https://forum.ragezone.com/members/262309.html"]day[/URL][/B][/I]s (requires server restart)
/@sysconfig [new config value] //change system configuration
/@tb_avg_price //Recalculate average transaction price of trading agency
/@test_off // End the program test
/@test_on Test type, other parameters // Start program test
/@testautomation_clear_allusers_completely //For test automation-Completely delete all users of the current account (non-recoverable)
/@testitem [testItem] //TestItem
/@toggle_guildwar_acceptable //Toggle guild war allowed status
/@toggle_onoff [id] [on/off] //Toggle content on/off
/@turn_ir [on|off] // Turn Input Restriction on and off
/@turn_netm [on|off] // Turn Net Moderator on and off
/@tutorial on/off // tutorial play
/@tutorialPlayer on/off // Forced setting to see if the guy needs to play the tutorial
/@unlock_all_movies // Unlock all videos
/@unreg_party // delete party match
/@update_bf_score [battleFieldId][gradeScore] //Set current battlefield score
/@update_pverank [continentId][level][time(ms)] //Current dungeon record setting
/@usage // IO related usage rate
/@use_style_warehouse on/off (omitted:on) // Whether to use style warehouse
/@versionInfoHide //
/@viptest [on/off] //Client's own Vip Test command on/off
/@ware_duration [time in seconds] //Adjust warehouse fee period
/@warehousegold_max [amount] //100 can be stored in the warehouse up to KRW 100 0 is the original
/@world_of_party_match //
/@write_board //Climbing bulletin board writing [id] [content] [number]
```

## World Server GM Commands

```
/@abnormality abnormal state ID //force abnormal state
/@abnormality_off abnormality ID //force abnormality
/@abnormality_show abnormality ID //force abnormality
/@abnormality_time [abnormality ID] [duration] //force abnormality by specifying duration
/@accept_revival // resurrect if resurrected
/@accomplish_achievement_rate //achieve achievements until the current season achievement rate is exceeded
/@add_actpoint [actPoint value] //Change coin of adventure
/@add_bf_score //Addition of battlefield control points [Score]
/@add_daily_clear_count [addBonusCount] //Increase the number of daily bonus quests completed in the Valkyon Order
/@add_ep [EpPoint] //Change EP Point
/@add_epexp [exp] //Change EP Exp
/@add_exp [EXP value] //Add experience value
/@add_hp [HP value] //Adjust HP value
/@add_mat_enchant [templateId] [enchantStep] [multiplier] //Acquire material for material enhancement item
/@add_mat_upgrade [templateId] [enchantStep] [masterpiece] [awakened] [multiplier] //Acquire material for equipment upgrade item
/@add_maxactpoint [maxActPoint value] //Change the max value of coins of adventure
/@add_mp [MP value] //Adjust MP value
/@add_npcguild [npcGuildId] //Reputation forces appear
/@add_partner [Partner registration certificate templateId] //Summon after creating a partner
/@add_partner_grade //[buff grade]
/@add_partner_level //[level]
/@add_pet_exp //[experience]
/@add_pet_level //[level]
/@add_route_epexp [route] [exp] //Change by specifying the trait XP acquisition route
/@add_servant_energy [how much] //Pet energy increase or decrease
/@add_skill_polishing_exp [exp] //Change skill polishing exp
/@add_st [ST value] //ST value adjustment
/@addpoint_gmevent point //Add GM event
/@adjust_bonfire [time] //Change the remaining time of the bonfire created by the user
/@aibehavior [on distance] or [off] //Collecting Ai information of neighboring Npc
/@aiskill [on distance] or [off] // Collect skill information of neighboring NPCs
/@allabnormality [on/off] //Unconditionally apply abnormal state caused by skill
/@allhit [on/off] //Ignore skill enemies and hit unconditionally
/@allow_teleport on/off // Whether to allow teleport in restricted area
/@allreaction [0/1/2] //When a skill is hit, a reaction occurs unconditionally (no 0, 1 mini, 2 default)
/@angry [range] // change to anger mode
/@aoi // number of world objects around
/@apm_add [id] //automatic party matching pool entry
/@apm_ask //automatic party matching allow popup
/@apm_reset //Initialize automatic party matching allowed status
/@apm_use [on/off] //Change the automatic party matching mode
/@assert // assert information test
/@atk_speed [attack rate] // All skill speeds increase according to the rate
/@attendance [YYYY] [MM] [DD] //Check attendance on that date
/@autorevivaltime [min] //adjust autorevivaltime
/@ban_guild Character name // Deported guild member
/@block_quest [questId] //Prevent quest from starting
/@bookmark bookmark_id //bookmark (server)
/@box_prob tid //View the probabilities of variance items
/@breakshield [skillId] //
/@buy_styleshop_item [itemTid] //Purchase style shop items (Recommended using TeraPuppet)
/@calc_battle_field_ranking_next_time // Create battlefield ranking at next server start
/@calc_battle_field_Season_next_time //Create a battlefield season at the next server start
/@calmdown [range] // Release anger mode
/@cancelaction [next action number] //Forcibly cancel the action
/@card_collection_max_cost [maxCost] //Set the maximum cost of the card encyclopedia
/@change_daily_quest_record_reset_hour [id] //Ilque clear time change
/@change_daily_quest_seed_reset_hour [id] //Change the ilque seed regeneration time
/@change_epresettime changeResetDay // Change EpReset date
/@change_eventgage [eventName] [value:0 ~ max] //Change the dungeon event gauge value
/@change_exp_gain_data [on/off] or [level, ratio, on/off] // Command to adjust the amount of world experience gained
/@change_guildchief character name //delegation of guild leader
/@change_interval_event_system_playtime [incSeconds] // Change the cumulative play time increase interval (60: 1 hour, 1: 1 minute)
/@change_npc_ai [range] [huntingZoneId] [npcid] [patternListId] //Adjust NpcAi
/@change_npc_stat [range] [ratio] [type] //Adjust NpcStat ratio
/@change_npc_to_user // Release user transformation mode
/@change_party_manager [planetId] [userDbId] //Change party leader
/@change_user [CLASS] [RACE] [GENDER] //Change class race gender
/@change_user_status [battle/peace] //Change peace/battle status
/@change_user_to_npc [huntingZoneId] [templateId] //User transformation mode
/@change_worldspawn_lifetime [WorldSpawnId] [SpawnTerritoryGroupId] [lifeTime] // In WorldSpawnData.xml, modify the lifeTime of SpawnTerritory groups belonging to SpawnTerritoryGroup whose id is SpawnTerritoryGroupId among sub-nodes of WorldSpawn whose id is WorldSpawnId.
/@changefatiguepoint // Forced setting of productivity
/@changenpc [Hunterid] [NpcInstanceId] // Spawn NPC replacement
/@changenpcangermode [on/off] // anger mode on/off
/@charin character name // character login test
/@charm charm ID // forced to add charm
/@charout character name // character logout test
/@check_guildname Guild name //Duplicate guild name check
/@checkcell // check cell (for server)
/@cl_reset // reset the battle log tool
/@clear_achievement // reset achievement
/@clear_aggro // Delete Aggro
/@clear_all_achievement // reset all achievements
/@clear_all_crest [Sentence point] //Release sentence application and apply sentence point. If there is no argument, only disable the sentence application
/@clear_all_skill // Delete all acquired skills
/@clear_all_social // Delete all socials learned
/@clear_bonfire [street] //Delete the bonfire created by the user
/@clear_build_object [distance] //Delete build object created by user
/@clear_cont channel cleaning // channel cleaning
/@clear_daily_quest_complete // Clear daily quest completion record
/@clear_drevent // Add unskilled dungeon matching event to datasheet
/@clear_dungeonwork //reset dungeon task
/@clear_guild_skill //Clear all guild skills acquired
/@clear_quest [questId] [all] //Clear the quest DB
/@clear_recipe_world //Delete RECIPE from worldServer
/@clear_seren_guide //
/@clear_withdrawer // clear coward state
/@clearallabnormality // clear all buffs (clear all buffs without deactivating them.
/@clearbuff // delete all buffs
/@clearcool // Reset all skill cool times
/@clearfieldpoint //initialize field score
/@clearfp //initialize field score
/@clearware warehouse cleaning // warehouse cleaning
/@combatlog [on/off] //Enable combat log
/@combatwork [combat Work Id] //Forcibly execute the combat status work ID of the selected target NPC
/@complete_all_quest //Complete all automatic order quests
/@crash [file name] //crash
/@create_channel world //create channel
/@crest [Sentence point] //Release sentence application and apply sentence point. If there is no argument, only disable the sentence application
/@crest_all //Learn all sentences
/@crest_window //open sentence window
/@critical on/off // critical on/off
/@cube_prob tid //View cube item probability information
/@damage //Damage nearby monsters
/@debugsend [on/off] //Send debug information
/@delete_Tcat_Product_Sale [Item ID] //Tcat product discount off
/@despawn_territory [Hunter ID] [TerritoryId] [Channel ID] //Dispones everything in the Territory
/@despawn_worldspawn [WorldSpawnId] //Despawn all spawn territories belonging to WorldSpawn whose id is WorldSpawnId in WorldSpawnData.xml, and the corresponding world spawn operates from the beginning as when the server was restarted.
/@despawnalleventnpc // despawn all event npc
/@despawnallnpc // despawn all npc
/@destroy_channel world channel instance // delete channel
/@destroy_guild // Destroy the guild
/@disable_citywar_enter_limit //Restrictions on admission to Guild Battles are canceled (you can enter unconditionally)
/@disable_license [License name] //Disable license
/@disconn_all_arbiter // Disconnect all arbiter server sessions
/@dont_ban_battle_field //Prevent chatter in the loom field
/@dr_available_count //Black gap quest order amount adjustment
/@dr_balancing_usercount [userCount] //Modify the BalancingUserCount of the black gap at the current location
/@dr_close [hzid] [dr_tid] //close black gap
/@dr_expand //Forcibly expand the black gap at the current location
/@dr_fold //Forcibly shrink the black gap at the current location
/@dr_goto [hzid] [dr_tid] //Move to the black gap
/@dr_here //Summon black gap to user location
/@dr_inspect // Output black gap information at current location
/@dr_list_reserve //Retrieve reserved black gap EventGroup information
/@dr_open [hzid] [dr_tid] //open black gap
/@dr_open_group [egid] //Forcibly open the black gap EventGroup
/@dr_report //Print all open black gap information
/@dr_rereserve_group //Initialize black gap EventGroup reservation information and rebook
/@dr_rightnow //Ignore Countdown of all black gaps and start right away
/@dr_set_abnormality [abnormalityId] // Fix the abnormal state of all black gaps
/@dr_set_npcgroup [step] [groupTemplateId] //Fix n-step Spawn Npc in all black gaps
/@dr_set_questtemplate [id1] [id2] [id3] //Fix the quest TemplateId of all black gaps
/@dr_spawnreport // Print a list of waiting lists for black gap summons
/@dr_start_quest //Start Black Rift Quest
/@dr_step [step] //skip the black gap
/@dr_time [sec] //Black gap defense time adjustment
/@dr_user_count //Change the number of people in the black gap quest
/@drop_all_items [on/off] //If you kill npc, drop all items
/@dropitem template_id amount // Drop the item
/@dump_performance_data //
/@dungeon_flag [flag-name] //Set the dungeon flag
/@dungeon_timer [timer-value] //Set the dungeon timer
/@enable_citywar_enter_limit //Use the guild war admission restrictions
/@enable_license [License name] //Acquire license
/@enable_ride_vehicle [on/off] //Can board the vehicle unconditionally
/@enchantitemsuccess [-1: always fail, 0: default state, 1: always succeed] //Will you always succeed when reinforcing items?
/@end_citywar //End of battle
/@end_gmevent gmEventId channelId // End of GM event (reward payment)
/@end_npc_arena // End NPC Arena
/@endfe [contId(all=all)] [eventId(0=contall)] //End field event
/@endfieldevent [contId(all=all)] [eventId(0=contall)] //End field event
/@enter_dungeon [contId] [enter-index] //Enter the dungeon
/@enter_dungeon_party [contId] [enter-index] //(All party members in the same world) Enter the dungeon
/@enter_dungeonwork [dungeonId] [randomMode] [workid] //Enter the task selection solo dungeon
/@enter_gmevent gmEventId // Enter GM event
/@epexp_allrev on/off //All correction values ​​OnOff
/@epexp_defaultrev on/off // Default correction value OnOff
/@epexp_extrabonus on/off // other correction value OnOff
/@epexp_tsrev on/off //TS correction value OnOff
/@exitclear_cool [1/0] //If it is 1, it is always possible to ignore the emergency escape time. If it is 0, as usual
/@expdiv [Value to divide EXP] // Obtained by dividing the experience value by the parameter value
/@extend_party [partyToRaid] //Change Party ↔ Raid
/@extractitemfail [If it is 1, it always fails if it is 0, as it is] //Will it always fail when extracting items?
/@extractitemsuccess [If 1, always succeed, 0 if original] //Will you always succeed when extracting items?
/@fail_quest //Quest failure handling
/@fast_box //gacha and eventSeed animation skip
/@fast_cube on / off //Open without cube material
/@ferotation [on/off] // turn field event rotation on and off
/@festival_end [festivalId] //Disable festival
/@festival_start [festivalId] //Activate the festival
/@fight_npc_arena //Start NPC Arena battle
/@finish_battle_field [win/lose] //Force end the battlefield
/@finish_battle_field_round // end round
/@finish_tutorial // finish the tutorial
/@flyspeed value // adjust flight speed
/@force_change_user_status [on/off] [userStatus/1=battle/0=normal/2=peace (old bonfire)] //user status change
/@force_do_ep_passive on/off // attribute passive 100% activation on/off
/@forget_guild_skill [skillTemplateId] [isActive] //Remove guild skill
/@forget_skill skillTemplateId isActive // ​​Delete skill
/@forget_social [socialMotionId] //Social delete
/@free_flight on/off //On or off whether to fly without using flight energy
/@freeze_condition // condition value fixed
/@fulldump [file name] //full dump
/@gamble_test // gambling test
/@get key [id/name] //Get property value
/@number of get_quests //get the quests
/@get_region_info //Display the current region information
/@get_return_user_reward //Get reward for returning user
/@ghost [on] or [off] //Get server coordinates of those spawned around
/@giveup_promotion // give up the promotion test
/@gopos [x] [y] [z] //move to a specific location
/@goto [other character name] //teleport to another character
/@goto_battle_field_round //start from a specific round
/@goto_least_entered_fe [onlyEmpty=1] //Move to the event with the fewest people
/@gotofe [contId] [eventId] //Move to the start position of the field event
/@guild_ware_range [startIndex] [endIndex] [itemDbId] //Create item in guild warehouse
/@guildwar_accept [opposite guild name] //let's fight! XXX Guild
/@guildwar_giveup [name of the opponent guild] //hang ha buck ha
/@guildwar_raise [opposite guild name] [additional bet tactical chip] //let's fight XXX Guild
/@guildwar_start [opposite guild name] [betting tactical chip] //let's fight! XXX Guild
/@holdabnormality_clear // clear all stored buffs
/@idle_social_stop idle social stop/start //
/@ignoreskilllos [on/off] // Whether to check los when hitting a skill
/@increaseinvensize [minimum 48 to 88] //Only increase the character inventory size
/@insert_item templateId itemCount //item acquisition
/@insert_Tcat_Product_Sale [Item ID] [Discount price], [Time (minutes)] //Register Tcat product discount
/@interest [on distance] or [off] //Gather debug information of nearby guys
/@invincible [on/off] // invincible state
/@invisible [on/off] //NPC is close
/@invite_guild character name //invite guild member
/@is_tutorial_user //Check if you are a tutorial user
/@item_add [userName] [itemTemplateId] [amount] //Add item
/@item_del [userName] [itemTemplateId] [amount] //Delete item
/@item_list [userName] //item listing
/@item_multidel //
/@item_trade //
/@itemlevel itemLevel / off // Change item level
/@join_party [planetId] [userDbId] //Add party
/@jump_task [questId] [taskId] //Jump to a specific task of the quest
/@jumpto [huntingZoneId] [templateId] //teleport to NPC
/@kick_party [planetId] [userDbId] // kick off the party
/@kill range UU // kill NPC within radius
/@kill_mypet // destroy pet
/@kill_summonee character name //invite guild members
/@killme // suicide
/@killme2 // Suicide while breaking crystal
/@learn_all_epperk //Learn all epPerk
/@learn_epperk [skillId] [level] //Learn Ep Perk(characteristics, effects)
/@learn_guild_skill [skillTemplateId] [isActive] //Guild skill acquisition
/@learn_recommended_ep //Apply the recommended characteristics of each class
/@learn_skill skillTemplateId isActive // ​​skill acquisition
/@learn_social [socialMotionId] //Social learning
/@leave_dungeon //Leave the dungeon
/@leave_dungeon_party //(All party members in the same world) Exit the dungeon
/@leave_party // leave the party
/@level new level // change level
/@limited_drop_reset_point [gauge id] //reset quantity control drop point
/@limited_drop_set_point [gauge id] [capacity point] //Quantity control Drop point adjustment
/@list key [id/name] //property listing
/@load_drevent // Add unskilled dungeon matching event to datasheet
/@login [class] [number of animals] //login test
/@lootitem [Acquisition Radius] //Route items within the acquisition radius, (range> 0: route as much as a range, range <= 0: do not route, omit range: route as much as 500)
/@make_me_second // change yourself to a second character
/@make_party [target username] // configure party
/@make_party2 [target userDbId] //party configuration
/@make_vehicle_skill_book //Get a boarding skill book
/@makeitem [Template ID] [Quantity] [Enhanced] [Luxury(1)/Awakening(2)] //Create item
/@makeitem_damage [Template ID] [Enhanced] [Quantity] //Create damaged equipment
/@makeitem_op [Template ID] [Quantity] [Enhanced] [Luxury (1)/Awakening (2)] //Create an item with a high option level
/@makeitem_range [tid_start] [tid_end] [Quantity] //Make various items
/@makeitems [Template ID] [Template ID] [Template ID] .... [Quantity] //Create various items
/@makematerial [production item id] [number] //Create production item material
/@makemoney [amount] // make money
/@makeplaytestitem [Phase] [Enhancement value] //Set equipment at once
/@makeqbitem [questId] [taskId] // Temporary implementation of retrieving items
/@maketestitem [enchant] //Create test equipment item
/@match_battle_field //Forcibly match two parties to the battlefield [Battlefield TID] [Relative ID]
/@memstat //
/@merge_item fromInvenPos toInvenPos //Merge item
/@minigame_skip [true/false] //skip fishing minigame
/@move_to_village //Move to the nearest grave in case of death
/@mpfull [on/off] //MP full mode
/@msg_dungeon //StrSheet_MonsterBehavior.xml message output
/@msg_monsterbehavior [MonsterBehaviorId] [range(1000)] //Print message of StrSheet_MonsterBehavior.xml
/@msg_system [readableId] // Output the message of StrSheet_SystemMessage.xml
/@next_quiz point //Proceed to next question of OX quiz
/@next_repequiz point // OX quiz loser resurrection progress
/@next_task [questId] //Proceed next task
/@nocool [on/off] // Infinite skill cooldown mode
/@nodie [on/off] //I get hit but I won't die
/@nomod [on/off] //Position correction off mode during skill
/@nonpk_list //Search the list of Sections set to NonPk in this world
/@nonrecovery_actpoint [on/off] //Apply Coin of Adventure Natural Recovery
/@nonrecovery_hp [on/off] //HP automatic recovery on/off
/@nonrecovery_mp [on/off] //MP automatic recovery on/off
/@nonrecovery_st [on/off] //ST automatic recovery on/off
/@open_all_box //Open all EventSeeds & Gachas in inventory
/@open_bfstore [Store menu ID] //Open store without npc
/@packettest //
/@parcel_fee //Pay parcel fee
/@parcel_recv //receive parcel
/@parcel_return // parcel return
/@parcel_send // send parcel
/@passive_off passive ID // turn off passive state
/@passive_on passive ID // turn on passive status
/@passive_see //Print on passive status screen
/@passive_show passive ID // turn off passive status
/@pausenpc range //stop NPC
/@pegasus pegasusId // pegasus
/@perfect_level new level // level change + skill acquisition
/@perfect_skillPolishing //Activate all skill polishing
/@petevolution_success //[-1 = forced failure, 0 = normal, 1 = forced success]
/@petmix_success //[-1 = forced failure, 0 = normal, 1 = forced success]
/@pkmodeoff // Force PK state off
/@pkmodeOn //PK
/@playtimereward [daily/total] [reward ID] //Cumulative access time reward payment
/@prisoner [on/off] //set the prison state
/@producefatiguepoint // set productivity
/@produceitemfail [If it is 1, it always fails, if it is 0, as it is] //Will you always fail when making an item?
/@prof_bug New skill level //Insect collection skill change
/@prof_energy New skill level //Changed skill level for gathering energy
/@prof_herb New skill level //Changed herb collection skill level
/@prof_mineral New skill level //Mineral collection skill change
/@profile_world //world server profiling
/@pullmonster // pull the monster to my location
/@qatest_world on/off //
/@randomfe // start one event at a random rotation specified in the function
/@rank_add_point [point] // Add record competition inden point
/@rank_add_private_point [point] //Add personal points in the record competition
/@rank_add_record // record competition in-done record 1~10000 points randomly added
/@rank_clear // Clear record competition indon
/@rank_log [on/off] // Clear record competition index
/@rank_start // Start counting the record competition index
/@rank_test // record competition record film creation
/@ranktimer // output rank timer progress time
/@ranktimer_reset // Initialize rank timer record
/@ranktimer_state [on/off] // Whether to print ranktimer start and end messages
/@re //resurrection
/@reaction [reaction motion number] //forced reaction
/@recalc_stat // recalculate stats
/@recv_all_parcel //Receive all mail (for server team test)
/@recv_daily_bonus //Forcibly Receive Valkyon Order Daily Bonus
/@recv_weekly_bonus //Forcibly Receive Valkyon Orders Weekly Bonus
/@register_card [cardTemplateId] [amount] //Register card
/@registerParts //
/@reload_critical_adjust_datasheet //critical adjust datasheet reload
/@reload_datasheet_world //reload all datasheets
/@reload_dr //reload black gap datasheet
/@reload_dungeon [Dungeon ID] [DungeonRetry Reload] //Reload only the specified dungeon
/@reload_flying //flight-related reload
/@reload_huntingzone [Hunting zone ID] // Reload only the designated hunting zone
/@reload_item // Reload ItemTemplate
/@reload_limited_drop_datasheet //limited drop data sheet reload
/@reload_masstige_datasheet // reload masstige datasheet
/@reload_quest //reload all quest data sheets
/@reload_rank [id] //Reload record competition index xml
/@reload_token_exchange_datasheet //token exchange data sheet reload
/@reload_userskill // reread user skills
/@remove_guildtower //Remove Guild Tower
/@remove_target_guildtower //Remove Guild Tower
/@reputation_time_init [npcGuildId] //Reset the reputation time limit
/@reset_add_compensation_count // this Vent matching TASK reset to not receiving all additional rewards
/@reset_all_phaselevel_world //Reset all users' dungeon phase information (world)
/@reset_all_user_vip_store //reset all users Vip store
/@reset_attendance // reset attendance check
/@reset_daily_epexp //Reset daily experience
/@reset_daily_event_quest //Reset daily play guide events
/@reset_daily_quest //Reset the daily quest seed
/@reset_delivery_list //reset delivery list
/@reset_dungeon_clearcount //reset all dungeon cooldowns
/@reset_dungeon_enter_count // Delete dungeon entry count record
/@reset_dungeonhistory //reset all dungeon cooldowns
/@reset_ep //Ep system reset
/@reset_epperk //Ep Perk (property, effect) reset
/@reset_masstige_status //Reset the target item for national enhancement
/@reset_profile_world //reset world server profile data
/@resumenpc range //replay NPC
/@resurrection // resurrect
/@rightbaseitem [RightID] [ItemTID] //Get RightBaseItem
/@rightnow_gmevent gmEventId // Immediately start waiting GM event
/@sealitemnow [if it is 1, if it is 0, it will be original] //When the item is attributed, it will be attribute immediately
/@send_ask_code_hash //Send code hash request
/@set key value [id/name] //set property value
/@set_achievement_accomplished //achieve achievement
/@set_achievement_cond_value //set achievement condition value
/@set_add_compensation_count [eventId] [acquireNum] //Event Matching TASK Additional Reward Acquisition Count Manipulation
/@set_all_achievement_accomplished //achieve all achievements
/@set_autowatingtime [millisecond] //Set the waiting time for self fishing
/@set_bitetime [millisecond] //Set bite quality waiting time
/@set_condition value //Set the user's condition value
/@set_custom_string //[itemDbid] [String] Change item custom name
/@set_dlm_delay min [max] //Random delay period when performing world-arbiter tasks (unit: ms)
/@set_dr_clear_each [RewardId] //Set a single compensation for the crack of the construction
/@set_dr_clear_fail [RewardId] //Set the compensation for the crack failure in the construction
/@set_dr_clear_general [RewardId] //Set the global compensation for the crack in the space
/@set_dr_clear_personal [RewardId] //Set personal reward for the crack of space
/@set_dr_hp [hpRate] // Set the initial Hp ratio of the crack object in construction
/@set_dungeon_clear //Set dungeon clear
/@set_dungeon_reset_time //Set the time to delete the number of dungeon entries
/@set_dungeon_user_count //Adjust the number of users in the dungeon for testing
/@set_dungeonwork_value [hit/combo/timer] [value] //Set the test dungeon task value
/@set_equipexp [Proficiency exp] //Change equipment proficiency experience
/@set_exp [EXP value] //Set experience value
/@set_fishing_reward_table [tableId] //Set reward table id
/@set_gamble_master //Become a bastard
/@set_gamble_property // set the property
/@set_hurryup_gmevent [hurryUpRatio] [hurryUpCounts(csv)] //Set variable for GM event imminent deadline
/@set_login_day [period] [loginDay] //Daily play guide attendance check
/@set_minigamelevel [level] //Set the minigame level
/@set_money [amount] // set money
/@set_npcguild_exp [npcGuildId] [grade] [exp] //Set the reputation faction experience
/@set_npcguild_point [npcGuildId] [point] //Set reputation point
/@set_on_dungeon_event // Start all dungeon events
/@set_on_field_event // Start all EventGroups of field events
/@set_pc_level character name level // set character level
/@set_pc_loc Character name location string // Set character location
/@set_petdur [dur] //changing pet-dur temporarily
/@set_petprof [Proficiency] //Change Pet Proficiency
/@set_pkpoint [pkPoint] //Change pK point
/@set_promotion // achieve promotion
/@set_round_pve_kill_point //PveKill_Point[point]
/@set_round_pve_skill_point //PveSkill_Point[point]
/@set_skill_prof skillId skillProf // set skill proficiency
/@set_temper_ratio Enchant Probability //Fix Enchant Probability
/@set_token_exchange_point [tokenExchangeId] [point] //Token score adjustment
/@set_tutorial_user [on/off] //Set whether to be a tutorial user
/@set_walk_speed //set walking speed
/@set_world_worldparam [param-name] [param-value] //Modify WorldParam
/@setfeprogress [contId] [eventId] [setvalue] //Set field event progress
/@setfieldeventprogress [contId] [eventId] [setvalue] //Set field event progress
/@setmoney [name] [money] //set money
/@setrestbonus rest_bonus //
/@show_bonfire_info //Show current user's bonfire information
/@show_chapter //View meetinghouse
/@show_condition //View user's condition value
/@show_FinalConditionalSkillProb //Check the final probability of the partner skill (use after skill activation)
/@show_incubator //Open Pet Incubator
/@show_items [tabIdx] [beginIdx] [endIdx] //Check inventory item information
/@show_limited_drop_info [gauge id] //Show quantity control gauge information
/@show_petmanager //Open Pet Manager
/@show_phaselevel_world //My phase information
/@show_skill_learn huntingZoneId npcId //Show skill acquisition window
/@show_social_learn //Show learned social
/@show_temper_window //hanga~
/@show_time //Show current time
/@show_user_status //View user status
/@show_vs //Print the vehicle's speed
/@showfei [on/off] // field event status information text output
/@showfeinfo [on/off] // field event status information text output
/@showfep // show the internal value of the currently participating fieldEvent
/@showfeprogress // show the internal value of the currently participating fieldEvent
/@showinven //
/@showpos [x] [y] [z] [showTime] //Show vector location for debugging
/@shuttle [on/off] shuttleId // turn dynamic geo (shuttle) on and off
/@skill_cheater_world [on/off] [termSeconds(int)] [countThreashold(int)] [kick/nokick] //Change skill cheater settings
/@skill_miss_limit // When the monster fails to hit the target a number of times due to height difference, etc.
/@skillLog // Leave server file log
/@sm [system message number] //system message
/@social [socialMotionId] //social
/@spawn_bonfire typeid //Summon Bonfire
/@spawn_territory [HunterId] [TerritoryId] [Channel ID] // Spawn everything in the territory
/@spawn_worldspawn [WorldSpawnId] [SpawnTerritoryGroupId] // In WorldSpawnData.xml, change the current spawn territory group of WorldSpawn whose id is WorldSpawnId to SpawnTerritoryGroup whose id is SpawnTerritoryGroupId.
/@spawnalleventnpc // spawn all event npc
/@spawnallnpc // spawn all npc
/@spawncollection // Respawn all collections in user channel
/@spawnnpc [Hunting AreaId] [NpcTemplateId] [Count] // Let's spawn it
/@spawnworkobject [huntingZoneId] [templateId] // Spawn Work Object
/@speed multiplier // increase moving speed
/@speed_hack_check //spec check [on/off]
/@start_battle //start the battlefield immediately
/@start_citywar // start of battle
/@start_eventgroup [id] // Forced start of the dungeon event group
/@start_gmevent gmEventId // Add GM event
/@start_npc_arena // Start NPC Arena
/@start_promotion // start the promotion test
/@start_quest Quest ID // Start Quest
/@start_seren_guide [type, id] //Start Seren Guide
/@startfe [contId] [eventId] //start field event
/@startfieldevent [contId] [eventId] //start field event
/@startnpcskill skill_template_id //Run NPC skill
/@stfull [on/off] //ST full mode
/@stopFloatingCastleUserCheck //
/@store_changeinfo [index] //Show changes to store item sales (WorldServer)
/@stwork [combat Work Id] //Forcibly execute the combat status work ID of the selected target NPC
/@style_ware_range [startIndex] [endIndex] [itemDbId] //Create item in style warehouse
/@summonParty //Summon all party members to my location
/@swap_party [slotIndex1] [slotIndex2] //Change raid slot
/@sysconfig_world //
/@task_goal [questId] [taskIdx] [flag] //Set task goal
/@teleport [worldId] [x] [y] [z] //teletoby
/@teleport_channel //
/@temper_item temperItemSlot materialItemSlot // Item Smelting
/@test_parts_store //
/@testoff // end program test
/@teston Test type, other parameters // Start program test
/@this // Force the position of the characters in my account to the current character position
/@toggle_epInfo // Characteristics Info
/@track_dynamic // Tracks only one NPC currently held as a target in the track list
/@track_target //Add the selected target NPC to the tracking list
/@trade_accept //
/@trade_additem //
/@trade_request //
/@unidentifysuccess //Sewing unconditionally successful [on/off]
/@unRegisterParts //
/@untrack_target //Remove selected target NPC from tracking list
/@use_exp_gain_data [on/off] //
/@userawake [grade] //[0 = taste 1 = awake
/@vaporize // true transparency
/@vehicle_avatar [huntingZoneId] [templateId] // ride Kumas (avatar)
/@vehicle_clear_cooltime //Initialize the vehicle skill cooltime
/@vehicle_dettach //Kumas/Tank forced off
/@vehicle_killself //Destruction of the vehicle on board
/@vehicle_nocool [on/off] //Remove the skill cooldown of the vehicle.
/@view_channel // view channel
/@virtual_latency [min] [max] //Virtual latency
/@visit_all_sections //Visit all regions
/@vm_buy [vm inventory#,count] [...] //buy
/@vm_edit_buy [vm inventory #, user inventory #, tempId, number of lives, number of collections, price] [...] //Set the purchase machine
/@vm_edit_sell [collection amount] [vm inventory #, user inventory #, tempId, number of eight, number of collections, price] [...] //Vending machine setting
/@vm_sell [vm inventory#,count] [...] //sell
/@vm_show_buy //View purchase list
/@vm_show_sell //View sales list
/@ware_list //View warehouse
/@ware_range [startIndex] [endIndex] [itemDbId] //Create item in account warehouse
/@win_battle_field //force to win the battlefield
/@write_gcfunctions //
/@부활 // Resurrection
```

TIP: For the Items ID's its better to use  [Asura Item](https://tera-asura.ru/items/all)
