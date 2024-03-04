# Biodiversity Data Analysis Project

## Overview

Welcome to my Biodiversity Data Analysis Project! This project explores biodiversity data, focusing on species conservation status and observed sightings in national parks over the past week. The journey encompasses clear scoping, data acquisition, exploration, and hypothesis testing, culminating in valuable insights for biodiversity conservation.

## Project Scope

The foundation of our success lies in the well-defined project scope. We articulate clear goals, delineate the project's purpose, and consider adaptable analytical steps. This serves as our guiding roadmap, accommodating unexpected discoveries and adjustments during the exploration.

## Getting Started

### Data Acquisition and Setup

1. Download biodiversity data from 'biodiversity.zip'.
2. Configure the Jupyter notebook directory for seamless analysis.

### Setting up Your Git Repository

Establish a Git repository for version control, collaboration, and efficient documentation.

### Data Loading

Load essential data from 'species_info.csv' and 'observations.csv' to lay the groundwork for exploration.

## Data Exploration

### Explore and Explain Data

Delve into the data using descriptive statistics and visual examinations to extract valuable insights, patterns, and communicate findings through engaging visualizations.

## Analysis Highlights

1. **Joined Datasets on Scientific Name:**
   - Merged datasets for comprehensive analysis.

2. **Tidied Dataset:**
   - Filled null conservation status values for consistency.

3. **Filtered Data:**
   - Focused on endangered and threatened species for targeted analysis.

4. **Hypothesis Testing:**
   - Conducted chi-square tests of independence to assess relationships.

Mammals vs. Birds
χ² = 1.50
p = 0.21
φ = 0.90

Mammals vs. Fish
χ² = 17.72
p < .001
φ = 0.89

Mammals vs. Amphibians
χ² = 11.07
p < .001
φ = 0.91


## Conclusions

Mammals are Frequently Observed:
The data highlights a substantial prevalence of mammalian sightings, potentially influenced by the volume and size of species like the Northern Long-Eared Bat and Grizzly Bear.

Chi-Square Tests Reveal Significance:
Chi-square tests of independence indicate statistically significant associations between conservation status and species categories (mammals, birds, fish, amphibians).

Consideration for Less Visible Species:
While charismatic megafauna like Grizzly Bears attract attention, the analysis emphasizes the need to include less visible species in conservation efforts for a comprehensive approach.

Holistic Conservation Approach:
A call to action is made to parks and conservation agencies to adopt a holistic approach, safeguarding both conspicuous and inconspicuous species. This balance contributes to ecosystem resilience and sustainability.

Documentation and Collaboration are Key:
Establishing a Git repository not only ensures version control but also fosters efficient collaboration and documentation, vital aspects of successful data projects.

Transparency and Interpretation are Essential:
Transparency in the analytical process and thoughtful interpretation of findings contribute to a richer understanding of biodiversity dynamics and inform effective conservation strategies.

## Contributing

We welcome contributions and feedback! If you find any issues or have ideas for enhancements, please feel free to contribute.
