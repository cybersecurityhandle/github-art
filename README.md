# github-art

Contribution graph art. `generate.sh` creates backdated empty commits, laid out week by week, so the contribution graph spells **HACKER**.

Each letter is a 7×5 bitmap, with one row per weekday. Every "on" pixel gets five commits, which makes it a darker green.

```sh
git init && ./generate.sh && git push
```

The art spans June 2025 to February 2026. Switch the graph to the 2025 year to see the whole word.
