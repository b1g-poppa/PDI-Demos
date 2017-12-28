Commodities Extract Demo Created by David Hill

The purpose of this demo is to demonstrate how easily PDI can extract data from a Gzip file, transform it and then write to a database table.

The commodites data was sourced from Kaggle here: https://www.kaggle.com/unitednations/global-commodity-trade-statistics and is a dataset covers import and export volumes for 5,000 commodities across most countries on Earth over the last 30 years.

The remove nulls step also removes catgeory 48_paper_paperboard_articles_of_pulp_paper_and_board as it had invalid charatcers in some of the records.