# Twind Intellisense

Provides intellisense for [twind](https://github.com/tw-in-js/twind)

## VS Code Settings

### Recommended

```json5
{
	"editor.quickSuggestions": { strings: true },
	"editor.autoClosingQuotes": "always",
}
```

### Default

```json5
{
	"tailwindcss.colorDecorators": null, // inherit from "editor.colorDecorators"
	"tailwindcss.links": null, // inherit from "editor.links"
	"tailwindcss.validate": true,
	"tailwindcss.diagnostics.emptyClass": true,
	"tailwindcss.diagnostics.emptyGroup": true,
	"tailwindcss.diagnostics.conflict": "strict",
	"tailwindcss.preferVariantWithParentheses": false,
	"tailwindcss.fallbackDefaultConfig": true,
}
```

### Semantic Highlight (Experimental)

```json5
{
	"editor.semanticTokenColorCustomizations": {
		enabled: true,
	},
}
```

### Custom Theme

```json5
{
	"workbench.colorCustomizations": {
		"[Atom One Dark]": {
			"editorHoverWidget.background": "#17202ee5",
			"editorHoverWidget.border": "#6a7473",
			"editorSuggestWidget.background": "#17202ee5",
			"editorSuggestWidget.border": "#6a7473",
			"editorSuggestWidget.selectedBackground": "#009c70d0",
			"editor.wordHighlightBackground": "#0000",
		},
	},
}
```
