# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-import-declaration > invalid-import-default`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						RAW_MARKUP {value: "Unexpected token, expected "}
						"{"
					]
				}
			}
			location: Object {
				filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 14
					line: 1
				}
				start: Object {
					column: 7
					line: 1
				}
			}
		}
	]
	body: Array [
		JSImportDeclaration {
			defaultSpecifier: undefined
			importKind: undefined
			namespaceSpecifier: undefined
			loc: Object {
				filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
				end: Object {
					column: 25
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			source: JSStringLiteral {
				value: ""
				loc: Object {
					filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
					end: Object {
						column: 25
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
			}
			namedSpecifiers: Array [
				JSImportSpecifier {
					loc: Object {
						filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
						end: Object {
							column: 14
							line: 1
						}
						start: Object {
							column: 7
							line: 1
						}
					}
					imported: JSIdentifier {
						name: "default"
						loc: Object {
							filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
							identifierName: "default"
							end: Object {
								column: 14
								line: 1
							}
							start: Object {
								column: 7
								line: 1
							}
						}
					}
					local: JSImportSpecifierLocal {
						name: JSBindingIdentifier {
							name: "default"
							loc: Object {
								filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
								identifierName: "default"
								end: Object {
									column: 14
									line: 1
								}
								start: Object {
									column: 7
									line: 1
								}
							}
						}
						importKind: undefined
						loc: Object {
							filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
							end: Object {
								column: 14
								line: 1
							}
							start: Object {
								column: 7
								line: 1
							}
						}
					}
				}
				JSImportSpecifier {
					loc: Object {
						filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
						end: Object {
							column: 19
							line: 1
						}
						start: Object {
							column: 15
							line: 1
						}
					}
					imported: JSIdentifier {
						name: "from"
						loc: Object {
							filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
							identifierName: "from"
							end: Object {
								column: 19
								line: 1
							}
							start: Object {
								column: 15
								line: 1
							}
						}
					}
					local: JSImportSpecifierLocal {
						name: JSBindingIdentifier {
							name: "from"
							loc: Object {
								filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
								identifierName: "from"
								end: Object {
									column: 19
									line: 1
								}
								start: Object {
									column: 15
									line: 1
								}
							}
						}
						importKind: undefined
						loc: Object {
							filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
							end: Object {
								column: 19
								line: 1
							}
							start: Object {
								column: 15
								line: 1
							}
						}
					}
				}
				JSImportSpecifier {
					loc: Object {
						filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
						end: Object {
							column: 25
							line: 1
						}
						start: Object {
							column: 20
							line: 1
						}
					}
					imported: JSIdentifier {
						name: ""
						loc: Object {
							filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
							identifierName: ""
							end: Object {
								column: 25
								line: 1
							}
							start: Object {
								column: 20
								line: 1
							}
						}
					}
					local: JSImportSpecifierLocal {
						name: JSBindingIdentifier {
							name: ""
							loc: Object {
								filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
								identifierName: ""
								end: Object {
									column: 25
									line: 1
								}
								start: Object {
									column: 20
									line: 1
								}
							}
						}
						importKind: undefined
						loc: Object {
							filename: "esprima/es2015-import-declaration/invalid-import-default/input.js"
							end: Object {
								column: 25
								line: 1
							}
							start: Object {
								column: 20
								line: 1
							}
						}
					}
				}
			]
		}
	]
}
```

### `diagnostics`

```

 esprima/es2015-import-declaration/invalid-import-default/input.js:1:7 parse/js ━━━━━━━━━━━━━━━━━━━━

  ✖ Unexpected token, expected {

    import default from "foo"
           ^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
