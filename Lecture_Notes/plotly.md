libraries to use:
> import plotly.graph_objects as go   # graph_opjects package is the core of plotly  
> import plotly.io as pio
 
 
 
Things to be careful about:
> fig.write_html("boxplot_include_js.html", include_plotlyjs=True) 
  * this includes javascript, thus huge in size
> fig.write_html("boxplot_cdn.html", include_plotlyjs="cdn") 
  * this uses content delivery network, thus small in size
