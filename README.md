# World Happiness Analysis

## Project Overview
This project analyzes the factors that influence happiness levels around the world using data from the World Happiness Report (2015-2019). Through a combination of data analysis and visualization, the project explores the relationships between happiness scores and various socioeconomic factors across 155 countries.

![World Happiness Map](images/World_map.jpeg/800x400.png?text=World+Happiness+Distribution)

## Live Demo
View the analysis as an interactive web page: [World Happiness Analysis](https://github.com/yourusername/World-Happiness-Analysis)

## Key Findings

The analysis revealed several important insights about global happiness:

- **Economic prosperity matters**: GDP per capita shows a strong positive correlation with happiness, though the relationship is not perfect.
- **Health is crucial**: Life expectancy emerged as another strong predictor of happiness.
- **Social connections**: Family and social support consistently correlate with higher happiness scores.
- **Regional patterns**: The Americas and Oceania show more consistent happiness levels across countries, while Europe and Asia display greater variations.
- **Multi-dimensional nature**: Happiness is created through a complex interplay of conditions including economic prosperity, health, social bonds, personal freedoms, and good governance.

## Data Source
This analysis uses data from the World Happiness Report spanning 2015-2019. The World Happiness Report is released annually by the United Nations Sustainable Development Solutions Network and measures happiness based on the Cantril ladder question, where respondents rate their current lives on a scale from 0 to 10.

The dataset includes several key variables:
- Happiness Score (0-10 scale)
- GDP per Capita
- Social Support (Family)
- Life Expectancy
- Freedom (Perceived freedom of choice)
- Generosity (Charitable donations)
- Trust in Government (Absence of Corruption)

## Methodology
The analysis followed these steps:
1. Data collection and preprocessing from multiple yearly datasets (2015-2019)
2. Exploratory data analysis to understand the distribution of happiness scores
3. Correlation analysis to identify relationships between variables
4. Trend analysis to track changes over time
5. Regional comparisons to understand geographic patterns
6. Case study comparison of Finland vs. Canada

## Directory Structure
```
World-Happiness-Analysis/
├── index.html              # Main analysis page
├── images/                 # Visualization images
│   ├── GDP_vs_Happiness.png
│   ├── Health_vs_Happiness.png
│   ├── family_vs_happiness.png
│   ├── freedom_vs_happiness.png
│   ├── trust_vs_happiness.png
│   ├── generosity_vs_happiness.png
│   ├── finland_vs_canada.png
│   ├── Regional_analysis.png
│   ├── Happiness_score_distribution.png
│   └── Happiness_score_trend.png
├── README.md               # Project documentation
└── data/                   # Data files (if included)
    └── world_happiness_data_2015_2019.csv
```

## Technical Implementation
The analysis is presented as an interactive HTML page with the following features:
- Responsive design that works on desktop and mobile devices
- Side-by-side layout that pairs visualizations with explanations
- Highlight boxes to emphasize key insights
- Special note section discussing methodological limitations

## Limitations and Considerations
The README acknowledges important limitations of the World Happiness Report methodology:
- The report measures life satisfaction rather than emotional happiness
- Cultural biases may influence how people respond to happiness surveys
- When measured specifically on positive emotions, rankings can differ significantly from overall life satisfaction

## Future Work
Potential extensions of this project include:
- Incorporating more recent data (post-2019)
- Analyzing the impact of COVID-19 on global happiness trends
- Deeper exploration of within-country happiness variations
- Machine learning approaches to predict happiness scores

## Contact
For questions, collaboration opportunities, or further discussion, please contact:
- Venkatesh Shivandi: shivandi.v@northeastern.edu

## License
This project is available under the MIT License - see the LICENSE file for details.

## Acknowledgements
- World Happiness Report for providing the data
- Gallup World Poll for collecting the survey responses
- All the researchers contributing to our understanding of well-being across cultures
