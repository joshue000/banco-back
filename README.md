# repo-interview

REST API built with Node.js, TypeScript and Express using routing-controllers.

## Requirements

- Node.js 18+
- npm

## Installation

```bash
npm install
```

## Running

### Development
```bash
npm run start:dev
```

### Production
```bash
npm run build
npm start
```

## Docker

### Build image
```bash
docker build -t repo-interview .
```

### Run container
```bash
docker run -p 3002:3002 repo-interview
```

## API

The API is available at `http://localhost:3002/bp`
