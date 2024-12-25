# **PEP 8: Python Style Guide Summary**

---

## **Key Principles**
- **Readability**: Write code that is easy to understand.
- **Consistency**: Adhere to project conventions, prioritizing readability.

---

## **Code Layout**
- **Indentation**: Use **4 spaces** per level; avoid tabs.
- **Line Length**: Limit to **79 characters**.
- **Blank Lines**:
  - **2 blank lines** between top-level definitions.
  - **1 blank line** between class methods or logical sections.
- **Imports**:
  1. Standard library.
  2. Third-party packages.
  3. Local modules.
  - Use **absolute imports** unless relative ones improve clarity.
- **Encoding**: Use UTF-8 (`# -*- coding: utf-8 -*-`) when necessary.

---

## **String Usage**
- Use **single (`'`) or double (`"`) quotes** consistently.
- Use **triple quotes** (`"""`) for multi-line strings and docstrings.

---

## **Naming Conventions**
- **Variables/Functions**: `lowercase_with_underscores`
- **Constants**: `UPPERCASE_WITH_UNDERSCORES`
- **Classes**: `CamelCase`
- **Private Members**: `_single_leading_underscore`
- **Modules**: `lowercase` or `lowercase_with_underscores`

---

## **Commenting**
- **Inline Comments**: Start with `#`, leave one space, and ensure relevance.
- **Block Comments**: Align with the code they describe.
- **Docstrings**: Use triple double quotes for public modules, classes, and methods.

---

## **Whitespace Rules**
- Avoid:
  - Extra spaces inside parentheses/brackets.
  - Spaces before commas, colons, or semicolons.
  - Spaces around `=` in default parameter values.
- Use spaces around **binary operators** (`+`, `-`, `=`, etc.).

---

## **Programming Practices**
- Use `is`/`is not` for `None` comparisons (e.g., `if foo is None:`).
- Avoid bare `except:` clauses; use `except Exception:`.
- Use **context managers** (e.g., `with open() as file:`) for resource handling.
- Leverage **type hints** for clarity.
- Keep functions **short and focused**.

---

## **Additional Best Practices**
- Wrap the main program in:
  ```python
  if __name__ == "__main__":
      # Code here
  ```
- Use tools like **pylint**, **flake8**, or **black** for code quality.
- Document public APIs with clear, concise docstrings.

---
