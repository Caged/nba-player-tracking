![screen shot 2013-12-23 at 11 27 43 am](https://f.cloud.github.com/assets/25/1802714/8c60c31e-6c08-11e3-9271-8e5d5876167e.png)

**Install**

```
git clone https://github.com/Caged/nba-player-tracking.git
cd nba-player-tracking
npm install
bower install
brew install jq
```

**Sync**

```
./script/syncstats
./script/syncteams
./script/tometricdefs
./script/tocsv > source/players.csv
```

**Start**

```
./script/server
open http://localhost:4567
```
