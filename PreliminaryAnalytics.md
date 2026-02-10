> totals |>
+ left_join(high_days, by = "Date")
# A tibble: 2,020 × 3
   Date       Views high_performance
   <date>     <dbl>            <dbl>
 1 2020-07-30   342                1
 2 2020-07-31   415                1
 3 2020-08-01   146               NA
 4 2020-08-02   187               NA
 5 2020-08-03   129               NA
 6 2020-08-04    67               NA
 7 2020-08-05    85               NA
 8 2020-08-06   103               NA
 9 2020-08-07    99               NA
10 2020-08-08   141               NA
# ℹ 2,010 more rows
# ℹ Use `print(n = ...)` to see more rows
> totals |> 
+     inner_join(high_days, by = "Date")
# A tibble: 2 × 3
  Date       Views high_performance
  <date>     <dbl>            <dbl>
1 2020-07-30   342                1
2 2020-07-31   415                1
