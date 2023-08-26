# NIH Research Insights Dashboard

## Introduction
The "NIH Research Insights Dashboard" is an in-depth data analysis project designed to provide valuable insights into research projects funded by the National Institutes of Health (NIH). This documentation offers a comprehensive overview of the insights derived from the data, the advantages for users, the newly added columns, and the step-by-step process taken to develop the dashboard.

## Insights Extracted
Our "Exploring the NIH Research Universe" dashboard is a treasure trove of insights, offering a detailed look into the intricacies of NIH-funded research projects. Here’s a closer examination of the insights you can extract:

1. **Project Duration Trends**: Delve into the temporal dynamics of research projects. Uncover the distribution of project durations in both months and years. This insight allows you to spot trends in how long projects typically span, aiding in resource allocation and planning.

2. **Funding Dynamics by Award Type**: Understand how different award types influence funding levels. By correlating award types with funding amounts, you can discern patterns in how specific types of research receive funding and identify areas of emphasis.

3. **Geographical Funding Patterns**: Explore the geographical distribution of funding. This insight unveils regions with higher research activity and enables you to gauge the influence of location on funding allocation.

4. **Collaboration Impact**: Investigate the impact of collaboration on funding and project outcomes. By discerning trends in collaboration presence and funding levels, you can assess the value of partnership in research success.

5. **Temporal Funding Trends**: Visualize how award amounts vary across fiscal years. This insight showcases trends in funding over time, helping you understand budget fluctuations and align resources accordingly.

6. **Organizational Contribution**: Gain insights into the distribution of funding among organizations. This perspective highlights key players and contributors in the research landscape, aiding in benchmarking and strategic partnerships.

7. **Departmental Allocations**: Examine how funding is distributed across different department types. This insight reveals the priorities and areas of focus within the research domain, aiding in strategic resource allocation.

8. **Correlation of Award Amounts and Project Titles**: Understand the relationship between project titles and funding levels. This insight offers insights into how well funding aligns with research objectives and the importance of effective project naming.

9. **Geographic Variation in Collaboration**: Explore whether collaboration is influenced by the geographical distribution of projects. This insight helps you understand if geographic proximity encourages collaborative efforts.

10. **Research Focus and Award Amounts**: Uncover if specific research focus areas receive higher award amounts. This insight assists in identifying trends in funding emphasis across various research domains.

## User Benefits
Using the "NIH Research Insights Dashboard" translates into a host of tangible benefits for users seeking to make informed decisions and gain deeper insights into the world of NIH-funded research:

1. **Strategic Resource Allocation**: Make informed decisions on resource allocation by understanding funding trends and priorities, ensuring optimal utilization of available resources.

2. **Informed Grant Applications**: Tailor grant applications based on insights into funding patterns and project attributes, increasing the likelihood of securing funding.

3. **Collaboration Opportunities**: Identify potential collaboration partners based on their presence in collaborative projects, facilitating strategic partnerships.

4. **Geographical Research Insights**: Gain insights into research hotspots in specific regions, enabling targeted efforts for maximum impact and efficient resource allocation.

5. **Enhanced Project Planning**: Plan project durations effectively by analyzing the distribution of research timelines, leading to improved project management.

6. **Decision-Making Support**: Utilize data-driven insights to guide research and organizational strategies, fostering informed decision-making.

7. **Performance Benchmarking**: Benchmark your organization's funding distribution against others in the field for strategic positioning and improvement.

8. **Enhanced Research Impact**: Align project titles with funding trends to maximize research impact and visibility within the broader research landscape.

9. **Resource Optimization**: Optimize resource allocation by focusing on project types with higher award amounts, ensuring efficient utilization of resources.

10. **Operational Efficiency**: Streamline operations by leveraging insights to improve collaboration practices and refine research focus, resulting in enhanced operational efficiency.

In essence, the "NIH Research Insights Dashboard" empowers users with data-driven decision-making capabilities, enabling them to navigate the complex terrain of research funding with clarity, precision, and confidence.

## Added Columns
Several columns were introduced to augment the analysis and visualization of the data:
- **Project Duration (Months)**: Calculated duration in months between project start and end dates.
- **Project Duration (Years)**: Calculated duration in years between project start and end dates.
- **Total Award Amount**: Sum of award amounts for each project.
- **Geographical Region**: Classification of projects based on the org_state column.
- **Collaboration Indicator**: Binary column indicating project collaboration.

## Process Overview
The creation of the dashboard encompassed the following stages:

### Data Import and Cleanup
- Imported NIH research data into Power BI.
- Handled missing values and formatted columns for accurate analysis.

### Column Addition
- Introduced columns for project duration (months and years), total award amount, geographical region, and collaboration indicator.

### Visualization Design
- Devised slicers for fiscal year and country selection.
- Crafted three stacked column bar charts: award vs. project title, award vs. project duration (years), and total cost vs. award type.
- Formulated two stacked bar charts: project duration (months) vs. project ID and department type vs. total cost.
- Created a pie chart: organization name vs. percentage of award amount.

### Title and Documentation
- Included the title "NIH Research Insights Dashboard" in the final dashboard.
- Produced detailed documentation outlining the project, insights, user benefits, added columns, and the step-by-step process.

## Conclusion
The "NIH Research Insights Dashboard" emerges as a potent tool for exploring and comprehending NIH-funded research projects. Through its interactive visualizations, filtering options, and meaningful insights, users can make informed decisions, unearth patterns, and extract valuable knowledge from the data. This project underscores the potential of data analysis to offer actionable insights in the realm of research funding and resource allocation.
