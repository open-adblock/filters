# OpenAdBlock Filters

Shared filter data for the OpenAdBlock projects lives here.

- `dns/`: DNS preset URL lists, custom DNS rules, fetched upstream cache, and compiled blob output.
- `chrome/`: Chrome MV3 packaged filter metadata, generated cosmetic fixtures, and curated allowlists.

Project-local filter paths are compatibility links:

- `dns/filters` -> `../filters/dns`
- `chrome/mv3/filters` -> `../../filters/chrome`

Edit filter data in this shared directory so each project consumes the same source of truth.
