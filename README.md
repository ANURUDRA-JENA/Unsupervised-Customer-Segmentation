<h1>CustomerSegmentation using Unsupervised Learning</h1>

![CustomerSegmentationDiagram](https://github.com/ANURUDRA-JENA/Web-Scraping-Project-2/blob/ea36ed80013188a8929c0c9b598e12c1a451b471/asset_management/Designer%20(3).png)

<h3>Primary Objective:</h3>
<ul>
    <li>To perform a comprehensive analysis of transactional data from a UK-based non-store online retail business to optimize marketing and sales strategies.</li>
</ul>
<h3>Secondary Objectives:</h3>
<ul>
    <li>Clean and preprocess the dataset to ensure its reliability and consistency.</li>
    <li>Conduct exploratory data analysis to uncover patterns and correlations within the data.</li>
    <li>Analyze customer behavior,&nbsp;product dynamics,&nbsp;temporal trends,&nbsp;and country-specific patterns.</li>
    <li>Segment customers based on RFM analysis and K-Means clustering to identify high-value customers.</li>
    <li>Provide actionable insights to the business for strategic decision-making and growth.</li>
</ul>

<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong><span style="font-size:19px;">Summarizing the workflow and the results from the tests conducted:</span></strong></p>
<ul style="margin-bottom:0in;margin-top:0in;" type="disc">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Workflow</strong>: The project involves preprocessing data, feature selection, exploratory data analysis (EDA), generating RFM scores, and clustering. Key steps include handling missing values, outliers, and creating new features from the InvoiceDate.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Tests Conducted</strong>: Two hypothesis tests were performed:<ol style="margin-bottom:0in;margin-top:0in;" start="1" type="1">
            <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Frequent vs. Non-Frequent Customers</strong>: Tested if frequent customers spend more than non-frequent customers.</li>
            <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Recent vs. Older Customers</strong>: Tested if recent customers tend to spend more than older customers.</li>
        </ol>
    </li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Results Generated</strong>:<ol style="margin-bottom:0in;margin-top:0in;" start="1" type="1">
            <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Frequent Customers</strong>: Reject the null hypothesis; frequent customers spend more.</li>
            <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Recent Customers</strong>: Reject the null hypothesis; recent customers tend to spend more.</li>
        </ol>
    </li>
</ul>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong><span style="font-size:19px;">Summarizing the insights generated:</span></strong></p>
<ul style="list-style-type: disc;">
    <li>Top-Selling Products: The highest-selling products include items like the WHITE HANGING HEART T-LIGHT HOLDER and JUMBO BAG RED RETROSPOT.</li>
    <li>Customer Behavior: Frequent customers tend to spend significantly more than non-frequent customers. Recent customers also tend to have higher monetary values.</li>
    <li>Sales Trends: Sales peak in November and December, with the highest sales occurring in the afternoon.</li>
    <li>Country Analysis: The majority of sales come from the United Kingdom, followed by Germany and France.</li>
</ul>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Cluster 0: At-Risk or Lapsed Customers</strong></p>
<ul style="margin-bottom:0in;margin-top:0in;" type="disc">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Characteristics:</strong> Low recency, frequency, and monetary value.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Action:</strong> Prioritize reactivation campaigns and investigate reasons for inactivity. Consider seasonal offers or targeted campaigns to re-engage these customers.</li>
</ul>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Cluster 1: Champions or Loyal Customers</strong></p>
<ul style="margin-bottom:0in;margin-top:0in;" type="disc">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Characteristics:</strong> High recency, frequency, and monetary value.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Action:</strong> Maintain high engagement levels, explore up-selling and cross-selling opportunities, and consider feedback or brand ambassador programs.</li>
</ul>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Cluster 2: Potential Loyalists or Promising Customers</strong></p>
<ul style="margin-bottom:0in;margin-top:0in;" type="disc">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Characteristics:</strong> Moderate levels of recency, frequency, and monetary value.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Action:</strong> Implement tailored marketing strategies, loyalty programs, and incentives to increase purchase frequency and value.</li>
</ul>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Overall, the analysis provides valuable insights into customer behavior and helps identify opportunities for targeted marketing efforts to improve customer retention and loyalty.</p>


<h2>In Short...</h2>
<p>This project aims to analyze transactional data from a UK-based online retail business to gain valuable insights into customer behavior, product performance, and temporal trends. By cleaning the data, conducting exploratory analysis, and segmenting customers, the project will provide actionable recommendations to optimize marketing and sales strategies. The ultimate goal is to help the business understand customer needs, tailor product offerings, and enhance customer satisfaction and loyalty.</p>
You can simply go through the notebook and add the dataset into the colab "Sample file" and click Run all in the Runtime dropdown.
You can download the source code and the dataset from the link provided below:
https://drive.google.com/file/d/1GUCdNCi8SWxcRV6DNzQRKp3taLizRJFS/view?usp=sharing
