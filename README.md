# Personal-ChatGPT
Following Andrej Karpathy's "Let's build GPT: from scratch, in code, spelled out." youtube video, seen here: https://www.youtube.com/watch?v=kCc8FmEb1nY
Created a transformer network replicating the 'pre-training' stage of ChatGPT using data from Shakespearen works of literature.
This network outputs the next character (token) given a sequence of characters. This is slightly different from ChatGPT as its tokens are a chunk of characters/sub-words.
There is a lot of comments/notes in the code to provide the reader (and myself) a better understanding of the key components of this network.
Also attached is a text file of notes throughout building this network, that they didn't seem suitable for putting into the code and a pdf version of the .ipynb file for readability purposes.
Overall, the transformer has ~10 million parameters and outputs a training loss similar to that of GPT-2.
