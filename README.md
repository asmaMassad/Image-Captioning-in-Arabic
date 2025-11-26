# Arabic Caption Generation for Images Using Transfer Learning

In this work we addressed the Arabic image captioning
task, by developing two approach for the task and comparing
their results.

The first approach was fine-tuning a general pretrained
GPT2 Arabic language model AraGPT2 for the task of image
captioning using native Arabic dataset. the other Approach is
fine-tuning GPT2 general language model using the English
version of the dataset and then translating the English caption.
We also fine-tuned the same English caption architecture on
a much larger dataset (COCO) to inspect the effects of the
dataset size on the fine tuning process.

The results showed that with the small dataset, the native
Arabic model outperformed the translated captions from the
English model. However, the translated captions from the
COCO model outperformed the other models, which shows
that fine-tuning a model on a large English dataset and then
translate the caption with machine translation is a viable
option.

We also concluded that the task of image captioning needs
its own unique evaluation metrics that reflects the task requirement
