# README Editions

- [Simple edition](../README.minimal.md): A clean, single-column layout with a visitor counter.
- [Wired World edition](../README.styled.md): Blog-inspired blue and cyan or red and black artwork, angled navigation, and a mixed layout. The top section places About Me and Tech Stack in two columns; Find Me Elsewhere, GitHub Activity, and Visitors each use the full-width layout below.
- [Repository home](../README.md): The active GitHub profile README.

Both editions are tracked in Git. Their artwork lives in `img/readme/`, and they use the same visitor counter.

## Switch the profile README

Run one of these commands from the repository directory in PowerShell:

```powershell
# Use the simple edition
Copy-Item -LiteralPath README.minimal.md -Destination README.md

# Use the Wired World edition
Copy-Item -LiteralPath README.styled.md -Destination README.md
```

Commit and push `README.md` to update the GitHub profile. When editing an edition, update its matching backup as well.
