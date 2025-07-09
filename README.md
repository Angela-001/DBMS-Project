# DBMS-Project

Maintaining high passenger satisfaction is critical in the highly competitive airline industry. Positive 
experiences encourage favorable reviews, while dissatisfied passengers often share negative word-of mouth online, an influential factor in purchase decision making.
The amount of review data generated from airline reviews is unstructured, huge, and grows 
exponentially with time, which poses a challenge in managing, organizing, and performing analytics. Text 
mining provides automated methods to uncover hidden patterns and sentiments within large‐scale 
review data, revealing relationships that traditional data analysis would miss.
MongoDB is well suited to this task due to its flexible schema design, which enables data scalability and 
does not suffer from query latencies that increase with an increase in data compared to traditional 
databases. Additionally, it can analyze data of any structure directly within the database in real time and 
give the analytical results in real time.
This project aims to efficiently store, clean, and analyze large-scale unstructured airline review data 
using MongoDB to extract meaningful information about customer sentiments. 
The project’s goals are:
1. To ingest the airline review CSV data into MongoDB.
2. Conduct data cleaning, preprocessing, and store data into MongoDB collections.
3. Apply sentiment analysis to quantify customer satisfaction.
4. Identify common complaint themes among the reviews via keyword analysis.
5. Apply data visualization to identify customer satisfaction patterns across airlines, over time, and 
across different traveler types.

## Technologies Used

- Python 3.10
- Jupyter Notebook
- pandas, numpy, TextBlob, NLTK, Plotly

## Dataset

Airline review data was sourced from Kaggle at https://www.kaggle.com/datasets/juhibhojani/airline-reviews 

- The dataset includes 23,171 reviews from 497 airlines.
- Features of the dataset are: 
  - Airline Name
  - Overall Rating
  - Review Title
  - Review Date
  - Verified (whether the review is verified or not)
  - Review
  - Aircraft
  - Type of Traveller
  - Seat Type
  - Route
  - Date Flown
  - Seat Comfort
  - Cabin Staff Service
  - Food & Beverages
  - Ground Service
  - Inflight Entertainment
  - Wifi & Connectivity
  - Value for Money
  - Recommended
      
