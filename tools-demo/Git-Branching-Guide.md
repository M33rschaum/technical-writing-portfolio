# 🌿 Git Branching Guide

## 🌱 Creating a New Branch

```bash
git checkout -b feature/my-new-feature
```
Creates and switches to a new branch named `feature/my-new-feature`.

---

## 🔄 Switching Branches

```bash
git checkout main
```
Switches to the `main` branch.

---

## 📌 Listing Branches

```bash
git branch
```
Lists all local branches. The current branch will be highlighted.

---

## 🧹 Deleting a Branch

```bash
git branch -d feature/my-new-feature
```
Deletes the branch locally.

```bash
git push origin --delete feature/my-new-feature
```
Deletes the branch on the remote.

---

## ⬆️ Pushing a Branch to Remote

```bash
git push origin feature/my-new-feature
```
Pushes the new branch to the remote repository.

---

## 📥 Pulling a Remote Branch

```bash
git checkout -b feature/my-new-feature origin/feature/my-new-feature
```
Creates and checks out a local tracking branch from a remote one.

---

## 🧬 Merging a Branch into Main

```bash
git checkout main
git merge feature/my-new-feature
```
Switches to `main` and merges changes from `feature/my-new-feature`.

---

## 🧪 Previewing a Merge

```bash
git merge --no-commit --no-ff feature/my-new-feature
```
Previews the merge without creating a commit.

---

## 🧨 Aborting a Merge

```bash
git merge --abort
```
Cancels a merge and returns to the pre-merge state.

---

## ✨ Rebasing a Branch

```bash
git checkout feature/my-new-feature
git rebase main
```
Reapplies your branch’s commits on top of `main`.

---

## 🚫 Aborting a Rebase

```bash
git rebase --abort
```
Cancels a rebase in progress.

---

## 🔧 Resolving Merge Conflicts

```bash
# Edit conflicted files, then:
git add <filename>
git commit
```
Manually resolve conflicts, stage changes, and commit.

---

## 📤 Force Pushing After Rebase

```bash
git push --force
```
Force-pushes rebased changes to the remote.

---

## 👀 Viewing Branch History

```bash
git log --oneline --graph --all
```
Visualizes the commit history across branches.
