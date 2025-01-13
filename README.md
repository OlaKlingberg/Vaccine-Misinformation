# Vaccine Misinformation – A Twitter Pandemic

## Background
This project was developed for the course *Data Mining Project* (DTSA-5506), at University of Colorado Boulder.

## Description
The project investigates the dissemination of COVID-19 vaccine misinformation on Twitter (now renamed X) from December 1, 2020 till July 31, 2021.

## Data Source
The data comes from the study [ANTi-Vax: a novel Twitter dataset for COVID-19 vaccine misinformation detection](https://www.sciencedirect.com/science/article/pii/S0033350621004534?via%3Dihub) and can be accessed from [github.com/sakibsh/ANTIVax](https://github.com/sakibsh/ANTiVax).

## Key features
* **Topic Modeling**: Applies **Latent Dirichlet Allocation (LDA)** to identify and compare prevalent topics in tweets containing misinformation versus those without.
* **Network Analysis**: Constructs and analyzes a network of the main spreaders of vaccine misinformation to understand their influence and reach.

## Key Results
### Topic modeling
Out of the nine topics identified in the misinformation tweets, seven included *experimental* among their salient terms, indicating the degree to which the idea that the vaccines were experimental dominated the misinformation.

[Misinformation topics](https://github.com/user-attachments/assets/8638cbed-3c84-49f9-9936-93a1f31c3704)

Out of the five topics identified in the tweets not containing misinformation, three had *worry* among their salient terms.

![Non-Misinformation topics](https://github.com/user-attachments/assets/69da75a3-5501-497b-be25-4c24c19d7326)

### Network analysis
Using a custom metric to calculate misinformation impact, the network analysis shows that the 15 most impactful misinformers together represented just over 50% of the total misintormation impact represented in the dataset.
![Pareta Chart of Misinformer Impact](https://github.com/user-attachments/assets/f18ce6e1-a4ce-41f5-9152-bdc9299cf723)

## Repository Content
* [Vaccine Misinformation - A Twitter Pandemic. Report](https://olaklingberg.github.io/Vaccine-Misinformation/Vaccine%20Misinformation%20%E2%80%93%20A%20Twitter%20Pandemic.%20Report.pdf)
* [Vaccine Misinformation - A Twitter Pandemic. Slide Presentation](https://olaklingberg.github.io/Vaccine-Misinformation/Vaccine%20Misinformation%20%E2%80%93%20A%20Twitter%20Pandemic.%20Presentation.pdf)
* Images linked to from the report:
  * [Topics in tweets containing vaccine misinformation - Intertopic Distance Map](https://olaklingberg.github.io/Vaccine-Misinformation/visualized_clusters_2024-12-10_0008.html)
  * [Topics in tweets NOT containing vaccine misinformation - Intertopic Distance Map](https://olaklingberg.github.io/Vaccine-Misinformation/visualized_clusters_2024-12-10_0048.html)
  * [Network graph over the main misinformers](https://olaklingberg.github.io/Vaccine-Misinformation/retweeter_network_2024-12-08_2047.html)
