# ai-api-docs

[![npm version](https://img.shields.io/npm/v/ai-api-docs.svg)](https://www.npmjs.com/package/ai-api-docs)
[![npm downloads](https://img.shields.io/npm/dm/ai-api-docs.svg)](https://www.npmjs.com/package/ai-api-docs)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-api-docs)](https://github.com/lxgic-studios/ai-api-docs/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate API documentation from your route files. Supports markdown and OpenAPI output.

## Install

```bash
npm install -g ai-api-docs
```

## Usage

```bash
npx ai-api-docs ./src/routes/
# → API docs written to API_DOCS.md

npx ai-api-docs ./src/routes/ --format openapi -o spec.yaml
# → OpenAPI 3.0 spec

npx ai-api-docs ./src/api/ -o docs/api.md
# → Custom output path
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT


---

Built by [LXGIC Studios](https://github.com/LXGIC-Studios)

🔗 [GitHub](https://github.com/LXGIC-Studios) · [Twitter](https://x.com/lxgicstudios)

💡 Want more free tools like this? We have 100+ on our GitHub: [github.com/lxgicstudios](https://github.com/lxgicstudios)
