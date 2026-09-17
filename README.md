# The root of nlcsbiology.com

**repo: `mompel226.github.io`** — the one repository whose name GitHub treats as special.

It holds no site. Its whole job is two files:

| File | What it does |
|---|---|
| `CNAME` | holds `nlcsbiology.com`. This one line is what attaches the domain — **to the whole account, not just this repo**. Every other repo is then served at `nlcsbiology.com/<repo>/` without being touched. |
| `index.html` | sends anyone who types `nlcsbiology.com` on to `/biology-hub/`, carrying a `#door` through, so `nlcsbiology.com/#plants` opens the Plants door. |

## Do not delete the CNAME file

Removing it detaches the domain from **all eleven sites at once**, and they fall back to
`mompel226.github.io/<repo>/`. It is one line of text doing the work of eleven settings screens.

## The addresses it creates

    nlcsbiology.com                  → the Biology Hub, the front door
    nlcsbiology.com/biology-hub/       NLCS edition
    nlcsbiology.com/igcse-biology-hub/ open edition
    nlcsbiology.com/human-body-hub/
    nlcsbiology.com/life-on-earth-hub/
    nlcsbiology.com/plants-hub/
    nlcsbiology.com/classification-lab/
    nlcsbiology.com/plants-lab/
    nlcsbiology.com/digestion-lab/
    nlcsbiology.com/protein-enzyme-sim/
    nlcsbiology.com/B11-starch-calibration-curve-pract/
    nlcsbiology.com/veterinary-society/

The old `mompel226.github.io/<repo>/` addresses redirect here, so anything already sent to a
class still works.

## The DNS behind it

At Gabia: four `A` records on `@` — `185.199.108.153`, `.109.153`, `.110.153`, `.111.153` —
and a `CNAME` on `www` pointing at `mompel226.github.io.` All four A records matter; with one,
the site works intermittently.

---

Made by Dr Daniel Mompel Riera · NLCS Jeju

## Licence

[**AGPL-3.0**](LICENSE). Use it, change it, run it — free, and you never need to ask. If you change it
and let anyone else use it, *including over a network*, you have to publish your source under the same
licence.

**Not covered:** third-party images and media keep their own licences — see the picture credits.

© 2026 Dr Daniel Mompel Riera. I hold the copyright, so I can grant other terms: if you want to use any of
this commercially, ask me at <dmompelriera@nlcsjeju.kr>.
