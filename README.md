# Discord Political Party Bot

A Discord bot that simulates political factions and voting for control of a Discord server, with certain features being restricted or available based on faction control.

## Overview

This bot creates a simulated political environment within your Discord server where users can:

- Join different political factions/parties
- Vote in elections for server control
- Access (or be restricted from) certain features based on ruling party policies
- Participate in debates and policy-making decisions

## Features

- **Faction System**: Create and join political parties with unique platforms
- **Voting Mechanism**: Hold regular elections for server control
- **Policy Implementation**: Winning factions can implement policies affecting server features
- **Role Management**: Automatic assignment of roles based on faction membership
- **Command System**: Intuitive slash commands for all bot interactions

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/probsJustin/discord_democracy_bot.git
   cd discord_democracy_bot
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up your `.env` file:
   ```
   discord_token=YOUR_DISCORD_BOT_TOKEN
   ```

4. Start the bot:
   ```bash
   npm start
   ```

## Usage

The bot uses Discord's slash commands. Here are some examples:

- `/hello` - Basic greeting command (currently implemented)
- `/join-party [party-name]` - Join a political faction
- `/vote [candidate]` - Cast your vote in an election
- `/create-policy [details]` - Propose a new server policy

## Development

This bot is built with:
- [Discord.js](https://discord.js.org/) - Discord API library
- TypeScript - For strongly typed JavaScript
- Node.js - Runtime environment

The project structure follows a modular pattern:
- `src/bot.ts` - Main bot initialization
- `src/command.ts` - Command interface definition
- `src/commands.ts` - Command registration
- `src/commands/` - Individual command implementations
- `src/listeners/` - Event listeners for Discord events

## Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the ISC License - see the LICENSE file for details.

## Resources

- [Discord.js Documentation](https://discord.js.org/#/docs/discord.js/stable/general/welcome)
- [Discord.js GitHub](https://github.com/discordjs/discord.js)
- [Project Structure Based on This Tutorial](https://sabe.io/tutorials/how-to-build-discord-bot-typescript)

## Contact

For issues and feature requests, please use the [GitHub issue tracker](https://github.com/probsJustin/discord_democracy_bot/issues).