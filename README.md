# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```


### 1. e.g. The WorldCup Football API

```
Livescores API

Fixtures by ID: https://rapidapi.com/api-sports/api/api-football?endpoint=apiendpoint_9e5959e2-9609-4fe9-98de-91574b894ff7

```
#### 1.1 Header Parameters
```
  X-RapidAPI-Key=SIGN-UP-FOR-KEY
  X-RapidAPI-Host=api-football-V1.p.rapidapi.com
```

#### 1.2 Request
```shell
curl --request GET --url https://api-football-v1.p.rapidapi.com/v3/timezone --header 'X-RapidAPI-Host: api-football-v1.p.rapidapi.com' --header 'X-RapidAPI-Key: SIGN-UP-FOR-KEY'
```
#### 1.3 Result

```json
{
    "api": {
        "results": 1,
        "fixtures": [
            {
                "fixture_id": 855736,
                "league_id": 4265,
                "league": {
                    "name": "World Cup",
                    "country": "World",
                    "logo": "https:\/\/media.api-sports.io\/football\/leagues\/1.png",
                    "flag": null
                },
                "event_date": "2022-11-21T00:00:00+08:00",
                "event_timestamp": 1668960000,
                "firstHalfStart": null,
                "secondHalfStart": null,
                "round": "Group Stage - 1",
                "status": "Not Started",
                "statusShort": "NS",
                "elapsed": 0,
                "venue": "Al Bayt Stadium",
                "referee": null,
                "homeTeam": {
                    "team_id": 1569,
                    "team_name": "Qatar",
                    "logo": "https:\/\/media.api-sports.io\/football\/teams\/1569.png"
                },
                "awayTeam": {
                    "team_id": 2382,
                    "team_name": "Ecuador",
                    "logo": "https:\/\/media.api-sports.io\/football\/teams\/2382.png"
                },
                "goalsHomeTeam": 2,
                "goalsAwayTeam": 1,
                "score": {
                    "halftime": "1-0",
                    "fulltime": "2-1",
                    "extratime": null,
                    "penalty": null
                }
            }
       ]
    }
}
```

### AURORA Testnet Network Contact Address

RPC: https://testnet.aurora.dev

Channel id: 1313161555

Explorer Address: e.g. https://testnet.aurorascan.dev/address/0xB795248717271c50d6D19312B6085bC8c686A529



####  1.Main Contract

Address: 0xB795248717271c50d6D19312B6085bC8c686A529


