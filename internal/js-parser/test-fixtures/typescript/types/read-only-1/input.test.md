# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > types > read-only-1`

### `ast`

```javascript
JSRoot {
	corrupt: false
	directives: Array []
	filename: "typescript/types/read-only-1/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/types/read-only-1/input.ts"
		end: Object {
			column: 37
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	comments: Array [
		CommentLine {
			id: "0"
			value: " Error"
			loc: Object {
				filename: "typescript/types/read-only-1/input.ts"
				end: Object {
					column: 37
					line: 1
				}
				start: Object {
					column: 29
					line: 1
				}
			}
		}
	]
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "'readonly' type modifier is only permitted on array and tuple literal types."}]}
			}
			location: Object {
				filename: "typescript/types/read-only-1/input.ts"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 26
					line: 1
				}
				start: Object {
					column: 20
					line: 1
				}
			}
		}
	]
	body: Array [
		TSTypeAlias {
			id: JSBindingIdentifier {
				name: "T30"
				loc: Object {
					filename: "typescript/types/read-only-1/input.ts"
					identifierName: "T30"
					end: Object {
						column: 8
						line: 1
					}
					start: Object {
						column: 5
						line: 1
					}
				}
			}
			typeParameters: undefined
			trailingComments: Array ["0"]
			loc: Object {
				filename: "typescript/types/read-only-1/input.ts"
				end: Object {
					column: 27
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			right: TSTypeOperator {
				operator: "readonly"
				loc: Object {
					filename: "typescript/types/read-only-1/input.ts"
					end: Object {
						column: 26
						line: 1
					}
					start: Object {
						column: 11
						line: 1
					}
				}
				typeAnnotation: TSStringKeywordTypeAnnotation {
					loc: Object {
						filename: "typescript/types/read-only-1/input.ts"
						end: Object {
							column: 26
							line: 1
						}
						start: Object {
							column: 20
							line: 1
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```

 typescript/types/read-only-1/input.ts:1:20 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ 'readonly' type modifier is only permitted on array and tuple literal types.

    type T30 = readonly string;  // Error
                        ^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
