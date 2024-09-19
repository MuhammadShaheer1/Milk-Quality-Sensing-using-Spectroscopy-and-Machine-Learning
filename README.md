# Milk-Quality-Sensing-using-Spectroscopy-and-Machine-Learning

Most of Pakistan’s economy today is dependent on the agriculture and dairy industry. The 
biggest problem that consumers face regarding the dairy industry is the adulteration of pure 
milk with water and detergents. We propose a solution to measure the quality of milk through
attenuation of light waves as they pass through a milk sample. The degree of attenuation is 
dependent on the amount of fat and protein present in the sample. The higher the fat and 
protein content, the more light is reflected, and we get more attenuation.

## Part-1

In the first part, we identified the top seven adulterants that can be used in our 
country. Then we identified the top six techniques which can be used to measure the 
quality of milk. We cross analysed the adulterants with these techniques to determine 
which techniques are more effective for certain adulterants. In the end, we made a 
comparison analysis which listed the techniques against the adulterants along with 
their figure of merits.

## Part-2

In the second part, we chose a specific technique called spectrophotometric 
techniques to measure milk quality. We chose different samples of milk having 
different protein and fat content and analysed them on Spectrophotometer. In the 
end, we build a PLS Regression model which can predict the fat and protein content in 
milk.

## Part-3

In the third part, we build a small device based on raspberry Pi to predict the fat 
content. This device consists of a light detection sensor which measures the absorption of light passing 
through milk samples. We chose different milk samples available in the market having 
different fat content. We collected the sensor readings for each sample and trained a 
model on this data. This model is also able to predict fat content in a milk sample 
effectively.
