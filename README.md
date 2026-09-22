# Saintfield Hurling Camp

Public information and interest page for a free hurling and camogie camp for
boys and girls aged 9-12, Monday evenings 6-7pm through October and November,
at the Saintfield 3G arena, Co. Down.

Run by the Social Slashers with Saul GAC and Carryduff Hurling. Supported by
Down GAA, Ulster GAA, and a grant from the Noah Donohoe Foundation.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The public camp page |
| `coaches.html` | Coach availability form (not linked from search engines) |
| `style.css` | Shared styles for both pages |
| `*.jpg` | Photographs from Saul GAC sessions |

## Adding your Google Form links

Both pages have a `CONFIG` block at the top of their `<script>`. Paste the
Google Form share link between the quotes and commit the change:

```js
var CONFIG = {
  parentFormUrl: "https://forms.gle/your-link-here",
  ...
};
```

While those are left empty the pages use a built-in form that opens a
pre-filled email instead, so they work either way.

Currently wired to:

- Register interest: <https://forms.gle/4MpDeyzXFMpf7mfs6>
- Coach availability: <https://forms.gle/Nbn2UG8MYKjbVfKa6>
