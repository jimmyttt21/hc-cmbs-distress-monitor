# Hamilton Capital | CMBS Distress Monitor

Public CMBS delinquency and distress dashboard compiled from Trepp, CRED iQ, MBA, and Morningstar DBRS.

## View

- Open `index.html` together with `data.json` in the same folder.
- Or enable GitHub Pages on this repo (Settings, Pages, branch `main`, folder `/`) so the live URL is `https://jimmyttt21.github.io/hc-cmbs-distress-monitor/`.

## Update rule

Weekly automation (Monday 8:00 America/New_York) checks vendor publications, appends only verified new prints to `data.json`, and flags any series that moves 25 bp on adjacent prints or 50 bp over three months.

Missing months are omitted. Values are not interpolated or invented.

## Files

- `data.json` source of truth
- `index.html` dashboard
