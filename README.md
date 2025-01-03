# Data-Analytics-project-Social_buzz-

Project Overview:
The objective of this project is to analyze the client's content categories and identify the top 5 categories with the largest popularity. Popularity is measured by a "Score" assigned to each reaction type. The project involves data gathering, cleaning and modeling datasets, and presenting findings in a PowerPoint presentation.

Data Sources:
The client provided 7 datasets, of which 3 were found relevant to the problem statement based on the data model. These datasets were cleaned, merged, and modeled to prepare the data for analysis.

Selected Datasets:
Dataset 1: Contains details of content IDs, categories, and types.
Dataset 2: Includes reaction types and scores associated with each content.
Dataset 3: Links reaction data with content details.

Data Model:
The data model explains relationships between the datasets: 
Content ID links details about content and reaction information.
Reaction type and reaction score as measures of popularity.

Steps Taken:
1. Requirements Gathering
Identified the client's key question: What are the top 5 categories with the largest popularity?
Determined that "popularity" is based on the total "Score" for each reaction type.
2. Data Cleaning
Carried out the following steps to ensure readiness of data:
Erased rows with missing or incomplete values.
Converted data types to make it compatible for analysis.
Deleted irrelevant columns that did not relate to the business question.
3. Data Modeling
Merged the three cleaned datasets based on common fields such as Content ID and Category.
Summed up reaction scores to determine the total popularity for each category of content.
4. Analysis
Calculated the total popularity score for each category.
Ranked the categories to identify the top 5 based on the aggregated scores.
5. Visualization
Designed visuals to aid narration for the client based on:
Top 5 categories with their popularity scores
Contribution of reaction types towards the scores.

Findings:
Top 5 Content Categories by Popularity Score:
Animals (73,271): Content featuring animals dominated user engagement.
Healthy Eating: Health-conscious users frequently engaged with wellness-related content.
Food: Culinary content remains universally appealing.
Science: Factual and educational content attracted significant attention.
Technology: Users showed interest in tech trends and gadgets.

Trends & Insights:
Seasonal Peaks: January, May, and December saw heightened activity, likely tied to holidays, resolutions, and events.
Content Diversity: 16 unique categories with balanced popularity shares, although "Animals" showed a notable lead.

Recommendations
Content Strategy:
Animals & Science: Partner with educational institutions and shelters to create engaging content.
Healthy Eating: Collaborate with influencers for recipes, challenges, and fitness tips.
User Engagement:
Personalization: Use behavioral data to tailor recommendations.
Experimentation: A/B test formats like videos vs. infographics to optimize engagement.
Scaling Analytics:
Implement real-time analytics for continuous monitoring.
Track user metrics to refine content strategies


