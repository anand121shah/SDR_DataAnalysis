
# Sales Development Representatives Performance Analysis

This report presents an analysis of the performance of Sales Development Representatives (SDRs) based on their activities and metrics. 

## Dataset

The dataset includes the following features:

- User ID and User name: Identifiers for each individual on the team.
- User locked: Indicates whether the user's account is currently locked.
- Cumulative booked meetings: Total number of meetings booked by each user.
- Prospects added: Number of new potential clients or customers each user has identified.
- Prospects active: Number of prospects that are currently being actively engaged or managed by each user.
- Prospects contacted: Number of prospects that each user has made contact with.
- Meeting conversion rate: Proportion of contacts that have resulted in a booked meeting.
- Touches per prospect: Average number of interactions or "touches" each user has with each prospect.
- Emails delivered: Number of emails each user has successfully sent to prospects.
- Outbound calls: Number of calls each user has made to prospects.
- LinkedIn tasks completed: Number of tasks related to LinkedIn that each user has completed.
- Other tasks completed: Number of other tasks (not related to email, calls, or LinkedIn) each user has completed.
- Overdue tasks: Number of tasks that are currently overdue for each user.
- Response time: Average time it takes for each user to respond to messages or inquiries.
- Responses count: Total number of responses each user has sent.

## Data Visualization

Several visualizations were created to understand the distributions and relationships of the data:

- Histograms for 'Cumulative booked meetings', 'Prospects added', 'Outbound calls', and 'LinkedIn tasks completed'.
- Scatter plots for 'Prospects contacted' vs 'Emails delivered', 'Other tasks completed' vs 'Overdue tasks', 'Response time' vs 'Responses count', 'Meetings booked vs Prospects owned', 'Meetings booked vs Prospects contacted', 'Meetings booked vs Response time', and 'Responses count vs Calls made'.
- Boxplot for 'Touches per prospect'.
- Bar plot for 'User locked' status counts.

## Insights

- The top 10 SDRs who booked the most "quality" meetings (defined by the meeting conversion rate - the ratio of cumulative booked meetings to prospects contacted) were identified both before and after removing outliers from the dataset.
- Active users (those who made more than 20 calls per day over the period) were identified, and basic statistics for these users were calculated.
- The most responsive users (those with the shortest response time) were identified.

## Scatter Plots Interpretation

- The scatter plot of "Meetings Booked vs Prospects Owned" shows that as the number of prospects owned increases, the number of meetings booked also generally increases.
- The scatter plot of "Meetings Booked vs Prospects Contacted" shows a similar trend, with more meetings booked as more prospects are contacted.
- The scatter plot of "Meetings Booked vs Response Time" does not show a clear trend. This suggests that the number of meetings booked is not strongly correlated with response time.
- The scatter plot of "Responses Count vs Calls Made" shows that as the number of calls made increases, the number of responses sent also generally increases.

These insights provide valuable information for understanding the effectiveness and efficiency of the sales development representatives. However, remember that correlation does not imply causation, and these trends should be considered within the broader context of the team's operations and strategies.
