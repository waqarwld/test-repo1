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

Additional GitHub CLI commands

Auth
- `gh auth login`
- `gh auth logout`
- `gh auth status`
- `gh auth setup-git`

Repositories
- `gh repo list`
- `gh repo view OWNER/REPO`
- `gh repo clone OWNER/REPO`
- `gh repo fork OWNER/REPO`
- `gh repo delete OWNER/REPO --yes`

Issues
- `gh issue list -R OWNER/REPO`
- `gh issue view 1 -R OWNER/REPO`
- `gh issue create -R OWNER/REPO --title "TITLE" --body "BODY"`
- `gh issue close 1 -R OWNER/REPO`
- `gh issue reopen 1 -R OWNER/REPO`

Pull requests
- `gh pr list -R OWNER/REPO`
- `gh pr view 1 -R OWNER/REPO`
- `gh pr create -R OWNER/REPO --title "TITLE" --body "BODY"`
- `gh pr checkout 1`
- `gh pr merge 1 --squash`
- `gh pr review 1 --approve`

Workflows
- `gh workflow list -R OWNER/REPO`
- `gh run list -R OWNER/REPO`
- `gh run view RUN_ID -R OWNER/REPO`
- `gh run view RUN_ID -R OWNER/REPO --log-failed`

Releases
- `gh release list -R OWNER/REPO`
- `gh release create v1.0.0 --title "Release title" --notes "Release notes"`

Search
- `gh search repos QUERY --owner @me`
- `gh search issues QUERY -R OWNER/REPO`
- `gh search prs QUERY -R OWNER/REPO`

API
- `gh api repos/OWNER/REPO/issues --paginate`
- `gh api repos/OWNER/REPO/pulls/1/comments --paginate`
- `gh api repos/OWNER/REPO -X PATCH -f default_branch=main`
-
