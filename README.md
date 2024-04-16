# newsdesk

News feed storage for Språkbanken Text.

- Feeds are kept in `data/<feed>.yaml`
- A feed is a list of entries with the properties `title`, `body` and `created`:
  ```
  - title:
      sv: Det händer saker
      en: Things are happening
    body:
      sv: Brödtexten kan innehålla <strong>HTML</strong>.
      en: Body text may contain <strong>HTML</strong>.
    created: 2023-11-30
  ```
- That's it for now! You can access the feed at its GitHub raw url: https://raw.githubusercontent.com/spraakbanken/newsdesk/main/data/korp.yaml
