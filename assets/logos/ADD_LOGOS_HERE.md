# Add your logo files here

The site expects these exact filenames in this folder (`assets/logos/`). Drop each logo in, matching the name below, and it'll appear automatically — no HTML editing needed.

| Tool | Expected filename |
|---|---|
| AWS S3 | `aws-s3.png` |
| AWS Lambda | `aws-lambda.png` |
| Salesforce | `salesforce.png` |
| Apex | `apex.png` |
| Lightning Web Components | `lightning.png` |
| REST APIs | `rest-api.png` |
| Dataloader | `dataloader.png` |
| JIRA | `jira.png` |

## Notes

- **Format:** PNG or SVG both work. If you use SVG, rename the `<img>` `src` in `index.html` to match (e.g. `aws-s3.svg`) — swap the extension in each `<img src="...">` line under the "tool-grid" section.
- **Size:** Logos are displayed at 22×22px, so square icons (any resolution, ideally 128×128px or larger, transparent background) look best.
- **If a file is missing:** the site won't break — it automatically falls back to a small text badge (e.g. "S3", "λ") so the layout stays intact until you add the real logo.
- **Where to get official logos legitimately:**
  - AWS (S3 and Lambda): [AWS Architecture Icons](https://aws.amazon.com/architecture/icons/) — official AWS brand/architecture asset packs.
  - Salesforce (Salesforce, Apex, Lightning): [Salesforce Brand Experience](https://brand.salesforce.com/) — official brand guidelines and downloadable assets.
  - JIRA: [Atlassian Design / Brand Assets](https://www.atlassian.com/company/news/press-kit) — official Atlassian press/brand kit.
  - REST API and Dataloader don't have a single official "brand logo" — a generic icon (e.g. from a source you have rights to use, like an icon set you've licensed) works fine here.
- Each brand has its own usage guidelines (color, minimum size, clear space, no modification) — worth a quick check before publishing publicly, since these are trademarked marks.

Once your files are in this folder, keep the same relative structure when you upload to GitHub:

```
your-repo/
├── index.html
├── README.md
└── assets/
    └── logos/
        ├── aws-s3.png
        ├── aws-lambda.png
        ├── salesforce.png
        ├── apex.png
        ├── lightning.png
        ├── rest-api.png
        ├── dataloader.png
        └── jira.png
```
