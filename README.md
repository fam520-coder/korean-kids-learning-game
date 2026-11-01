# Korean Kids Learning Game

Public Korean learning games by Myeong So for ages 5–11, with two challenge levels and eight game modes.

## Complete standalone build

`index.html` is the complete self-contained application. Both background artwork and company logo are embedded as data URLs. No assets folder, external script, installation, or build step is required. `_headers` adds HTTP response headers on Cloudflare.

Upload these three files directly to Cloudflare static hosting, or serve this repository root from any static web server.

## Saved progress

The game uses the owner's existing Supabase project with a browser-safe publishable key. Its progress table and row-level security rules have already been installed and tested. This upload requires no database migration or schema file.

The game asks for no names, emails, passwords or birth dates. It stores scores and quiz progress under an anonymous learner ID. Each learner can access only their own records. A shared browser shares an identity. Clearing browser data or changing browsers loses access to that identity.

## Audio and artwork

The listen button uses a Korean browser voice when available. Artwork is AI-generated. The Myeong So logo belongs to the owner. This game does not yet include narrated or sung lesson videos. Publishing this repository grants no license to reuse the logo.
