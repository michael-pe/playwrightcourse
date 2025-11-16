# 1. Instructions and Notes

GIT :(Local)
git init
git status
git add .
git commit -m "first commit"
git branch -M main

GIT :(Remote)
git remote add origin https://github.com/michael-pe/playwrightcourse.git
git remote -v
git push -u origin main
git config --list

## 1.1. In this session... 

### 1.1.1. Playwright Test Agents - Installation

**Pre-Check**
1. ✅ VS Code version (> `1.105.0 `) -> Update if required
2. ✅ Check playwright version - good to have it latest
   
```sh
npx playwright --version # Returns current version
npm view playwright version # Returns latest version
```
3. ✅ Update playwright (recommended)

```sh
npm install -D @playwright/test@latest
npx playwright install
```

**Installation Steps**
1. Run `npx playwright init-agents --loop=vscode`
2. Check the generated files
3. Done !🎉

### 1.1.2. Ref:
- [Updating Playwright](https://playwright.dev/docs/intro#updating-playwright)
- [Playwright Agents](https://playwright.dev/docs/test-agents)
- [Agents md](https://github.com/openai/agents.md?tab=readme-ov-file)
---