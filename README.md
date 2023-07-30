# Cosmetic Produts Comparison

Nowadays we have a lot of different types of products and brands avaiable on the market and their number is constantly growing, especially in the beauty industry. 
When buying cosmetic products we want to make the best choice comparing their ingredients, reviews and then looking for the best price, but it is hard to do in this volume of data.

This project respond to those needs by showing similarity of hair care products on HEBE website in easy way using data science. 

In order to obtain the results, web scrapping was used to download the data which includes chemical components of cosmetics, their prices and ratings. Preprocessing the ingredient lists was done via word embedding, then visualize ingredient similarity was applied by using the Dimensionality-Reduction technique called t-SNE and finally the interactive visualization was created using Bokeh library.

In addition, this project helps us to find a substitution for our favourite product at a better price!

### Libraries which were used:
- Pandas
- Numpy
- Beautiful Soup
- Matplotlib
- Seaborn
- Sklearn
- Bokeh
