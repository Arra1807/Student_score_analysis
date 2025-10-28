# Student_score_analysis
Dette er et søndagsprosjekt hvor jeg utforsker et datasett med både lineær og klassifikasjonsmodell. Mål er å undersøke hvordan faktorer som antall timer studert, søvntimer og oppmøteprosent påvirker elevers eksamensresultater.

Datasettet består av et visst antall elevers poengsum fra en prøve, samt relevante faktorer som kan påvirke prestasjonen. Datasettet ble hentet fra Kaggle, url: https://www.kaggle.com/datasets/grandmaster07/student-exam-score-dataset-analysis/data.

Projektet ble utført på google colab, og notebooken er tilgjengelig i repoet.

Notebooken består av databehandling, hvor jeg undersøker om mulige feil/manglende verider, og en enkel utforskende analyse. 
Modeller benyttet:
        Lineær regresjon - for å forutsi eksamenscore
        Random Forest-klassifikator - For å klassifisere karakterer (A-F)
Evaluering:
          MSE, R^2-score for regresjonsdelen
          Presisjon, recall,F1-score og confusion matrix for klassifikasjonsdelen.

Biblioteker brukt:
Pandas
Numpy
Scikit-learn 
Matplotlib

Andre verktøy:
Python 
Google Colab

Resultater:
Random Forest ga en moderat (~15%) for klassifiering.
Modellen forvekslet ofte midtre karakterer (B-E), noe som viser til overlapp i datasettet
Feature importance viste at hours_studied hadde størst innflytelse på resultatene.

Mulig videre arbeid:
Balansere datasettene for bedre klassedistribusjon,
utforske flere modeller,
Evt. optimalisere hyperparametere.

