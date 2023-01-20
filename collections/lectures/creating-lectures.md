---
title: Creating Lectures
description: How to create lectures
---

Creating lectures in CaC is as easy as creating a new Markdown file and typing
stuff right away! All you need to do is create a new Markdown file in the
`collections/lectures` directory with the following contents:

```markdown
---
title: Title of the lecture
description: Description of your lecture
---

Lecture content goes here!
```

The lines between the `---` fences are called frontmatter. Frontmatter is a way to
identify metadata in Markdown files. Metadata can be anything but CaC takes two
possible keys: "title", and "description". The title is required. You can leave
the description out or empty but make sure the title is sufficient to describe the
content of the lecture.

> Without a title the listing of lectures will be empty.
