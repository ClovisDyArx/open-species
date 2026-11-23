# open-species

A mobile app that makes it easy for anyone to record wildlife sightings
(photo + exact GPS + species ID help) and turn them into data that
researchers can actually use.

> Status: early planning. This is a personal, non-commercial learning project.

## Vision

- Take a photo of an animal, get species suggestions (manual or AI-assisted), keep or correct them.
- Capture exact location, time and context automatically (GPS, EXIF).
- Work **offline-first** (forests have no signal) and sync later.
- Export observations to **standard biodiversity formats** (Darwin Core, GBIF-ready, CSV, GeoJSON).
- Later: gamification driven by real data gaps ("this area has no insect records in 3 years").
- Observations are structured for science (count, behaviour, sex/age, uncertainty), not just photos.
- Missions based on under-surveyed areas and taxa.
- Interoperability first: standard exports, optional bridge to national systems.

## Inspiration: Artportalen

The Swedish national species observation system
([Artportalen](https://www.artportalen.se/), run by SLU Artdatabanken) inspired the
concept and the shape of the data. See [docs/artportalen.md](docs/artportalen.md)
for what we learned, including why direct submission is not planned at first.
I am **not affiliated** with SLU or Artdatabanken.

## Docs

- [docs/artportalen.md](docs/artportalen.md): what Artportalen offers, API access and constraints
- [docs/data-model.md](docs/data-model.md): observation data model and export mapping
- [docs/roadmap.md](docs/roadmap.md): architecture choices and build order

## License

See [LICENSE](LICENSE).
