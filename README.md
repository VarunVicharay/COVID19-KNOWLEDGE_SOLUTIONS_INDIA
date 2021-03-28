# COVID19-KNOWLEDGE_SOLUTIONS_INDIA

**Introduction:**
We will see the detailed representation of COVID19 data for each and every state in India with the help of various graphs and plots and pie charts. We will import imported different libraries such as panda, numpy, matplotlib, seaborn, plotly, for visualization and representation of the data. 
This data science project will help us to get an overall view of the situations of every state and the attention which is required to tackle this pandemic accordingly.
Here we used pandas’ data frame function to information about the total number of cases, deaths and cured (for Indian national and foreign national) in each State/Union Territory recorded at a particular date and time.

**Merging Data Frames:**
We have altered the columns of the table according to our needs. We created a new column of ‘new cases’ and deleted the columns which are not required such as Time, ConfirmedIndianNational, ConfirmedForeignNational. And in the end have grouped all the dates and State/Union Territory into a single State/Union Territory with multiple corresponding dates.

**State-wise Covid19 Status in India:**
The python library ‘matplotlib’,’seaborn’ provides tools for beautiful visualizations, including pie charts. I have created pie charts for plotting the number of active, recovered and deaths in various states and union territories in India.
This information of each state and union territory is also in the form of horizontal bar charts which represents the number of cured and confirmed cases with green and red colour respectively.

**Overall Covid19 Status in India:**
This pie chart shows the overall active ,recovered and died cases in India.

**Visualising the Spreads Geographically:**
For this step, the python library ‘folium’ is used. ‘Folium’ makes it easy to visualize data that’s been manipulated in Python on a map. The latitude and longitude of each state and union territory is added to the information table. Each state and union territory is plotted on the map. The ring around each state and union territory indicates the number of confirmed covid cases where the size of the circle is proportional to the number of cases.

**Let’s check the trend of the virus:**
In this section the ‘plotly’ library is used. To check the trend of the virus I plotted a graph between the date on x-axis and number of confirmed cases of y axis. This graph is represent in different forms for different types of representations, such as cumulative cases, cases on a daily basis, etc

**Forecasting:**
In this section ‘fbprophet’ library is used for the prediction of confirmed, recovered, death cases. The data for all 3 are divided into 2 parts: training data and test data. m.predict() states that given a trained model, it predicts the label of a new set of data i.e. future. To compare the outcome of the test data we create a graph of the actual data and the predicted data.

**Summary:**
1. This report aims to increase the level of awareness of the intellectual and technical issues surrounding the analysis of Covid19 data.
2. Through this report we can clearly see that the dataset of Covid19 was first imported to python and then a series of analysis has been done it.
3. We created, merged and cleaned the dataset and can can draw conclusions through various graphs and pie charts.
4. The pie charts and bar graphs show the data, curret trends and future trends of Covid19.
5. The visualizations show that the cases are increasing continouosly day-by-day and hence necessary measures should be taken to contain it.
