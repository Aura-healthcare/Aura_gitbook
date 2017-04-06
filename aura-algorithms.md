# Aura Algorithms

Epilepsy seizure prediction is a very wide challenge. In 2017, International League Against Epilepsy revised an expanded ~30 seizure types classification\[1\]. In addition, each patient physiological response to epilepsy seizure is unique.

Our approach is to learn incrementally to detect patient specific patterns corresponding to seizure pre-ictal phase. To do so we will rely on data science recent development in Supervised learning algorithms. Recurrent neural networks and especially LSTM networks algorithms have shown outstanding performance on multiples applications such as speech recognition or automatic image captioning. very well  to multi-label time series classification\[2\].

## Training Phase

![](/assets/auraalgorithmstrainingarchitecture.png)

#### Monitoring Phase

![](/assets/auraalgorithmsmonitoringarchitecture.png)

## Algorithm evaluation

We will use 3 metrics to assess the performance of epilepsy seizure prediction algorithms:

* seizure prediction sensitivity
* number of false prediction
* time interval between seizure prediction alert and seizure onset

## Source Code

The Aura Algorithm source code will be soon distributed under GPL license and available on **Github.**

## References

\[1\] Robert S. Fisher, J. Helen Cross, Jacqueline A. French, Norimichi Higurashi, Edouard Hirsch, Floor E. Jansen, Lieven Lagae, Solomon L. Moshe, Jukka Peltola, Eliane RouletPerez, Ingrid E. Scheffer, and Sameer M.Zuberiobert  -** Operational classification of seizure types by the International League Against Epilepsy: Position Paper of the ILAE Commission for Classification and Terminology. **_Epilepsia, 1–9, 2017_

