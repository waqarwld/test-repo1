gh commands

Session: 2026-06-26
- `gh auth status`
- `gh repo create test-repo1 --public --source=. --push`
- `gh repo create test-repo1 --public`
- `gh auth setup-git`
- `gh repo view test-repo1 --json name,owner,visibility,url`
- `gh api repos/waqarwld/test-repo1 -X PATCH -f default_branch=main`
- `gh search repos devops-ai-playbook --owner @me`
- `gh repo view waqarwld/devops-ai-playbook --json name,owner,visibility,url,isPrivate`
-
