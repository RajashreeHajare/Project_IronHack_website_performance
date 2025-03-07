# README: IronHack_Bootcamp_ Vanguard Website Performance Analysis Project

---

## Project Background

In this project, the basis was that the digital world is evolving, and so are Vanguard’s clients. Vanguard believed that a more intuitive and modern User Interface (UI), coupled with timely in-context prompts (cues, messages, hints, or instructions provided to users directly within the context of their current task or action), could make the online process smoother for clients. However, the critical question was: Would these changes encourage more clients to complete the process?

---

### The Experiment Conducted

A/B Testing

An A/B test was conducted from 3/15/2017 to 6/20/2017 by the Vanguard team.

- **Control Group:** Clients interacted with Vanguard’s traditional online process.
- **Test Group:** Clients experienced the new, spruced-up digital interface.

Both groups navigated through an identical process sequence: an initial page, three subsequent steps, and finally, a confirmation page signaling process completion.

The goal was to see if the new design leads to a better user experience and higher process completion rates.

---

#### The Data Tools provided: 

There were three datasets that will guide this analysis:

1. Client Profiles (`df_final_demo` ): Contains demographics like age, gender, and account details of our clients.

2. Digital Footprints (`df_final_web_data`): Conytains detailed trace of client interactions online, divided into two parts: `pt_1` and `pt_2`.

3. Experiment Roster (`df_final_experiment_clients`): Contains a list revealing which clients were part of the grand experiment.

---

##### Outline

1. Introduction:
   - Overview of the project and the importance of enhancing the user interface for better client experience.

2. The Experiment:
   - Detailed description of the A/B testing methodology used to compare the traditional and new UI.

3. Data Overview:
   - Explanation of the datasets provided for analysis:
     - `df_final_demo`: Client demographic data.
     - `df_final_web_data`: Online interaction data (merge `pt_1` and `pt_2`).
     - `df_final_experiment_clients`: List of clients involved in the A/B test.

4. Analysis AFinal thoughts and strategic implications for Vanguard based on the analysis is to further simplify the UI as error rate is high and average of clients is between 49 to 50.pproach:
   - Steps to merge and clean the data using python.
   - Use statistical tools and techniques to analyze the impact of the new UI on user experience and process completion rates; performmed using python.
   - Interpret and visualize outputs using Tableau.

5. Key Findings from my analysis:
   - Summary of key insights derived from the data analysis, such as:
     - Increase in both male and female user interactions.
     - Marginal drop in average age of users.
     - Increased average visits per visitor.
     - Decreased drop-off rate.
     - Increased average duration of time on site.
     - Stability in balance metrics, increased completion rate, and reduced volatility.
     - Improved sales and customer behavior metrics, such as average steps completed and increased customer satisfaction.

6. Recommendations:
   - Suggestions based on findings to further enhance user experience and engagement.

7. Conclusion:
   - Final thoughts and strategic implications for Vanguard based on the analysis suggest further simplifying the UI due to a high error rate and an average client age of 49 to 50.

---

**Tools used:  
	- Python
	- Tableau
	- Microsoft Excel 