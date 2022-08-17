# Source Tracing: Detecting Voice Spoofing (Dataset)

## About the Dataset:
The dataset is built on the basis of [ASVspoof 2019 LA dataset](https://www.asvspoof.org/database). The dataset is aimed at training systems for classifying different spoofing attributes, representing  characteristics of different modules in the whole pipeline.

To make sure the attributes of all the methods in the evaluation are covered in the training set and there is no speaker overlap between these sets, we first divided all speakers in the LA dataset to two parts, one as training speaker set and the other for evaluation speaker set. For our evaluation set ,we choose the utterances from the evaluation set speakers with label bona fide, A01, A05, and A07 to form our evaluation set. And we select utterances with label A02-A04, A06, A08-A19 from the training set speakers and these speakers' bona fide utterances to form our training set. Note that the division will inevitably leave some utterances unused in the experiment. In this setup, our training set contains 67 speakers and 79620 utterances, while the evaluation set has 11 speakers and 5832 utterances. 


## File Description

1. train_spk.txt: id of speakers in the training set
2. eval_spk.txt: id of speakers in the eval set
3. train_utt.txt: id of utterance labels in the training set
4. eval_utt.txt: id of utterance labels in the eval set
