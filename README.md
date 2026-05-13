# Discord Bot Project

A multi-functional Discord bot written in **Python** featuring an economy system, fun commands, and utility tools.

## Features

## How to Use

This bot utilizes **Discord Slash Commands**. To use a command, simply type `/` in the message bar, select the bot, and choose from the list of available commands. 

- **Auto-completion**: As you type, the bot will suggest commands and parameters.
- **Integrated Help**: Descriptions for each command and its arguments are visible directly within the Discord interface.

## Commands & Features

### Fun & Utility
- avatar: Fetching user high-resolution profile picture.
- banner: Fetching user profile or server banner.
- flip: Tossing a coin with a rare chance for a "super flip."
- bonk: Delivering a firm bonk with a wooden plank to a target.
- ship: Calculating compatibility between two users with a progress bar.
- iq: Measuring user IQ with "questionable" accuracy.
- roulette: Playing a risky game of Russian Roulette.
- arrest: Issuing a fake FBI arrest warrant for Discord crimes.
- achievement: Awarding a randomized achievement to a user.
- fflip: Sending a randomized "polite" insult to a target.
- say: Broadcasting a message through the bot (Owner only).
- ban: Performing a realistic-looking fake ban.

### Economy (Mari Coin)
- slot: Testing your luck on the Slot Machine to earn coins.
  - Cost: 10 Mari Coins per spin.
  - Rewards: Up to 1000 coins for a Mega Jackpot.
  - Compensation: Claim 100 coins once every 24 hours if balance is low.
  - Data: Automatic persistence in the local database.

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
