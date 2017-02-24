# List of projects

This lists data analytics projects that I've done. Both research projects and side projects are included.

  - [Shiny App - Predicting Avian Flu Outbreak by Weather Indicators]
  - [Shiny App - Next Word Prediction]
  - [The Thriving of Punishers - a Python Model]
  - [Mobile App Design - Identifying Risk Factors associated with Flu Outbreak]
  - [Web scrapping on OKC: what kind of profile image attracts more visitors?]
  

### Shiny App - Predicting Avian Flu Outbreak by Weather Indicators

This application uses real-word weekly temperature and snow depth data to identify the correlation between the week number of the weekly parameters and the time of the avian influenza introudctions. 

Weekly temperature is significantly correlated with the week numbers of the flu outbreaks in all cases (p < 0.05). Veterinarians and farm workers can use this app to predict the timing of the flu outbreaks in the turkey farms, thus receive better guidance on the early detection to prevent the upcoming avian influenza outbreaks. A brief introduction about the background of this topic can be found [here][link1].


##### Usage

* Use the bar to adjust the weekly parameters on the left
* The app will show the corresponding week in red color from all eight locations. For example, if you want to know which week has the weekly temperature of 8 celsius, you can adjust the bar to 8 and see the red bar on the graph.
* The blue bar indicates the week with historial avian flu outbreaks. 
* If you want to see the correlation between the weekly indicators and the time of flu outbreaks, switch to the 'correlation test' tab to check the p-value.
* The raw week numbers can be found in the 'Table' tab.


### Shiny App - Next Word Prediction

This app is the capstone project of coursera data science track. A presentation of the app can be found [here][link2].

##### Usage
Enter two words in the text box and the app will show the prediction of the next word. 

* The app uses Kats back-off model. 
* Probabilities from both 2-gram and 3-gram model will be compared and the word with the highest probability will be returned.


### The thriving of punishers - a python model

This project is the final course project of Intelligent Agent. A model was built to illustrate the evolution of voluntary punishment. A brief introduction can be found [here][link3].


### Mobile App Design - Identifying Risk Factors associated with Flu Outbreak

This project is a collaboration work to design a mobile app used in the turkey farms for collecting key information about flu outbreaks. A brief description can be found [here][link4].

### Web scrapping on OKC: what kind of profile image attracts more visitors?

This project is to look at visitor statistics by using RCurl. The goal is to investigate the impact of profile pictures on visitors. Specifically, to characterize the feature of visitors attracted by different types of profile pictures, I performed the following steps:

1. Created three accounts on OKC with same profile descriptions and different pictures;
2. Use RCurl to capture the data of visitors;
3. Use ggplot to plot the visitor features.


##### Results
Due to the security reseason, my accounts were blocked after a short period of web scrapping. However, this small portion of data revealed [something interesting]:

* The number of visitors are almost proportional to the cleavage scale on the photos(?)
* Age distribution: unknown pretty girl attracts more old guys(?)




   [link1]: <https://rpubs.com/lilsummer1989/228300>
   [Shiny App - Predicting Avian Flu Outbreak by Weather Indicators]: <https://lilsummer.shinyapps.io/weatherIndicators/>
   [Shiny App - Next Word Prediction]: <https://lilsummer.shinyapps.io/NextWordPrediction/>
   [link2]:<https://rpubs.com/lilsummer1989/238392>
   [The Thriving of Punishers - a Python Model]: <https://github.com/lilsummer/modeling_punishment_py>
   [link3]: <https://github.com/lilsummer/modeling_punishment_py>
   [Mobile App Design - Identifying Risk Factors associated with Flu Outbreak]: <http://www.slideshare.net/XiCassieGuo/mobile-survey-appillustration?ref=https://www.linkedin.com/>
   [link4]: <http://www.slideshare.net/XiCassieGuo/mobile-survey-appillustration?ref=https://www.linkedin.com/>
   [Web scrapping on OKC: what kind of profile image attracts more visitors?]: <https://rpubs.com/lilsummer1989/58718>
   [something interesting]: <https://rpubs.com/lilsummer1989/58718>
   
   
 
 
   
  
