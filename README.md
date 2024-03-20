**Problem**

We are trying to create a multi-label classification model that uses ensemble techniques. A random forest is utilized and the purpose is to try and predict specific items based on a set of product features.

_Note_: Please use workbook model3.ipynb for the latest workß

**Results & Findings**

We have very low accuracy and our hamming and other metrics are unfortunately not within an acceptable range. There are more than 6k in potential results/labels which would need to be paired down. Also, there is a bunch of inconsistencies in the data even when doing preprocessing using known NLP cleaning techniques and tokenization through lemmatization.

**Next Steps**

Using something like RAG as suggested by our TA's would probably yield much better results. At the end of the day, this project requires a heavy amount of preprocessing as the data needs a lot of work.
