# Upstream Sync Setup

## Remotes

| Remote     | Repo                                        | Access     |
|------------|---------------------------------------------|------------|
| `origin`   | https://github.com/anujj-ti/openclaw        | read/write |
| `upstream` | https://github.com/openclaw/openclaw        | read-only  |

## One-time setup

```bash
git remote add upstream https://github.com/openclaw/openclaw.git
```

---

## Your changes → push to your fork

```bash
git add .
git commit -m "your message"
git push origin main
```

## Pull updates from original repo

```bash
git fetch upstream
git merge upstream/main
git push origin main
```
