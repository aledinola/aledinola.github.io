# Website migration instructions

Owner: Alessandro Di Nola. Repository: aledinola/aledinola.github.io.
Source: https://sites.google.com/site/alessandrodinolaphd/
Destination repository: https://github.com/aledinola/aledinola.github.io/tree/main
Intended website address: https://aledinola.github.io/ — no custom domain.

This project migrates Alessandro Di Nola's academic website from Google Sites to
GitHub Pages. GitHub is the shared home for the project files and these instructions;
local checkouts on each computer are working copies.

## Current authorized scope

Initially focus on collecting and verifying content. Continue copying documents
linked from the existing website into this repository so the new website can serve
them directly. The repository already exists; check completed work before continuing.
Do not create the new website layout yet. Do not enable GitHub Pages,
add a custom domain, replace the original site, or publish a site without a later request.

## Preserve content

- Preserve the existing website's wording, research descriptions, and linked documents
  unless Alessandro explicitly requests changes. Preserve the biography verbatim.
- Preserve document bytes; do not substitute newer, similarly named, or regenerated files.
- Use content/page-content.json and content/*.txt as the captured source content.
- Keep source-to-local mappings and checksums in migration/ up to date.
- Record inaccessible or ambiguous files explicitly. Never claim a missing file was migrated.
- Leave Google Drive and Dropbox originals and their sharing settings unchanged.
- External article/profile/code-repository links remain external references.
- Read migration/INVENTORY.md before continuing. The recovered files have been imported;
  unresolved source links are listed there for a later recovery step.

## Working across sessions and computers

- Before making changes, read the repository README and applicable AGENTS.md instructions.
- Check the Git working tree, recent commits, and migration inventory to establish what
  has already been completed. Preserve existing work and clearly report progress or blockers.
- Pull current changes before starting work when the working tree permits it; do not
  overwrite uncommitted work or force-push to resolve differences between computers.
- Keep these instructions in the repository so every computer receives them when it
  clones or pulls the project. Saving a file locally does not synchronize it to GitHub;
  commit and push authorized completed changes, and report anything still local.
