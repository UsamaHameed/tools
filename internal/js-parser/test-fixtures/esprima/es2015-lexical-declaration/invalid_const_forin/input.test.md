# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-lexical-declaration > invalid_const_forin`

### `ast`

```javascript
JSRoot {
	body: [
		JSForInStatement {
			body: JSBlockStatement {
				body: []
				directives: []
				loc: SourceLocation esprima/es2015-lexical-declaration/invalid_const_forin/input.js 1:22-1:24
			}
			left: JSVariableDeclaration {
				kind: "const"
				declarations: [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: SourceLocation esprima/es2015-lexical-declaration/invalid_const_forin/input.js 1:11-1:12 (x)
						}
						init: JSNumericLiteral {
							value: 0
							loc: SourceLocation esprima/es2015-lexical-declaration/invalid_const_forin/input.js 1:15-1:16
						}
						loc: SourceLocation esprima/es2015-lexical-declaration/invalid_const_forin/input.js 1:11-1:16
					}
				]
				loc: SourceLocation esprima/es2015-lexical-declaration/invalid_const_forin/input.js 1:5-1:16
			}
			right: JSReferenceIdentifier {
				name: "y"
				loc: SourceLocation esprima/es2015-lexical-declaration/invalid_const_forin/input.js 1:20-1:21 (y)
			}
			loc: SourceLocation esprima/es2015-lexical-declaration/invalid_const_forin/input.js 1:0-1:24
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "js"
				message: RAW_MARKUP {value: "Loop variable declaration may not have an initializer"}
			}
			location: {
				language: "js"
				path: UIDPath<esprima/es2015-lexical-declaration/invalid_const_forin/input.js>
				end: Position 1:16
				start: Position 1:5
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/es2015-lexical-declaration/invalid_const_forin/input.js>
	loc: SourceLocation esprima/es2015-lexical-declaration/invalid_const_forin/input.js 1:0-2:0
}
```

### `diagnostics`

```

 esprima/es2015-lexical-declaration/invalid_const_forin/input.js:1:5 parse(js) ━━━━━━━━━━━━━━━━━━━━━

  ✖ Loop variable declaration may not have an initializer

    for (const x = 0 in y){}
         ^^^^^^^^^^^


```
