# Discord Bot Project

A multi-functional Discord bot written in **Python** featuring an economy system, fun commands, and utility tools.

## Features

### Fun & Utility Commands
- **!avatar [user]**: Get a user's profile picture.
- **!banner [user]**: Get a user's profile banner.
- **!flip**: Perform a coin flip.
- **!bonk <user>**: Bonk a user with a wooden plank.
- **!ship <user1> <user2>**: Calculate love percentage.
- **!iq [user]**: Measure IQ (for entertainment only).
- **!roulette <user>**: Play Russian roulette.
- **!arrest <user>**: Issue a fake arrest warrant.
- **!achievement <user>**: Award a fake achievement.
- **!fflip <user>**: Politely insult someone.
- **!say <text>**: Make the bot say something (Owner only).
- **!ban <user>**: Fake ban a user.

### Economy (Mari Coin)
- **!slot**: Spin the slot machine using Mari Coins.
- Includes a compensation system and persistent database storage.

### Discord Rich Presence (RPC)
Includes a standalone script to update your Discord status with custom details and uptime tracking.

## Technical Details
- **Language**: Python 3.x
- **Library**: `discord.py`
- **Database**: SQLite3
- **Structure**:
  - `bot.py`: Main entry point.
  - `cogs/`: Modular command sets (MariCoin, Fun, Utils).
  - `scripts/`: Management and RPC scripts.
  - `data/`: Persistent storage.

---
*Created as part of a self-learning project.*
