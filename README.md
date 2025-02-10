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
- Initial Data Collection: [Team Name]
- Analysis: [Student Name]
- Documentation: [Student Name]

## Version History
- v1.0: Initial data cleaning and analysis
- v1.1: Added feature engineering
- v1.2: Updated documentation and insights

## Data Dictionary

| Column Name | Data Type | Description | Possible Values/Examples | Notes |
|------------|-----------|-------------|--------------------------|-------|
| Gender | Categorical | User's gender identity | "female", "male", "non-binary" | Inclusive of multiple gender identities |
| Age | Numerical | User's age | 18-25 | Gen-Z age range |
| Location | Categorical | City of residence | "Mumbai", "Delhi", "Bangalore", etc. | Major Indian cities |
| Education | Categorical | Highest education level | "Undergraduate", "Graduate", "Postgraduate" | Current educational status |
| Occupation | Categorical | Primary work/study status | "Student", "Intern", "Freelancer", "Full-time Job", "Part-time Job" | Reflects professional diversity |
| Primary_App | Categorical | Main dating app used | "OkCupid", "Hinge", "Bumble", "Tinder", "None" | Primary platform preference |
| Secondary_Apps | Categorical | Additional dating apps used | "Hinge", "OkCupid", "Bumble", "Tinder", "None" | Multiple app usage |
| Usage_Frequency | Categorical | How often the app is used | "Daily", "Weekly", "Monthly" | Engagement level |
| Daily_Usage_Time | Categorical | Time spent on dating apps daily | "30 minutes", "1 hour", "1.5 hours", "2 hours", "3 hours" | App usage duration |
| Reason_for_Using | Categorical | Motivation for using dating apps | "Casual Dating", "Finding a Partner", "Casual Fun", "Social Interaction" | User intentions |
| Challenges | Categorical | Difficulties encountered | "Lack of Genuine Matches", "Time-Wasting", "Safety Concerns", "None" | Pain points in dating apps |
| Desired_Features | Categorical | Features users want to see | "Location-Based Matching", "Video Calls", "Detailed Profiles", "Audio Calls", "AI Recommendations" | Product improvement suggestions |
| Preferred_Communication | Categorical | Preferred communication method | "Video Calls", "Voice Notes", "Text" | Communication preferences |
| Partner_Priorities | Categorical | What users value most in a partner | "Personality > Interests > Values", "Values > Personality > Appearance", "Appearance > Interests > Personality" | Relationship value hierarchy |
| Active_App_Count | Numerical | Number of active dating apps | 0-3 | Engineered feature showing app diversity |
| Gender_Encoded | Numerical | Encoded gender for ML models | 0, 1, 2 | One-hot or label encoded gender |
| Location_Type_Encoded | Numerical | Encoded location type | 0 (Non-Metro), 1 (Metro) | Binary location encoding |
| Scaled_Age | Numerical | Standardized age values | Typically between -3 and 3 | Normalized age for modeling |
| Scaled_Satisfaction | Numerical | Standardized satisfaction scores | Typically between -3 and 3 | Normalized satisfaction metric |

_Last Updated: February 10, 2025_
