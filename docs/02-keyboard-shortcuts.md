# GitHub Keyboard Shortcuts

## ⌨️ Master GitHub Navigation

Keyboard shortcuts can significantly speed up your GitHub workflow. This comprehensive guide covers all essential shortcuts.

## Table of Contents
- [Universal Shortcuts](#universal-shortcuts)
- [Site-Wide Shortcuts](#site-wide-shortcuts)
- [Repository Shortcuts](#repository-shortcuts)
- [Code Editor Shortcuts](#code-editor-shortcuts)
- [Pull Request Shortcuts](#pull-request-shortcuts)
- [Issue Shortcuts](#issue-shortcuts)
- [Comment Shortcuts](#comment-shortcuts)
- [Search Shortcuts](#search-shortcuts)

## Universal Shortcuts

These work across the entire GitHub interface:

| Shortcut | Action |
|----------|--------|
| `?` | Show keyboard shortcuts help |
| `s` or `/` | Focus search bar |
| `g` `n` | Go to notifications |
| `g` `i` | Go to issues |
| `g` `p` | Go to pull requests |
| `Esc` | Close dialog/modal |

## Site-Wide Shortcuts

### Navigation

```
g + c    Go to Code tab
g + i    Go to Issues tab  
g + p    Go to Pull Requests tab
g + a    Go to Actions tab
g + b    Go to Projects tab
g + w    Go to Wiki tab
g + g    Go to Discussions tab
```

### Quick Actions

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + K` | Open command palette |
| `Ctrl/Cmd + /` | Toggle forward slash for search |
| `Ctrl/Cmd + B` | Insert bold text |
| `Ctrl/Cmd + I` | Insert italic text |
| `Ctrl/Cmd + Shift + .` | Open command palette |

## Repository Shortcuts

### File Browser

| Shortcut | Action |
|----------|--------|
| `t` | Activate file finder |
| `w` | Switch branch or tag |
| `y` | Expand URL to canonical form |
| `l` | Jump to line |
| `.` | Open in github.dev (web editor) |
| `>` | Open in github.dev (alternative) |
| `Shift + .` | Open in new codespace |

### Code Navigation

```
Arrow Up/Down    Navigate through files
Enter           Open selected file
Backspace       Go to parent directory
Ctrl/Cmd + F    Find in file
```

### Viewing Code

| Shortcut | Action |
|----------|--------|
| `b` | Open blame view |
| `Shift + B` | Close blame view |
| `Ctrl/Cmd + Shift + K` | Delete line |
| `Ctrl/Cmd + F` | Search in file |
| `Ctrl/Cmd + G` | Find next |
| `Ctrl/Cmd + Shift + G` | Find previous |

## Code Editor Shortcuts

### Editing Files on GitHub

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + F` | Start searching in file |
| `Ctrl/Cmd + G` | Find next |
| `Ctrl/Cmd + Shift + G` | Find previous |
| `Ctrl/Cmd + Shift + F` | Replace |
| `Ctrl/Cmd + Shift + R` | Replace all |
| `Alt + G` | Jump to line |
| `Ctrl/Cmd + Z` | Undo |
| `Ctrl/Cmd + Y` | Redo |
| `Ctrl/Cmd + Home` | Go to start of file |
| `Ctrl/Cmd + End` | Go to end of file |

### Selection

```
Shift + Arrow Keys       Select text
Ctrl/Cmd + A            Select all
Ctrl/Cmd + D            Select word
Ctrl/Cmd + L            Select line
```

### Multi-Cursor

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + Click` | Add cursor |
| `Ctrl/Cmd + Alt + Arrow Up/Down` | Add cursor above/below |
| `Ctrl/Cmd + Shift + L` | Add cursors to all matches |
| `Esc` | Cancel multiple cursors |

## Pull Request Shortcuts

### Viewing Pull Requests

| Shortcut | Action |
|----------|--------|
| `c` | Open commits list |
| `t` | Open changed files list |
| `Ctrl/Cmd + Shift + Enter` | Submit comment |
| `Ctrl/Cmd + Enter` | Submit comment and close |
| `r` | Quote selected text in reply |

### Review Mode

```
n    Next file
p    Previous file
j    Next comment
k    Previous comment
```

### Diff View

| Shortcut | Action |
|----------|--------|
| `Alt + Click` | Toggle diff display mode |
| `o` or `Enter` | Open file |

## Issue Shortcuts

### Issue Management

| Shortcut | Action |
|----------|--------|
| `c` | Create new issue |
| `l` | Filter by or edit labels |
| `m` | Filter by or edit milestones |
| `a` | Filter by or edit assignee |
| `r` | Quote selected text in reply |
| `o` or `Enter` | Open issue |

### Issue Navigation

```
j or Arrow Down    Next issue
k or Arrow Up      Previous issue
q                  Exit issue view
```

## Comment Shortcuts

### Formatting Text

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + B` | Bold text |
| `Ctrl/Cmd + I` | Italic text |
| `Ctrl/Cmd + K` | Insert link |
| `Ctrl/Cmd + Shift + 7` | Insert ordered list |
| `Ctrl/Cmd + Shift + 8` | Insert unordered list |
| `Ctrl/Cmd + Shift + .` | Insert quote |
| `Ctrl/Cmd + E` | Insert code |

### Comment Actions

```
Ctrl/Cmd + Enter           Submit comment
Ctrl/Cmd + Shift + P       Toggle preview/write
Tab                        Indent (in code blocks)
Shift + Tab               Outdent
```

### Advanced Formatting

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + G` | Insert suggestion block |
| `r` | Quote selected text |
| `@username` | Mention user |
| `#issue_number` | Reference issue |
| `:emoji:` | Insert emoji |

## Search Shortcuts

### Repository Search

| Shortcut | Action |
|----------|--------|
| `/` or `s` | Focus search box |
| `Esc` | Close search |
| `Enter` | Jump to selected result |
| `Arrow Up/Down` | Navigate results |

### Advanced Search Syntax

```
code:query          Search code
path:path          Search in path
repo:owner/name    Search in repository
user:username      Search user's repos
org:orgname       Search organization
language:name     Search by language
stars:>n          Repos with stars > n
forks:>n          Repos with forks > n
size:>n           Repos larger than n KB
created:YYYY-MM-DD  Created on date
pushed:YYYY-MM-DD   Pushed on date
```

## Markdown Shortcuts

### In Comments & Issues

| Shortcut | Markdown | Result |
|----------|----------|--------|
| `Ctrl/Cmd + B` | `**bold**` | **bold** |
| `Ctrl/Cmd + I` | `*italic*` | *italic* |
| ``` Ctrl/Cmd + K ``` | `[text](url)` | [link](#) |
| `Tab` | Indent code | Indented |
| Drag & Drop | - | Upload file |

### Quick Formatting

```markdown
# Heading 1
## Heading 2  
### Heading 3

- Bullet list
1. Numbered list

`inline code`

```language
code block
```

> Quote

---
Horizontal rule

- [ ] Task list
- [x] Completed task
```

## GitHub CLI Shortcuts

### Repository Commands

```bash
gh repo view                # View repo
gh repo clone              # Clone repo
gh repo create             # Create repo
gh repo fork               # Fork repo
```

### Issue Commands

```bash
gh issue list              # List issues
gh issue create            # Create issue
gh issue view              # View issue
gh issue close             # Close issue
```

### Pull Request Commands

```bash
gh pr list                 # List PRs
gh pr create               # Create PR
gh pr checkout             # Checkout PR
gh pr merge                # Merge PR
gh pr review               # Review PR
```

## Browser Extensions

### Enhanced Navigation

Consider these extensions for more shortcuts:
- **Octotree**: File tree navigation
- **Refined GitHub**: Enhanced UI with shortcuts
- **GitHub Hovercard**: Quick user/repo info
- **OctoLinker**: Navigate dependencies

## Custom Shortcuts

### Browser Settings

You can create custom shortcuts:
1. Use browser extensions
2. Set up bookmarklets
3. Use tools like AutoHotkey (Windows)
4. Use Keyboard Maestro (Mac)

## Productivity Tips

### 🚀 Power User Moves

1. **Press `?` frequently** - Discover context-specific shortcuts
2. **Use `.` to open web editor** - Quick edits without cloning
3. **Master `g` navigation** - Fastest way to move around
4. **Use `t` for file finder** - Quickly locate files
5. **Learn comment formatting** - Speed up documentation
6. **Use command palette** - `Ctrl/Cmd + K` for everything

### Workflow Examples

#### Quick File Edit
```
1. Navigate to repo
2. Press 't' to open file finder  
3. Type filename
4. Press '.' to open editor
5. Make changes
6. Commit with Ctrl+S
```

#### Fast PR Review
```
1. Open pull request
2. Press 'c' for commits
3. Press 't' for files
4. Use 'n'/'p' to navigate
5. Press 'r' to quote and comment
6. Ctrl+Enter to submit
```

## Cheat Sheet Summary

### Top 20 Most Used Shortcuts

```
?         Help
s or /    Search  
.         Open editor
t         File finder
g+c       Go to code
g+i       Go to issues
g+p       Go to PRs
w         Switch branch
l         Jump to line
c         Create (context)
n/p       Next/Previous
j/k       Down/Up
r         Reply/Quote
o         Open
y         Permanent link
Esc       Close dialog
Ctrl+K    Command palette
Ctrl+B    Bold
Ctrl+I    Italic
Ctrl+Enter Submit
```

## Platform Differences

### Windows/Linux vs Mac

| Windows/Linux | Mac | Action |
|---------------|-----|--------|
| `Ctrl` | `Cmd` | Main modifier |
| `Alt` | `Option` | Secondary modifier |
| `Shift` | `Shift` | Same on both |
| `Enter` | `Return` | Same on both |

## Practice Exercises

1. **Navigation Challenge**: Try moving between tabs using only keyboard
2. **File Finder Drill**: Find 5 files using `t` command
3. **Formatting Speed**: Format a comment using only shortcuts
4. **PR Review Race**: Review a PR without touching mouse

## Additional Resources

- [GitHub Keyboard Shortcuts Documentation](https://docs.github.com/en/get-started/using-github/keyboard-shortcuts)
- [GitHub CLI Manual](https://cli.github.com/manual/)
- [Refined GitHub Extension](https://github.com/refined-github/refined-github)

---

**[← Previous: Getting Started](./01-getting-started.md)** | **[Next: Tips & Tricks →](./03-tips-and-tricks.md)**

**[← Back to Main](../README.md)**
