# Bangladesh Hijri month starts

Start dates of Hijri (lunar) months in Bangladesh, as announced by the **National Moon Sighting Committee** (Islamic Foundation Bangladesh, Baitul Mukarram).

The committee publishes its decisions only as press releases and news reports, so this file collects them in a machine-readable form. The **Salat** prayer-times app downloads [`bd-months.json`](bd-months.json) to keep its Hijri calendar in line with Bangladesh.

## Format

```json
{ "hijri": "1448-03", "start": "2026-08-15", "note": "…", "source": "https://…" }
```

- `hijri`: Hijri year and month, `YYYY-MM` (01 = Muharram … 12 = Zilhaj)
- `start`: Gregorian date of the 1st of that month in Bangladesh
- `note`, `source`: what was announced, and a link to the report

## Adding a month

After each committee announcement, add one entry with a link to an official or news source, then commit. Only add dates that were actually announced.
