# design-tokens-ntgcentral

Bootstrap theme based on NTG Central design tokens.

## Installation

```bash
npm install design-tokens-ntgcentral
```

## Usage

### In React/JavaScript projects

```javascript
import "design-tokens-ntgcentral/dist/ntgcentral-theme.css";
```

### In HTML

```html
<link
  rel="stylesheet"
  href="node_modules/design-tokens-ntgcentral/dist/ntgcentral-theme.css"
/>
```

## Components

### Accordion

The accordion component has been fully customized with NTG Central design tokens:

- **Text Color**: Primary blue (`$ntg-central-brand-colour-primary-blue-default`)
- **Expanded State**: Secondary green dark (`$ntg-central-brand-colour-secondary-green-600-dark`) for text and icons
- **Hover State**: Neutral background with green icons
- **Focus State**: NTG Central focus border (`$effect-ntgc-focus-state-border`)
- **Font Weight**: Bold (700) for better readability
- **Borders**: Light blue borders (`$ntg-central-brand-colour-neutrals-lightblue-600`)

#### Interactive Features

The accordion requires Bootstrap's JavaScript bundle for full functionality:

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
```

See `examples/preview.html` for a complete implementation example.

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
  - `src/_accordion.scss` - Accordion component customizations
  - `src/_buttons.scss` - Button component customizations
  - `src/index.scss` - Main theme entry point
- `examples/` - Usage examples and previews

For detailed setup instructions, see [GETTING-STARTED.md](GETTING-STARTED.md).
