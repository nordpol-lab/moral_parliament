Replication code for the main analysis in the paper "Strategic Moralization in Parliamentary Debates".


The SWERIK Riksdag records data used for the analysis is available: https://github.com/swerik-project/riksdagen-records/releases#release-v1.4.2
The SWERIK Riksdag persons data used for the analysis is available: https://github.com/swerik-project/riksdagen-persons/releases/tag/v1.2.1

To parse the XML data and link the speeches with the applicable metadata to construct the full dataset used for the analysis, run data/create_dataset.py and make sure the data is placed under the data/ directory.

Running descriptives & Regression analysis: scripts/moralization_analysis.ipynb
