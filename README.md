# Magisk Repo Submissions
This is the place for developers to submit their Magisk Module to the [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo).

## Instructions
1. Please read the [full documentation](https://github.com/topjohnwu/Magisk/blob/master/docs/README.MD). You are expected to have decent knowledge to both Magisk and `git` in order to do a submission
2. Create a new Github repository in your personal account, and push your module files to the repo. If you do not want to start from scratch, the [magisk-module-template](https://github.com/topjohnwu/magisk-module-template) will be a good start.
3. **Only the `master` branch will be visible to the user!** If you are using the module template, you have to manually create the `master` branch. **Submissions with no `master` branch will not be accepted!**
4. File a request by [creating an issue](https://github.com/topjohnwu/Magisk_Repo_Submissions/issues/new). The title of the new issue should start with **`[Submission]`**, and you should provide a **GitHub link** (no other site support) of your own **module's repository**.
5. A collaboration invitation will be sent to your email, please accept it so you have permissions to update your repo.

## Remove a Module
Once you accepted the invitation for collaboration on GitHub, you have **admin** permission; this means you can delete it yourself via GitHub.

## Notes
- After you accepted the invitation, **you should update your module directly to the repo on [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), NOT your personal repo!** Once your repo is successfully cloned to [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), you can delete the one on your account afterwards since it will no longer be used.
- Every time you finish upgrading your repo, increase the `versionCode` in `module.prop`. Magisk Manager compare this value with the local installed module to determine whether an update is available.
