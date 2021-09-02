## For AAAI paper
----
The processing FewFC data for 《What the role is vs. What plays the role:
Semi-supervised Event Argument Extraction via Dual Question Answering》 (the argument extraction process data and the role recognition process data).

* First divide the FewFC data into train/dev/test at a ratio of 8:1:1 (only part of it at the time)
* Leave 0.6 of the train data as unlabeled set
* Use the data of 0.01/0.05/0.1 train as the labeled set

The data division of ACE is the same as the above process.
* After processing with [ace2005 preprocessing tools](https://github.com/nlpcl-lab/ace2005-preprocessing), use the divided train/dev/test
* Leave 0.6 data in train as unlabeled set
* Use the data of 0.1/02/0.4 as the labeled set
* Since ACE 2005 dataset is not free, no relevant data is attached here.
