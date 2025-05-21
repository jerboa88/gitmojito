<!-- Project Header -->
<div align="center">
  <h1 class="projectName">🌿 gitmojito - Gitmoji x GitHub Labels</h1>

  <p class="projectBadges">
    <a href="https://unmaintained.tech/">
      <img src="https://unmaintained.tech/badge.svg" alt="No Maintenance Intended" title="No Maintenance Intended"/>
    </a>
    <img src="https://johng.io/badges/category/Other.svg" alt="Project category" title="Project category">
    <img src="https://img.shields.io/github/languages/top/jerboa88/gitmojito.svg" alt="Language" title="Language">
    <img src="https://img.shields.io/github/repo-size/jerboa88/gitmojito.svg" alt="Repository size" title="Repository size">
    <a href="LICENSE">
      <img src="https://img.shields.io/github/license/jerboa88/gitmojito.svg" alt="Project license" title="Project license"/>
    </a>
  </p>

  <p class="projectDesc">
    A set of reusable Emoji labels for GitHub issues and PRs
  </p>

  <br/>
</div>


## About
gitmojito is a set of reusable Emoji labels for GitHub issues and PRs. These labels are designed to be as universal as possible, but you can customize them to fit your needs. Since every project is different, I would recommend using the labels as a starting point and adapting them to your project, rather than the other way around.


