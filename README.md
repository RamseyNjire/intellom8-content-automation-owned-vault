# Intellom8 Content Automation-Owned Vault

This repository is the automation-owned vault slice for Intellom8 content operations.

It exists so remote automation tools can create draft notes safely without writing directly into the main local Obsidian vault.

## Working Model

- `main` holds the reviewed baseline structure
- `automation/short-form-generated` is the branch targeted by short-form note generation
- automation writes only into the generated area
- human review decides what gets rewritten, moved, or promoted into the main vault

## Primary Paths

- `00 Home/` for lightweight orientation notes
- `02 Ideas/Short Form/Generated/` for automation-created short-form drafts
- `02 Ideas/Short Form/Reviewed/` for notes a human has accepted or refined

## Notes

- Keep automation writes constrained to the generated area
- Treat generated drafts as disposable unless reviewed
- This repo is designed to be opened in Obsidian if needed
