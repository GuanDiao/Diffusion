# Diffusion

A simple Python project.

## Usage

Run the main script:

```bash
python d.py
```

## GitHub and Local Code

Changes made directly on GitHub (e.g., editing a file through the web interface) **do not** automatically affect your local copy. To sync remote changes to your local machine, you need to explicitly pull them:

```bash
git pull origin main
```

Conversely, local changes only appear on GitHub after you commit and push them:

```bash
git add .
git commit -m "your message"
git push origin main
```

## Repository Security

To protect your code from unwanted changes by others:

- **Private repository**: Set the repository visibility to *Private* in GitHub Settings so only invited collaborators can see or modify it.
- **Branch protection rules**: Enable branch protection on your default branch (Settings → Branches) to require pull request reviews before any changes are merged.
- **Limit collaborator access**: Only grant write access to people you trust (Settings → Collaborators).
