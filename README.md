# 98th Academy Awards (Oscars 2026) Data

Structured JSON data for the 98th Academy Awards ceremony.

- **Date:** March 15, 2026
- **Venue:** Dolby Theatre, Hollywood, Los Angeles
- **Categories:** 24
- **Format:** JSON

## Schema

```json
{
  "show": { "name": "...", "edition": "...", "year": 2026, "date": "YYYY-MM-DD", "venue": "..." },
  "categories": [{
    "id": "kebab-case-id",
    "name": "Display Name",
    "nominees": [{
      "id": "category-id--slug",
      "title": "Film Title",
      "people": ["Person Name"],
      "image": "",
      "winner": false
    }]
  }]
}
```

## License

This data is provided for informational purposes. Nominee and category information is sourced from publicly available Academy Awards announcements.
