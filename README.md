# Riot PHP
PHP wrapper around Riot Games APIs. 

### Features
- 🎉 PSR-18 & PSR-17 compliant - no more dependency on one specific HTTP Client!
- 🎉 Dependency-injection first - easy usage with all modern frameworks! 
- 🎉 GitHub Actions for Quality Assurance - it just works!
- 🎉 Single Responsibility - only API communication inside!

## Getting started
Riot PHP is available via [Composer](https://getcomposer.org/). It does not implement HTTP Client on its own
and uses PSR-17 and PSR-18 abstraction so you are free to choose any HTTP Client you want. 

```
composer require simivar/riot-php symfony/http-client nyholm/psr7
```

## APIs Coverage
| API                  | Docs                                                              | Status | 
| -------------------- | ----------------------------------------------------------------- | ------ |
| Account v1           | [docs](https://developer.riotgames.com/apis#account-v1)           | -      |
| Champion Mastery v4  | [docs](https://developer.riotgames.com/apis#champion-mastery-v4)  | -      |
| Champion v3          | [docs](https://developer.riotgames.com/apis#champion-v3)          | -      |
| Clash v1             | [docs](https://developer.riotgames.com/apis#clash-v1)             | -      |
| League Exp v4        | [docs](https://developer.riotgames.com/apis#league-exp-v4)        | -      |
| League v4            | [docs](https://developer.riotgames.com/apis#league-v4)            | -      |
| Lol Status v3        | [docs](https://developer.riotgames.com/apis#lol-status-v3)        | -      |
| Lor Match v1         | [docs](https://developer.riotgames.com/apis#lor-match-v1)         | -      |
| Lor Ranked v1        | [docs](https://developer.riotgames.com/apis#lor-ranked-v1)        | -      |
| Match v4             | [docs](https://developer.riotgames.com/apis#match-v4)             | -      |
| Spectator v4         | [docs](https://developer.riotgames.com/apis#spectator-v4)         | -      |
| Summoner v4          | [docs](https://developer.riotgames.com/apis#summoner-v4)          | 100%   |
| Tft League v1        | [docs](https://developer.riotgames.com/apis#tft-league-v1)        | -      |
| Tft Match v1         | [docs](https://developer.riotgames.com/apis#tft-match-v1)         | -      |
| Tft Summoner v1      | [docs](https://developer.riotgames.com/apis#tft-summoner-v1)      | -      |
| Third Party Code v4  | [docs](https://developer.riotgames.com/apis#third-party-code-v4)  | 100%   |
| Tournament Stub v4   | [docs](https://developer.riotgames.com/apis#tournament-stub-v4)   | -      |
| Tournament v4        | [docs](https://developer.riotgames.com/apis#tournament-v4)        | -      |

# Legal notice
Riot PHP isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially 
involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks 
or registered trademarks of Riot Games, Inc.
