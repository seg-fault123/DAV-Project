We possess three Excel files: match_data, players_data, and teams_data. The match_data file encompasses comprehensive information pertaining to matches on a seasonal basis. The players_data file contains detailed information about players on a seasonal basis, while the teams_data file comprises all the information related to teams on a seasonal basis.


The file match_data have 46 columns named
result_code(String),	series_id(Integer),	event_sub_status(String),	start_date(Date),	winning_margin(Integer),	venue_id(Integer),	venue_name(String),	game_id(Integer),	event_name(String),	toss_winner_id(Integer),	toss_choice(String),	home_team_id(Integer),	home_team_name(String),	season(String),	team1_name(String),	team1_id(Integer),	team1_score(Integer),	team1_all_out_points(Integer),	team1_extra_points(Integer),	team1_raid_points(Integer),	team1_tackle_points(Integer),	team1_raids_done(Integer),	team1_successful_raids(Integer),	team1_unsuccessful_raids(Integer),	team1_empty_raids(Integer),	team1_tackles_done(Integer),	team1_successful_tackles(Integer),	team1_unsuccessful_tackles(Integer),	team1_all_outs(Integer),	team2_name(String),	team2_id(Integer),	team2_score(Integer),	team2_all_out_points(Integer),	team2_extra_points(Integer),	team2_raid_points(Integer),	team2_tackle_points(Integer),	team2_raids_done(Integer),	team2_successful_raids(Integer),	team2_unsuccessful_raids(Integer),	team2_empty_raids(Integer),	team2_tackles_done(Integer),	team2_successful_tackles(Integer),	team2_unsuccessful_tackles(Integer),	team2_all_outs(Integer),	winning_team_name(String),	winning_team_id(Integer).

The file players_data have 17 columns named
player_id(Integer), 	player_name(String),	match_played(Integer),	team_id(Integer),	position_name(String),	team_full_name(String),	total_points(Integer),	season(String),	successful_raids(Integer),	raid_points(Integer),	successful_tackles(Integer),	tackle_points(Integer),	do_or_die_raid_points(Integer),	super_raids(Integer),	super_tackles(Integer),	super_10s(Integer),	high_5s(Integer).

The file teams_data have 15 columns named
match_played(Integer),	team_id(Integer),	team_name(String),	season(String),	total_points(Integer),	successful_raids(Integer),	raid_points(Integer),	successful_tackles(Integer),	tackle_points(Integer),	do_or_die_raid_points(Integer),	super_raids(Integer),	super_tackles(Integer),	total_points_conceded(Integer),	all_outs_inflicted(Integer),	all_out_conceded(Integer).

note :- column format is Column_Name(Data_Type)


