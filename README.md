# Discord Player Info Bot (Template, may change later)

## Overview

The Discord Player Info Bot is a bot designed to provide player information on command. This bot can be used in gaming communities to display stats, profiles, and other relevant information about players in various games.

## Features

- Retrieve and display player statistics.
- Support for multiple games.
- Easy-to-use command structure.
- Configurable settings for personalized usage.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v12 or higher)
- [Discord.js](https://discord.js.org/) (v13 or higher)
- A Discord Bot Token (You can get this from the [Discord Developer Portal](https://discord.com/developers/applications))

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/discord-player-info-bot.git
   cd discord-player-info-bot

2. Install the dependencies:
   ```js
   npm install

3. Create a .env file in the root directory and add your Discord Bot Token:
   ```env
   DISCORD_TOKEN=your-bot-token

## Running: 

 Start the bot with:
   ```bash
   node index.js
   ```

## Usage

### Commands:

- !playerinfo [playername] - Displays information about the specified player.
- !gamestats [game] [playername] - Shows stats for a player in a specific game.
- !help - Lists all available commands.

## Configuration:

 ```json
  {
     "prefix": "!",
     "games": ["game1", "game2", "game3"]
  }
```

## Acknowledgments

- [Discord.js](https://discord.js.org/)
- [Node.js](https://discord.js.org/)

## Creators:

-  <a href="https://www.linkedin.com/in/thiago-laass/"> Thiago Laass</a>
-  <a href="https://www.linkedin.com/in/isaac-penaforte-690697248/"> Isaac Penaforte</a>
