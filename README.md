# quarto-reviewer-response

A [Quarto](https://quarto.org/) template for responding to reviewers. Modified from [klb2/review-response-template](https://github.com/klb2/review-response-template).

## Creating a New Article

To create a new article using this format:

```bash
quarto use template haiiliin/quarto-reviewer-response
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add haiiliin/quarto-reviewer-response
```

Then, add the format to your document options:

```yaml
format:
  reviewer-response-pdf: default
```

## Options

- `journal.name`: The name of the journal.
- `journal.manuscript`: The manuscript number.
- `journal.editor`: The name of the editor.
- `color.comment.font`: The font color used for comment block.
- `color.comment.background`: The background color used for comment block.
- `color.comment.frame`: The frame color used for comment block.
- `color.change.background`: The background color used for change block.
- `color.change.frame`: The frame color used for change block.
- `color.concluding.font`: The font color used for concluding block.
- `color.concluding.background`: The background color used for concluding block.
- `color.concluding.frame`: The frame color used for concluding block.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd), see the [PDF output](template.pdf).
