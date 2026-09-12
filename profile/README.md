# OpenDiving

**A dive log built to outlive every vendor.** An open-source logbook for scuba divers,
recreational and technical: log dives with multi-tank gas mixtures, import them straight
from your dive computer's export files — full depth, temperature and tank-pressure
profile, deco ceiling and dive events included — group them into trips, and keep gear
service history and c-cards in one place. Cloud dive logs come and go, and years of dive
history go with them; here every file you upload stays downloadable, and one click takes
everything back out in open formats. Self-hosting is what turns that from a promise into
a guarantee.

![OpenDiving's dashboard](https://raw.githubusercontent.com/opendiving/opendiving/main/docs/screenshots/dashboard.png)

- **Hosted instance** — <https://opendiving.app>, a closed beta with a waitlist. The same
  code at the same release as an install you run yourself; the difference is only who
  operates it.
- **Install it yourself** — [opendiving/opendiving](https://github.com/opendiving/opendiving):
  one command, a domain and a mail relay.
- **Backend** — [opendiving/opendiving-api](https://github.com/opendiving/opendiving-api),
  FastAPI and PostgreSQL.
- **Frontend** — [opendiving/opendiving-web](https://github.com/opendiving/opendiving-web),
  Next.js and TypeScript.
- **Interchange format** — DiveJSON, the open format a whole logbook moves in:
  <https://divejson.org>.

**Status: `v0.1.0`, the first release.** AGPL-3.0. Issues and discussions live on the
repository each belongs to; the front door is the place to start.
