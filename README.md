# Purpose

This repository hosts my personal blog.

# Run Locally

Start the `hugo` server:

```bash
hugo server --buildDrafts
hugo server -D
```

Navigate to: http://localhost:1313/

# Creating a Post

```
hugo new posts/my-first-post.md
```

# Publishing

```
hugo
```

Static assets are published to `public/`. In your hosting provider,
publish the contents of this directory, and you're good to go!
