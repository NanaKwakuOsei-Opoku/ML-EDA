# Gen-Z Dating App Usage Analysis in India

## Dataset Overview
This dataset analyzes dating app preferences and usage patterns among Gen-Z users (ages 18-25) across major Indian cities. The analysis provides insights into user behavior, preferences, and challenges faced on dating platforms.

## Data Quality Assessment

### Missing Values
- Primary_App: 107 missing values
- Secondary_Apps: 114 missing values
- Challenges: 117 missing values

### Data Distribution
#### Demographics
- Gender: Well-balanced distribution (Female: 35.2%, Male: 34.2%, Non-binary: 30.6%)
- Age Groups: Primarily 21-23 (39.4%), followed by 18-20 (35.0%), and 24-26 (25.6%)
- Location: 7 major cities covered (Mumbai, Kolkata, Delhi, Bangalore, Pune, Chennai, Hyderabad)
- Education: Even distribution across Graduate (169), Undergraduate (166), and Postgraduate (165)

#### Usage Patterns
- Primary Apps: OkCupid (118), Hinge (106), Bumble (93), Tinder (76)
- Usage Frequency: Daily (181), Weekly (161), Monthly (158)
- Daily Usage Time: Ranges from 30 minutes to 3 hours, with 1.5-2 hours being most common

## Key Insights

### Dating App Preferences
1. Platform Popularity
   - OkCupid leads as the primary app choice
   - Significant number of users (107) don't use any primary dating app
   - Hinge and Bumble show strong presence as secondary apps

2. Usage Patterns
   - Metro vs Non-Metro divide: 73.8% users from metro cities
   - Daily users form the largest segment (181 users)
   - Average session time: 1.5-2 hours most common

3. User Motivations
   - Primary reasons: Casual Dating (138), Finding a Partner (130)
   - Communication preferences: Video Calls (195), Voice Notes (162)
   - Partner priorities vary, with personality-first approach leading

### Challenges and Features
1. Major Challenges
   - Lack of Genuine Matches (135 users)
   - Time-Wasting (127 users)
   - Safety Concerns (121 users)

2. Desired Features
   - Location-Based Matching (111 users)
   - Video Calls (103 users)
   - Detailed Profiles (102 users)

## Data Cleaning Steps
1. Duplicate Check: No duplicates found in the dataset
2. Standardization: 
   - Categorical values standardized
   - Gender categories normalized
   - Location names standardized
3. Missing Values: Handled based on context
4. Feature Engineering:
   - Created Active_App_Count
   - Encoded categorical variables
   - Scaled numerical features

## Ethical Considerations
1. Bias in data collection: Overrepresentation of certain groups may lead to skewed results.
2. Ensure diverse demographic representation to avoid limiting the generalizability of the findings.

## Recommendations for Future Analysis
1. Include more non-metro cities for better geographic representation
2. Add relationship outcome tracking
3. Include user retention metrics
4. Expand age range to capture broader trends

## Technical Details
- Data Processing: Python (pandas, numpy)
- Visualization: matplotlib, seaborn
- Feature Engineering: StandardScaler for numerical variables
- Version Control: GitHub

## Contributors
- Initial Data Collection: [Team Name]
- Analysis: [Student Name]
- Documentation: [Student Name]

## Version History
- v1.0: Initial data cleaning and analysis
- v1.1: Added feature engineering
- v1.2: Updated documentation and insights

## Data Dictionary

| Column Name | Data Type | Description | Notes |
|------------|-----------|-------------|-------|
| Gender | Categorical | User's gender identity | Reflects diverse gender identities in the dataset |
| Age | Numerical | User's age | Focuses on Gen-Z age range (18-25) |
| Location | Categorical | City of residence | Represents major Indian cities |
| Education | Categorical | Highest education level | Captures current educational status |
| Occupation | Categorical | Primary work/study status | Reflects professional diversity of users |
| Primary_App | Categorical | Main dating app used | Indicates primary platform preference |
| Secondary_Apps | Categorical | Additional dating apps used | Captures multi-app usage behavior |
| Usage_Frequency | Categorical | How often the app is used | Measures engagement level |
| Daily_Usage_Time | Categorical | Time spent on dating apps daily | Quantifies app interaction duration |
| Reason_for_Using | Categorical | Motivation for using dating apps | Reveals user intentions and expectations |
| Challenges | Categorical | Difficulties encountered on dating apps | Highlights pain points in user experience |
| Desired_Features | Categorical | Features users want to see | Provides product improvement suggestions |
| Preferred_Communication | Categorical | Preferred communication method | Indicates communication preferences |
| Partner_Priorities | Categorical | What users value most in a partner | Reflects relationship value hierarchy |
| Active_App_Count | Numerical | Number of active dating apps | Engineered feature showing app diversity |
| Gender_Encoded | Numerical | Encoded gender for ML models | Prepared for machine learning preprocessing |
| Location_Type_Encoded | Numerical | Encoded location type | Binary encoding for location |
| Scaled_Age | Numerical | Standardized age values | Normalized for modeling purposes |
| Scaled_Satisfaction | Numerical | Standardized satisfaction scores | Normalized metric for analysis |

## Data Cleaning Process
Based on the task document requirements, we undertook the following data cleaning steps:

1. Duplicate Check
   - Verified and removed any duplicate rows
   - Ensured unique entries in the dataset

2. Missing Value Handling
   - Identified columns with missing values
   - Strategically decided to:
     * Flag missing values
     * Investigate reasons for missingness
     * Considered appropriate imputation or removal methods

3. Categorical Value Standardization
   - Normalized categorical variables
   - Ensured consistency in:
     * Case sensitivity
     * Spelling variations
     * Uniform representation of categories

4. Outlier Detection and Handling
   - Used box plots and Interquartile Range (IQR) method
   - Analyzed numerical columns for potential outliers
   - Made informed decisions about outlier treatment

## Ethical Considerations
- Ensured balanced representation across demographic groups
- Identified potential biases in data collection
- Maintained privacy and anonymity of data sources
- Critically evaluated the dataset's generalizability

## Recommendations for Future Analysis
1. Expand data collection to include more diverse geographic regions
2. Investigate reasons for missing data
3. Conduct deeper bias analysis
4. Develop more sophisticated feature engineering techniques

_Last Updated: February 10, 2025_
