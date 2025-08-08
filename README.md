# Multi-API Documentation

OpenAPI documentation for multiple APIs, automatically published to GitHub Pages.

## Setup

```bash
npm install
npm run build
```

## Usage

- Add OpenAPI specs to `apis/<name>/openapi.yaml`
- Run `npm run build` to generate docs
- Push to trigger GitHub Actions deployment

## Structure

```
apis/
├── books/openapi.yaml
└── pets/openapi.yaml
```

GitHub Actions builds and deploys to Pages automatically.
