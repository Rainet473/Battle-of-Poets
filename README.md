# Battle-of-Poets
Built two poem generators using two different model architectures of NLP. You can access the notebook for Kaggle. [(Battle of Poets)](https://www.kaggle.com/code/arijeetpramanik/battle-of-poets?scriptVersionId=138264319).
* The objective of this poem was to understand the implementation of Sequence Models and Pytorch.
* Both the models seem to perform equally well in generating poems.
* The transformer architecture was modified by using only the encoder part of the model for generation.
* The networks were shallow and trained on a small dataset and hence wasn't that good in reaching human-level performance. However, it is still able to figure the patterns of a poem by going through 500 poems.
* The model was also trained on a bigger dataset (containing 2000 poems). It seemed that it was able to use correct grammar in that case. (However This is not shown in the notebook)

