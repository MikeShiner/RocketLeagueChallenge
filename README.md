# RocketLeagueChallenge

Programming challenge for pulling Rocket League stats

# Challenge

Write a program which takes in a SteamID and produces the following Rocket League statitics for the player:

- Platform & Username
- Lifetime Wins & Lifetime Win Rank
- Lifetime Goal-shot ratio

- Current Season Name
- Matches played this season
- Tier
- Rating

## REST Endpoints

### Player Data

`https://api.tracker.gg/api/v2/rocket-league/standard/profile/steam/<steamID>`

### Tips:

- Program can be written in any language
- The above rest endpoint returns JSON data and will contain much of what you need, you'll need to loop through a lot of the structure to pull out the data you need
- Use a HTTP Client pull data from this URL (make sure to replace `<steamId>`)
- The current season is 16, but don't hardcode this

### How to complete

- Pull this repo
- Create a branch
- Complete the challenge
- Push your code to your branch
- Submit a pull request for me to review
