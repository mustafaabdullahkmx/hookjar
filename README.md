# hookjar

Small typed hooks: debounce, localStorage, media query, toggle

Small but I use it weekly.

## How to use

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Highlights

- useLocalStorage with JSON serialization
- useDebounce with leading/trailing options
- Tiny: no dependencies besides React
- useMediaQuery SSR-safe

## Installation

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── roadmap.md
│   └── usage.md
├── scripts/
│   └── dev.sh
├── src/
│   ├── config.js
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

## Development

```bash
npm install
npm test
```

## License

MIT - see [LICENSE](LICENSE).
