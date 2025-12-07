---
theme: [wide, coffee]
title: Individual Consumption Behaviors
toc: false
---

# Individual Consumption Behaviors

Individual consumption plays a critical role in shaping both economic activity and environmental impact. How people spend, travel, eat, heat their homes, and manage waste all contribute to their ecological footprint, particularly through carbon emissions. Although consumption is often framed as a personal choice, it is also shaped by structural conditions such as income levels, infrastructure, energy availability, and lifestyle norms. In high-income countries, a relatively small number of daily behaviors, from transportation choices to home energy use, account for a disproportionate share of carbon emissions. By examining patterns in spending, income, and lifestyle behaviors, we can better understand how individual actions contribute to broader economic trends and environmental outcomes. The following visualizations provide insight into these relationships: the first situates personal spending within the economic landscape, while the latter two break down how specific lifestyle behaviors relate to carbon emissions.

---

<h1>Visualization: Individual Lifestyle Behaviors and Emissions</h1>

<div class='tableauPlaceholder' id='viz1763930944326' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;An&#47;AnnualConsumerExpendituresintheU_S_&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AnnualConsumerExpendituresintheU_S_&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;An&#47;AnnualConsumerExpendituresintheU_S_&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1763930944326');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1227px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

---

## Analysis

### 1. Annual Personal Consumption Expenditure vs. Income by U.S. State

This scatterplot shows the relationship between average annual income per person and average annual personal consumption expenditure across U.S. states. The clear positive trend indicates that individuals in higher-income states tend to spend more overall, reinforcing the strong connection between income and consumption capacity. However, the slope of the line is less than one-to-one, meaning spending increases at a slower rate than income. This reflects the economic concept of diminishing marginal propensity to consume: as people earn more, they spend proportionally less and save or invest more. Outliers may reflect regional cost-of-living differences, such as high-income states where expensive housing inflates expenditure, or lower-income states where necessary goods still require a baseline level of spending. Overall, this visualization shows that while income is a major driver of total consumption, it does not explain all variation, leaving room for cultural and geographic factors.

### 2. Average Carbon Emissions per Person Across Lifestyle Categories

This heatmap table ranks lifestyle categories by their average carbon emissions, showing which daily life factors are most strongly associated with overall carbon output. Transportation-related variables stand out as the most carbon-intensive: vehicle fuel type, monthly vehicle distance, and primary transportation mode produce the highest average emissions. This aligns with well-established research showing that private car use, especially gasoline and diesel vehicles, is one of the most significant contributors to individual carbon footprints. Middle-tier categories such as grocery spending, home heating type, and internet/screen use show moderate emissions, reflecting mixed consumption patterns related to energy use, food choices, and household behavior. Meanwhile, categories such as diet type, recycling habits, and shower frequency show relatively small differences between categories, indicating that while these behaviors matter, they are overshadowed in magnitude by transportation and energy consumption. The results indicate that transportation behaviors dominate individual carbon footprints, suggesting that lifestyle interventions and policy initiatives targeting how people travel could generate the most significant reductions. Measures such as improving public transit accessibility, subsidizing low-emission vehicles, supporting active transportation infrastructure, or discouraging high-emission vehicle use would be far more impactful than interventions targeting lower-emission lifestyle categories.

### 3. Average Monthly Carbon Emissions Within the Selected Lifestyle Category

This bar chart presents a breakdown of carbon emissions across the specific subgroups of whichever lifestyle category the user selects. While Visualization 2 shows which lifestyle categories are most strongly associated with overall emissions, this visualization reveals how much variation exists within each category. For example, Primary Transportation Mode displays notable variation: individuals who rely on private vehicles have meaningfully higher emissions than those who walk, bike, or use public transit, pointing to clear opportunities for targeted behavior change within this category. In contrast, other categories such as Social Activity Frequency show relatively minor differences between subgroups, implying that modifying behaviors within these domains would have a far smaller impact on emissions. These contrasts highlight the importance of identifying which lifestyle behaviors contain meaningful internal variation—because encouraging movement toward lower-emission subgroups in those categories can yield more substantial reductions than attempting to intervene in areas where subgroup differences are minimal.

---

## Design Rationale

The dashboard integrates three visualizations to provide a multi-layered understanding of individual consumption patterns and their relationship to carbon emissions.

1. **Scatterplot**: The scatterplot was chosen to contextualize individual lifestyle emissions within broader economic patterns. Although income and spending are continuous variables, the scatterplot best showcases their relationship and highlights the baseline level of consumption that persists regardless of income. This visualization establishes an important economic foundation for the dashboard: it reminds viewers that consumption is deeply tied to structural and socioeconomic conditions, not just behavioral choice. Including a trend line further clarifies this relationship by revealing how consumption increases with income but at a diminishing rate, which helps frame later discussions about the role of personal behavior versus economic constraints.

2. **Heatmap**: The heatmap aggregates each lifestyle feature into a single average carbon emission value, allowing viewers to quickly compare which aspects of daily life contribute most to carbon output. A heatmap was selected instead of a bar chart or table because color encoding makes relative differences among features more visually intuitive and reduces cognitive effort. Sorting the features by decreasing emissions further strengthens interpretability, highlighting high-impact behaviors such as vehicle type or driving distance. This design choice supports high-level policy or intervention analysis by showing where the largest carbon reductions are theoretically achievable across lifestyle domains.

3. **Bar Chart**: A bar chart was used because it clearly displays variation within a single behavioral category and allows for easy comparison of subgroup emissions. This design enhances the interactivity of the dashboard by letting users select a specific lifestyle behavior and immediately observe how its subgroups differ. The chart reveals where meaningful internal variation exists, such as in primary transportation mode, where private vehicle users emit far more than public transit users, and where subgroup differences are minimal, such as in social activity frequency. Including this level of detail helps viewers assess whether personal behavioral interventions should target entire lifestyle categories or focus on specific subgroups where the largest emission reductions are possible.

---

## Citations

Robertts, D. (n.d.). U.S. Personal Expenditures by State 1997–2019 [Data set]. Kaggle. https://www.kaggle.com/datasets/davidbroberts/us-personal-expenditures-by-state-19972019?resource=download

Kabir, S. (n.d.). Average Income and Rent in the United States [Data set]. Kaggle. https://www.kaggle.com/datasets/shahriarkabir/average-income-and-rent-in-united-states

Petit, A. (n.d.). U.S. Population by State [Data set]. Kaggle. https://www.kaggle.com/datasets/alexandrepetit881234/us-population-by-state

Duman, M., Yıldız, B., Baytar, H., Bayindir, E., & Gulasar, S. (n.d.). Individual Carbon Footprint Calculation [Data set]. Kaggle. https://www.kaggle.com/datasets/dumanmesut/individual-carbon-footprint-calculation