FastFood
================

# Brands by item count:

![](FastFood_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

# Highest calorie item per brand:

![](FastFood_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->

# Lowest calorie item per brand:

![](FastFood_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->

# Items highest in cholesterol:

![](FastFood_files/figure-gfm/unnamed-chunk-5-1.png)<!-- -->

# Items highest in sodium:

![](FastFood_files/figure-gfm/unnamed-chunk-6-1.png)<!-- -->

# Average calories per item per brand:

![](FastFood_files/figure-gfm/unnamed-chunk-7-1.png)<!-- -->

# Let’s introduce a couple of ratios: protein-to-calories and fiber-to-total-carbs

``` r
fastfood <- fastfood %>% 
  mutate(
    protein_to_calorie = protein/calories,
    fiber_to_carb = fiber/total_carb
  )
```

Foods that offer the most protein per calorie:

![](FastFood_files/figure-gfm/unnamed-chunk-9-1.png)<!-- -->

Foods with the highest fiber-to-carbohydrate ratio:

![](FastFood_files/figure-gfm/unnamed-chunk-10-1.png)<!-- -->

# A closer look into the brands available (or soon-to-be-available) in Lithuania:

That would be McDonald’s, Subway and Burger King.

# Looking at the McDonald’s highest protein-to-calorie item:

![](FastFood_files/figure-gfm/unnamed-chunk-12-1.png)<!-- -->
