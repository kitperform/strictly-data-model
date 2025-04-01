Couple
  - couple_id
  - pro_dancer_id
  - celebrity_id
  
Series
  - series_number
  - first_episode_id


ProfessionalDancer
  - pro_dancer_id
  - pro_dancer_first_name
  - pro_dancer_last_name

Celebrity
  - celebrity_id
  - celebrity_first_name
  - celebrity_last_name

CompetitionRound
  - competition_round_id
  - competition_round_name [quarter-final, semi-final, final]

Theme
  - theme_id
  - theme_name

Score
  - score_id
  - performance_id
  - judge_id
  - score

Episode
  - episode_id
  - week_number
  - series_number
  - date_transmission
  - theme_id
  - competition_round_id
  
Dance
  - dance_id
  - dance_name
  
Judge
  - judge_id
  - judge_name_first
  - judge_name_last

Performance
  - couple_id
  - dance_id
  - song_id
  - episode_id

DanceOff
  - episode_id
  - couple_id
  
Song
  - song_id
  - artist_id
  - song_name

Artist
  - artist_id
  - artist_name
  