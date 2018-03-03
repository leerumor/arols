Adaptive recommendation based on Online Learning Style
========

AROLS is an open source platform for adaptive online learning. Quickly register or create your own courses to simplify everyone's study with our powerful, intelligent recommendation engine.

AROLS project uses the [OULAD](https://analyse.kmi.open.ac.uk/open_dataset) dataset, analysis learners' log data and make dynamique recommendations. The source file of AROLS are composed by following folders:
* Preprocessing: agragate raw log data.
* Clustering: clean and normalize data, then use Kmeans, Birch and other clustering algorithm to cluster learners based on their online learning style.
* CF-AROLS: make recommendations to a cluster of learners by applying colloaborative filtering and association rules.
* LSTM-AROLS: make recommendations to a cluster of learners by generating a deep artificial network based on LSTM.


AROLS WEB
========
For more information, see [AROLS WEB](https://github.com/leerumor/arolsweb).
