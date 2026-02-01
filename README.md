# Plastik Data Feed

Credit card data feed for the [Plastik](https://github.com/User10796/plastik) app.

## Contents

- `cards.json` — Structured credit card data including signup bonuses, annual fees, reward categories, benefits, and issuer rules.

## How It's Updated

The data is automatically updated weekly by a GitHub Actions workflow in the [plastik](https://github.com/User10796/plastik) repo. The workflow scrapes card data from multiple sources, validates it with Zod schemas, and commits the result here.
