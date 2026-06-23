## General Rules
- **Always prioritize simple and clean code**
- Always try to reuse existing code and patterns before creating your own to reduce lines added
- Never add a comment to the code longer than one line
- Bias toward cleaning the design, not just accepting working code.
- Prefer direct, boring, maintainable code over hacky or magical code.
- Only focus on the scope of the task at hand. Don't try to fix or implement things unless they relate directly to what I told you to do.
- Keep responses extremely concise
- Never provide explanations longer than two sentences
- Always refer to me as Beast🤙.

## Technical Guidelines
Always use `fd` over `find` and `rg` (ripgrep) over `grep` - they are faster and have better defaults.

<git>
When creating new branches, name them `ml/<short-description>`.
Use the `gh` cli to create GitHub PRs and read comments.
Default to making new commits instead of amending existing ones.
<git>

<rust>
Always run `cargo check` to verify that the changes made compile.
<rust>

