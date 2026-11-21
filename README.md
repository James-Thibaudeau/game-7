# Game 7: The Road to the Cup

A retro hockey deckbuilder set in the 1986 playoffs. Pick a club, then play through four best-of-7 rounds against tougher and tougher opponents to win the Cup. Lose a series and your run is over.

The whole game is a single HTML file with no build step and no dependencies.

## Play

Open `game7.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 8777
```

Then go to http://localhost:8777/game7.html.

Progress (your current run, Hall of Fame, unlocks) is saved in your browser's local storage.

## How it plays

- **The run:** 16 teams and four rounds: Division Semifinal, Division Final, Conference Final and The Final. Home ice follows the 2-2-1-1-1 format.
- **Key shifts:** you play the big moments (20:00, 12:00 and the final 2:00 of each period). Between them, the game is simulated from team ratings and momentum.
- **Cards and Legs:** each beat you get 3 Legs to spend on cards from the skaters on the ice. Attack cards move the puck up the ice and shoot. Defense cards counter or steal against the other team's next play. Unspent Legs carry over (up to 2).
- **Your deck grows:** after a win you add a new play or upgrade a card. After a loss, Video Review lets you cut or upgrade one.
- **The grind:** injuries, fatigue, penalties, fights, timeouts and pulling the goalie all come into play. Win a series and the team picks up a new superstition, a permanent perk for the rest of the run.
- **Between runs:** achievements unlock coaching perks. Winning the Cup unlocks Dynasty Levels, each adding a new challenge.

The in-game **How to Play** screen has the full rules.

### Controls

| Key | Action |
| --- | --- |
| `1`–`7` | Play a card |
| `Space` | End beat |
| `T` | Timeout |
| `P` | Pull goalie |

## Notes

All teams and players are fictional parodies. The game is not affiliated with any league.

## License

[MIT](LICENSE)
