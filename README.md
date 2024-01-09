# NBA-Predictor
	getNBAdata -> web scraper portion
	parsedata -> abstracting and a little cleaning of data
	predictor -> feature engineering, cleaning, prediction of data
 
## next steps
- not extremely satisfied with accuracy and setting a goal of hitting above 70% accuracy for future games.
- after researching, the upset rate of an NBA game is 32%, meaning simple logistic models are upper bounded to effectively 68%.
- Looking at different research papers(linked below) and more, I noticed that most neural network models allow for accuracy over 70% and complex neural networks to hit high 70s.
- Currently learning the use of neural networks to hopefully improve the accuracy

### research papers
- Ondřej Hubáček, Gustav Šourek, Filip Železný, Exploiting sports-betting market using machine learning, https://doi.org/10.1016/j.ijforecast.2019.01.001. (convolutional neural network)
- Osken C., Onay C. Predicting the winning team in basketball: A novel approach. Heliyon. 2022;8:e12189. doi: 10.1016/j.heliyon.2022.e12189. (Artificial Neural Network, 76%)
- Ozkan I.A. A novel basketball result prediction model using a concurrent neuro-fuzzy system. Appl. Artif. Intell. 2020;34:1038–1054. doi: 10.1080/08839514.2020.1804229 (concurrent neuro-fuzzy system, 79.2%)
- Loeffelholz B., Bednar E., Bauer K.W. Predicting NBA games using neural networks. J. Quant. Anal. Sport. 2009;5:1–17. doi: 10.2202/1559-0410.1156. (fusion neural network of probability, general neural networks and radial basis functions, 74.33%)
