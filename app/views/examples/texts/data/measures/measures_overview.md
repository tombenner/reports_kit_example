A measure is what is being counted (or aggregated in another way). For example, if you want to count `Post`s created over time, then the measure would be `post`:

```yaml
measure: post
dimensions:
- created_at
```

You can use any model as the measure. If you want to use multiple models in one report, see [Series](/subcategories/series).
