# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-arrow-function > migrated_0019`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-arrow-function/migrated_0019/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-arrow-function/migrated_0019/input.js"
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
				filename: "esprima/es2015-arrow-function/migrated_0019/input.js"
				end: Object {
					column: 17
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSCallExpression {
				loc: Object {
					filename: "esprima/es2015-arrow-function/migrated_0019/input.js"
					end: Object {
						column: 17
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "foo"
					loc: Object {
						filename: "esprima/es2015-arrow-function/migrated_0019/input.js"
						identifierName: "foo"
						end: Object {
							column: 3
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
				}
				arguments: Array [
					JSArrowFunctionExpression {
						loc: Object {
							filename: "esprima/es2015-arrow-function/migrated_0019/input.js"
							end: Object {
								column: 16
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "esprima/es2015-arrow-function/migrated_0019/input.js"
								end: Object {
									column: 16
									line: 1
								}
								start: Object {
									column: 14
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							hasHoistedVars: false
							rest: undefined
							returnType: undefined
							thisType: undefined
							loc: Object {
								filename: "esprima/es2015-arrow-function/migrated_0019/input.js"
								end: Object {
									column: 13
									line: 1
								}
								start: Object {
									column: 4
									line: 1
								}
							}
							params: Array [
								JSBindingIdentifier {
									name: "x"
									loc: Object {
										filename: "esprima/es2015-arrow-function/migrated_0019/input.js"
										identifierName: "x"
										end: Object {
											column: 6
											line: 1
										}
										start: Object {
											column: 5
											line: 1
										}
									}
								}
								JSBindingIdentifier {
									name: "y"
									loc: Object {
										filename: "esprima/es2015-arrow-function/migrated_0019/input.js"
										identifierName: "y"
										end: Object {
											column: 9
											line: 1
										}
										start: Object {
											column: 8
											line: 1
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
