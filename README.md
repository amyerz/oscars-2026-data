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

## Usage

Fetch the raw JSON directly:

```
https://raw.githubusercontent.com/amyerz/oscars-2026-data/main/oscars-2026.json
```

Or use with the [award-carousel](https://github.com/amyerz/award-plugins) widget:

```html
<div class="award-carousel"
     data-src="https://raw.githubusercontent.com/amyerz/oscars-2026-data/main/oscars-2026.json"
     data-poll="60">
</div>
```

## License

This data is provided for informational purposes. Nominee and category information is sourced from publicly available Academy Awards announcements.
