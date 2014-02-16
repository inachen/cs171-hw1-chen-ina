1. d3.selectAll("tbody tr")[0].length-1 calculates the number of rows in the table

2. color(0) would return an orange-red color. color(10) would return a less intense color of orange-red compared to color(0). color(150) will produce a silver color.

3. If the maximum and minimum rate values were passed to domain(), then the domain interval is much smaller. The range of orangered-silver colors will be mapped to be a much smaller interval of colors (color(10) will become silver). This would be appropriate in the situation where we want to visualize the values of the Rate column. 