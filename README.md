# Customer Service Call Analysis Dashboard

This project is a Customer Service Call Analysis Dashboard that visualizes data related to customer service calls, providing insights into various metrics such as average talk duration, speed of answer, satisfaction ratings, and more. The dashboard helps in analyzing agent performance, call topics, and service efficiency.

## Dataset Overview

The dataset contains the following key columns:

- **Agent**: Name of the agent handling the call.
- **Answered (Y/N)**: Indicates if the call was answered or not.
- **Avg Talk Duration**: The average duration of the conversation.
- **Call Id**: Unique identifier for each call.
- **Date**: Date the call was resolved.
- **Resolved (Y/N)**: Whether the issue was resolved.
- **Time**: The time of the call.
- **Topic**: The subject or reason for the call (e.g., Contract-related, Technical Support, Payment-related).
- **Satisfaction Rating**: Customer rating of satisfaction on a scale (e.g., 1-5).
- **Speed of Answer in Seconds**: Time taken for the agent to answer the call.

## Dashboard Features

The dashboard includes various visualizations:

1. **Tree Map**: Shows the number of calls handled by each agent.
2. **Pie Chart**: Breaks down the total calls received by agents.
3. **Bubble Chart**: Displays satisfaction ratings for each agent.
4. **Bar Graph**: Compares speed of answer in seconds across agents.
5. **Trend Line**: Tracks the number of calls over time for analysis of patterns.

## Key Insights

- **Agent Performance**: The dashboard highlights which agents answered the most calls and their average speed of response.
- **Customer Satisfaction**: Visualizes customer ratings to help identify areas for improvement.
- **Call Topics**: Shows what topics or issues are most frequently reported by customers.

## Tools Used

- **Tableau**: Used for building the visualizations and interactive dashboard.
- **Pandas**: Data cleaning and preparation.
- **Python**: For any data preprocessing needed before visualization.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/customer-service-dashboard.git
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## How to Use

1. Load the dataset into the project.
2. Open the Tableau file to view the interactive dashboard.

## Who Would Find This Project Useful?

This project will be useful for:
- **Customer Service Managers**: To monitor agent performance and identify areas where customer service can be improved.
- **Business Analysts**: To gain insights into customer interactions and service efficiency.
- **Call Center Supervisors**: To assess call response times, customer satisfaction, and call topics to optimize operations.
- **Data Analysts**: Looking to explore real-world customer service datasets and develop dashboards for reporting.

## Conclusion

This project provides a comprehensive analysis of customer service calls to help improve agent performance and customer satisfaction. The dashboard enables quick insights into response times, satisfaction levels, and call patterns.

## License

This project is licensed under the MIT License.
