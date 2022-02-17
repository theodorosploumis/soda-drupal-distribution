## Basic terminology

- **SODA**: 
The [Drupal installation profile](https://www.drupal.org/developing/distributions). 
Some times you may find it as *Soda Profile* also.

- **Open Data**: Please check on [Wikipedia](https://en.wikipedia.org/wiki/Open_data).

- **Dataset**:
SODA's main goal is to collect, manage and distribute open data. Each collection of data is reffered as a Dataset. 
A dataset may be for example a collection of statistics about road traffic, a list of books, a map of school 
locations etc. In Soda, Datasets are simply ```Contect types``` (of entity Node) that 
have been exposed through the REST API and Drupal's interface to public.

- **Dataset fields or Fields**:
Datasets should have fields and fields keep data. For example, a Dataset with traffic data may have fields such as 
ID, timestamp of the log, location etc.

- **Dataset item or Data item or simply Item**:
The individual (unique) piece of data of a Dataset. Many data items create a Dataset.

- **REST API**:
Please check on [Wikipedia](https://en.wikipedia.org/wiki/Representational_state_transfer). Soda offers an extensible REST API for its Datasets.
