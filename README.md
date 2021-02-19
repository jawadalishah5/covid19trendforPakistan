# covid19trendforPakistan
This code finds similarities between different countries for COVID19, and predicts future trend for Pakistan.


Run the file on Google colab or Jupyter-notebook

My model takes the past data of each country and predicts it future on that basis. Since in the pastdata the number of cases in the initial days were much low. And the number of cases sometimes drops and
sometimes get higher in day to day purpose. But when number of cases gets much higher (in validation
set) the actual curve keeps on increasing (Russia) and the countries where they control , it keeps on
decreasing (Israel and Belgium). But my prediction works on the fact that it sometimes decreases and
sometime increases. So it’s not that much better technique to predict but for the countries like (Romania
and Canada), It fits better. And on the basis of that model we can predict the future values of Pakistan.
