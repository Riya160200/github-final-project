# Git CLI Capstone Tasks — Complete Using Your Own Repository

These steps explain how to produce the four CLI evidence files required by the assignment. Do not submit invented terminal output; run each command and save its real output.

## Task 6 — `forked-repo`
1. Fork `ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub` on GitHub.
2. Replace `YOUR_USERNAME` below with your GitHub username.
3. Run this command and save both the command and response in a file named `forked-repo`:

```bash
curl -s https://api.github.com/repos/YOUR_USERNAME/mcino-Introduction-to-Git-and-GitHub
```

## Task 7 — `merge_branches`
In the cloned lab repository, run:

```bash
git checkout main
git merge bug-fix-typo
```

Save the actual command and terminal output in `merge_branches`. The grading instructions expect the output to show that one file changed. If the branch is missing, revisit the earlier lab steps that create it.

## Task 8 — `bug-fix-revert`
Use the pull request number and repository from your own lab. The assignment asks for a `curl` command and output that verify the pull request and show its source fork. For example, after replacing the placeholders:

```bash
curl -s https://api.github.com/repos/YOUR_USERNAME/mcino-Introduction-to-Git-and-GitHub/pulls/PR_NUMBER
```

Save the command and its real output in `bug-fix-revert`. If the lab specifies a different endpoint or command, follow the lab instructions.

## Task 9 — `github-branches`
Run this inside the repository:

```bash
git branch -a
```

Save the actual command and output in `github-branches`.

## Before submitting
- Ensure the GitHub repository is public.
- Check that each requested file exists at the expected path.
- Use your own GitHub username, repository URL, and pull request number.
- Submit real CLI output generated from your completed lab.
