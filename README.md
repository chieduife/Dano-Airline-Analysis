# Dano Airline Satisfaction Rate Analysis

## Table of Content
- [Project Overview](Project.Overview)
- [Data Source](Data.Source)
- [Tools](Tools)
- [Project Structure](Project.Structure)
- [Data Cleaning](Data.Cleaning)
- [Explanatory Data Analysis(EDA)](Explanatory.Data.Analysis (EDA))
- [Data Insight](Data.Insight)
- [Results/Findings](Reslts/Findings)
- [Recommendation](Recommendation)
- [Limitations](limitations)
- [Refrence](Reference)



## Project Overview
---
Dano Airlines, a British airline headquartered in London, United Kingdom, has recently received its latest passenger survey results, which indicate a significant drop in customer satisfaction, with the rate falling below 50% for the first time. The data comprises feedback from over 120,000 airline passengers, including additional details about their flights, travel types, and assessments of various factors such as cleanliness, comfort, service, and overall experience. The objective of this project is to propose a data-driven strategy aimed at enhancing Dano Airlines satisfaction rate.


## Data Soure
---
This dataset was provided at the conclusion of the training program conducted by Digitaley Drive as the final project. Below is the link to the data set

[Download Data set](https://docs.google.com/spreadsheets/d/15Kp-2yfQFNRGJPNOkpMwG-OMX8xVZOJ5VL7f35v7sQ/edit#gid=1647986900)

## Tools
- Power query - Cleaning and Modeling
- Power Bi - Visualization
- Github - Documentation


## Project Structure
 This project was executed following the subsequent process.

- Data Collection

This initial phase of the project delves into acquiring the Dano Airline dataset. The dataset was provided by the academy following the successful completion of our training. 

- Data Cleaning

 The Data Cleaning phase is an integral step in any data analysis project. In this section, i meticulously outline the procedures and techniques employed to ensure that the dataset is accurate, reliable, and ready for analysis within Power BI. This process encompasses data validation, removal of duplicates, handling missing values, and addressing any anomalies or inconsistencies present in the raw data. The goal is to create a clean and structured dataset that forms the basis for our insights and visualizations and this was done using power query.

- Data Visualization

 Data Visualization, a critical aspect of data analysis. This phase involves the development of an interactive and insightful dashboard within Power BI. Through this dashboard and accompanying reports, I present a comprehensive view of Dano Airline's satisfaction levels. My visualization offer a deeper understanding of the key performance metrics and the specific factors contributing to the decline in satisfaction rates. Utilizing charts, graphs, and tables, I bring the data to life, enabling stakeholders to quickly grasp the insights derived from the dataset.
 
- Data Documentation

Upon the completion of the analysis, I understand the importance of clearly communicating the findings and recommendations. To this end, I have created a detailed documentation repository on GitHub. This documentation is a valuable resource that explains the insights I derived from the dataset. It also provides a comprehensive overview of the recommendations made as an analyst to assist Dano Airline in their pursuit of enhancing customer satisfaction. The GitHub documentation serves as a reference point for both project stakeholders and the broader community interested in understanding the data-driven strategies I have proposed.


## Data Cleaning 
I imported the dataset into Power Query for data cleansing and transformation. During this process, I noticed that the 'arrival delay' column had a 1% rate of missing values. To address this, I filled in these missing values with a '0'. Additionally, I performed a thorough data validation and quality check on all rows and columns in the dataset to maintain its accuracy and integrity. After ensuring the dataset met the necessary quality standards, I closed the data transformation process and loaded it into Power BI for further analysis.


## Explanatory Data Analysis [EDA]
Gaining a profound understanding of the dataset, I uncovered a significant drop in the satisfaction rate, precisely reaching the 50% mark. The initial satisfaction rate, which stood at 259.76k, dropped to 129.88k. This decline raised considerable concerns among Dano Airline's stakeholders.

In terms of customer breakdown, we had 56.43k satisfied customers, whereas the number of customers expressing neutrality or dissatisfaction totaled 73.45k. This indicated a substantial proportion of our customers were dissatisfied.

Further examination revealed that we had 23.78k first-time customers, contrasting with 106.10k returning customers. This analysis underscored a low rate of first-time customers, with the majority of our customer base comprising loyal returnees.

I also conducted an analysis of satisfaction rates based on customer type. It emerged that 81.69% of satisfied customers were returning customers, while only 18.31% were first-time customers. This observation highlighted that first-time customers exhibited below-average satisfaction levels, calling for attention and action.

The Exploratory Data Analysis (EDA) is outlined as follows:

- Count of Satisfaction 
- Satisfaction based on travel type 
- Satisfaction based on Customer type
- Indicators demonstrating a high level of satisfaction
- Indicators demonstrating a high level of Dissatisfaction

## Data Analysis 

- Count of satisfaction

  
Regarding the distribution of customers, we found that there were 56.43k customers who were satisfied with our services. However, the number of customers who either felt neutral or expressed dissatisfaction amounted to 73.45k. This observation carries significant implications as it suggests that a considerable portion of our customer base was not content with their experience. In essence, there was a notable disparity between satisfied and dissatisfied customers, highlighting the need for improvements and interventions to enhance overall satisfaction and address the concerns of those who were not content with our services.

- Satisfaction based on Travel Type
  
Upon conducting a comprehensive analysis, it became evident that a predominant proportion of our customer base primarily undertook their journeys for business purposes. Specifically, 69.06% of our clientele were engaged in business-related travel, while the remaining 30.94% embarked on their journeys for personal reasons. This finding sheds light on the fact that a considerable number of our dissatisfied customers are those who often find themselves on business-related trips. It's worth noting that these individuals might have specific expectations and needs associated with their professional travel, which can serve as valuable insights to enhance our services and better cater to their requirements.


- Satisfaction based on customer type

  
An examination was conducted to assess satisfaction rates based on the type of customer. The data showed that a striking 81.69% of satisfied customers belonged to the category of returning customers, while a significantly smaller percentage, only 18.31%, fell into the category of first-time customers.
This observation carries important implications for our business. Specifically, it underscores the fact that first-time customers, on average, exhibited lower levels of satisfaction in comparison to their returning counterparts. These findings warrant our immediate attention and action as they indicate an opportunity to enhance the experience of first-time customers, potentially by better orienting them to our services and facilities. By addressing their unique needs and expectations, we can work towards improving their satisfaction levels and fostering their loyalty in the long term. This, in turn, can lead to increased customer retention and a stronger bottom line for our business.

### Indicators demonstrating a high level of satisfaction

 These are measures that the Customers at Dano Airline has demonstrated a good satisfaction rate
  
- Satisfaction by In-flight-service

  
 The flight service has received commendable feedback and boasts a high rating, signifying its quality and customer satisfaction. Passengers on this flight can expect a positive and enjoyable experience in the air.
Upon boarding, passengers can enjoy a range of activities and amenities to make their journey pleasant and engaging. Some of the in-flight activities and services that may be available include:
In-Flight Entertainment: Modern flights often feature a variety of entertainment options, including movies, TV shows, music, and games. Passengers can select from a diverse range of options to keep themselves entertained during the flight.  Dining Services: High-quality meals and snacks are often provided on longer flights. Passengers can savor delicious meals and beverages, including special dietary options.  Cabin Crew Services: The cabin crew is there to attend to passengers' needs, ensuring a comfortable and safe journey. Passengers can request assistance or information from the friendly and professional crew members.

The flight provides a high-quality in-flight service, offering a variety of activities and amenities to make your journey enjoyable and engaging. Whether you prefer to relax with a movie, stay connected, indulge in delicious cuisine, or explore reading materials, the flight experience is designed to cater to diverse passenger preferences and enhance your overall travel experience.


- Satisfaction by Seat Comfort

  
The seat comfort on this flight is exceptional and has consistently received high ratings from passengers. This level of comfort plays a crucial role in enhancing the overall flight experience, and it's not surprising that customers highly value a comfortable seat for several compelling reasons such as reduced stress, restful journey and also it helps the physical well- being of the customer, the high rating for seat comfort reflects the importance of this factor in passengers' travel experience. A comfortable seat not only contributes to passengers' physical well-being but also enhances their ability to rest, stay productive, and enjoy the journey. It plays a pivotal role in customer satisfaction, loyalty, and positive word-of-mouth, making it a key consideration for both airlines and passengers.          


- Satisfaction by On-board Service

  
 The on-board service provided by this airline is exceptional, consistently earning high ratings from passengers, the high rating for the on-board service reflects the integral role it plays in passengers' overall travel satisfaction. A quality on-board service contributes to comfort, convenience, and a positive experience, making passengers feel well taken care of and valued. This, in turn, fosters customer loyalty and positive recommendations, making it a vital component of an airline's success.

- Satisfaction by Online Boarding

  
 The online boarding process for this airline is highly regarded, consistently receiving top ratings from passengers. the high rating for online boarding reflects the fundamental role it plays in enhancing the overall travel experience for passengers. The convenience, time efficiency, reduced stress, and flexibility associated with this process make it a valuable service appreciated by travelers. A seamless online boarding experience not only contributes to customer satisfaction but also fosters loyalty and positive recommendations, making it an essential element of an airline's success.

### Indicators demonstrating a high level of Dissatisfaction

These are measures that the Customers at Dano Airline has demonstrated a good satisfaction rate

- Arrival Delay by Satisfaction
  
The issue of arrival delays is a concerning aspect for this airline, as it has been consistently rated poorly by passengers. This low rating indicates the significance of the problem and its impact on customer satisfaction. The reasons behind customers' disdain for arrival delays are multifaceted and have significant implications for both travelers and the airline, particularly considering the majority of our customers are business-oriented individuals.

Disruption of Plans: Arrival delays disrupt passengers' travel plans, causing inconvenience and stress. For business travelers, time is of the essence, and delays can lead to missed meetings, appointments, and opportunities.

Wasted Time: Passengers must spend additional time at the airport or in the aircraft due to delays. This wasted time can be frustrating, especially for those with busy schedules.

Missed Connections: Delays can result in missed connections, affecting passengers' itineraries and leading to further inconvenience and rescheduling efforts.

Loss of Productivity: Business travelers often have work to complete during their flights. Arrival delays reduce the time available for productive work, impacting their business operations.

Customer Frustration: Passengers become increasingly frustrated when delays occur frequently. This frustration can negatively affect their perception of the airline and discourage future bookings.

Due to the fact that majority of our customers are business men this could affect their bsuiness in several ways:

Financial Loss: Arrival delays can lead to financial losses for businesses. Missed meetings or delayed cargo shipments can result in revenue loss and added expenses.

Operational Inefficiencies: For business travelers, delayed arrivals can disrupt tight schedules, leading to operational inefficiencies and potential financial repercussions.

Business Reputation: Frequent delays can harm a business's reputation. If business travelers repeatedly experience inconveniences with an airline, they are less likely to recommend it to others.

Customer Retention: Businesses rely on the loyalty of their customers. For airlines catering to business travelers, frequent delays can lead to reduced customer retention and a loss of valuable clients.

Considering the majority of our customers are business-oriented individuals, it is crucial to address the issue of arrival delays promptly and effectively. These delays not only disrupt the travel plans of business travelers but also have broader implications for their businesses and the airline itself. By improving punctuality and reducing delays, the airline can enhance the overall satisfaction of its customer base, especially those who rely on efficient travel to conduct their business activities.

- Depature Delay by Satisfaction

  
The presence of departure delays is a concerning issue for this airline, as it has consistently received low ratings from passengers in this regard. These low ratings underscore the significance of the problem and its adverse impact on customer satisfaction. Given that a substantial portion of our customer base consists of business-oriented individuals, it is imperative to address the issue of departure delays effectively and promptly. These delays not only inconvenience business travelers but also have broader implications for their businesses and the airline itself.

- Satisfaction by In-Flight Wifi Service

The in-flight Wi-Fi service provided by this airline has been consistently rated poorly by passengers, indicating a significant issue that affects customer satisfaction. The reasons behind customers' dissatisfaction with the in-flight Wi-Fi service are diverse and have significant implications, especially considering that the majority of our customers are business-oriented individuals.


Unreliable Connectivity: In-flight Wi-Fi often suffers from unreliable or slow connections, making it challenging for passengers, especially business travelers, to access crucial emails, documents, or conduct online tasks efficiently.

Lack of Speed: Slow internet speeds can hinder productivity. Business travelers, in particular, require fast connections for video conferencing, file transfers, and other work-related activities.


Limited Coverage: The availability of in-flight Wi-Fi can be limited on certain routes or aircraft, leading to passenger frustration when expecting connectivity that isn't available.

Technical Issues: Frequent technical problems and disconnections can lead to an unsatisfactory experience. Passengers may also struggle with setup and configuration difficulties.

Productivity Loss: Inefficient in-flight Wi-Fi disrupts business travelers' ability to stay productive during flights. This impacts work-related tasks, communications, and meeting preparations.

Missed Opportunities: A poor in-flight Wi-Fi service can result in missed business opportunities. Business travelers may not be able to close deals, address urgent matters, or respond to important emails while in the air.

Financial Impact: Business travelers may be less inclined to choose the airline for future trips if they perceive that in-flight Wi-Fi is inadequate. This can lead to financial repercussions and reduced loyalty.


Given that a significant portion of our customer base consists of business-oriented individuals, it is essential to address the issue of poor in-flight Wi-Fi effectively. Offering a reliable, high-speed, and cost-effective in-flight Wi-Fi service is vital to enhancing overall customer satisfaction and ensuring the continued loyalty of those who depend on efficient connectivity during their business travels.




- Satisfaction by Online booking

  
The low rating for the ease of online booking is a concerning issue for our airline, as it reflects ongoing challenges in this area. This poor rating indicates the significance of the problem and its impact on customer satisfaction. The reasons behind customers' dissatisfaction with the ease of online booking are diverse;

Inconvenience: A cumbersome online booking process can be frustrating and inconvenient for customers. It may involve excessive steps, technical issues, or unclear instructions, leading to an unpleasant experience.

Time-Consuming: Customers, especially business travelers, value efficiency. An intricate online booking process that takes too long to complete can be a major source of frustration and time wastage.

Loss of Productivity: For business-oriented passengers, any delay or hassle in the booking process can disrupt their work schedules, resulting in lost productivity.

Missed Opportunities: If the online booking process is complicated, some customers may abandon their bookings or turn to competitors with simpler booking systems, causing potential revenue loss for the airline.


### Findings

1. High Satisfaction with In-Flight Services: Passengers have expressed high levels of satisfaction with in-flight services, including seat comfort, on-board service, and online boarding.

2. Low Satisfaction with Punctuality: On the flip side, passengers have shown dissatisfaction with punctuality, both in terms of departure and arrival delays.

3. Importance of Punctuality for Business Travelers: The majority of the airline's customer base comprises business-oriented individuals. Punctuality is crucial for these passengers, as delays can disrupt their schedules, lead to missed business opportunities, and result in financial losses.

4. Online Booking Process Needs Improvement: The ease of online booking has been rated poorly by customers. The online booking process should be made more user-friendly and efficient to cater to the needs of travelers, especially business-oriented individuals.

5. Customer Satisfaction's Impact on Business: Customer satisfaction plays a pivotal role in an airline's success. Satisfied customers are more likely to become loyal, recommend the airline to others, and positively impact its reputation.

6. Financial Implications: Poor ratings for punctuality and online booking can lead to financial repercussions. Delays can result in lost opportunities and revenue, while a complicated booking process can drive customers to competitors.

7. Operational Efficiency: Delays, whether in departure or arrival, can disrupt the operational efficiency of both the airline and business travelers, leading to scheduling and productivity challenges.

8. Reputation Management: Maintaining a positive reputation is essential, as negative word-of-mouth can dissuade potential customers from choosing the airline. A focus on improving areas of concern is vital for reputation management.

The findings suggest that while in-flight services receive positive feedback, addressing issues related to punctuality and online booking, particularly for business travelers, is crucial for improving overall customer satisfaction and ensuring the long-term success of the airline, and the major reason for a significant decline in satisfaction rate is due to delays in arrivval and departure , given that majority of our customers are Business inclined people.


### Recommendation

To increase the satisfaction rate and address the issues of arrival and departure delays, improve the ease of online boarding, and enhance in-flight Wi-Fi service, consider the following recommendations:

1. Invest in Punctuality:

- Implement rigorous scheduling and operational procedures to minimize delays.

- Utilize advanced technology for real-time tracking and management of flights.

- Ensure efficient turnaround times between flights to reduce departure delays.

- Communicate promptly with passengers in case of delays, providing clear information and updates.


2. Streamline Online Booking:

- Redesign the online booking process to make it more intuitive and user-friendly.
  
- Optimize the website and mobile apps for easy navigation and quick booking.
  
- Offer clear, step-by-step instructions for the booking process.
  
- Provide a responsive customer support system to assist with any issues.
  
3. Enhance In-Flight Wi-Fi Service:

- Upgrade the in-flight Wi-Fi infrastructure to offer faster and more reliable connections.
  
- Consider offering different Wi-Fi packages, including complimentary basic access and premium high-speed options.
  
- Promote the availability of in-flight Wi-Fi during the booking process to attract tech-savvy travelers.
  
- Ensure proper technical support for passengers experiencing connectivity issues.
  
4. Continuous Improvement in In-Flight Services:

- Maintain the high quality of in-flight services, including seat comfort, dining options, and entertainment.
  
- Regularly gather feedback from passengers to identify areas for improvement.
  
- Train cabin crew to provide exceptional service and personalized attention to passengers.
  
5. Cater to Business Travelers:

- Recognize the needs of business-oriented travelers and tailor services accordingly.
  
- Offer dedicated business-class amenities and services to meet their expectations.
  
- Create business-friendly packages that include priority boarding, additional legroom, and workspace options.

6. Efficient Ground Operations:

- Ensure efficient ground handling at airports to minimize turnaround times.
  
- Implement strategies to handle baggage and cargo efficiently.
  
- Coordinate closely with airport authorities to reduce ground-related delays.
  
7. Proactive Communication:

- Keep passengers informed about any changes, delays, or issues that may affect their travel plans.
  
- Use various communication channels, such as mobile apps, email, and SMS, to reach passengers.
  
- Provide clear instructions for rebooking or connecting flights in case of delays.

  
By implementing these recommendations, the airline can work towards increasing overall customer satisfaction, reducing both arrival and departure delays, and improving the ease of online booking and in-flight Wi-Fi services. These actions can lead to a more positive travel experience for passengers, including the majority of business-oriented travelers, ultimately contributing to the airline's success and reputation.


## Limitations

While the recommendations provided can be beneficial, there are some observed limitations to be aware of:

1. Cost Considerations: Implementing some of these improvements, such as upgrading in-flight Wi-Fi or enhancing online booking processes, may require significant financial investments. The airline must carefully evaluate the budget constraints and prioritize changes accordingly.
   

2. Operational Challenges: Achieving punctuality and minimizing delays may be challenging due to various factors, including weather conditions, air traffic control, and airport congestion. While improvements can be made, complete elimination of delays may not be possible.
   

3. Technological Constraints: The success of in-flight Wi-Fi improvements is subject to the availability of advanced technology and infrastructure, which may vary depending on the airline's routes and aircraft.
   

4. Training and Staffing: Enhancing in-flight and ground services may require additional training for cabin crew and ground personnel. It's essential to ensure that staff are adequately prepared to deliver improved services.


5. Customer Adoption: Changes to the online booking process or Wi-Fi services may take time for customers to adopt and adapt to. Some passengers may continue to face challenges despite improvements.

6. Competitive Landscape: The airline industry is highly competitive, and other airlines may also be making improvements to attract and retain passengers. Staying ahead of the competition can be challenging.

7. External Factors: Factors like government regulations, global events (e.g., pandemics), and economic conditions can impact airline operations and passenger satisfaction, often beyond the airline's control.

8. Customer Expectations: Meeting the diverse needs and expectations of passengers, especially business travelers, can be a complex task. Preferences and requirements may vary widely.
   

To address these limitations, it's essential for the airline to conduct thorough feasibility studies, prioritize improvements, and implement changes gradually. Additionally, continued feedback from passengers and regular evaluation of the effectiveness of these recommendations will be crucial in refining strategies and ensuring the best possible passenger experience.


### Refrence
[Link to Data set](https://docs.google.com/spreadsheets/d/15Kp-2yfQFNRGJPNOkpMwG-OMX8xVZOJ5VL7f35v7sRQ/edit#gid=1647986900)












  
