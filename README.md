
## Migrant Equity Dashboard
Feel free to download this project and give it a run! Alternatively, open the 'Overview' PDF for a brief glance at the dashboard!

-Note reinitialized git repository, original project date early October 2024.

#### Goal and Motivation
According to the International Organization's Migration Report, in 2020 over 281 million people migrated internationally whether as a legal immigrant, illegal immigrant, refugee, or asylum seeker. Regulations on international migration are one of the primary policy concerns internationally, with many different camps arguing about the economic impacts, moral callings, and administrative aspects of international migration. The debate on internation migration has a heavy focus strictly on whether or not international migration should be accepted or supported, but it doesn't tackle one fundamental concern- the actual quality of the migration. Many migrants leave their origin countries hoping for a more secure and fruitful life, this dashboard aims to question whether or not this life is actually attainable for accepted migrants, by comparing indicators for education, poverty, employment, and literacy for foreign-born populations vs. native-born populations.

#### Data Overview
The Organization for Economic Co-operation and Development (OECD) is a coalition containing 38 member states, including the U.S., Mexico, Australia, and a majority of the EU, and is where the entirety of the data was sourced. The OECD conducts many efforts into producing publicly available data regarding global trade, economics, health, and in this case, immigration. This dashboard aims to use this data to enable the user to compare various statistics regarding the lives of foreign-born vs. native-born populations in OECD countries.

#### Methods
This dashboard has largely been constructed using the framework of HoloViz Panel, a dashboarding python module coupled with Plotly to create both interactive and visually appealing dashboards. The progam relies on two primary executable files, a main and a constructe API. The API file reads the necessary data from the excel files collected from the OECD, which is in turn used in the main file to construct pandas dataframes. These data frames serve as the source for the widgets and visualizations that comprise the dashboard.

