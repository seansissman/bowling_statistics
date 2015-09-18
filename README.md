# bowling_statistics

We should come up with the inputs needed.

This is what I came up with.

I figure once the team's are set up and the player handicap has been set - the only thing you want to input is the player and the score.

Player, Team, and Score.

Player Table
_____________
Playerid -- Player Name -- Handicap

Team Table
_________
TeamID -- Playerid

Score tables
_________
Date -- MatchID -- PlayerID --- Raw Score ---Handicap Adj Score

Matchup (Schedule) Table
_________
MatchID -- HomeTeam (TeamID) -- AwayTeam (TeamID) -- Date

Season Table (this doesn't seem right, but I think we need to create like a League Season so you can keep track over my seasons and also I think we should consider making it for many different leagues. That way if we put it out on the web other Bowling leagues can use it.
______
SeasonID -- TeamID