## Labels
Names, descriptions, and emojis used are based on popular conventions like [Gitmoji](https://gitmoji.dev/), [All Contributors](https://allcontributors.org/), [Conventional Commits](https://www.conventionalcommits.org/), [the Angular convention](https://github.com/angular/angular/blob/main/contributing-docs/commit-message-guidelines.md), and [the default GitHub labels](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels#about-default-labels). The colors used are from the [Tailwind CSS v4 color palette](https://tailwindcss.com/docs/colors#default-color-palette).

Labels are written in lowercase to speed up repeated typing. They are grouped into several categories. Generally, labels in the same category share the same emoji to group them together.

### Type
These labels are used to indicate the type of issue/PR. Unique colors and emojis are used to make them easily distinguishable.

![bug](https://img.shields.io/badge/🐛%20bug-84cc16)
![feature](https://img.shields.io/badge/✨%20feature-f59e0b)
![docs](https://img.shields.io/badge/📝%20docs-3b82f6)
![question](https://img.shields.io/badge/💬%20question-7c3aed)
![security](https://img.shields.io/badge/🔒%20security-ef4444)
![performance](https://img.shields.io/badge/🚀%20performance-14b8a6)
![test](https://img.shields.io/badge/✅%20test-22c55e)
![refactor](https://img.shields.io/badge/♻️%20refactor-06b6d4)
![style](https://img.shields.io/badge/🎨%20style-ec4899)
![build](https://img.shields.io/badge/🔧%20build-64748b)
![ci](https://img.shields.io/badge/👷%20ci-f97316)
![i18n](https://img.shields.io/badge/🌍%20i18n-d946ef)

| Name          | Description                                                                              | Color                 | Notes                       |
| ------------- | ---------------------------------------------------------------------------------------- | --------------------- | --------------------------- |
| ♻️ refactor    | TYPE: A code change that neither fixes a bug nor adds a feature                          | #06b6d4 (Cyan 500)    | **Emoji:** Gitmoji          |
| ✅ test        | TYPE: Adding missing tests or correcting existing tests                                  | #22c55e (Green 500)   | **Emoji:** Gitmoji          |
| ✨ feature     | TYPE: An enhancement or a new feature                                                    | #f59e0b (Amber 500)   | **Emoji:** Gitmoji          |
| 🌍 i18n        | TYPE: Translations and changes related to internationalization                           | #d946ef (Fuschia 500) | **Emoji:** All Contributors |
| 🎨 style       | TYPE: Changes that do not affect the meaning of the code (white-space, formatting, etc.) | #ec4899 (Pink 500)    | **Emoji:** Gitmoji          |
| 🐛 bug         | TYPE: Something isn't working                                                            | #84cc16 (Lime 500)    | **Emoji:** Gitmoji,         |
| 👷 ci          | TYPE: Changes to our CI configuration files and scripts                                  | #f97316 (Orange 500)  | **Emoji:** Gitmoji          |
| 💬 question    | TYPE: A question about the project                                                       | #7c3aed (Violet 500)  | **Emoji:** All Contributors |
| 📝 docs        | TYPE: Documentation only changes                                                         | #3b82f6 (Blue 500)    | **Emoji:** Gitmoji          |
| 🔒 security    | TYPE: A code change that improves security                                               | #ef4444 (Red 500)     | **Emoji:** Gitmoji          |
| 🔧 build       | TYPE: Changes that affect the build system or external dependencies                      | #64748b (Slate 500)   |                             |
| 🚀 performance | TYPE: A code change that improves performance                                            | #14b8a6 (Teal 500)    |                             |

### Status
These labels are used to indicate the status of an issue/PR. They share the same emoji and are color-coded. Darker shades are used to differentiate between other label categories. There are no labels for cancelled or completed issues because GitHub already allow you to close an issue with a reason like 'completed' or 'not planned'.

![new](https://img.shields.io/badge/🚦%20new-1d4ed8)
![confirmed](https://img.shields.io/badge/🚦%20confirmed-4d7c0f)
![in progress](https://img.shields.io/badge/🚦%20in%20progress-b45309)
![blocked](https://img.shields.io/badge/🚦%20blocked-b91c1c)

| Name          | Description                                                                             | Color               | Notes |
| ------------- | --------------------------------------------------------------------------------------- | ------------------- | ----- |
| 🚦 new         | STATUS: A new issue that needs triage                                                   | #1d4ed8 (Blue 700)  |       |
| 🚦 confirmed   | STATUS: An issue that has been reproduced and is ready to be worked on                  | #4d7c0f (Lime 700)  |       |
| 🚦 in progress | STATUS: An issue that is currently being worked on                                      | #b45309 (Amber 700) |       |
| 🚦 blocked     | STATUS: An issue that is blocked by another issue, user input, or other external factor | #b91c1c (Red 700)   |       |

### Priority
These labels are used to indicate the priority of an issue/PR. They share the same emoji and are color-coded, with the color indicating the priority of the issue. Lighter shades are used to differentiate between other label categories.

![low](https://img.shields.io/badge/🚩%20low-93c5fd)
![medium](https://img.shields.io/badge/🚩%20medium-fde047)
![high](https://img.shields.io/badge/🚩%20high-fdba74)
![critical](https://img.shields.io/badge/🚩%20critical-fca5a5)

| Name       | Description                                | Color                | Notes |
| ---------- | ------------------------------------------ | -------------------- | ----- |
| 🚩 low      | PRIORITY: An issue that is not urgent      | #93c5fd (Blue 300)   |       |
| 🚩 medium   | PRIORITY: An issue that is somewhat urgent | #fde047 (Yellow 300) |       |
| 🚩 high     | PRIORITY: An issue that is urgent          | #fdba74 (Orange 300) |       |
| 🚩 critical | PRIORITY: An issue that is critical        | #fca5a5 (Red 300)    |       |

### Effort
These labels are used to indicate the effort required to complete an issue/PR and are based on the Fibonacci series. They share the same emoji and are color-coded, with darker shades indicating a greater effort and lighter shades indicating a lesser effort.

![1](https://img.shields.io/badge/⏳%201-e4e4e7)
![2](https://img.shields.io/badge/⏳%202-a1a1aa)
![3](https://img.shields.io/badge/⏳%203-52525b)
![5](https://img.shields.io/badge/⏳%205-27272a)
![8](https://img.shields.io/badge/⏳%208-09090b)

| Name | Description                                   | Color              | Notes |
| ---- | --------------------------------------------- | ------------------ | ----- |
| ⏳ 1  | EFFORT: An issue requiring a very low effort  | #e4e4e7 (Zinc 200) |       |
| ⏳ 2  | EFFORT: An issue requiring a low effort       | #a1a1aa (Zinc 400) |       |
| ⏳ 3  | EFFORT: An issue requiring a medium effort    | #52525b (Zinc 600) |       |
| ⏳ 5  | EFFORT: An issue requiring a high effort      | #27272a (Zinc 800) |       |
| ⏳ 8  | EFFORT: An issue requiring a very high effort | #09090b (Zinc 950) |       |

### Other
These labels are used to indicate other information about an issue/PR. Some replace default GitHub labels. They share the same color.

![good first issue](https://img.shields.io/badge/👋%20good%20first%20issue-fef08a)
![help wanted](https://img.shields.io/badge/🙋‍♂️%20help%20wanted-fef08a)
![epic](https://img.shields.io/badge/🗄️%20epic-fef08a)

| Name               | Description                                       | Color                | Notes |
| ------------------ | ------------------------------------------------- | -------------------- | ----- |
| 👋 good first issue | An issue that is good for first-time contributors | #fef08a (Yellow 200) |       |
| 🙋‍♂️ help wanted      | An issue that needs help from the community       | #fef08a (Yellow 200) |       |
| 🗄️ epic             | An issue that is a collection of other issues     | #fef08a (Yellow 200) |       |


## Usage
See [labels.yml](labels.yml) for the list of labels in YAML format.

You can manually create these labels in your GitHub repository, or they can be automatically synced between repositories with the GitHub API using [micnncim/action-label-syncer](https://github.com/micnncim/action-label-syncer) or [brpaz/action-label-syncer](https://github.com/brpaz/action-label-syncer) (an updated fork).

If you are getting the labels programmatically, I would recommend fixing the tag to a specific version like `v1.0.0` instead of using `latest`, as the labels may change over time.


## Versioning
This project follows [Semantic Versioning](https://semver.org/) with the following guidelines:

Major:
- Removing labels
- Renaming labels
- Other breaking changes

Minor:
- Adding labels
- Changing label color
- Changing label description

Documentation or CI changes do not trigger a new release.


## Contributing
Contributions, issues, and forks are welcome.


## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

This project is not affiliated with GitHub or Gitmoji.
