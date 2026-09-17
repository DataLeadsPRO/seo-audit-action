# DataLeads SEO Audit (GitHub Action)

Run a full SEO audit on any URL - on-page and technical checks - and return the report as JSON.

Calls the DataLeads API endpoint `POST /v1/seo/audit` and writes the JSON response to `dataleads-result.json` plus the `result` output.

## Usage

```yaml
steps:
  - uses: DataLeadsPRO/seo-audit-action@v1
    with:
      url: https://example.com
      api_key: ${{ secrets.DATALEADS_API_KEY }}
```

Get a client key at [data.dataleads.pro](https://data.dataleads.pro).

## License

MIT
