Pre-trained transformer models like BERT have achieved state-of-the-art performance on a wide 
range of downstream NLP tasks, including sentiment classification, paraphrase detection, and semantic textual similarity.
However, despite their impressive performance, these models are not without their limitations. One
key issue is that they are highly prone to overfitting to the training data due to the high complexity of
pre-trained models and aggressive finetuning, which can lead to poor generalization to new, unseen
examples. This is especially problematic in scenarios where the training data is limited or biased.
To address this challenge, researchers have proposed various regularization techniques that aim to
encourage smoother and more robust model behavior. One such approach is smoothness inducing
adversarial regularization (SMART), which manages the complexity of the model by imposing smoothness
constraints on the model’s decision boundary using adversarial training.

We explore managing only the model's complexity via SMART. With a less complex model, we can finetune on each of the respective downstream tasks 
and explore using various combinations of finetuning on particular tasks.
