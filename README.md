# Frappe JS and Python Snippets

## Overview
This Visual Studio Code extension provides useful Frappe framework snippets for both JavaScript and Python. These snippets will help speed up your development process when working with Frappe applications.

## Features
The extension includes the following snippets:

### JavaScript Snippets:
- **custom_button_frappe**: A quick snippet to add code of add custom button.
- **frappe_call**: Easily call a backend method with `frappe.call`.

### Python Snippets:
- **@**: make Method whitelisted.
- **frappe_set_value**: Set a value in Frappe using frappe.db.set_value.

## How to Use
1. Install the extension.
2. Start typing the snippet trigger (e.g., `frappe.call`) and select the snippet from the suggestion list.

## Snippets in Detail

### JavaScript Snippets
| Trigger      | Content                        |
|--------------|--------------------------------|
| `dialog_frappe` | dialog box code  |
| `frappe_call` | `frappe.call(...)` |

### Python Snippets
| Trigger               | Content                                   |
|-----------------------|-------------------------------------------|
| `@`  | `@frappe.whitelist()` |
| `frappe_set_value`       | `frappe.db.set_value('DocType', 'name', 'field_name', new_value)` |

## Installation
1. Download and install this extension from the VS Code marketplace.
2. Open any JavaScript or Python file and start typing to use the snippets.

## License
This extension is licensed under the MIT License.
