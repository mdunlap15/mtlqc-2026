# MTL + Québec trip app — Jul 19–24, 2026

Live: https://mdunlap15.github.io/mtlqc-2026/

## Activating the two dynamic tiers
**Shared Trip tab (Supabase):** create a project → SQL editor → run `supabase/schema.sql` → put Project URL + anon key into `config.js`.

**Concierge chat (Railway):** deploy the `mtlqc-concierge` repo → set `ANTHROPIC_API_KEY` → generate a domain → put the URL into `config.js` (`TRIP_KEY` must match if you changed it).

Everything else is static and already live. Bump `CACHE` in `sw.js` when changing icons/assets.
