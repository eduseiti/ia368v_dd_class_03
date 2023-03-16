# ia368v_dd_class_03
Third ia368v DD class ― Deep Learning reranking

Applying text (re)ranking over BM25 candidate retrievals, using miniLM model.

Using [this training dataset created from MS MARCO](https://storage.googleapis.com/unicamp-dl/ia368dd_2023s1/msmarco/msmarco_triples.train.tiny.tsv) and [this miniLM pretrained model](https://huggingface.co/microsoft/MiniLM-L12-H384-uncased) reached the nDCG@10 == 0.6615.