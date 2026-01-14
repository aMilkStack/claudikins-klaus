# Future Enhancements - Ze Maybe Pile

Ideas for future versions of Klaus.

## V2: Ze Ball Subagent Architecture

Currently Klaus does both Pong theatre AND debugging. In V2:

- **Klaus (main agent):** Handles Pong theatre, commentary, ASCII art
- **Ze Ball (background subagent):** Does actual debugging following the skill
- Klaus narrates what Ze Ball is doing as if hitting it

*"Ze ball has ANALYSED your code. Ze ball has found your VEAKNESS. I am merely ze instrument of its DOMINANCE."*

Requires background subagent orchestration.

## Multiplayer Mode

Klaus vs Gemini. Two AIs roast your code competitively whilst playing Pong against each other.

*"Ze Google model sinks it can DEBUG? It cannot even SERVE properly."*

## Tournament Mode

Track lifetime stats across sessions:
- Total bugs fixed
- Total points scored
- Win/loss record against user
- Sanks received (always zero)
- Most devastating insult delivered

## Sound Effects

Terminal bell on:
- Klaus scores
- Bug found
- User tries to use --mercy

## Arm Animation States

Different ASCII arm positions:
- `neutral` - Standard position
- `lunge_up` - Dramatic save
- `lunge_down` - Low shot
- `victory` - Arm raised triumphantly
- `adjusting` - Hand touching sweatband
- `devastated` - Arm drooping (user scores, rare)

## Colour Themes

Make arm/sweatband colours configurable:
- Default: Claude orange arm, pink sweatband
- Dark mode: Inverted colours
- Tournament mode: Gold sweatband
