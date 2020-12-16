# FewFC
* Few-shot Financial Chinese event extraction datase
--------
## Important
* In order to accelerate the research on few-shot event extraction, incremental event extraction and low resources event extraction, we introduce FewFC, a new Chinese Financial sentence-level event extraction
* dataset constructed from news reports on the Internet and announcements issued by listed companies.
  This data set is also used for [CCKS TASK 3 evaluation](https://biendata.xyz/competition/ccks_2020_3/).

--------
## Details

The data set contains 10 financial field event types and 8982 sentences.

> **Event_Definition.pdf**
>
> * Explains the definition of event types and event roles

> ### Rearranged Dataset
>
> > **train_base.json**
> >
> > * Training set from source domain with 5 event types.
> >
> > **test_base.json**
> >
> > * Test set from source domain.
> >
> > **train_trans.json**
> >
> > * Training set from target domain.
> >
> >  **test_trans.json**
> >
> > * Test set from target domain.
>
> ### Original Dataset
>
> * Data divided according to the CCKS evaluation
>
> > **train_base.json**
> >
> > * Training set from source domain in Phase I Evaluation. Same as train_base.json in rearranged dataset.
> >
> > **train_trans_2_type.json**
> >
> > * Training set from target domain with only 2 event types in Phase I Evaluation. Part of the train_trans.json in rearranged dataset.
> >
> > **dev_base.json**
> >
> > * Development set from source domain in Phase I Evaluation. Same as test_base.json in rearranged dateset.
> >
> > **dev_trans.json**
> >
> > * Developement set from target domain with only 2 event types in Phase I Evaluation. Part of the test_trans.json in rearranged dataset.
> >
> > **train_trans_5_type.json**
> >
> > * Training set from target domain with all 5 event types in Phase II Evaluation. Same as train_trans.json in rearranged dataset.
> >
> > **test_trans.json**
> >
> > * Test set from target domain with all 5 event types. Part of the test_trans.json in rearranged dataset.
> ### Partial Dataset
> * Data division used in the paper “**What the role is vs. What plays the role:Semi-supervised Event Argument Extraction via Dual Question Answering**”

---

## Cite

If you use the dataset or the code, please cite this paper:

```
@inproceedings{Yang2021,
  author    = {Yang Zhou and
               Yubo Chen and
               Jun Zhao and
               Yin Wu and
               Jiexin Xu and
               Jinlong Li
               },
  title     = {What the role is vs. What plays the role: Semi-supervised Event Argument Extraction via Dual Question Answering},
  booktitle = {Proceedings of AAAI-21},
  publisher = {{AAAI} Press},
  year      = {2021},
}
```
## License
Copyright: This data set is released by the nlp group of the Institute of Automation of the Chinese Academy of Sciences, collected by China Merchants Bank, licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).




