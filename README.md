# Custom color schemes for Mitsubishi GX Works

## Тема VS Code

Экспортировать цвета текущией темы VS Code:

```
Developer: Generate Color Theme From Current Settings
```

Определить цвета в редакторе:

```
Developer: Inspect Editor Tokens and Scopes
```

Описание цветов - https://code.visualstudio.com/api/references/theme-color#editor-colors

## Соответствие цветов GX Works 3

| GX Works                                      | VS Code                     |
| --------------------------------------------- | --------------------------- |
| **ST Editor**                                 |                             |
| Normal Text                                   | editor.foreground           |
| Normal Background                             | editor.background           |
| Monitor Value                                 | debugTokenExpression.value  |
| Error                                         | editorError.foreground      |
| Syntax                                        | token - keyword.control     |
| Operator                                      | token - keyword.operator    |
| Comment                                       | token - comment text        |
| Constant                                      | token - constant            |
| Character String Constant                     | token - "string"            |
| Device                                        |                             |
| Global Label                                  | editor.foreground           |
| Local Label                                   | editor.foreground           |
| Standard / Safety Shared Global Label         |                             |
| Row No. Text                                  | editorLineNumber.foreground |
| Collapse Text                                 |                             |
| Outline Display                               |                             |
| Highlight Row                                 |                             |
| Texts in Highlighting Matching Brackets       |                             |
| Backgrounds in Highlighting Matching Brackets |                             |
| Track Changes                                 |                             |
| Highlight Incremental Search                  |                             |

