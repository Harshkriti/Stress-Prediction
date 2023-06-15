# Stress-Prediction

In today's fast-paced and demanding world, stress has become a significant health concern affecting individuals of all ages. The adverse impact of chronic stress on physical and mental well-being highlights the need for effective stress management strategies. Leveraging the rich data collected by these wearables, there is a significant opportunity to develop predictive models that can accurately assess and predict an individual's stress levels. By analyzing physiological measurements, activity patterns, and other relevant data points, such models can provide valuable insights into an individual's stress levels. 

Many individuals are often unaware of their own stress levels and the impact it can have on their overall well-being. Stress can manifest in various ways, both physically and mentally, and its effects may go unnoticed until they escalate. This lack of awareness can lead to chronic stress, burnout, and other health issues. We aim to develop and implement a stress analytics solution that uses fitness data from smartwatches to predict stress.

A survey was conducted among my classmates to collect the health data from Apple watch. This health data collected via the survey had over 100 features. Out of those, the most important features that are associated with Stress were selected which are:

1. Blood Oxygen Saturation (%): Percentage of O2-saturated hemoglobin in the blood

2. Heart Rate Variability (ms): Time between beats measured in milliseconds

3. Respiratory Rate (count/min): Number of breaths per minute

4. Sleep Analysis [Deep] (hr): Number of hours of Deep sleep

5. Sleep Analysis [REM] (hr): Number of hours of REM sleep

6. Step Count (count): Number of steps walked in a day

7. Walking Heart Rate Average (count/min): Number of breaths per minute while walking



There are 2 models that were used for predicting stress-

Model 1 - Use a cumulative average of the features over a 90 day period to predict stress at the end of 3 months. 

Model 2 - Use a rolling average of the features over a time period of 30, 60, 90  to predict stress.

