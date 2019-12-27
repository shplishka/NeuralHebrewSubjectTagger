
Neural Hebrew Subject Tagger
=================================
|LICENCE|

In this project, we focused on the analysis of Hebrew sentences, with the overall purpose
of researching and developing a unique model capable of identifying the subject in
sentences. Identifying a subject is quite complex, on the one hand, and of great
importance, on the other. Among the many important benefits that can be gained from
such a system is the ability to optimize systems of categorization, summarization and
translation.
To tackle this task, we used deep learning technologies and research methods. After

researching, we built models from three types of complex neuronal networks -- Bi-
LSTM, LSTM and GRU -- with the model architecture being Seq2Seq combined with Attention Mechanism. For Word Embedding we used Word2Vec.

The results of the study achieved a high percentage of success. In terms of model fit and
Loss function, Bi-LSTM with Attention showed 97.65 percent matching results, the
LSTM model with Attention presented 0.82 and the GRU with Attention 0.98 percent.
These results were significantly superior to classical models that exist today in the field.

Links
-----

Corpus:
https://github.com/NLPH/SVLM-Hebrew-Wikipedia-Corpus/blob/master/SVLM_Hebrew_Wikipedia_Corpus.txt

Paper:
https://github.com/NLPH/SVLM-Hebrew-Wikipedia-Corpus/blob/master/Phonemes_freqency_Silber-Varod-Latin-Moyal.pdf


License
-------

As it was generated from Hebrew Wikipedia sources, which are licensed under the `CC-BY-SA 3.0`_  license, this corpus is thus also necessarilly licensed under the same license.

.. _CC-BY-SA 3.0: https://creativecommons.org/licenses/by-sa/3.0/

|LICENCE| image:: https://github.com/NLPH/SVLM-Hebrew-Wikipedia-Corpus/blob/master/License-CC-BY-SA-3.0-blue.svg
  :target: https://github.com/NLPH/SVLM-Hebrew-Wikipedia-Corpus/blob/master/LICENSE
