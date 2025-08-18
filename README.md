<strong>

<div align="center">
 
<a href="https://github.com/TheMrityunjayPathak" title="Mrityunjay's GitHub"><img src="https://github.com/user-attachments/assets/301effa3-f09e-487c-9739-44863e5aaf96"></a>

</div>

<div align="center">
 
<a href="#about">
About
</a>&nbsp;&nbsp;&nbsp;
<a href="#skills">
Skills
</a>&nbsp;&nbsp;&nbsp;
<a href="#projects">
Projects
</a>&nbsp;&nbsp;&nbsp;
<a href="#certificates">
Certificates
</a>&nbsp;&nbsp;&nbsp;
<a href="#blogs">
Blogs
</a>

</div>

<div align="right">
 
<a href='mailto:themrityunjaypathak@gmail.com' title='Email'>
<img src='https://github.com/user-attachments/assets/f24b0e80-2aba-4f1c-8cff-4ce0d75d0f57' width="83px" align="center"></a>
&nbsp;
<a href='https://drive.google.com/file/d/1qZe-iR6gvuIzDrQY7ZU75e5hnN-Nwavp/view?usp=sharing' title='Resume'>
<img src='https://github.com/user-attachments/assets/3c69bd98-4582-4e7d-82d6-b5d9f7212a25' width="100px" align="center"></a>

</div>

## About

Hi 👋, I'm Mrityunjay Pathak
 
I'm a Data Scientist with a knack for uncovering patterns and trends that drive smarter decisions.

🎯 Tools and Technologies

• Programming Language : I'm familiar with Python, a powerful language for data science and machine learning.

• Libraries : I'm also familiar with essential data science libraries like NumPy, Pandas, Matplotlib, Seaborn and Plotly.

• Machine Learning : I have experience with Scikit-learn, a famous machine learning library used widely across industries.

• Database : I can work with MySQL, a popular database management system to handle and retrieve data effectively.

• BI Tool : I'm familiar with Power BI to perform data analysis, create dynamic dashboards and extract meaningful insights.

• Web Framework : I have experience with FastAPI, a high-performance web framework for building APIs with Python.

• Containerization : I can work with Docker for packaging application and their dependencies into containers.

• Version Control : I'm familiar with Git, which helps in keeping track of changes in code and collaborating effectively with a team.

📫 Connect with Me

