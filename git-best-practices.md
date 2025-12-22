# Git Best Practices: Commit Messages

Well-crafted commit messages are essential for project maintainability, debugging, and collaboration. They serve as a searchable log of "Why" a change was made, not just "What" was changed.

## 1. The 50/72 Rule
* **Subject Line (50 characters):** A concise summary of the change. 
* **The Blank Line:** A mandatory empty line must exist between the subject and the body.
* **The Body (72 characters):** Explains the "why" and "how" of the change. Hard-wrapped at 72 characters for terminal readability.

## 2. The Imperative Mood
Commit subjects should complete the sentence: *"If applied, this commit will..."*
* **Correct:** `feat: add user authentication`
* **Incorrect:** `added user authentication` or `adding user authentication`

## 3. Atomic Commits
* Commit early and often.
* Each commit should represent a single "logical" change.
* Avoid "Mega-commits" that fix 5 different unrelated bugs.

## 4. Useful Commands
* `git commit`: Opens the default editor for long-form messages.
* `git commit -v`: (Verbose) Shows the "diff" in the editor while writing the message.
* `git config --global core.editor "code --wait"`: Sets VS Code as the default editor.