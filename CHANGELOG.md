# Change Log

All notable changes to the "Filequest" extension will be documented in this file.

## [0.1.1] - 2026-02-04

### Fixed
- Fixed refresh button not reloading data from disk
- Added file watcher to detect external changes to `.filequest-tasks.json`
- Extension now auto-syncs when database file is modified externally

## [0.1.0] - 2026-02-03

### Initial Release

#### Features
- Create and manage multiple tasks
- Mark files and folders as done/undone
- Visual file decorations in explorer (✓ done, ○ in progress)
- Active task selection for quick marking
- Bulk directory operations (recursive file addition)
- Custom sidebar view with task progress tracking
- Right-click context menu integration
- Git-friendly data storage in `.filequest-tasks.json`
- CLI command support for automation
- Smart directory filtering (excludes node_modules, .git, etc.)
- Workspace-relative file paths for portability
- Alphabetical file sorting for merge conflict avoidance

#### Commands
- `Filequest: Create New Task` - Create a new task
- `Filequest: Set Active Task` - Set the active task
- `Filequest: Mark File as Done` - Mark file/folder as done
- `Filequest: Mark File as Undone` - Add file/folder to task
- `Filequest: List All Tasks` - Show all tasks
- `Filequest: Show Files in Task` - View files in a task
- `Filequest: Delete Task` - Delete a task
- `Filequest: Remove File from Task` - Remove file from task
