# mobile-data
## About Dataset
### Context
Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.

He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.

Bob wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.
### Attributes

<b>battery_power:</b> Total energy a battery can store in one time measured in mAh.

<b>blue:</b> Whether or not the phone has Bluetooth enabled.

<b>clock_speed:</b> Speed at which a phone's processor executes instructions measured in GHz.

<b>dual_sim:</b> Whether or not the phone supports two SIM cards.

<b>fc:</b> Front camera mega pixels.

<b>four_g:</b> Whether or not the phone supports 4G connectivity.

<b>int_memory:</b> Internal memory of the phone measured in Gigabytes.

<b>m_dep:</b> Depth of mobile screen.

<b>mobile_wt:</b> Weight of mobile phone measured in grams.

<b>n_cores:</b> Number of cores in the phone's processor.

<b>pc:</b> Primary camera mega pixels.

<b>px_height:</b> Pixel resolution height.

<b>px_width:</b> Pixel resolution width.

<b>ram:</b> Random Access Memory of the phone measured in Megabytes.

<b>sc_h:</b> Screen height of the phone measured in inches.

<b>sc_w:</b> Screen width of the phone measured in inches.

<b>talk_time:</b> The longest time that a single battery charge will last when you are continuously talking on the phone measured in hours.

<b>three_g:</b> Whether or not the phone supports 3G connectivity.

<b>touch_screen:</b> Whether or not the phone has a touch screen.

<b>wifi: </b>Whether or not the phone has wifi connectivity.

<b>price_range:</b> Price range of the phone with 1 being the lowest and 3 being the highest.

In this problem you do not have to predict actual price but a price range indicating how high the price is


### Model Comparison for Mobile Price Range Classification
In this study, eight different machine learning algorithms were compared for their performance in classifying the price range of mobile phones. The models used were: CatBoost, AdaBoost, Convolutional Neural Network (CNN), Decision Tree, K-Nearest Neighbors (KNN), Multi-Layer Perceptron (MLP), Random Forest, and Support Vector Machine (SVM). The goal was to find the most accurate model for this task.
### Model Accuracies
The following table shows the accuracy scores of each model:
<table>
  <tr>
    <th>Model</th>
    <th>Accuracy</th>
  </tr>
  <tr>
    <td>CatBoost</td>
    <td>92%</td>
  </tr>
  <tr>
    <td>AdaBoost</td>
    <td>81%</td>
  </tr>
  <tr>
    <td>CNN</td>
    <td>91%</td>
  </tr>
  <tr>
    <td>Decision Tree</td>
    <td>84%</td>
  </tr>
  <tr>
    <td>KNN</td>
    <td>95%</td>
  </tr>
  <tr>
    <td>MLP</td>
    <td>95%</td>
  </tr>
  <tr>
    <td>Random Forest</td>
    <td>90%</td>
  </tr>
  <tr>
    <td>SVM</td>
    <td>97%</td>
  </tr>
</table>

![download (2)](https://user-images.githubusercontent.com/75095471/218519307-0f9cdefc-8d90-45b9-bbaa-14f190036fa3.png)

Model Performance Analysis
Based on the accuracy scores, it can be seen that the KNN model outperforms all other models with a 95% accuracy score. The CatBoost and CNN models also performed well, with an accuracy score of 92% and 91% respectively. On the other hand, the AdaBoost and Decision Tree models had a lower accuracy score, with 81% and 84% respectively.
It's important to note that the accuracy scores for MLP, Random Forest, and SVM models are not specified, so it's difficult to compare their performance to the other models. Additionally, it is important to consider other factors such as model complexity, training time, and interpretability when choosing a model for a specific use case.
Conclusion
In conclusion, the KNN model appears to be the best performing model for classifying the price range of mobile phones, followed by the CatBoost and CNN models. However, it is recommended to consider all aspects of the models and their performance before making a final decision.
