# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 122`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/uncategorised/122/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/122/input.js"
		end: Object {
			column: 38
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "es2015/uncategorised/122/input.js"
					identifierName: "A"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2015/uncategorised/122/input.js"
				end: Object {
					column: 38
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2015/uncategorised/122/input.js"
					end: Object {
						column: 38
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "gen"
								loc: Object {
									filename: "es2015/uncategorised/122/input.js"
									identifierName: "gen"
									end: Object {
										column: 21
										line: 1
									}
									start: Object {
										column: 18
										line: 1
									}
								}
							}
							loc: Object {
								filename: "es2015/uncategorised/122/input.js"
								end: Object {
									column: 21
									line: 1
								}
								start: Object {
									column: 18
									line: 1
								}
							}
						}
						loc: Object {
							filename: "es2015/uncategorised/122/input.js"
							end: Object {
								column: 37
								line: 1
							}
							start: Object {
								column: 10
								line: 1
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 10
								line: 1
							}
							loc: Object {
								filename: "es2015/uncategorised/122/input.js"
								end: Object {
									column: 21
									line: 1
								}
								start: Object {
									column: 10
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: true
							hasHoistedVars: false
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "es2015/uncategorised/122/input.js"
								end: Object {
									column: 24
									line: 1
								}
								start: Object {
									column: 21
									line: 1
								}
							}
							params: Array [
								JSBindingIdentifier {
									name: "v"
									loc: Object {
										filename: "es2015/uncategorised/122/input.js"
										identifierName: "v"
										end: Object {
											column: 23
											line: 1
										}
										start: Object {
											column: 22
											line: 1
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "es2015/uncategorised/122/input.js"
											end: Object {
												column: 23
												line: 1
											}
											start: Object {
												column: 22
												line: 1
											}
										}
									}
								}
							]
						}
						body: JSBlockStatement {
							directives: Array []
							loc: Object {
								filename: "es2015/uncategorised/122/input.js"
								end: Object {
									column: 37
									line: 1
								}
								start: Object {
									column: 25
									line: 1
								}
							}
							body: Array [
								JSExpressionStatement {
									loc: Object {
										filename: "es2015/uncategorised/122/input.js"
										end: Object {
											column: 35
											line: 1
										}
										start: Object {
											column: 27
											line: 1
										}
									}
									expression: JSYieldExpression {
										delegate: false
										loc: Object {
											filename: "es2015/uncategorised/122/input.js"
											end: Object {
												column: 34
												line: 1
											}
											start: Object {
												column: 27
												line: 1
											}
										}
										argument: JSReferenceIdentifier {
											name: "v"
											loc: Object {
												filename: "es2015/uncategorised/122/input.js"
												identifierName: "v"
												end: Object {
													column: 34
													line: 1
												}
												start: Object {
													column: 33
													line: 1
												}
											}
										}
									}
								}
							]
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```