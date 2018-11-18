# md-it-mermaid

> markdown-it plugin for mermaid

## Usage

```bash
yarn add md-it-mermaid
```

```javascript
const MarkdownIt = require('markdown-it')
const mditMermaid = require('md-it-mermaid')

const parser = new MarkdownIt(options)

parser.use(mditMermaid)

parser.render('### md-it-mermaid')
```
