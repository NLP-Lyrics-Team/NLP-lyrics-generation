## About us
We are two students of the MSc of *Engineering in Computer Science* of *Sapienza University of Rome* and this project has been developed as part of the *Data Mining 20-21 course*. Visit our *LinkedIn* profiles to learn more about us.

- [Ivan Fardin](https://www.linkedin.com/in/ivan-fardin-304a001a3/)
- [Claudiu Ivan](https://www.linkedin.com/in/claudiu-gabriel-ivan-835a33176/)

## NLP lyrics generation
Generate lyrics of multiple genres by exploiting the capacity of a generative neural network trained on a dataset consisting of thousands of real musical texts.

To achieve this goal, we decided to
- Build a various lyrics dataset made up of good quality texts
- Preprocess lyrics to remove non-English ones and to improve vocabulary size for better variability of text generation and model training
- Use pre-trained Word2vec word embedding to avoid misspellings and capture word contexts
- Develop an LSTM neural network because suitable for data sequences
- As a further step, we tried to implement a GAN and a WGAN to improve performance.

## Related Work
- [Long Short-term Memory](https://www.researchgate.net/publication/13853244_Long_Short-term_Memory#read)
- [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf)
- [Language Generation with Recurrent Generative Adversarial Networks without Pre-training](https://arxiv.org/pdf/1706.01399.pdf)
- [Generative Adversarial Networks](https://arxiv.org/pdf/1406.2661)
- [Wasserstein GAN](https://arxiv.org/pdf/1701.07875)
- [Learning with a Wasserstein Loss](https://arxiv.org/pdf/1506.05439)
- [Improved Training of Wasserstein GANs](https://arxiv.org/pdf/1704.00028v3.pdf)
- [Generative Adversarial Networks and Word Embeddings for Natural Language Generation](https://academicworks.cuny.edu/cgi/viewcontent.cgi?article=4093&context=gc_etds)
- [When Glove meets GAN: Adversarial Language Generation Using Dense Vector Embeddings](https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1184/reports/6908905.pdf)
- [End-to-End Differentiable GANs for Text Generation](http://proceedings.mlr.press/v137/kumar20a/kumar20a.pdf)
- [Training Language GANs from Scratch](https://arxiv.org/pdf/1905.09922.pdf)

## License
This project is licensed under the MIT License.
