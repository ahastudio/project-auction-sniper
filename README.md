# Auction Sniper

## Generate TypeScript definitions for CodeceptJS

<https://codecept.io/commands#typescript-definitions>

```bash
mkdir ./tests/typings
npx codeceptjs def --output ./tests/typings
```

## Write `.env` file

```properties
SENDBIRD_APP_ID=<Your Application ID>
SENDBIRD_CHANNEL_URL=<Your Channel URL>
```

## Run tests

### E2E Test

```bash
npm start

# in a new tab
npm test -- --verbose
```

### Unit Test

```bash
npx jest
```
