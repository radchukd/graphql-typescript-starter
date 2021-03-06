# Graphql starter

Server template for project using graphql

## Included Packages

- Apollo Server Express
- Apollo Server Testing
- Eslint
- Express
- GraphQL Code Generator
- Husky
- Jest
- MongoDB
- Nodemon
- Prettier
- Typescript

## Getting started

### Manual

```bash
# Clone the repository
git clone --depth=1 https://github.com/radchukd/graphql-starter <project_name>

# Install dependencies
cd <project_name> && yarn install

# Configure .env
cp .env.example .env

# Build and run the project
yarn build && yarn start
```

### Docker

```bash
  # Build image
  docker build -t <image_name> .

  # Run image
  docker run -p 3001:3001 <image_id>

```

## Available scripts

In the project directory, you can run:

### `yarn build`

### `yarn debug`

### `yarn dev`

### `yarn generate`

### `yarn lint`

### `yarn lint-fix`

### `yarn test`

### `yarn type-check`

### `yarn start`
