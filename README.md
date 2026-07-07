# Ayush Kumar Gupta Portfolio

This is a static portfolio site. Open `index.html` directly in a browser, or use the VS Code Live Server extension for a cleaner preview.

## Files

- `index.html` - portfolio content, project cards, YouTube demo cards, credentials, and contact links
- `styles.css` - visual design and responsive layout
- `projects/` - detailed project pages linked from the selected work cards
- `videos.html` - full video library
- `certificates.html` - full certificates and proof-points page
- `assets/ayush-profile.jpeg` - profile image
- `assets/Ayush_Kumar_Gupta_Resume.pdf` - downloadable resume
- `assets/certificates/` - certificate images used on the site
- `assets/documents/` - downloadable certificate PDFs
- `assets/linkedin/` - archived LinkedIn screenshots used as source material

## Add Videos Later

For the full video library, edit `videos.html`. Duplicate one `<article class="video-card">...</article>` block, then replace:

- the YouTube embed ID in `src`
- the `title`
- the small category label
- the visible project name

For YouTube Shorts, use the same format: `https://www.youtube-nocookie.com/embed/VIDEO_ID`.

If a video should appear on the homepage preview too, also add it to the smaller `video-grid` inside `index.html`.

## Add Certificates Later

Copy the image into `assets/certificates/`, then duplicate one `<figure>...</figure>` block in `certificates.html`. If it should appear on the homepage preview too, also add it to the `certificate-grid` inside `index.html`.

## Add Project Pages Later

Duplicate any file inside `projects/`, rename it, update the title/content, and link to it from the selected work card in `index.html`.

## Recommended VS Code Extensions

- Live Server, for one-click preview
- Prettier, for formatting
- HTML CSS Support, for easier editing
