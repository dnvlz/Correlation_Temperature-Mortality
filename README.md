# Correlation_Temperature-Mortality

Correlation between mean temperature and mortality for the year 2006 in Mexico City

* Region and domain category: Mexico City, Mexico and weather phenomena
* Question: Was there a correlation between mean temperature and number of deaths in Mexico City on 2006?
* Data:
  1. Center for Scientific Research and Higher Education at Ensenada (CICESE)
    http://clicom-mex.cicese.mx/
  2. National Institute of Statistics and Geography (INEGI)
    https://www.inegi.org.mx/programas/mortalidad/#Microdatos
  3. Retouched CSV and DBF files can be found here
    https://drive.google.com/drive/folders/1zKCjSoLF6XIB8DNkU5aHYZayseJXv8dA?usp=sharing
  
The visual addresses my research question by showing a plot of the number of deaths and the mean temperature in Celsius degrees throughout 2006. It also includes the Pearson coefficient (corr) and the p-value.
I performed a Fourier smoothing (keeping the 10% most relevant frequencies) on both datasets to produce a clearer graphic, but kept the unfiltered plots for the sake of showing the original data.

Conclusion: that there was an inverse relationship between temperature and mortality in Mexico City during 2006. The Fourier smoothed curves show this relationship with clarity.
The analysis brings new questions to the table: is this correlation general? i.e., does this happen every year and in every city of the world? Is it a local phenomenon? Did something particularly odd happen during the year 2006 in Mexico City?
