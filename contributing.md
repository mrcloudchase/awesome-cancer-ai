# Contribution Guidelines

Thanks for helping build a better map of AI tools for fighting cancer.

## What belongs here

An entry should meet all of these:

- Open source code, open model weights, or open data. Projects with gated weights or non-commercial licenses are fine as long as the description says so.
- Used in cancer research or care, or a general medical AI tool with a documented cancer application.
- Active within the last two years, or foundational enough that current work still builds on it. Unmaintained or archived projects go in [archive.md](archive.md), not the README.
- Documented well enough that someone can actually use it.

Commercial products without any open component do not belong here.

## How to add an entry

1. Search the README first to avoid duplicates.
2. Add the entry to the end of the most fitting section. Open an issue first if you think a new section is needed.
3. Use this exact format:

   ```markdown
   - [Name](https://link) - One sentence on what it does and its cancer scope.
   ```

   - Separate the link and description with a plain hyphen surrounded by spaces, not an en or em dash.
   - Start the description with a capital letter and end it with a period.
   - Do not repeat the project name in the description.
   - Mention gated weights, non-commercial licenses or proprietary API dependencies in the description.
   - No badges, emoji, or star counts.
4. Link to the project's GitHub repository when it has one, otherwise to its primary site or model card. Do not add trailing slashes.
5. Run `npx awesome-lint` locally and fix anything it reports.
6. Open a pull request with a title like `Add ProjectName` and a sentence on why the project qualifies.

## Updating or removing an entry

Pull requests that fix dead links, correct licenses, or move stale projects to the archive are very welcome. Please say in the PR what changed and link to the evidence.

## Code of conduct

Be kind. Many people reading and contributing to this list are doing so because cancer has touched their lives.
