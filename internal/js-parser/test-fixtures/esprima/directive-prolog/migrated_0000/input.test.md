# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > directive-prolog > migrated_0000`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/directive-prolog/migrated_0000/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/directive-prolog/migrated_0000/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/directive-prolog/migrated_0000/input.js"
				end: Object {
					column: 46
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSCallExpression {
				arguments: Array []
				loc: Object {
					filename: "esprima/directive-prolog/migrated_0000/input.js"
					end: Object {
						column: 45
						line: 1
					}
					start: Object {
						column: 1
						line: 1
					}
				}
				callee: JSFunctionExpression {
					id: undefined
					loc: Object {
						filename: "esprima/directive-prolog/migrated_0000/input.js"
						end: Object {
							column: 43
							line: 1
						}
						start: Object {
							column: 1
							line: 1
						}
					}
					head: JSFunctionHead {
						async: false
						generator: false
						hasHoistedVars: false
						params: Array []
						rest: undefined
						returnType: undefined
						thisType: undefined
						typeParameters: undefined
						loc: Object {
							filename: "esprima/directive-prolog/migrated_0000/input.js"
							end: Object {
								column: 12
								line: 1
							}
							start: Object {
								column: 10
								line: 1
							}
						}
					}
					body: JSBlockStatement {
						loc: Object {
							filename: "esprima/directive-prolog/migrated_0000/input.js"
							end: Object {
								column: 43
								line: 1
							}
							start: Object {
								column: 13
								line: 1
							}
						}
						directives: Array [
							JSDirective {
								value: "use\\x20strict"
								loc: Object {
									filename: "esprima/directive-prolog/migrated_0000/input.js"
									end: Object {
										column: 31
										line: 1
									}
									start: Object {
										column: 15
										line: 1
									}
								}
							}
						]
						body: Array [
							JSWithStatement {
								loc: Object {
									filename: "esprima/directive-prolog/migrated_0000/input.js"
									end: Object {
										column: 41
										line: 1
									}
									start: Object {
										column: 32
										line: 1
									}
								}
								body: JSEmptyStatement {
									loc: Object {
										filename: "esprima/directive-prolog/migrated_0000/input.js"
										end: Object {
											column: 41
											line: 1
										}
										start: Object {
											column: 40
											line: 1
										}
									}
								}
								object: JSReferenceIdentifier {
									name: "i"
									loc: Object {
										filename: "esprima/directive-prolog/migrated_0000/input.js"
										identifierName: "i"
										end: Object {
											column: 39
											line: 1
										}
										start: Object {
											column: 38
											line: 1
										}
									}
								}
							}
						]
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```