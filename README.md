# Magisk Repo Submissions
This is the place for developers to submit their Magisk Module to the [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo).

## Prerequisite
1. Read the [Magisk Documentation](https://github.com/topjohnwu/Magisk/blob/master/docs/README.MD). Module developers are expected to be familiar with Magisk and GitHub.
2. Create a repository with your personal GitHub account, and host your module in the repo.

## Requirements
- A valid Magisk Module. (e.g. proper and unique `id`, `versionCode` should be an integer etc.)
- A well formatted `README.md` containing information about the module.
- English must be used in `README.md`, other languages are allowed.
- No material infringing copyright.

## What Will NOT be Approved
- A repo without `master` branch.
- A module that only contains some simple boot scripts.
- A module that only uses `system.prop` to modify system props.
- A module that is simply a duplicate of an existing module, or only small modification are done. In layman's term: no plagiarism.

## Submission
1. [Create an issue](https://github.com/Magisk-Modules-Repo/submission/issues/new) with the title starting with **`[Submission]`**. The body of the issue is the **GitHub link** of your own **module's repository**.
2. A moderator will review your module and decide whether your module is **approved** or **rejected**.
3. Once approved, your module will be cloned to [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), and a collaboration invitation will be sent to your email so you have admin permissions to the module.

## Removal
- Once you accepted the invitation for collaboration on GitHub, you have **admin** permission; this means you can delete the module yourself via GitHub.

## Notes
- You should update your module directly to the repo on [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), NOT your personal repo! Your personal repository hosting your module will not be used by Magisk in any way.
- Every time you finish upgrading your repo, increment `versionCode` in `module.prop`. Magisk Manager compare this value with the local installed module to determine whether an update is available.
