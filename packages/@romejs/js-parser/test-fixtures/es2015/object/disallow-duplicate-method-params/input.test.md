# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > object > disallow-duplicate-method-params`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 23
      line: 4
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 12
          index: 15
          line: 2
        }
        start: Object {
          column: 11
          index: 14
          line: 2
        }
      }
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Argument <emphasis>a</emphasis> name clash in strict mode'}
        advice: Array [
          log {
            category: 'info'
            text: 'Defined already here'
          }
          frame {
            location: Object {
              filename: 'input.js'
              end: Object {
                column: 12
                index: 15
                line: 2
              }
              start: Object {
                column: 11
                index: 14
                line: 2
              }
            }
          }
        ]
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 2
          index: 22
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: ObjectExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 21
            line: 3
          }
          start: Object {
            column: 1
            index: 1
            line: 1
          }
        }
        properties: Array [
          ObjectMethod {
            kind: 'method'
            key: StaticPropertyKey {
              value: Identifier {
                name: 'bar'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 7
                    index: 10
                    line: 2
                  }
                  start: Object {
                    column: 4
                    index: 7
                    line: 2
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 7
                  index: 10
                  line: 2
                }
                start: Object {
                  column: 4
                  index: 7
                  line: 2
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 16
                index: 19
                line: 2
              }
              start: Object {
                column: 4
                index: 7
                line: 2
              }
            }
            body: BlockStatement {
              body: Array []
              directives: Array []
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 16
                  index: 19
                  line: 2
                }
                start: Object {
                  column: 14
                  index: 17
                  line: 2
                }
              }
            }
            head: FunctionHead {
              async: false
              generator: false
              hasHoistedVars: false
              predicate: undefined
              rest: undefined
              returnType: undefined
              thisType: undefined
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 14
                  index: 17
                  line: 2
                }
                start: Object {
                  column: 7
                  index: 10
                  line: 2
                }
              }
              params: Array [
                BindingIdentifier {
                  name: 'a'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 9
                      index: 12
                      line: 2
                    }
                    start: Object {
                      column: 8
                      index: 11
                      line: 2
                    }
                  }
                  meta: PatternMeta {
                    optional: undefined
                    typeAnnotation: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 9
                        index: 12
                        line: 2
                      }
                      start: Object {
                        column: 8
                        index: 11
                        line: 2
                      }
                    }
                  }
                }
                BindingIdentifier {
                  name: 'a'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 12
                      index: 15
                      line: 2
                    }
                    start: Object {
                      column: 11
                      index: 14
                      line: 2
                    }
                  }
                  meta: PatternMeta {
                    optional: undefined
                    typeAnnotation: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 12
                        index: 15
                        line: 2
                      }
                      start: Object {
                        column: 11
                        index: 14
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
    }
  ]
}
```