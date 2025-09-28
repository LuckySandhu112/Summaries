20 AI concepts:-

1] LLM(Large language model):
A neural network that is trained to predict the next term of the of an input sequence.

Example:
Input: "All that glitters"   --->   Output: "is not Gold"


2] Tokenization:
The input text is broken into small tokens.

Example: All that glitters.
        |All| |_| |that| |_| |glitt| |ers|.


3] Vectorization:
The mapping(coordinates) of a word in a n dimensional space such that similar meaning words are all clustered together and opposite meaning words are somewhere far away.


4] Attention Mechanism:
It help to understand what a sentence really means. is sees the nearby words to understand what it means.

 Example:
   "Apple"
   1) Tasty apple          -> The apple that we eat
   2) Apple's revenue      -> The apple company
   3) The apple of my eyes -> a person who you love


5] Self supervised learning:
Instead of telling the model exactly what it needs to do, the input is like this that it know what it should do.

Example:         _
5...4...3...2...|_|                 _
What will be in |_|,,,, Most probably it should be 1, see the input is like this that you can predict what should be the next number, models also work as this by predicting what can come next.

eg: If we give an input of :
  All that glitters,,,, The model will complete the sentence by adding is not gold at the end of the line.


6] Transformer:
It takes the input tokens convert it into Attention block then to a neural network and then gives a bunch of outputs.


7] Fine tuning:
Question & answers
A neural network that is trained to predict the next token of an input sequence.

Example:
Who is the president of USA?
"Donald Trump" "I don't know"


8] Few shot prompting:
a technique for guiding AI models by including a small number of examples of the desired input-output format within the prompt itself, without updating the model's weights
Query --> LLM --> Response


9] Retrieval Augmented Generation:
An AI framework that enhances LLMs by combining them with external, up to date data sources.
    ____        ____
   |   Documents    |
Server -> Input -> LLM ---> High quality responses
   |____Examples____|


10] Vector database:
It stores and searches for vector embeddings, which are numerical representations of unstructured data like text, images, and audio.


11] Model context protocol:
an open, standardized way for large language models (LLMs) to interact with external data, tools, and services, enabling them to go beyond their training data to perform complex tasks.


12] Context engineering:
the practice of systematically structuring, selecting, and optimizing the information provided to a large language model (LLM) to improve its performance and ensure it can solve complex tasks


13] Agents:
long running process
user --> agent --> LLM
           |____--> external system


14] Reinforcement Learning:
A type of machine learning where an "agent" learns optimal behavior through trial and error by interacting with an "environment" to maximize cumulative rewards


15] Chain of thought:
Breaks the problem step by step

Example:
Question -> How many keystrokes are need to type the numbers 1 to 1000?
Answer ->one-digit numbers from 1 to 9 = 9
two-digit numbers from 10 to 99 = 90
three-digit numbers from 100 to 500 = 901
total digits = one-digit + two-digit + three-digit
total digits = 9 + 90(2) + 901(3) = 2892


16] Reasoning models:
A model that can figure out how to solve a particular problem step by step. also known as LRM's


17] Multi-modal models:
a type of Artificial Intelligence that can process, understand, and integrate different types of data, or modalities, simultaneously, such as text, images, audio, and video


18] Small language models:
AI language models with fewer parameters and simpler architectures than Large Language Models (LLMs)
as an example, if in SLM there are 3-30 million parameters, in LLM there will be 3-300 billion parameters


19] Distillation:
Process of making small language models


20] Quantization: 
a technique to reduce the precision of an AI model's parameters, typically by converting them from high-precision floating-point numbers to lower-precision integers or fixed-point numbers


