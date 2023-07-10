# MT23challengeCodalab

This repository contains all the files needed to create a competition in Codalab as in July 2023. The files need to be zipped and the zip can be uploaded to Codalab. Notice that this repository does not contain the test sets used in the competition, they are included as empty files.

The competition [MT2023@UdS, guc2esp Translation](https://codalab.lisn.upsaclay.fr/competitions/14480) run from July to September 2023 and it is still open for comparison purposes.

## MT2023@UdS, guc2esp Translation

### Way&uacute;unaiki to Spanish translation

<p>Way&uacute;unaiki is the native language spoken in the Way&uacute;u community, located in the Caribbean region connecting Colombia and Venezuela, where the language coexists with Spanish. In this challenge we want to create translation resources for the Way&uacute;u community.</p>

#### The shared task

<p><strong>Phase I, development</strong>: We provide training data extracted from the Tatoeba challenge [1,2]. It mostly belongs to the relogious domain. We substracted a set from the original Tatoeba corpus: the in-domain test set that is going to be used for evaluating your MT engine in this phase. Together with the parallel corpus we provide, you can use any other data you can find to train your MT engine, but please, don&#39;t use the original Tatoeba corpus which would also contain the test set. Upload the translation into Spanish of the test set to Codalab. The translation will be evaluated using BLEU, TER, chrF and COMET. chrF is the official evaluation metric of the challenge.</p>

<p><strong>Phase II, evaluation</strong>: We provide an out-of-domain test set (general domain) in Way&uacute;unaiki and you will have a week to upload its translation into Spanish to Codalab. The translation will be evaluated using BLEU, TER, chrF and COMET but only chrF is the official evaluation metric of the challenge. Notice that the best system in an in-domain test set is not necessarily the best system in a general domain.</p>

#### References & Inspirations
<p>[1] J&ouml;rg Tiedemann. 2020. The Tatoeba Translation Challenge &ndash; Realistic Data Sets for Low Resource and Multilingual MT. In Proceedings of the Fifth Conference on Machine Translation, pages 1174&ndash;1182, Online. Association for Computational Linguistics.</p>
<p>[2] <a href="https://github.com/Helsinki-NLP/Tatoeba-Challenge">https://github.com/Helsinki-NLP/Tatoeba-Challenge</a></p>
<p>[3]&nbsp;Barry Haddow, Rachel Bawden, Antonio Valerio Miceli Barone, Jindřich Helcl, and Alexandra Birch. 2022.&nbsp;<a href="https://aclanthology.org/2022.cl-3.6">Survey of Low-Resource Machine Translation</a>.&nbsp;<em>Computational Linguistics</em>, 48(3):673&ndash;732.</p>
<p>[4]&nbsp;<a href="https://www.statmt.org/wmt22/translation-task.html">https://www.statmt.org/wmt22/translation-task.html</a></p>
<p>[5] <a href="https://turing.iimas.unam.mx/americasnlp/2023_st.html">https://turing.iimas.unam.mx/americasnlp/2023_st.html</a></p>

