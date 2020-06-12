# vscode-jest-snippets

[Jest](https://facebook.github.io/jest) snippets extension for [Visual Studio Code](https://code.visualstudio.com/).

## Snippets

Below is a list of all available snippets and the triggers of each one. The **→** means the `TAB` key.

### Globals

|   Trigger | Content            |
| --------: | ------------------ |
|   `desc→` | describe           |
|  `desco→` | describe.only      |
|  `descs→` | describe.skip      |
|  `desce→` | describe.each      |
| `descoe→` | describe.only.each |
| `descse→` | describe.skip.each |
|     `ae→` | afterEach          |
|     `aa→` | afterAll           |
|     `be→` | beforeEach         |
|     `ba→` | beforeAll          |

### Tests

|   Trigger | Content              |
| --------: | -------------------- |
|     `it→` | it                   |
|    `ito→` | it.only              |
|    `its→` | it.skip              |
|    `itt→` | it.todo              |
|    `ite→` | it.each              |
|    `ita→` | it(..., async ...)   |
|   `test→` | test                 |
|  `testo→` | test.only            |
|  `tests→` | test.skip            |
|  `testt→` | test.todo            |
|  `teste→` | test.each            |
| `testoe→` | test.only.each       |
| `testse→` | test.skip.each       |
| `testet→` | test.each (table)    |
|  `testa→` | test(..., async ...) |

### Expect

|   Trigger | Content                            |
| --------: | ---------------------------------- |
|    `exp→` | expect                             |
|   `expr→` | expect.resolves                    |
|  `exprj→` | expect.rejects                     |
|  `expas→` | expect.assertions(count)           |
|  `expha→` | expect.hasAssertions()             |
|     `tb→` | toBe                               |
|   `tbct→` | toBeCloseTo                        |
|    `tbd→` | toBeDefined                        |
|    `tbf→` | toBeFalsy                          |
|   `tbgt→` | toBeGreaterThan                    |
|  `tbgte→` | toBeGreaterThanOrEqual             |
|    `tbi→` | toBeInstanceOf                     |
|   `tblt→` | toBeLessThan                       |
|  `tblte→` | toBeLessThanOrEqual                |
|    `tbn→` | toBeNull                           |
|    `tbt→` | toBeTruthy                         |
|    `tbu→` | toBeUndefined                      |
|     `tc→` | toContain                          |
|    `tce→` | toContainEqual                     |
|     `te→` | toEqual                            |
|    `tse→` | toStrictEqual                      |
|   `thbc→` | toHaveBeenCalled                   |
|  `thbct→` | toHaveBeenCalledTimes              |
|  `thbcw→` | toHaveBeenCalledWith               |
| `thblcw→` | toHaveBeenLastCalledWith           |
|    `thr→` | toHaveReturned                     |
|   `thrt→` | toHaveReturnedTimes                |
|   `thrw→` | toHaveReturnedWith                 |
|  `thlrw→` | toHaveLastReturnedWith             |
|  `thnrw→` | toHaveNthReturnedWith              |
|    `thl→` | toHaveLength                       |
|    `thp→` | toHaveProperty                     |
|     `tm→` | toMatch                            |
|    `tmo→` | toMatchObject                      |
|    `tms→` | toMatchSnapshot                    |
|   `tmis→` | toMatchInlineSnapshot              |
|     `tt→` | toThrow                            |
|    `tte→` | toThrowError                       |
|  `ttems→` | toThrowErrorMatchingSnapshot       |
| `ttemis→` | toThrowErrorMatchingInlineSnapshot |

### Templates

| Trigger | Content |
| ------: | ------- |
|  `jfn→` | jest.fn |

## Settings

The `editor.snippetSuggestions` setting in vscode `settings.json` will show snippets on top of the suggestion list.

```json
"editor.snippetSuggestions": "top"
```

## Credits

- Thanks to [andys8](https://github.com/andys8/vscode-jest-snippets) for snippet base
