# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > errors > wrong-opening-tag-fragment`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSXElement {
				attributes: []
				children: []
				selfClosing: false
				name: JSXIdentifier {
					name: "something"
					loc: SourceLocation jsx/errors/wrong-opening-tag-fragment/input.jsx 1:1-1:10
				}
				loc: SourceLocation jsx/errors/wrong-opening-tag-fragment/input.jsx 1:0-1:14
			}
			loc: SourceLocation jsx/errors/wrong-opening-tag-fragment/input.jsx 1:0-1:14
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: [
					log {category: "info", text: [RAW_MARKUP {value: "Originated from opening tag of <emphasis>"}, "something", RAW_MARKUP {value: "</emphasis>"}]}
					frame {
						location: SourceLocation jsx/errors/wrong-opening-tag-fragment/input.jsx 1:1-1:10
					}
				]
				category: ["parse"]
				categoryValue: "js"
				message: [RAW_MARKUP {value: "Expected a corresponding JSX closing tag for <emphasis>"}, "something", RAW_MARKUP {value: "</emphasis>"}]
			}
			location: {
				language: "js"
				path: UIDPath<jsx/errors/wrong-opening-tag-fragment/input.jsx>
				end: Position 1:10
				start: Position 1:1
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: ["jsx"]
	path: UIDPath<jsx/errors/wrong-opening-tag-fragment/input.jsx>
	loc: SourceLocation jsx/errors/wrong-opening-tag-fragment/input.jsx 1:0-2:0
}
```

### `diagnostics`

```

 jsx/errors/wrong-opening-tag-fragment/input.jsx:1:1 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected a corresponding JSX closing tag for something

  ℹ Originated from opening tag of something

    <something></>
     ^^^^^^^^^


```
