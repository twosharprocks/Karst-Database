# Reviewing vault updates

Karst-Database contains public copies of cave and regional notes maintained in a personal vault. Changes are prepared on a separate branch and proposed through a pull request. Publishing requires the owner's review and merge; the preparation process never updates the main branch.

## What a prepared update includes

- Eligible notes from the vault's Published folder, formatted with structured information in frontmatter and references last.
- Only approved attachments referenced by those exported notes.
- Eight approved public summaries that exclude sensitive location, route and exploration details. Editing or renaming the full vault originals does not replace these summaries with their full content.
- A change summary and the results of the privacy and link checks in the pull request description.

The original notes, private attachment register, identity mappings and detailed review reports are kept outside this repository. Files in the private attachment folder, files marked with the private filename suffix and content matching protected file identities are excluded. Renaming a protected attachment does not grant permission to publish it.

## Before merging a pull request

Review the changed records and new attachments. Pay particular attention to newly added sites, changed access information and any public summaries flagged because their full source notes have changed. Check that the intended public information is complete without disclosing sensitive details.

If a private attachment is linked, an approval is missing, a protected record cannot be identified, or a note with previously reviewed omissions changes, preparation stops for review. These cases do not silently fall back to exporting the full note. A run with no changes does not create an empty pull request.

The checks enforce recorded publishing decisions and file identities. They do not automatically determine whether new prose contains sensitive information; that remains part of reviewing the pull request.

## Requesting an update

Ask the vault preparation assistant to **prepare Karst update**. It will fetch the current main branch, prepare and verify the public changes, push a review branch and open a pull request. It will return the pull request link or explain what needs review if preparation is blocked.

This process updates Karst-Database. The separate digital-garden website publishing process has its own configuration.
