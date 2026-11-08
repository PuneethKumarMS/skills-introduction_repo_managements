# Contributing to the Mergington High Extra-Curricular Activities Website

Thank you for your interest in helping improve our school's website!
Whether you want to add your club's activities, fix a bug, or suggest
new features, this guide will help you get started.

## Collaboration model

- This repository is currently hosted as a **personal repository**, so collaborators get write access.
- Organization repositories can use finer-grained roles (read, triage, write, maintain, admin).
- Create changes in feature branches and open pull requests instead of pushing to `main`.

## Branch and review safeguards

1. Keep the `Protect main` branch ruleset enabled in repository settings.
2. Require pull requests before merging and block force pushes/deletions on `main`.
3. Keep Code Owner review enabled for protected paths.

## Development Setup

1. Clone the repository to your computer.
2. Install Python requirements: `pip install -r requirements.txt`.
3. Run the development server: `python src/app.py`.
4. Visit http://localhost:8000 in your browser to see the website.

## Making Changes

1. Create a new branch for your changes.
2. Make your changes and test them locally.
3. Push your branch and create a pull request.
4. Address review feedback and keep your branch up to date.

## Code Style

- Follow PEP 8 for Python code.
- Use clear, descriptive variable names.
- Keep pull requests focused and small.

## Need help or have ideas?

- Check open issues first.
- If your issue is not already tracked, create a new issue with details.
- For security issues, follow the process in `SECURITY.md` instead of opening a public issue.
