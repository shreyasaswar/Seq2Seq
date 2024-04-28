# Seq2Seq
Recreating the model from the paper -  Sequence to Sequence Learning with Neural Networks

# English to Chinese Translation with Sequence to Sequence Learning

This repository contains an implementation of the Sequence to Sequence (Seq2Seq) model for machine translation, as introduced in the paper **"Sequence to Sequence Learning with Neural Networks"** by Ilya Sutskever, Oriol Vinyals, and Quoc V. Le. The model is trained on a dataset of English and Chinese parallel sentences.

## Introduction

The Seq2Seq model is a type of encoder-decoder architecture, where the encoder encodes the input sequence (in this case, an English sentence) into a fixed-length context vector. The decoder then generates the output sequence (a Chinese translation) one token at a time, using the context vector and the previously generated tokens.

This implementation is a step-by-step recreation of the model described in the paper, with some modifications to accommodate the English-Chinese language pair and to improve training efficiency.

## Dataset

The model is trained on a dataset of parallel English and Chinese sentences. The dataset used in this implementation is a subset of a larger corpus, containing approximately 30,000 sentence pairs.

## Implementation

The implementation is provided in the form of a Jupyter Notebook, which guides you through the entire process of data preparation, model construction, training, and evaluation.

To get started, simply open the `seq2seq_translation.ipynb` notebook in your preferred Jupyter environment. The notebook contains detailed explanations and code for each step, making it easy to understand and follow along.

## Results


After training the model on the English-Chinese dataset for a limited number of epochs, the results are not satisfactory. The model struggles to generate accurate and fluent Chinese translations from English input sentences. However, it is important to note that this is a baseline implementation, and with further training, hyperparameter tuning, and architectural modifications, the performance can be significantly improved.
It is recommended to manually inspect the generated translations to assess their quality and identify areas for improvement. Additionally, training the model for more epochs and employing hyperparameter tuning techniques are expected to lead to better results.

## Future Work
This implementation serves as a baseline for further exploration and improvements in the field of neural machine translation. Some potential future work could include:

Experimenting with more advanced Seq2Seq architectures, such as attention mechanisms or transformer models.
Incorporating techniques for handling rare or unknown words more effectively.
Exploring different hyperparameter configurations and optimization strategies.
Training the model for more epochs and employing hyperparameter tuning techniques.
Training the model on larger datasets to improve translation quality.

By addressing these aspects, the performance of the English-to-Chinese translation model can be significantly enhanced, leading to more accurate and fluent translations.

## References

- Sutskever, I., Vinyals, O., & Le, Q. V. (2014). Sequence to sequence learning with neural networks. In Advances in Neural Information Processing Systems (pp. 3104-3112).
- https://huggingface.co/datasets/larryvrh/WikiMatrix-v1-En_Zh-filtered?library=true 

## License

This project is licensed under the [MIT License](LICENSE).
