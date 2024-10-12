This is one of the 200 Concrete Open Problems in Mechanistic Interpretability highlighted by
Neel Nanda in one of his posts. The problem is about continuing common sequences in natural
language by the language model, but the sequence should not be present prior in the prompts.
Some common examples of sequences present in natural language are as follows:

● “1, 2, 3, 4, ” → completed by ‘5’

● “January, February, March, ” → completed by ‘April’

● “Alpha, beta, ” → completed by ‘gamma’

Now, the work I have done on this task is mostly centered around Edge Attribution Patching and
the corresponding computational graphs and scores related to GPT2-small. The second half of
the notebook is similar what Neel has done in case of IOI, I am doing activation patching and
checking the attention head pattern for the sequences. There is also the visualizations in case
of activation and attribution patching for the above task.
