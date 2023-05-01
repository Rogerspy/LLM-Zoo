# LLM-Zoo

# Backbones

| Model        | Version                        | Open-source | Size           | Backbone    | <div style="width:65px">Training Data</div>                                                                                                                                                                                                                                                                     | Languages | Domain  | Demo                                | GitHub                                              | Huggingface                                                       | Paper                                      | Official Blog                                                                                          | Release Time |
| :------------: | :------------------------------: | :-----------: | :--------------: | :-----------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------: | :-------: | :-----------------------------------: | :---------------------------------------------------: | :-----------------------------------------------------------------: | :------------------------------------------: | :------------------------------------------------------------------------------------------------------: | :------------: |
| MOSS         | moss-moon-003-base             | Y           | 16B            | CodeGen     | <details><summary><b>Details</b></summary>100B Chinese tokens and 20B English tokens</details>                                                                                                                                                                                                                                        | zh, en    | General | [[link](https://moss.fastnlp.top/)] | [[link](https://github.com/OpenLMLab/MOSS)]         | [[link](https://huggingface.co/fnlp/moss-moon-003-base)]          | \-                                         | [[link](https://txsun1997.github.io/blogs/moss.html)]                                                  | 2023.4.21    |
| LLaMA        | llama-7b/13b/33b/65b           | Y           | 7B/13B/33B/65B | \-          | <details><summary><b>Details</b></summary>1T tokens (English CommonCrawl, C4, Github, Wikipedia, Gutenberg and Books3, ArXiv, Stack Exchange)</details>                                                                                                                                                                               | en        | General | \-                                  | [[link](https://github.com/facebookresearch/llama)] | [[link](https://huggingface.co/decapoda-research/llama-7b-hf)]    | [[link](https://arxiv.org/abs/2302.13971)] | [[link](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)]                             | 2023.02.27   |
| BloombergGPT | \-                             | N           | 50B            | BLOOM-style | <details><summary><b>Details</b></summary>363B financial datasets (web, news, filings, press, bloomberg) and 345B public datasets (PILE, C4, wikipedia)</details>                                                                                                                                                                     | en        | Finance | \-                                  | \-                                                  | \-                                                                | [[link](https://arxiv.org/abs/2303.17564)] | [[link](https://www.bloomberg.com/company/press/bloomberggpt-50-billion-parameter-llm-tuned-finance/)] | 2023.03.30   |
| Linly (伶荔)   | Linly-Chinese-LLaMA 7b/13b/33b | Y           | 7B/13B/33B     | LLaMA       | <details><summary><b>Details</b></summary>Chinese-English parallel corpora [[link](https://statmt.org/wmt18/translation-task.html#download)], Chinese Wikipedia, community interaction, news data [[link](https://github.com/CLUEbenchmark/CLUECorpus2020)], scientific literature [[link](https://github.com/ydli-ai/CSL)]</details> | zh        | General | \-                                  | [[link](https://github.com/CVI-SZU/Linly)]          | [[link](https://huggingface.co/P01son/Linly-Chinese-LLaMA-7b-hf)] | \-                                         | \-                                                                                                     | 2023.3.28    |
