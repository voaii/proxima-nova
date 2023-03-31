# Proxima Nova

The CSS and web font files to easily self-host the “Proxima Nova” font. 

## Quick Installation

```javascript
yarn add @voaii/proxima-nova // npm install @voaii/proxima-nova
```

Within your app entry file or site component, import it in.

```javascript
import "@voaii/proxima-nova"; // Defaults to weight 400.
```

Supported variables:

- Weights: `[400,700]`
- Styles: `[italic,normal]`
- Supported subsets: `[latin]`

Finally, you can reference the font name in a CSS stylesheet, CSS Module, or CSS-in-JS.

```css
body {
  font-family: "Proxima Nova";
}
```
