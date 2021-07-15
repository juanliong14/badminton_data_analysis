# BWF Badminton Tournament and Match data
This contains data for all BWF World Tour (2018-04/2021) tournaments. Each record is a specific match played at a tournament. The data is split up per discipline (men's singles, women's singles, men's doubles, women's doubles and mixed doubles). All data is scraped from the official BWF website using python. Matches that were walkovers are removed from the data as I feel they would not contribute. I will try to keep this data up-to-date and might add other tournaments aswell.

## Data set
### Singles - Contain match details as per the table below
- tournament : The name of the tournament
- city : The city the tournament is played
- country : The country this tournament is played
- date : The date this match is played
- tournament_type : The type of this tournament (Super 100 - Super 1000)
- discipline : The discipline of this match (useful when merging different datasets)
- round : The round of this match in the tournament
- winner : Number (1 or 2) specifying if team 1 or team 2 won the match (0 if one of the teams retired)
- nb_sets : Number of sets played
- retired : Boolean stating if a team retired 
- game_i_score : Final score of game i
- team_one_players : Name of the player of team one
- team_two_players : Name of the player of team two
- team_one_nationalities : Abbreviation of the nationality of the player of team one
- team_two_nationalities : Abbreviation of the nationality of the player of team two
- team_one_total_points : Total number of points scored by team one during the match
- team_two_total_points : Total number of points scored by team two during the match
- team_one_most_consecutive_points : Most conseccutive points scores by team one during the match
- team_two_most_consecutive_points : Most conseccutive points scores by team two during the match
- team_one_game_points : Total number of game points team one had during the match
- team_two_game_points : Total number of game points team two had during the match
- team_one_most_consecutive_points_game_i : Most consecutive points scores by team one during game i
- team_two_most_consecutive_points_game_i : Most consecutive points scores by team two during game i
- team_one_game_points_game_i : Total number of game points team one had during game i
- team_two_game_points_game_i : Total number of game points team two had during game i
- game_i_scores : List of all score changes during game i

### Doubles - Contain match details as per the table below
- tournament : The name of the tournament
- city : The city the tournament is played
- country : The country this tournament is played
- date : The date this match is played
- tournament_type : The type of this tournament (Super 100 - Super 1000)
- discipline : The discipline of this match (useful when merging different datasets)
- round : The round of this match in the tournament
- winner : Number (1 or 2) specifying if team 1 or team 2 won the match (0 if one of the teams retired)
- nb_sets : Number of sets played
- retired : Boolean stating if a team retired 
- game_i_score : Final score of game i
- team_one_player_one : Name of player one of team one
- team_one_player_two : Name of player two of team one
- team_two_player_one : Name of player one of team two
- team_two_player_two : Name of player two of team two
- team_one_player_one_nationality : Abbreviation of the nationality of player one of team one
- team_one_player_two_nationality : Abbreviation of the nationality of player two of team one
- team_two_player_one_nationality : Abbreviation of the nationality of player one of team two
- team_two_player_two_nationality : Abbreviation of the nationality of player two of team two
- team_one_total_points : Total number of points scored by team one during the match
- team_two_total_points : Total number of points scored by team two during the match
- team_one_most_consecutive_points : Most conseccutive points scores by team one during the match
- team_two_most_consecutive_points : Most conseccutive points scores by team two during the match
- team_one_game_points : Total number of game points team one had during the match
- team_two_game_points : Total number of game points team two had during the match
- team_one_most_consecutive_points_game_i : Most consecutive points scores by team one during game i
- team_two_most_consecutive_points_game_i : Most consecutive points scores by team two during game i
- team_one_game_points_game_i : Total number of game points team one had during game i
- team_two_game_points_game_i : Total number of game points team two had during game i
- game_i_scores : List of all score changes during game i

# Usage
Please abide the license of this dataset. I have put time and effort into collecting this data and maintaining this dataset. Feel free to use this data for research purposes, but make sure to cite it. 
# badminton_data_analysis
