# It ain't cheating when it's a function. 
A cheeky function to give you a headstart during the final exam hehe.
Let's just say that if there will be questions similar to 3.1.9, 3.1.11, and 3.1.12, well... then you're in luck hehe.

The following code must be run to get this function:

```
cheat <- function(exercise_number) {
  if(exercise_number == 9) {
    solution_9 <- 
    ("tooth_growth <- ToothGrowth,
    plot <- ggbetweenstats(
      data = tooth_growth,
      x = 'supp',
      y = 'len',
      title = 'Tooth Growth by Supplement Type',
      xlab = 'Supplement Type',
      ylab = 'Tooth Length'"
    )
    return(cat(solution_9))

  } else if (exercise_number == 11) {
     solution_11 <- 
     "gg_vs_plotly <- cran_downloads(packages=c('ggplot2', 'plotly'), 
                                   from='2014-01-01', to = '2024-02-01')
     gg_vs_plotly_plot <- ggplot(gg_vs_plotly,
                                aes(x = date,
                                    y = count,
                                    color = package)) +
        geom_line() +
        labs(
        title = 'Package popularity over time',
        x = 'Date',
        y = 'Package Downloads',
        color = 'package'
      ) +
      transition_reveal(date)"
     return(cat(solution_11))
  } else if(exercise_number == 12) {
    solution_12 <- 
    "install.packages('quantmod')
    library(quantmod)
    getSymbols('ASML', src = 'yahoo', from = '2023-01-01', to = '2023-12-31')
    chart_Series(ASML$ASML.Close, name = 'ASML Stock 2023')
  # ASML makes machines that make computer chips."
    return(cat(solution_12))
  } else {
    stop("Provide number 9, 11 or 12")
  }
}
```
If you want the answer for question 3.1.9 you simply do:

```
cheat(9)
```
And there you go!

```
tooth_growth <- ToothGrowth,
    plot <- ggbetweenstats(
      data = tooth_growth,
      x = 'supp',
      y = 'len',
      title = 'Tooth Growth by Supplement Type',
      xlab = 'Supplement Type',
      ylab = 'Tooth Length'
```

 

