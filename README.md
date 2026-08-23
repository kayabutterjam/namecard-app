# Namecard Reader — app

The built page for the Namecard Reader, published with GitHub Pages.

**→ https://kayabutterjam.github.io/namecard-app/**

Photograph a business card on your phone; a vision model reads it and the contact
is saved to Postgres, tagged with the event and time you collected it. Open the
link on your phone and use Share → Add to Home Screen.

This repo holds only the compiled single-file page. It is public because
free-tier GitHub Pages requires it. The page embeds a Supabase *anon* key, which
is designed to be public — row-level security is what protects the data, and every
table and storage object here is owner-only.

Source, database schema and deploy docs live in a separate private repo.
