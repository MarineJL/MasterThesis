# Master Thesis: How to predict the hit potential of a song?


Every week, thousands of songs are released on the market, but only a small fraction of those encounters great and popular success. Foster by the streaming platforms which revolutionized music consumption in less than a decade, the competition is harsh.

This master thesis aims at predicting the hit potential of a song. Based on data related to audio and meta contents exported from Spotify web API, I first focus on understanding how music has evolved over time and the analysis of the predictor variables. I then work on a classification problem, test and compare a set of algorithms depending on defined performance criteria to find the best model.
In this master thesis, I developed my own coding notebooks in both R and Python to perform ETL (extract, transform, load), text analysis and predictive modeling.

From the ever-changing business model, to the unprecedented influence of rap and hip-hop movements, this paper demonstrates that it is possible to successfully respond to listeners changing tastes, trends and innovation, using Data Science.
Being able to perform accurate predictions is a must at a time when music consumption relies on individual behaviors and recommendation systems.

Keywords: Predictive modeling, Data Science, Machine Learning, Data Analytics, Classification, R, Python, Music Industry, Streaming


I – Introduction .................................................................................................. 6

II – State of play of the music industry................................................................ 8
II.1 – History of the music industry: from phonograph to streaming ..................................... 8
II.1.1 - A serie of innovations ...................................................................................................8 II.1.2 - The growing challenge of online music piracy ..............................................................9 
II.1.3 - Streaming dominates the music industry .....................................................................9
II.2- Freemium models: Spotify and the new actors............................................................ 10
II.2.1 - Freemium model: a new way of consuming music.....................................................10 
II.2.2 - Spotify: the world’s biggest music streaming platform ..............................................12 
II.2.3 - A competitive business: Who run the market?...........................................................13 
II.2.4 - Which future for music industry? ...............................................................................14

III – Data collection........................................................................................... 17
III.1 - Data sources: which data are available? .................................................................... 17
III.1.1 - Different sources........................................................................................................17
III.1.2 - Choice of Spotify Data................................................................................................18
III.2 - Features to extract .................................................................................................... 20
III.2.1 - Definition of Spotify features: audio vs. meta ...........................................................20 
III.2.2 - Spotify for developers and API...................................................................................24

IV – How did hit songs evolve over time: Is there a hit song receipt? ................ 25
IV.1 – Features Analysis over the last 60 years ................................................................... 25
IV.1.1 – Objectives & Data collection.....................................................................................25 
IV.1.2 – Artists Analysis ..........................................................................................................25 IV.1.3 - Audio Features Analysis.............................................................................................29 
IV.1.4 - Lyrics Analysis ............................................................................................................39
IV.2 - Focus on the most played songs on Spotify ............................................................... 46
IV.2.1 - Objective & Data collection .......................................................................................46
IV.2.2 - Exploratory Analysis ..................................................................................................46
IV.3 - Results and discussions: Is there a hit-song recipe? What is a hit song?..................... 51

V – Methods..................................................................................................... 53
V.1 - A classification problem ............................................................................................. 53 
V.2 - Mathematical models ................................................................................................ 54 
V.2.1 - Logistic Regression......................................................................................................54 
V.2.2 - Stepwise Logistic Regression ......................................................................................55 
V.2.3 - K-Nearest Neighbors...................................................................................................57 
V.2.4 - Penalized regression...................................................................................................58
V.2.5 - Trees..................................................................................................................61 
V.2.6 - Random Forest ...........................................................................................................62

VI - Results ....................................................................................................... 65
VI.1 - Performance criteria ................................................................................................. 65 
VI.2 - Algorithm comparison .............................................................................................. 66

VII – Discussion ................................................................................................ 69
VII.1 - Business Applications............................................................................................... 69
VII.1.1 - Taste profiling ...........................................................................................................69
VII.1.2 - Innovative listening and discovery experiences .......................................................70
VII.2 - Toward a globalization of tastes and industry? ........................................................ 71
VII.2.1 - The seasonal effect...................................................................................................71 VII.2.2 - Unpredictable events ...............................................................................................72

Conclusion........................................................................................................ 74 

VIII – References............................................................................................... 76

Annex 1 : Tweets and Sentiments Analysis - R Script ............................................................... 78 
Annex 2: How to get data from Spotify - Python Notebook ..................................................... 83 
Annex 3: Principal Component Analysis on the most played songs dataset .............................. 87 
Annex 4: Lyrics Analysis - Python Notebook............................................................................ 96 
Annex 5: How to predict if a song will become a hit? - R Markdown ...................................... 104
