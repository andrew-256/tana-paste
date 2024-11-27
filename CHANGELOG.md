# Change Log

All notable changes to the "tana-paste" extension will be documented in this file.

## [0.0.1] - 2024-11-26

### Added
- Initial release
- Basic syntax highlighting for Tana Paste format
- Support for:
  - Tana directives (`%%tana%%`, `%%search%%`, `%%view:type%%`)
  - References (`[[reference]]`)
  - Tags (`#tag` and `#[[multi word tag]]`)
  - Dates (`[[date:YYYY-MM-DD]]`)
  - Fields (`field::value`)
  - Node IDs (`^nodeID`)
  - List items and indentation
  - Checkboxes (`[ ]` and `[x]`)
  - Text formatting (bold, italic, highlight)
  - Code blocks
  - Images
- Auto-closing pairs for brackets, formatting markers
- Folding support for indented lists
