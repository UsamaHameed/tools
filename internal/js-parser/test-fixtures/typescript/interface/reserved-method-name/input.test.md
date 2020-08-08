# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > interface > reserved-method-name`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/interface/reserved-method-name/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/interface/reserved-method-name/input.ts"
		end: Object {
			column: 0
			line: 4
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		TSInterfaceDeclaration {
			id: JSBindingIdentifier {
				name: "I"
				loc: Object {
					filename: "typescript/interface/reserved-method-name/input.ts"
					identifierName: "I"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 10
						line: 1
					}
				}
			}
			extends: undefined
			typeParameters: undefined
			loc: Object {
				filename: "typescript/interface/reserved-method-name/input.ts"
				end: Object {
					column: 1
					line: 3
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			body: TSInterfaceBody {
				loc: Object {
					filename: "typescript/interface/reserved-method-name/input.ts"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 12
						line: 1
					}
				}
				body: Array [
					TSMethodSignature {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "catch"
								loc: Object {
									filename: "typescript/interface/reserved-method-name/input.ts"
									identifierName: "catch"
									end: Object {
										column: 9
										line: 2
									}
									start: Object {
										column: 4
										line: 2
									}
								}
							}
							loc: Object {
								filename: "typescript/interface/reserved-method-name/input.ts"
								end: Object {
									column: 9
									line: 2
								}
								start: Object {
									column: 4
									line: 2
								}
							}
						}
						optional: false
						loc: Object {
							filename: "typescript/interface/reserved-method-name/input.ts"
							end: Object {
								column: 18
								line: 2
							}
							start: Object {
								column: 4
								line: 2
							}
						}
						returnType: TSVoidKeywordTypeAnnotation {
							loc: Object {
								filename: "typescript/interface/reserved-method-name/input.ts"
								end: Object {
									column: 17
									line: 2
								}
								start: Object {
									column: 13
									line: 2
								}
							}
						}
						meta: TSSignatureDeclarationMeta {
							parameters: Array []
							rest: undefined
							typeParameters: undefined
							loc: Object {
								filename: "typescript/interface/reserved-method-name/input.ts"
								end: Object {
									column: 17
									line: 2
								}
								start: Object {
									column: 9
									line: 2
								}
							}
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