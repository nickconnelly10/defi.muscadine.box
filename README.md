# Muscadine DeFi Information Site

A clean, informative DeFi and Bitcoin resource site for the Muscadine ecosystem. Built as a static React app with educational content about Bitcoin and DeFi protocols.

## Features

- **Bitcoin Education**: Comprehensive guides on Bitcoin basics, wallet setup, and node connection details
- **DeFi Information**: Educational content about DeFi protocols, lending platforms, and token swapping
- **Clean UI**: Modern, responsive design with consistent styling
- **No Backend**: 100% static front-end app—no server or database required
- **Error Handling**: Global error boundaries and Sentry integration for robust error logging

## Getting Started

### 1. Clone & Install

```bash
git clone <repository-url>
cd defi.muscadine.box
npm install
```

### 2. Environment Variables (Optional)

Create a `.env` file in the root directory with:

```
VITE_SENTRY_DSN=your_sentry_dsn   # Optional, for error logging
```

- Get a Sentry DSN at https://sentry.io/ (optional)

### 3. Run Locally

```bash
npm run dev
```
Visit [http://localhost:3002](http://localhost:3002)

### 4. Build for Production

To generate a production build, run:

```bash
npm run build
```

The output will be in the `dist/` directory. **Note:** The `dist/` directory is automatically ignored by git and should not be committed.

### 5. Preview Production Build

```bash
npm run preview
```

## Favicon

- The favicon should be placed in `public/favicon.svg`.
- Do not edit or commit any favicon in the `dist/` directory; it is generated automatically during build.

## Deployment

- Deploys as a static site (e.g., Vercel, Netlify, S3, Cloudflare Pages)
- Vercel is pre-configured via `vercel.json`

## Project Structure

- `src/components/` — React UI components (Loader, ErrorBoundary)
- `src/types/` — TypeScript type definitions
- `public/` — Static assets (favicon, legal pages)
- `index.html` — Main HTML entry point

## Content Sections

### Bitcoin
- **About**: Introduction to Bitcoin and getting started guide
- **Node**: Information about Bitcoin nodes and connection details
- **Mempool**: Bitcoin transaction pool information and external links

### DeFi
- **About**: Introduction to DeFi and getting started guide
- **Earn & Borrow**: Links to lending platforms (Aave, Moonwell, Morpho)
- **Token Swap**: Links to decentralized exchanges (Aerodrome, Uniswap)

## Error Logging

- Sentry is integrated for front-end error monitoring (optional, set DSN in `.env`)

## Testing

- **Note:** There are currently no automated tests or test script in this project. If you add tests, update the README accordingly.

## Contributing

- PRs welcome! Please open an issue for feature requests or bugs.

## License

MIT 

*Built on BITCOIN • Secure • Transparent • Professional • Strava Club* 

## Product

- **Launch Health**: `https://health.muscadine.box` 