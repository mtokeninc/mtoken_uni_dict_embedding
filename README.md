# mtoken_uni_dict_embedding 

# Introduction
This repo contains some common utilities to construct universal words dictionary and words embedding from universal words dictionary.

## Background
Traditionally, a single large language model (LLM) works for one or some set of languages. As the international interaction and communication evolve in a commonplace pace, build a universal word dictionary or aggregate all languages into a single language book, seems could be a logical alternative way to fill the changing language gaps.

Given a concrete example:

In Cantoness (Spoken at HongKong, Maucau and Guangdong in China), when people send greetings and ask "if you have had lunch yet?"

Can present it as the following forms:

1. 你 食 咗 個 午 餐 未 (Cantoness)
2. 你 食 咗 lunch 未.  (Mix with Cantoness and English) 

With a single dictionary and properly words (Cantoness and English) embedding, in theory, get translate this case to pure Cantoness and English sentences after llm training.  
