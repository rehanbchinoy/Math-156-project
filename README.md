# text-generation-RNN
Final project for Math 156 (Machine Learning) at UCLA.

Inspired by Andrej Karpathy's blog post, "The Unreasonable
Effectiveness of Neural Networks", my team trained a
character-based RNN
model to simulate the works of classic literature, including
Homer's _The Odyssey_, and James Joyce's _Ulysses_.
You can find example snippets of output text in the
final report.

In addition to training the model, we 
modified key parameters of the model and evaluated the effect 
on the quality of the generated text. The modified
parameters include
batch size, epoch size, activation function,
and layer architecture.

The most interesting thing to me about this project is the
difference in performance between the GRU and the LSTM model.
I found it surprising that the GRU would outperform
the LSTM to such a high degree.
The superior performance of GRU over LSTM, besides potential
issues in optimizing initial parameters differently between
RNN’s, may be attributable to the fact that the training set
was both small, having only been trained on one novel,
and lengthy, given that Ulysses is composed of over
one million characters. Still, this is merely a hypothesis,
and as such remains an interesting open question that I 
hope to address in the future.