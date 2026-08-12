# Christopher Nolan Wiki — Chat

A tiny, self-contained chatbot for querying a small wiki about Christopher Nolan's
filmography. **Live site:** https://chanman22git.github.io/nolan-wiki/

Open `index.html` in any browser — no server, no build step, no API key. Everything
runs client-side; all wiki content is embedded in the page.

## How it works

The wiki was compiled from a handful of publicly-available articles into linked,
atomic pages (films, people, motifs, techniques, and contested interpretations).
The chatbot **retrieves** answers from those pages only — it never answers from a
language model's memory. Every answer shows its wiki-page citations and the
underlying source (tagged `reference` or `criticism`), and notes that all pages are
drafts (unreviewed).

Ask it about a film, a collaborator, a recurring motif, a directing technique, how
two films connect, or the famously ambiguous ending of *Inception* (which the wiki
records as four competing, unresolved readings).

## Note on sources

Content is paraphrased and compiled from public articles for a personal,
non-commercial project; no article text is reproduced verbatim, and no source PDFs
are included in this repository.
