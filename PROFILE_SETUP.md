# Dakura profile setup

The README controls the main profile content. Account details and pinned projects are configured separately on GitHub.

## Account details

Open your [GitHub profile](https://github.com/DakuraOfficial), choose **Edit profile**, and use these settings:

| Field | Recommendation |
| --- | --- |
| Name | Dakura |
| Bio | Software Developer \| AI & Automation \| Building intelligent systems for the real world. |
| Avatar | Choose and upload it manually through GitHub. Profile automation should leave the avatar unchanged. |
| Company | Optional. Use Code Ninjas only if you want to show that professional association and it is appropriate to do so. Otherwise leave it blank. |
| Website | Leave blank until you have a real public website to share. |
| Social accounts | Leave blank until you provide real accounts you want associated with Dakura. |
| Public email | Leave blank until you choose an address you want publicly visible. |

Save the profile details after reviewing them. The avatar is configured separately; no avatar change is part of this repository.

## Publish the profile README

GitHub displays a profile README when the repository is public, its name matches the username, and it contains a nonempty `README.md` at the root. `DakuraOfficial/DakuraOfficial` already meets these requirements. Publishing the revised files will update the profile.

For future updates, review the intended changes before publishing them on `main` using either method below.

**Git:** From the repository, review and publish the intended files:

```sh
git status
git diff
git add README.md PROFILE_SETUP.md assets/
git commit -m "Build Dakura professional profile"
git push origin main
```

**GitHub UI:** Open the repository on `main`, choose **Add file → Upload files**, and upload `README.md`, `PROFILE_SETUP.md`, and the complete `assets` folder. Preserve the folder structure and review the file list before committing to `main`. Do not upload local preview files or the `.git` folder.

After publication, open your public profile and check the README in GitHub light and dark themes and on a narrow screen. See GitHub's [profile README instructions](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme).

## Choose pinned projects

Start with two or three complete, well-documented public projects. Each should explain the problem, show how to run it, identify its current status, and include screenshots or a demo where useful. Expand toward six only when the additional projects are equally ready.

These are future priorities, not claims about repositories currently available:

1. A well-documented personal AI project.
2. A useful automation tool.
3. A complete full-stack application.
4. An AI agent or API integration.
5. A game-development project.
6. A technically interesting open-source tool.

To pin items manually, open your profile and select **Customize your pins**. Choose the eligible repositories or gists you want to showcase, then save. GitHub allows up to six repositories and gists combined; use the pin editor to arrange them in your preferred order. See GitHub's [pinning instructions](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/pinning-items-to-your-profile).

Publish individual project links only when they are real and ready to share. Keep Code Ninjas work as a professional overview unless you have authorization to release specific material; exclude company-owned code, credentials, internal endpoints, and confidential details.

## Information to add when ready

- Website: A real public site you want linked.
- Social accounts: Your chosen professional accounts.
- Public contact email: An address you explicitly want published.
- Project links: Public repositories, documentation, or demos for completed work.
- Project technologies: Confirmed stacks for each individual project.
- Project evidence: Approved screenshots, examples, and accurate outcomes.
- Company field: Your preference about showing the Code Ninjas association.

No placeholder URLs are needed. Missing optional contact details can remain blank.

## Keep the profile maintainable

- Update project availability and links as work becomes public. Describe ongoing work as ongoing, and verify technologies and outcomes before adding them.
- Keep `assets/header-light.svg` and `assets/header-dark.svg` local. The README's `<picture>` element selects the theme-appropriate header; preserve its relative paths when replacing either graphic.
- Keep technology SVGs in `assets/icons/` and update `assets/ATTRIBUTION.md` when adding or replacing third-party icons.
- Review the current role and project descriptions when they change. Add dates or impact metrics only when you can verify them.
- Keep the technology section clear about AI-assisted use and developing independent fluency. Add proficiency levels only when they accurately reflect your skills.
- GitHub already provides contribution activity on the profile. Add extra statistics only if they remain reliable, accurate, and useful.
