# Publishing vault updates

Karst-Database contains public copies of cave and regional notes maintained in a personal vault. The owner's local publisher checks for updates every 15 minutes, alongside the digital-garden website, and publishes verified changes directly to the main branch. Pull requests remain available when a separate review is wanted.

## What an update includes

- Eligible cave and regional notes from `1 - Published`, with structured information in frontmatter and references last.
- Only attachments approved for their exact contents and referenced by exported notes.
- Eight approved public summaries that omit sensitive location, route and exploration details. Editing the full vault originals never automatically replaces these summaries.

Full source notes, private rules, attachment identities and detailed reports stay outside this repository. Private folders, the private filename suffix and protected content identities prevent export; renaming a protected file does not grant publication permission. Byaduk Caves remains withheld pending a separate image-permission decision.

## When publication stops

A private reference, unapproved attachment, invalid link, changed note with previously reviewed omissions, missing protected identity, unexpected repository edit, or source change during preparation stops the Karst run. These cases require review and never fall back to publishing the full source. Unchanged runs create no commit.

The website retains its own privacy checks and the same reduced versions. Previously approved copies remain in use where a reviewed source needs a new decision. Both publishers start alongside each other; verified new attachment destinations are handed over after both finish and used by the next website cycle. The repositories may finish at different times; this is not an atomic deployment.

Checks enforce existing publication decisions and file identities. They do not assess the sensitivity of newly written prose, so sensitive material should stay in Unpublished or a private companion note. New attachments require explicit approval before export.

## Manual updates and review

Ask the vault preparation assistant to **prepare Karst update** for a review branch and pull request, or **publish Karst update** for the same checked automatic path. Scheduled runs use direct publication as authorized by the owner. Detailed local reports explain any held record or attachment.

The scheduled publisher runs on the owner's Windows computer while it is available and has access to the vault and GitHub. It reads the vault without editing the originals.
