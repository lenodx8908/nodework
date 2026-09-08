# nodework

Learning TypeScript by building tiny CLIs

## Examples

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Install

```bash
npm install
npm run build
```

## Highlights

- commander-based subcommands
- npm link friendly
- Ships as an ESM binary
- Strict tsconfig, no any

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```
