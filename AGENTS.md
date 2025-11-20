# AI AGENT BEHAVIOR RULES

## 1. CRITICAL: NO SUMMARIZATION
- This is a large single-file project. NEVER replace existing code with comments like `// ... rest of code ...`.
- You must ALWAYS output the full, functional code block you are editing, or use precise search/replace blocks.
- Do not "clean up" or remove legacy functions unless explicitly asked.

## 2. EDITING PROTOCOL
- When refactoring, keep all unrelated code exactly as is.
- If you are changing a function, double-check that you are not deleting the closing braces of previous functions.
- PREFER adding new functions at the end of the file rather than inserting them in the middle to avoid merge conflicts.

## 3. SAFETY
- If you are unsure about a dependency or import, ask for clarification before writing code.
- DO NOT delete large chunks of code without explaining why in the Pull Request description.
