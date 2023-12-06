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
