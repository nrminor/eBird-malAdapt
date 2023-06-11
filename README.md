# eBird-malAdapt
Exploring signatures of maladaptation in areas of avian population decline.

The scripts in this repository are intended to accomplish the following goals:
1. Run bioinformatic processing on provided short-read sequence data in as robust and reproducible a manner as possible.
2. Use the `ebirdst` package to compile eBird trend raster data for your study species of interest.
3. Infer Fst, Tajima's D, and dN/dS in genome windows for each sample.
4. Compare these signatures of selection with eBird trends at a range-wide, continental scale.

These goals are in the service of testing the following hypotheses:
- eBird Trends estimates can be used as a proxy for local fitness.
- Populations in decline are, by definition, maladapted and displaced from their local fitness peaks.
- Maladapted populations experience stronger directional selection than well-adapted populations.
- This strong selection will leave signatures in the genome.

By estimating selection in the genome while estimating population trends for each sample's collection week and location, we can test the hypothesis that populations that are displaced from local fitness optima by environmental change evolve in response.