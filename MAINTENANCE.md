# Portfolio Maintenance Guide

## Adding a New Challenge Writeup

1. Copy `writeups/TEMPLATE.md` to `writeups/bellingcat-challenge-XXX.md`
2. Fill in the template as you work through the challenge
3. If using images, create folder `images/bellingcat-XXX/`
4. Redact any personal info from screenshots before adding them
5. Update the main `README.md` with a link to your new writeup

## OPSEC Checklist Before Publishing

Before committing/pushing any writeup:

- [ ] Screenshots have no personal browser history visible
- [ ] No account usernames/emails visible in screenshots
- [ ] No EXIF data in images (or you've stripped it)
- [ ] No unintended tabs/bookmarks visible in browser screenshots
- [ ] File paths don't reveal your username/system details
- [ ] Any API keys or tokens are redacted

## Git Workflow

```bash
# First time setup (do once)
cd /path/to/osint-portfolio
git init
git add .
git commit -m "Initial portfolio setup"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/osint-portfolio.git
git push -u origin main

# Adding new writeups (repeat for each)
git add writeups/bellingcat-challenge-XXX.md
git add images/bellingcat-XXX/
git commit -m "Add Bellingcat Challenge XXX writeup"
git push
```

## Tips

- Write as you go, not after completion (you'll forget details)
- Include dead ends - shows analytical thinking
- Link to tools/resources you used
- Keep a "lessons learned" section - employers love this
- Update your main README with new skills/tools as you learn them
