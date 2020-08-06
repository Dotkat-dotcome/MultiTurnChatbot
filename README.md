# sopro-chatbot-ws18/19
Project based on a simple Seq2Seq chatbot tutorial in pytorch

# Abstract 
<p> While many chatbots have been implemented to response input queries, the bots do not converse the way we humans do in real life. This project aims at modeling a neural chatbot that generates context-specific response trained by a movie corpus. The model was extended to memorize the context by storing the last conversation turns to compute attention, and to avoid non-informative,  generic  answers  by  changing  the  search  decoder  to  Maximum-Mutual  Information/IDFdecoder while re-ranking the result.  The performance of the chatbot was evaluated using unigram to 4-gram BLEU scores for each response of the bot. </p>
