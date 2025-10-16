# Browser Mining Implementation

This implementation includes a complete browser-based cryptocurrency mining system with user consent.

## Setup Instructions

1. **Replace Wallet Address**: In `index.html`, find the `MINER_CONFIG` object and replace the `wallet` value with your actual Monero wallet address.

2. **Deploy to GitHub Pages**:
   - Upload all files to your GitHub repository
   - Enable GitHub Pages in repository settings
   - Your site will be available at `https://yourusername.github.io/repository-name`

## Configuration Options

- `threads`: Number of CPU threads to use (1-4 recommended)
- `throttle`: CPU usage limit (0.1 = 10%, 0.5 = 50%, etc.)
- `wallet`: Your cryptocurrency wallet address

## Features

- User consent dialog with clear explanation
- Persistent user preference storage
- Real-time mining statistics
- Start/stop controls
- Mobile-responsive design
