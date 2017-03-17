
``` r
library(ggplot2)

ggplot(data.frame(p = 1:6), aes(x = 1, y = p, fill = p)) +
  geom_raster() + 
  scale_fill_gradientn(colours = c("purple", "blue", "darkgreen", 
                                   "yellow", "orange", "red")) +
  theme_void() +
  guides(fill = FALSE)
```

![](lovewins_files/figure-markdown_github/unnamed-chunk-1-1.png)
