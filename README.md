# ML-EDA
Exploratory data analysis performed on India's Generation Z population online dating habits

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
1. Gender Representation
   - Balanced representation across gender categories
   - Inclusive of non-binary users

2. Geographic Diversity
   - Coverage across major Indian cities
   - Notable metro vs non-metro divide needs consideration

3. Privacy Considerations
   - No personally identifiable information included
   - Aggregate data used for analysis

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
- Initial Data Collection: [Jeremiah Ishaya]
- Analysis: [Nana Kwaku Osei-Opoku]
- Documentation: [Nana Kwaku Osei-Opoku]

## Version History
- v1.0: Initial data cleaning and analysis
- v1.1: Added feature engineering
- v1.2: Updated documentation and insights

_Last Updated: February 10, 2025_
