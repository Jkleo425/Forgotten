# Forgotten
Your average Roblox game.

## Project Structure

This project uses [Rojo](https://rojo.space/) for syncing code into Roblox Studio.

### Directory Structure
- `src/server/` - Server-side scripts
- `src/client/` - Client-side scripts (StarterPlayerScripts)
- `src/shared/` - Shared modules accessible from both client and server (ReplicatedStorage)

## Getting Started

### Prerequisites
- [Roblox Studio](https://www.roblox.com/create)
- [Rojo](https://rojo.space/) - For syncing code to Roblox Studio

### Building the Place
1. Install Rojo
2. Run `rojo serve` in the project directory
3. Open Roblox Studio
4. Install the Rojo plugin
5. Connect to the Rojo server

### Development
- The workspace includes a baseplate by default
- Server scripts go in `src/server/`
- Client scripts go in `src/client/`
- Shared modules go in `src/shared/`

## Project Configuration
- `default.project.json` - Rojo project configuration
- `wally.toml` - Package dependencies (Wally)
