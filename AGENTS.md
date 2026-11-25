# Workspace: <project name>

<Project description: what this project is about, its goal and scope.>

Each task keeps its artifacts in its own folder.

## Rules

### Folder per task

- One task = one folder in the project root. All artifacts go inside it, never loose in the root.

### Naming

- Folder names are **snake_case**, short, descriptive, in English (e.g. `teriberka_gastro_research`). "Descriptive" means the name reflects the **task's essence**, not generic placeholders like `session_check` — a reader should understand what the task is about from the name alone.
- Existing folders keep their style — they are tied to existing chats.

### Cleanliness

- **Root:** only task folders and shared docs. No loose files.
- **Inside a task folder:** keep only meaningful final artifacts. Clean up scratch files, debug scripts, and intermediate outputs once they've served their purpose.

## First-run setup

- If the placeholders above (`<...>`) are not filled yet, ask the user one question (e.g. "What is this project — its name and what is it about?") and use the answer to fill them in. Fill them **in English**. Then delete this section from the file.
