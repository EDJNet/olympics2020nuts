
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Medalists at the 2020 Summer Olympics - Wikidata & NUTS

<!-- badges: start -->

<!-- badges: end -->

In this repository you can find a dataset based with details about
medalists at the 2020 Summer Olympics extracted from Wikipedia and
Wikidata. When place of birth for a medalist was available, additional
data have been included about the NUTS 2 or NUTS 3 region where they
were born (relevant for European countries that are [covered by
NUTS](https://ec.europa.eu/eurostat/web/nuts/nuts-maps)).

The following files should be of most interest:

  - [medalists\_all.csv](medalists_all.csv): the main file, including
    all available data
  - [medalists\_nuts\_only.csv](medalists_nuts_only.csv): only medalists
    with a place of birth available in Wikidata, and located within a
    NUTS region
  - [medalists\_missing\_place\_of\_birth.csv](medalists_missing_place_of_birth.csv):
    table with all medalists with no recorded data of birth in Wikidata
    (you are welcome to contribute to reduce the size of this table by
    adding the relevant information to Wikidata if it publicly
    available).
  - [medals\_per\_million\_residents\_in\_nuts2.csv](medals_per_million_residents_in_nuts2.csv):
    a possible way to look at the data

You can find the script used to generate this dataset in the file
`index.Rmd`, or you can look at the [rendered version with
comments](https://edjnet.github.io/olympics2020nuts/).

For some early results based on this dataset, see:

  - [Ranking European regions by Olympics
    medals](https://www.europeandatajournalism.eu/eng/News/Data-news/Ranking-European-regions-by-Olympics-medals)
  - [The data you need to win the Olympics if you go
    NUTS](https://medium.com/european-data-journalism-network/the-data-you-need-to-win-the-olympics-if-you-go-nuts-6d03b9df34e6)

## Summary statistics and update status

Total medalists: 1 270 Total medalists with place of birth recorded in
Wikidata: 1 087 Total medalists with place of birth recorded in a NUTS
region: 406

Last updated: 2021-08-04 20:51:28

## Credits

This dataset has been generated by Giorgio Comai (OBCT/CCI) within the
scope of [EDJNet](europeandatajournalism.eu/), the European Data
Journalisn Network. It is released under a CC-BY license (Giorgio
Comai/OBCT/EDJNet)