[Kaggle](https://www.kaggle.com/themrityunjaypathak)&nbsp;&nbsp;|&nbsp;&nbsp;[LinkedIn](https://www.linkedin.com/in/themrityunjaypathak)&nbsp;&nbsp;|&nbsp;&nbsp;[GitHub](https://github.com/TheMrityunjayPathak)&nbsp;&nbsp;|&nbsp;&nbsp;[Medium](https://medium.com/@themrityunjaypathak)&nbsp;&nbsp;|&nbsp;&nbsp;[Portfolio](https://themrityunjaypathak.github.io/)

## Skills

<div align="left">

<a href=''><img src='https://github.com/user-attachments/assets/78edfa30-3f27-4318-b992-242a20a9dacf' title='Python' width='90px'></a> <a href=''><img src='https://github.com/user-attachments/assets/8cfc02b1-3e91-4a3c-b765-7f2635023d08' title='NumPy' width='90px'></a> <a href=''><img src='https://github.com/user-attachments/assets/8e24cdf0-5ca2-4491-a37f-af00d59d9bea' title='Pandas' width='90px'></a> <a href=''><img src='https://github.com/user-attachments/assets/d8c97060-0459-4959-bcd4-dd0c9f9aec4b' title='Matplotlib' width='90px'></a>
<br>
<a href=''><img src='https://github.com/user-attachments/assets/8d803cc2-3079-4962-9dab-72923eee8257' title='Seaborn' width='90px'></a> <a href=''><img src='https://github.com/user-attachments/assets/4a01d9a6-488c-477d-945d-cbda19aeb7c3' title='Plotly' width='90px'></a> <a href=''><img src='https://github.com/user-attachments/assets/aa29ca4d-502c-4897-bda0-2612434dc523' title='Scikit-learn' width='90px'></a> <a href=''><img src='https://github.com/user-attachments/assets/cff6805d-0843-42ff-8195-b3ff4d1e29bc' title='MySQL' width='90px'></a>
<br>
<a href=''><img src='https://github.com/user-attachments/assets/ecee95dc-e4b9-4d03-a673-c1508e232242' title='Power BI' width='90px'></a> <a href=''><img src='https://github.com/user-attachments/assets/d7b3414b-f1b9-4e95-ae4c-73630bff4582' title='FastAPI' width='90px'></a> <a href=''><img src='https://github.com/user-attachments/assets/6f168c07-670d-4b8e-a724-4d54a6c25363' title='Docker' width='90px'></a> <a href=''><img src='https://github.com/user-attachments/assets/9c5deb99-3359-43b3-9e18-b8fe5183e54b' title='Git' width='90px'></a>

</div>

## Projects

### AutoIQ : Car Price Prediction 
<a href="https://github.com/TheMrityunjayPathak/AutoIQ"><img src="https://github.com/user-attachments/assets/92d6ca72-44fa-4874-8495-f07811dddd60" title="GitHub" width="80px"></a> &nbsp; <a href="https://themrityunjaypathak.github.io/AutoIQ/"><img src="https://github.com/user-attachments/assets/5876b6a4-9ab2-48aa-90d3-70117399aff3" title="Application" width="80px"></a> &nbsp; <a href="https://autoiq.onrender.com/docs"><img src="https://github.com/user-attachments/assets/453026e0-6b16-4b24-af29-415de2bc6bf8" title="Swagger UI" width="80px"></a>

➔ Problem
- In the used car market, buyers and sellers often struggle to determine a fair price for their vehicle.
- This project aims to provide accurate and transparent pricing for used cars by analyzing real-world data.
- It will assist both buyers and sellers make data-driven decisions and ensure fair transactions.

➔ Solution

To address this problem, I built and deployed a complete end-to-end machine learning pipeline :
- Data Collection
  - Scraped a dataset of ~2,800 used cars from Cars24 using Selenium and BeautifulSoup.
- Data Optimization
  - Optimized memory consumption of dataset by downcasting data types.
  - Stored the dataset in Parquet format, which compresses data without losing information.
  - It also provides much faster read/write speeds compared to CSV.
- Preprocessing & Modeling
  - Implemented Scikit-learn Pipelines & ColumnTransformer to prevent data leakage.
- API Deployment
  - Deployed the machine learning model as an API using FastAPI, with :
    - /predict endpoint for real-time predictions.
    - /health endpoint for monitoring API status.
    - Input validation & rate limiting for reliability.
- Frontend Integration
  - Designed a HTML/CSS/JS website to send API calls and display predictions in a user-friendly way.
- Containerization
  - Created a multi-stage Dockerfile with .dockerignore for building an optimized and lightweight Docker image.

➔ 𝗜𝗺𝗽𝗮𝗰𝘁
- Built and deployed a complete machine learning pipeline as a FastAPI application.
- Reduced dataset memory usage by ~90% through data type optimization and Parquet conversion.
- Delivered ~30% lower MAE and ~12% higher R2-Score compared to the baseline model.
- Improved model stability by ~70%, ensuring more consistent and reliable predictions.
</details>

<hr>

### Pickify : Movie Recommender System
<a href="https://github.com/TheMrityunjayPathak/Pickify"><img src="https://github.com/user-attachments/assets/92d6ca72-44fa-4874-8495-f07811dddd60" title="GitHub" width="80px"></a> &nbsp; <a href="https://pickify.streamlit.app/"><img src="https://github.com/user-attachments/assets/5876b6a4-9ab2-48aa-90d3-70117399aff3" title="Application" width="80px"></a>

➔ Problem
- With the rise of streaming services, viewers now have access to thousands of movies across platforms.
- As a result, many viewers spend more time browsing than actually watching.
- This problem can lead to frustration, lower satisfaction and less time spent on the platform.
- Which can impact both the user experience and business performance.

➔ Solution
- A content-based movie recommender system built with clean and modular code with proper version control.
- It analyzes metadata of 5000+ movies to recommend top 5 similar titles based on a user selected input.
- The system uses techniques like CountVectorizer and CosineSimilarity to recommend similar movies.
- The project not only focuses on functionality but on building a clean and scalable solution.

➔ Impact

If this system gets scaled and integrated with a streaming service, this could :
- Reduce the time users spend choosing what to watch.
- Increase user engagement, watch time and customer satisfaction.
- Help streaming platforms retain users by offering better personalized content.

<hr>

### Netflix Data Analysis
<a href="https://github.com/TheMrityunjayPathak/Netflix-Data-Analysis"><img src="https://github.com/user-attachments/assets/92d6ca72-44fa-4874-8495-f07811dddd60" title="GitHub" width="80px"></a> &nbsp; <a href="https://www.kaggle.com/code/themrityunjaypathak/netflix-data-analysis"><img src="https://github.com/user-attachments/assets/7b33292b-2a68-4af3-ae25-281105385f8d" title="Notebook" width="80px"></a>

➔ Objective
- To analyze Netflix content data, uncovering valuable insights into how the platform evolves over time.

➔ 𝗦𝗼𝗺𝗲 𝗞𝗲𝘆 𝗙𝗶𝗻𝗱𝗶𝗻𝗴𝘀

Cleaned and analyzed dataset of 8000+ Netflix Movies and TV Shows.
- More than 60% of content on Netflix is rated for mature audiences.
  - Suggests that Netflix targets adult viewers to boost engagement and retention.
- More than 25% of Movies and TV Shows are released on 1st day of the month.
  - Shows a consistent release schedule, likely to align with subscription cycles.
- More than 40% of the content on Netflix is exclusive to United States.
  - Shows a strong focus on the U.S. market and content availability by location.
- More than 20% of the content on Netflix falls under the "Drama" genre.
  - Confirms that "Drama" is a key part of Netflix's content library.
- More than 23% of the content on Netflix was released in 2019 alone.
  - Indicates a major content push that year, possibly tied to growth or user acquisition goals.

<hr>

### Supermarket Sales Analysis
<a href="https://github.com/TheMrityunjayPathak/Supermarket-Sales-Analysis"><img src="https://github.com/user-attachments/assets/92d6ca72-44fa-4874-8495-f07811dddd60" title="GitHub" width="80px"></a> &nbsp; <a href="https://www.kaggle.com/code/themrityunjaypathak/supermarket-sales-analysis"><img src="https://github.com/user-attachments/assets/7b33292b-2a68-4af3-ae25-281105385f8d" title="Notebook" width="80px"></a>

➔ Objective
- To analyze Supermarket Sales data, identifying key factors for improving profitability and operational efficiency.

➔ 𝗦𝗼𝗺𝗲 𝗞𝗲𝘆 𝗙𝗶𝗻𝗱𝗶𝗻𝗴𝘀

Analyzed purchasing pattern of 9000+ customers of Supermarket.
- More than 15% of the products sold were Snacks.
  - Shows that Snacks are a convenient choice and a big source of revenue.
- More than 32% of the sales were occurred in West region of Supermarket.
  - Suggests that West region is a strong performing area as compared to others.
- Health and Soft drinks are the most profitable category in Beverages.
  - Shows that both type of drinks option sells well.
- November was the most profitable month contributing about 15% of the total annual profits.
  - Makes it an ideal time for running promotions and special offers.

## Certificates

<div>

<a href="https://www.hackerrank.com/certificates/e41a7578cc82" title="HackerRank Python (Basic)"><img src="https://github.com/user-attachments/assets/a06b46c9-6ff8-41d7-a035-c4f02d624422" width="175px" align="center"/></a> &nbsp;&nbsp; <a href="https://www.hackerrank.com/certificates/09ec62ca442f" title="HackerRank SQL (Basic)"><img src="https://github.com/user-attachments/assets/b49b401f-bcc4-4574-9fe9-e79052e324dc" width="175px" align="center"/></a>

</div>

## Blogs

<a href="https://medium.com/@themrityunjaypathak/simple-linear-regression-an-overview-8bfe6614ede8" title="Simple Linear Regression"><img src="https://github.com/user-attachments/assets/707ee381-da5a-4c4a-ae99-23b003fb7cd2" width="175px" align="center"/></a> &nbsp;&nbsp; <a href="https://medium.com/@themrityunjaypathak/multiple-linear-regression-an-overview-5d0283d31f3f" title="Multiple Linear Regression"><img src="https://github.com/user-attachments/assets/e5f5573d-9a1a-47aa-b71e-a9007027d303" width="175px" align="center"/></a>

<div align="right">
 
<a href="#" title="Scroll To Top"><img src="https://github.com/user-attachments/assets/d659b889-7e76-4fb3-a55a-3a14abb4df5a" width="30px"></a>

</div>

<a href='#'><img src='https://github.com/user-attachments/assets/e841a7d6-c1cb-49da-8922-5436987cc4d1'></a>

</strong>
