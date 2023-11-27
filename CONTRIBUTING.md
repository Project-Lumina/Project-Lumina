# 🚀 Contributing to Project Lumina

Thank you for considering contributing to Project Lumina! Your efforts play a vital role in making this project better for everyone. Below is a simple rundown of the contribution process. For a more comprehensive guide on pull requests, we recommend checking [GitHub's official documentation](https://docs.github.com/en/pull-requests).

## Simple Run Down for Contributing

1. **Fork:** Begin by forking the repository on GitHub.
2. **Clone:** Clone the forked repository to your local machine (or edit via github.com).
3. **Branch:** Create a new branch for your contributions if necessary.
4. **Commit:** Make changes and commit them.
5. **Push:** Push your changes to your fork on GitHub.
6. **Pull Request:** Open a pull request and explain your contributions.

## Submitting your own Category or Pack

If you wish to add your own category or pack to the mod menu in the shortcut, follow these steps for the `gh-pages` branch:

- **Pack Preparation:** Create a folder on your local device containing .mcpack, .zip, and pack icon files. Ensure filenames match the pack's name in lowercase (e.g., esp.mcpack, esp.zip, and esp.png).
- **Upload:** Upload the folder to any 'category directory' within the [packs directory](https://github.com/riqvip/Project-Lumina/tree/gh-pages/packs). For example, you can upload it to the "hacks" directory.
   - Optionally, you can add a new category directory (steps on this are further down), but note that it may not be accepted as unnecessary categories are discouraged.
- **Update packs.json:** Add your pack to the packs.json file in the packs directory. Refer to the JSON code block for guidance.

```json
"(Pack Name)": {
  "author": "(Your Username)",
  "description": "(Pack Description)",
  "icon": "https://projectlumina.xyz/packs/(category)/(pack name)/(pack name).(image extension)",
  "zip": "https://projectlumina.xyz/packs/(category)/(pack name)/(pack name).zip",
  "mcpack": "https://projectlumina.xyz/packs/(category)/(pack name)/(pack name).mcpack"
}
```

- If you opted to create a new category for your pack, ensure you follow these additional steps:
   
   1. **Update packs.json:** Add the new category to the packs.json file. This involves creating an entry for the category, specifying its name and any relevant details.
      
   2. **Place Your Pack:** Once the category is added, insert your pack into this newly created category within the packs.json file. Below is a JSON code block for reference.

```json
  "(Category Name)": {
    "(Pack Name)": {
      "author": "(Your Username)",
      "description": "(Pack Description)",
      "icon": "https://projectlumina.xyz/packs/(category)/(pack name)/(pack name).(image extension)",
      "zip": "https://projectlumina.xyz/packs/(category)/(pack name)/(pack name).zip",
      "mcpack": "https://projectlumina.xyz/packs/(category)/(pack name)/(pack name).mcpack"
    }
  }
```
> **Note:** You can look at the current version of the [packs.json](https://github.com/riqvip/Project-Lumina/blob/gh-pages/packs/packs.json) file for layout of the categories and packs to know the full structure.

## Guidelines
Contribute effectively by adhering to these guidelines:

- Ensure contributions include necessary and related changes.
- Include appropriate tests, and confirm existing tests pass.
- Treat all contributors with respect, avoiding harassment or discrimination.
- Mind security implications, addressing and reporting vulnerabilities.
- Verify contributions align with the project's chosen license.

## Thank You!
Your contribution makes Project Lumina even better. For questions or assistance, join our [Discord server](https://discord.com/invite/7ppv6m7huM).
