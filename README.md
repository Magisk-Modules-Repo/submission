# Magisk Repo Submissions
This is the place for developers to submit their Magisk Module to the [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo).

Please [follow me on Twitter](https://twitter.com/topjohnwu) for real-time announcements about the status of the MagiskBot server, emergency issues, new rules or features etc.

## Requirements
- A valid Magisk Module. Please read the [Developer Guides](https://topjohnwu.github.io/Magisk/guides.html) for instructions.
- A well formatted `README.md` containing information about the module. English must be used in `README.md`; other languages are still allowed.
- Only modules that are designed to run on most devices will be accepted. **Device specific modules will be rejected.**
- Modules that are trivial will be rejected. What defines as trivial? Simple boot scripts, prop files, systemize apps etc.

## Submission
1. [Create an issue](https://github.com/Magisk-Modules-Repo/submission/issues/new) with the title starting with **`[Submission]`**. The body of the issue is the **GitHub link** of your own **module's repository**.
2. A moderator will review your module and decide whether your module is **approved** or **rejected**.
3. Once approved, your module will be cloned to [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), and a collaboration invitation will be sent to your email so you have admin permissions to the module.

## Removal
- Once you accepted the invitation for collaboration on GitHub, you have **admin** permission; this means you can delete the module yourself via GitHub.

## Important Notes
- You should update your module directly to the repo on [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), NOT your personal repo! Your personal repository hosting your module will not be used by Magisk in any way.
- Every time you finish upgrading your repo, increment `versionCode` in `module.prop`. Magisk Manager compare this value with the local installed module to determine whether an update is available.
