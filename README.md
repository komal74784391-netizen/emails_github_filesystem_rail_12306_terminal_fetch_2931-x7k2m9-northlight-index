# Northlight Studio — Works Index

The public index of work made at Northlight Studio.

Each record lives under `works/` as a Markdown file with YAML front matter.
Fields:

- `title` — display title of the work
- `project` — stable project handle; the companion repository is named exactly
  after this handle under the studio account
- `status` — review state: `pending-approval`, `under-review`, `published`, `shelved`
- `track`, `cycle`, `updated` — editorial metadata
- `code_repo` — optional link to the project's companion repository

House rule: a record only carries `code_repo` once the work is on show and the
companion repository has actually been released. The link always uses the full
repository name of the companion repository.
