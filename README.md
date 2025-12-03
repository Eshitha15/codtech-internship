# ⭐ TASK 1 – Version Control Using Git (CODTECH Internship)

## 📌 Objective
To set up a Git repository, create branches, intentionally generate a merge conflict, resolve it using GitHub, and document the entire process with proper commit history.

# ✅ TASK OVERVIEW
In this task, I created a Git repository, added multiple branches, made conflicting changes, triggered a merge conflict, resolved it using the GitHub UI, and documented every step clearly.

 # ✔ Step 1: Created GitHub Repository
- Repository Name: **codtech-internship**
- Added default `README.md`
- Main branch initialized

## ✔ Step 2: Created Branches
- **feature-A**
- **feature-B**

Both were created using GitHub’s branch dropdown UI.

## ✔ Step 3: Introduced Conflicting Changes

### 🔹 On feature-A
Updated README.md to:
HELLO FROM FEATURE A


### 🔹 On feature-B
Updated the SAME LINE in README.md to:

HELLO FROM FEATURE B


This ensures a conflict is guaranteed.

---

## ✔ Step 4: Created Pull Request (feature-B → main)
GitHub displayed:


Can't automatically merge. Conflicts must be resolved.


This confirmed the merge conflict.

---

## ✔ Step 5: Resolved Merge Conflict (GitHub UI)
Inside the conflict editor, GitHub showed markers:

<<<<<<< HEAD
HELLO FROM FEATURE A

HELLO FROM FEATURE B

feature-B


I removed the markers and combined both changes as:


HELLO FROM FEATURE A AND FEATURE B — conflict resolved.


Then clicked:
- **Mark as resolved**
- **Commit merge**

The conflict was successfully resolved.

---

## ✔ Step 6: Merged Pull Request
After resolving the conflict, the PR showed:


Able to merge

I clicked **Merge pull request → Confirm merge**.

Merge completed successfully.


## ✔ Step 7: Documented the Entire Task
- Added `conflict-resolution.md`
- Included all screenshots inside `/screenshots`
- Verified commit history
