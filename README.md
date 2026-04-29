# OpenAdBlock Filters

Shared filter data for the OpenAdBlock projects lives here.

- `manifest.json`: remote browser filter manifest served through jsDelivr.
- `dns/`: DNS preset URL lists, custom DNS rules, fetched upstream cache, and compiled blob output.
- `browser/`: shared browser client filter metadata, generated cosmetic fixtures, and curated allowlists for Chrome, Android, iOS, and other app variants.

Consumer projects should not commit filter data. Keep this repo checked out
next to the project repos in the multi-project workspace:

- `open-adblock/dns` reads `../filters/dns` for DNS blob builds.
- `open-adblock/chrome` reads `../filters/browser` for browser client validation and can create an ignored local runtime link when loading the MV3 extension unpacked.

Edit filter data in this repo so each project consumes the same source of truth.
