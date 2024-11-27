# Tana Paste VSCode Extension

Syntax highlighting and editing support for Tana Paste format in Visual Studio Code. This extension enhances the editing experience for Tana Paste files, providing syntax highlighting, auto-completion, and formatting features.

## Features

### Syntax Highlighting
- **Tana Directives**
  - `%%tana%%` - Document header
  - `%%search%%` - Search nodes
  - `%%view:type%%` - View specifications (table, cards, tabs, calendar)

- **References and Tags**
  - Double bracket references: `[[reference]]`
  - Tags: Both `#tag` and `#[[multi word tag]]`
  - Node IDs: `^nodeID`
  - Dates: `[[date:2024-11-26]]`

- **Structure**
  - Fields with `::` separator
  - List items with `-` and proper indentation
  - Checkboxes: `[ ]` and `[x]`

- **Formatting**
  - **Bold** text using `**double asterisks**`
  - __Italic__ text using `__double underscores__`
  - ^^Highlighted^^ text using `^^carets^^`

- **Additional Elements**
  - Code blocks with ```
  - Images using `![alt](url)` syntax

### Editor Features
- Auto-closing pairs for:
  - Brackets (`[]` and `[[]]`)
  - Formatting markers (`**`, `__`, `^^`)
- List folding support
- Smart word selection

## Usage

1. Install the extension
2. Create or open a file with `.tanapaste` extension
3. Start writing in Tana Paste format

Example:
```
%%tana%%
- My First Note #[[personal notes]]
  - Created:: [[date:2024-11-26]]
  - Status:: [[In Progress]]
  - [x] Task 1
  - [ ] Task 2
    - Assigned to:: [[John]]
```

## Known Issues

Please report issues at [repository issue tracker].

## Release Notes

### 0.0.1
Initial release of Tana Paste support with basic syntax highlighting and editor features.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This extension is licensed under the [MIT License](LICENSE).

---

**Enjoy writing in Tana Paste!**
