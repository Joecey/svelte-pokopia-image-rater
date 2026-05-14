# Pokopia Image Rater

Get inspired by popular Pokopia builds on Reddit while saving your favorites to a personal mood board.

## Project Structure

### 🤖 Scraper (`apps/scraper`)
Scrapes the r/pokopia subreddit for new builds, using an LLM to read comments and descriptions to provide an overall vibe for each build.

### 🌐 Web (`apps/web`)
SvelteKit webapp that presents the best builds of the week and allows you to save and make notes on your own mood board.

## Getting Started

### Install Dependencies
```sh
pnpm install
```

### Development

Run both services:
```sh
# Web app
pnpm dev:web

# Scraper
pnpm dev:scraper
```

### Build

Build all apps:
```sh
pnpm build
```

Build individually:
```sh
pnpm build:web
pnpm build:scraper
```

### Production

```sh
# Preview web app
pnpm preview:web

# Start scraper
pnpm start:scraper
```

## Other Commands

```sh
# Type checking
pnpm check

# Linting
pnpm lint

# Formatting
pnpm format
```
