# Food Hygiene
This project has effectively examined data on food hygiene ratings from the UK Food Standards Agency to aid the editorial team of "Eat Safe, Love", a food magazine, in identifying potential establishments for upcoming articles. The analysis encompassed three primary phases:


Within this segment, the project established a MongoDB database named "uk_food" and a corresponding collection named "establishments" to manage the supplied data. This procedure entailed importing data from the "establishments.json" file and ensuring the correct configuration of the database. Essential libraries such as PyMongo and Pretty Print (pprint) were imported, and the "establishments" collection was made ready for further analysis.


This section encompassed executing precise database adjustments as per the magazine editors' directives. These alterations comprised the inclusion of a new halal restaurant, "Penang Flavours," situated in Greenwich, updating its BusinessTypeID, eliminating establishments under the Dover Local Authority jurisdiction, and converting selected numeric values stored as strings into their numerical counterparts.


In the exploratory analysis section, we tackled a range of inquiries posed by Eat Safe, Love, aimed at assisting them in making well-informed decisions regarding the establishments to highlight in their articles. This process encompassed pinpointing establishments with particular hygiene scores, identifying top-rated establishments within the London area, ascertaining the highest-rated establishments in proximity to "Penang Flavours," and tabulating the count of establishments with a hygiene score of 0 within each Local Authority region.

# References
UK Food Standards Agency. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB. Contains public sector information licensed under the Open Government Licence v3.0.
