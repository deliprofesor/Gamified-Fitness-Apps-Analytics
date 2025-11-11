#  Data Dictionary — *Gamified Fitness Apps Dataset*

##  General Overview
This dataset contains coded information on **103 gamified fitness tracking applications**, focusing on the **game mechanics** they include (points, badges, levels, leaderboards, etc.).  
Each row represents a single application.

The goal of this dataset is to explore **how gamification is applied in the fitness context**, which mechanics are most common, and how these relate to user engagement and popularity.

---

##  Variables

| **Variable Name** | **Type** | **Description** |
|------------------|-----------|-----------------|
| `App_Name` | Text | Name of the fitness application |
| `Developer` | Text | Developer or company name |
| `Category` | Categorical | Application category (Fitness, Health, Lifestyle, etc.) |
| `Platform` | Categorical | Platform where the app is available (Android, iOS, Web) |
| `Release_Year` | Numeric | Year of release |
| `Active_Users` | Numeric | Number of active users (estimated or reported) |
| `Download_Count` | Numeric | Total download count (in thousands or millions) |
| `Average_Rating` | Numeric (0–5) | Average user rating |
| `In_App_Purchases` | Boolean (0/1) | Indicates if the app offers in-app purchases |
| `Social_Features` | Boolean (0/1) | Indicates if the app supports social or group interactions |

---

##  Game Mechanics

| **Mechanic** | **Type** | **Description** |
|--------------|-----------|-----------------|
| `Points_System` | Boolean (0/1) | Users earn points for completing activities |
| `Badges` | Boolean (0/1) | Badges or achievements awarded for specific goals |
| `Levels` | Boolean (0/1) | Users can progress through levels as they advance |
| `Leaderboards` | Boolean (0/1) | Rankings among users (e.g., weekly leaderboard) |
| `Challenges` | Boolean (0/1) | Daily or weekly activity challenges |
| `Rewards` | Boolean (0/1) | Physical or digital reward systems |
| `Progress_Bars` | Boolean (0/1) | Visual progress indicators |
| `Avatars` | Boolean (0/1) | Personalized avatar or character system |
| `Narrative_Story` | Boolean (0/1) | Story-driven or adventure-based fitness elements |
| `Feedback_System` | Boolean (0/1) | Real-time feedback on performance |
| `Social_Competition` | Boolean (0/1) | Competitive elements among users |
| `Social_Collaboration` | Boolean (0/1) | Cooperative or team-based features |
| `Customization` | Boolean (0/1) | Ability to customize user profile or experience |
| `Virtual_Currency` | Boolean (0/1) | In-app virtual currency or coin system |
| `Goal_Setting` | Boolean (0/1) | Allows users to set personal goals |
| `Reminders` | Boolean (0/1) | Gamified notifications or reminders |
| `Streaks` | Boolean (0/1) | Streak systems that reward daily consistency |
| `Unlockables` | Boolean (0/1) | Features or content unlocked via achievements |
| `Quests` | Boolean (0/1) | Long-term thematic missions or quests |

---

##  Additional Variables (If Available)

| **Variable Name** | **Type** | **Description** |
|------------------|-----------|-----------------|
| `User_Engagement_Score` | Numeric | Engagement level (e.g., average sessions, task completion rate) |
| `Retention_Rate` | Numeric | User retention percentage (%) |
| `Avg_Session_Time` | Numeric | Average session duration (minutes) |
| `App_Price` | Numeric | Price of the application (USD) |

---

##  Notes

- Boolean variables are coded as:  
  `1 = Present`, `0 = Not Present`
- Some applications may lack user or rating data.
- The dataset is based on **qualitative coding** of app store descriptions and features.

---

**Source:**  
Data adapted from [scholarsarchive.byu.edu](https://scholarsarchive.byu.edu) — *Review of Gamified Fitness Tracker Apps Dataset*.

---
