CF Profit = 
var max_sales = MAXX(ALL('Xmas Dataset'[Country]),[Total Profit])
var min_sales = MINX(ALL('Xmas Dataset'[Country]),[Total Profit])
var color = 
SWITCH(
    True(),
    [Total Profit] = max_sales, "green",
    [Total Profit] = min_sales, "red",
    "#404040"
)
RETURN color
