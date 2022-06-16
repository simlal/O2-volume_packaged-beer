# Exploration of relationship between dissolved oxygen (DO or O2) readings and packaged beer volume using test dataset of 3 different lots of beers from a Québec craft brewery using Kaggle cloud computational environment with a Jupyter notebook. 
---------
## The beers :

- [Notre Folie](https://siboire.ca/fr/boutique/bieres/3968024-notre-folie-100-qc/)
- [IPA Test #96](https://untappd.com/b/siboire-microbrasserie-ipa-test-96-citra-spectrum-citra-lupomax-citra/4847087)
- [Inspiration](https://siboire.ca/fr/boutique/bieres/213673-inspiration/)

## The measurements :
1. Weight of packaged beer : 
    Lab balance with 0.01 g readability
2. 3-minutes shaken DO readings of packaged using CBoxQC (Anton Paar; [CboxQC](https://www.anton-paar.com/us-en/products/details/cboxqc/)) and c-DGM (Haffmans; [c-DGM](https://foodandbeverage.pentair.com/en/products/haffmans-portable-optical-co2-o2-tpo-meter-c-dgm))

---

## The test dataset : 
.csv file from recorded data of 3 experiments with following template :
|Beer|Lot |Density (Plato)|weight (g)|O2 (ppb)|CO2 (vol/vol)|
|----|----|---------------|----------|--------|-------------|
|NF  |1670|     2,48      |   498,0  |   62,7 |     2,57    |

**test dataset fname : o2-vol-3beers-1668-1670-1671_full.csv**

## Useful information :
- Empty can weight (hard print) = 15.8 g
- -/+ 3% of labelled volume range for true volume of beer in package ([CFIA laws](https://inspection.canada.ca/exigences-en-matiere-d-etiquetage-des-aliments/etiquetage/industrie/exigences-en-matiere-d-etiquetage-des-boissons-alc/fra/1392909001375/1392909133296?chap=0))
- [Water density @ 20C](https://collett.atmos.colostate.edu/classes/AT560/2007/water-density.pdf) From Handbook of Chemistry

--- 

## Question
<code style="background:yellow;color:red">**Is there relationship between dissolved O2 levels and volume of beer in final package? Could we estimate O2 levels from volume of beer in package?**</code>
***
