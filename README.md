# PMLR Proceedings Template Repository

This repository serves as a template for preparing the proceedings for PMLR

## Instructions for Proceedings Preparation

### Required Files

To publish your proceedings with PMLR, you need to provide:

1. **A BibTeX file** with details of each paper in the proceedings.
2. **A collection of PDF files** (and optional supplementary files).

### BibTeX File Format

Your BibTeX file must contain:

#### 1. A single `@Proceedings` entry with conference details including:
- `booktitle`: Citation to the volume (e.g., "Proceedings of the Learning for Dynamics and Control Conference")
- `name`: Long name of the conference (e.g., "Learning for Dynamics and Control Conference")
- `shortname`: Conference abbreviation without year (e.g., "L4DC")
- `year`: Conference year (e.g., "2025")
- `editor`: Editors' names in "Lastname, Firstnames" format, separated by "and"
- `volume`: The assigned PMLR number (283)
- `start`: First day of conference in YYYY-MM-DD format
- `end`: Last day of conference in YYYY-MM-DD format
- `address`: Conference location in venue, city, country format
- `conference_url`: URL of the conference website
- `conference_number`: Number in the conference series, if applicable

#### 2. An `@InProceedings` entry for each paper with:
- `title`: Paper title
- `author`: Authors in "Lastname, Firstnames" format, separated by "and"
- `pages`: Page numbers in "startpage–endpage" format
- `abstract`: Paper abstract (can include LaTeX math, HTML tags for emphasis, etc.)

Paper identifiers should follow the format `lastnameYY` where `lastname` is the lowercase last name of the first author and `YY` is the last two digits of the year. For disambiguating papers, use letters (e.g., `reid25a`, `reid25b`).

### Paper and Supplementary Files

- Paper PDFs must have filenames corresponding to their BibTeX entry identifiers (e.g., `reid25a.pdf`)
- Supplementary files must begin with the same ID plus `-supp` suffix (e.g., `reid25a-supp.pdf`)
- For software links, add a `software` field to the BibTeX entry with the URL
- For video links, add a `video` field to the BibTeX entry with the URL

### Permission Forms

Each author must sign a permission form. The forms should be:
- Named according to the paper ID with `Permission` suffix (e.g., `reid25aPermission.pdf`)
- Placed in a separate directory called `vXpermissions` (e.g., `v283permissions`).

## Sectioned Proceedings (Optional)

To organize proceedings in sections, add a `sections` field to the `@Proceedings` entry and a `section` field to each paper entry.

## Submission Process

### Initial Proceedings Submission

Once your proceedings are ready:

1. Fork this template repository
2. Add your prepared files according to the specifications above
3. Create a pull request back to the original repository
4. Complete the checklist in the pull request template

The PMLR editorial team will review your submission and publish the proceedings if everything is in order.

## Additional Resources

- [PMLR Specification](https://proceedings.mlr.press/spec.html) - Detailed specification
- [PMLR FAQ](https://proceedings.mlr.press/faq.html) - Frequently asked questions
- [LaTeX Style Files](http://www.jmlr.org/papers/format/pmlr-v1.sty) - Official style files

For questions or clarifications, please contact the PMLR editors at proceedings@mlr.press.
