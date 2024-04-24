# newsdesk

News feed storage for Språkbanken Text.

- Feeds are kept in `data/<feed>.yaml`
- A feed is a list of entries with the properties `title`, `body` and `created`:
  ```
  - title:
      swe: Det händer saker
      eng: Things are happening
    body:
      swe: Brödtexten kan innehålla <strong>HTML</strong>.
      eng: Body text may contain <strong>HTML</strong>.
    created: 2023-11-30
  ```
- The `title` and `body` fields may also be plain strings
- Additional fields may be added without restriction

That's it for now! You can access the feed at its GitHub raw url: https://raw.githubusercontent.com/spraakbanken/newsdesk/main/data/korp.yaml
