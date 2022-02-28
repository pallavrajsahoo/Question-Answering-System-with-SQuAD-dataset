# Question-Answering-System-with-SQuAD-dataset

We will train our NLP models on the Stanford Question Answering Dataset (SQuAD), a reading comprehension dataset with more than 100,000 questions. SQuAD was one of the first with a public leaderboard and thus was able to garner a large amount of research result and publicity towards itself. Questions in the dataset can be answered from the context that accompanies them, without requiring any domain-specific knowledge; thus they belong to the class of single-hop question answering problem.

Here's an example of what our model will do: given a question,

    When did Beyonce start becoming popular?

and a block of text containing the answer, called the context,

    Beyoncé Giselle Knowles-Carter (/biːˈjɒnseɪ/ bee-YON-say) (born September 4, 1981) is an American singer, songwriter, record producer and actress. Born and raised in Houston, Texas, she performed in various singing and dancing competitions as a child, and rose to fame in the late 1990s as lead singer of R&B girl-group Destiny's Child. Managed by her father, Mathew Knowles, the group became one of the world's best-selling girl groups of all time. Their hiatus saw the release of Beyoncé's debut album, Dangerously in Love (2003), which established her as a solo artist worldwide, earned five Grammy Awards and featured the Billboard Hot 100 number-one singles "Crazy in Love" and "Baby Boy".

our model will be able to extract the answer from this context, which is ```in the late 1990s ```
