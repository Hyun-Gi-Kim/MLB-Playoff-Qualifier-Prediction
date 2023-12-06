# MLB-Playoff-Qualifier-Prediction
### Original Column descriptions:

### [Categorical/Class Variables] 
##### lgID: unique league identifier (6 possible classes or null)
##### teadID: unique team identifier (149 classes)
##### franchID: unique franchise identifier (120 classes)
##### divID: unique division identifier (3 classes)
##### DivWin: whether team won its division (Y, N, or null)
##### WCWin: whether team won a wild card spot (Y, N, or null)
##### LgWin: whether team won its league (Y, N, or null)
##### WSWin: whether team won the World Series (Y, N, or null)
##### name: team name (139 classes)
##### park: team home ballpark (212 classes)
##### teamIDBR: unique Baseball Reference team identifier (101 classes)
##### teamIDlahman45: unique Lahman database team identifier (148 classes)
##### teamIDretro: unique Retrosheet team identifier (149 classes)

### [Numerical/Continuous Variables]
##### yearID: calendar year (season)
##### Rank: ordered ranking of team's finish for its division (league_id and div_id)

### [Game outcomes]
##### G: games
##### Ghome: home games
##### W: wins
##### L: losses

### [Hitting]
##### R: runs
##### AB: at bats
##### H: hits
##### 2B: doubles
##### 3B: triples
##### HR: home runs
##### BB: walks
##### SO: strikeouts
##### SB: stolen bases
##### CS: caught stealing
##### HBP: hit by pitch
##### SF: sacrifice flies

### [Pitching]
##### RA: runs allowed
##### ER: earned runs
##### ERA: earned run average
##### CG: complete games
##### SHO: shutouts
##### SV: saves
##### Ipouts: outs pitched
##### HA: hits allowed
##### HRA: home runs allowed
##### BBA: walks allowed
##### SOA: strikeouts allowed

### [Fielding]
##### E: errors
##### DP: double plays
##### FP: fielding percentage

### [Home ballpark]
##### attendance: total attendance for home games
##### BPF: park factor for batters
##### PPF: park factor for pitchers

### Added Column descriptions: 

### [Hitting]
##### 1B: singles 
##### BA: Batting Average   (The ratio of hits to at-bats)
##### OBP: On-Base Percentage   (The percentage of plate appearances resulting in the batter reaching bases)
##### SLG: Slugging Percentage   (A measure of the team's power-hitting ability, calculated as total bases divided by at-bats)
##### TB: Total Bases   (The sum of bases earned through singles, doubles, triples, and home runs)
##### OPS: On-Base Plus Slugging   (The sum of OBP and SLG)
##### GPA: Gross Production Average   (A measure of a player's overall offensive production, combining OBP and SLG)
##### TA: Total Average   (A metric considering total bases, walks, hit by pitch, stolen bases, and other factors per plate appearance)
##### PSN: Power-Speed Number   (A combined measure of player's home run and stolen base proficiency)
##### ISO: Isolated Power   (A measure of a team's raw power, calculated as SLG minus BA)
##### BABIP: Batting Average on Balls in Play   (The ratio of walks and hit by pitch to toal at-bats)

### [Pitching]
##### WHIP: Walks plus Hits per Inning Pitched   (A measure of a pitcher's effectiveness in preventing baserunners)
##### BAA: Batting Average Against   (The opposing batters' batting average against the team's pitchers)
##### K/BB: Strikeouts per Walk   (The ratio of strikeouts to walks, indicating a pitcher's control and dominance)
##### BB/HBP_ratio: Walks and Hit by Pitch Ratio   (The ratio of walks and hit by pitch to total at-bats)
##### IP: Inning Pitched   (The total number of innings pitched by the team's pitchers, converted from outs)


### Fielding
##### P%: Power Percentage   (The percentage of runs squared divided by the sum of runs squared and runs allowed squared, providing a measure of a team's power)
##### WP: The ratio of wins to total games played, indicating the team's winning rate.
