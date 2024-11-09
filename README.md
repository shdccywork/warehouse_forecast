This is a Python project to predict 7 days outbound volume(Unit: number of cartons) of a warehouse with Dart_XGBoost.
This poject also discuss How RMSE and R-square are affected under different feastures( dimensions). 

Certainly! Below is the provided table formatted in Markdown:

```markdown
| No. | df_ML                                                        | Feature Description                                     | XGBoost trained? |   RMSE   |   R²   |
|-----|--------------------------------------------------------------|--------------------------------------------------------|------------------|---------|--------|
| 1   | df_warehouse                                                 | Original warehouse data - missing date                 | No               | #N/A   | #N/A   |
| 2   | df_warehouse_date_range                                      | Full date range & with a lag of 7 days                | Yes              | 938.704 | 0.175  |
| 3   | df_warehouse_date_range_time_feature                         | Year, month, day, day of year, day of week, week of year | Yes              | 521.117 | 0.746  |
| 4   | df_warehsoue_date_range_time_feature_holidays               | Hong Kong Holidays                                     | Yes              | 522.756 | 0.744  |
| 5   | df_warehsoue_date_range_time_feature_holidays_lags         | Lag day from lag 1 to lag 7                            | Yes              | 394.714 | 0.854  |
| 6   | df_warehsoue_date_range_time_feature_holidays_lags_seasonal | Seasonal data                                          | Yes              | 383.298 | 0.862  |
| 7   | df_warehsoue_date_range_time_feature_holidays_lags_seasonal_trend | Trend data                                        | Yes              | 957.506 | 0.141  |
```

### Rendered Table

| No. | df_ML                                                        | Feature Description                                     | XGBoost trained? |   RMSE   |   R²   |
|-----|--------------------------------------------------------------|--------------------------------------------------------|------------------|---------|--------|
| 1   | df_warehouse                                                 | Original warehouse data - missing date                 | No               | #N/A   | #N/A   |
| 2   | df_warehouse_date_range                                      | Full date range & with a lag of 7 days                | Yes              | 938.704 | 0.175  |
| 3   | df_warehouse_date_range_time_feature                         | Year, month, day, day of year, day of week, week of year | Yes              | 521.117 | 0.746  |
| 4   | df_warehsoue_date_range_time_feature_holidays               | Hong Kong Holidays                                     | Yes              | 522.756 | 0.744  |
| 5   | df_warehsoue_date_range_time_feature_holidays_lags         | Lag day from lag 1 to lag 7                            | Yes              | 394.714 | 0.854  |
| 6   | df_warehsoue_date_range_time_feature_holidays_lags_seasonal | Seasonal data                                          | Yes              | 383.298 | 0.862  |
| 7   | df_warehsoue_date_range_time_feature_holidays_lags_seasonal_trend | Trend data                                        | Yes              | 957.506 | 0.141  |

You can copy and paste this Markdown code into any Markdown-compatible editor or viewer to see the formatted table. If you need any further adjustments or additional information, feel free to ask!
