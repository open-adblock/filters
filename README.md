# OpenAdBlock Filters

Shared filter data for the OpenAdBlock projects lives here.

- `dns/`: DNS preset URL lists, custom DNS rules, fetched upstream cache, and compiled blob output.
- `browser/`: shared browser client filter metadata, generated cosmetic fixtures, and curated allowlists for Chrome, Android, iOS, and other app variants.

Project-local filter paths are compatibility links:

- `dns/filters` -> `../filters/dns`
- `chrome/mv3/filters` -> `../../filters/browser`

Edit filter data in this shared directory so each project consumes the same source of truth.
