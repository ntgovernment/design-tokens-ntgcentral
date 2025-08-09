# design-tokens-ntgcentral

Bootstrap theme based on NTG Central design tokens.

## Installation

```bash
npm install design-tokens-ntgcentral
```

## Usage

### In React/JavaScript projects

```javascript
import 'design-tokens-ntgcentral/dist/ntgcentral-theme.css';
```

### In HTML

```html
<link rel="stylesheet" href="node_modules/design-tokens-ntgcentral/dist/ntgcentral-theme.css">
```

## Development

```bash
# Install dependencies
npm install

# Build theme
npm run build

# Build in development mode
npm run build:dev

# Watch for changes
npm run watch
```

## Files

- `dist/ntgcentral-theme.css` - Compiled Bootstrap theme with NTG Central design tokens
- `_variables.scss` - Design tokens as SCSS variables
- `_root.scss` - CSS custom properties mapping
- `src/` - Theme source files

For detailed setup instructions, see [GETTING-STARTED.md](GETTING-STARTED.md).