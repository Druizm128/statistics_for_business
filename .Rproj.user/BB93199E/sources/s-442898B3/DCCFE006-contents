library(tidyverse)

fun_draw_histogram <- function( tbl, col_name ){
  tbl %>% 
    ggplot( aes(x = {{col_name}}) ) + 
    geom_histogram()  
}