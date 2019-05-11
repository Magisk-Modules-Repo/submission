# Magisk Repo Submissions
This is the place for developers to submit their Magisk Module to the [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo).

You might want to [follow me on Twitter](https://twitter.com/topjohnwu) for real-time announcements about the status of the MagiskBot server, emergency issues, new rules or features etc.

## Announcements
- **2019.5.10**: All repos on [Magisk-Modules-Grave](https://github.com/Magisk-Modules-Grave) is removed before scheduled date due to ID clashes.
- **2019.5.1**: 140 outdated modules are removed from Magisk-Modules-Repo. Removed modules are moved to [Magisk-Modules-Grave](https://github.com/Magisk-Modules-Grave), and scheduled to be wiped out on **2019.6.1**.
- **2019.3.28**: A new Magisk installer format is now enforced. Please carefully read through the [updated documentations](https://topjohnwu.github.io/Magisk/guides.html) to learn how to migrate to the new format. All modules that are not updated will be removed on May 1st, 2019.
- **2018.10.16**: All DNS related modules are restored back to Magisk-Modules-Repo.

## Prerequisite
1. Read the [Magisk Documentation](https://topjohnwu.github.io/Magisk/). Module developers are expected to be familiar with Magisk and GitHub.
2. Create a repository with your personal GitHub account, and host your module in the repo.

## Requirements
- A valid Magisk Module. (e.g. proper and unique `id`, `versionCode` should be an integer etc.)
- Follow the format of the official [Magisk Module Installer](https://github.com/topjohnwu/magisk-module-installer).
- A well formatted `README.md` containing information about the module.
- English must be used in `README.md`, other languages are allowed.
- No material infringing copyright.

## What Will NOT be Approved
- If you cannot properly submit a module, it means you cannot even read basic instructions.  
Your module will never get approved even if you get it right after multiple "tries".
- A repo that does not follow the format of [Magisk Module Installer](https://github.com/topjohnwu/magisk-module-installer).
- A repo without `master` branch.
- A module that only contains some simple boot scripts.
- A module that only uses `system.prop` to modify system props.
- A module that is simply a duplicate of an existing module, or only little modifications are done.  
In other words: no plagiarism.

## Submission
1. [Create an issue](https://github.com/Magisk-Modules-Repo/submission/issues/new) with the title starting with **`[Submission]`**. The body of the issue is the **GitHub link** of your own **module's repository**.
2. A moderator will review your module and decide whether your module is **approved** or **rejected**.
3. Once approved, your module will be cloned to [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), and a collaboration invitation will be sent to your email so you have admin permissions to the module.

## Removal
- Once you accepted the invitation for collaboration on GitHub, you have **admin** permission; this means you can delete the module yourself via GitHub.

## Notes
- You should update your module directly to the repo on [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), NOT your personal repo! Your personal repository hosting your module will not be used by Magisk in any way.
- Every time you finish upgrading your repo, increment `versionCode` in `module.prop`. Magisk Manager compare this value with the local installed module to determine whether an update is available.
