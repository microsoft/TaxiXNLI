# TaxiXNLI

This repository contains necessary data associated with the [Analyzing the Effects of Reasoning Types on Cross-Lingual Transfer Performance](https://aclanthology.org/2021.mrl-1.8/), published in [EMNLP 2021 Multilingual Representation Learning workshop](https://sites.google.com/view/mrl-2021/program?authuser=0).

1. `datav1.0.zip` contains the TaxiXNLI dataset:
  - For both diagnostic and translated experiments train file is same (`train.jsonl`)
  - translated test set: `test_translated.jsonl`
  - diagnostic test set: `test_diagnostic.jsonl` 
      1. "1" and "0" means an examples belongs and does not belong to the category respectively. 
      2. "-1" means we have not annotated it for that particular category. 
2. `keywords.txt`: 
    1. (not used in paper) A list of keywords specific to categories. This was used to see if the equivalent words between English and target languages aligns better after few-shot training. 
3. `sentences.txt`: 
    1. Set of sentences, sampled from the translated data (in all languages) 
    2. This is used to check if the sentences are aligned better after the few-shot training. 
4. `original/`: This folder contains Hindi, Spanish and Swahili annotations of translated P-H pairs on a small subset of the Translated data.

# Citation

Kindly cite the EMNLP 2021 ACL Anthology version:

```
@inproceedings{k-etal-2021-analyzing,
    title = "Analyzing the Effects of Reasoning Types on Cross-Lingual Transfer Performance",
    author = "K, Karthikeyan  and
      Sathe, Aalok  and
      Aditya, Somak  and
      Choudhury, Monojit",
    booktitle = "Proceedings of the 1st Workshop on Multilingual Representation Learning",
    month = nov,
    year = "2021",
    address = "Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.mrl-1.8",
    pages = "86--95",
    abstract = "Multilingual language models achieve impressive zero-shot accuracies in many languages in complex tasks such as Natural Language Inference (NLI). Examples in NLI (and equivalent complex tasks) often pertain to various types of sub-tasks, requiring different kinds of reasoning. Certain types of reasoning have proven to be more difficult to learn in a monolingual context, and in the crosslingual context, similar observations may shed light on zero-shot transfer efficiency and few-shot sample selection. Hence, to investigate the effects of types of reasoning on transfer performance, we propose a category-annotated multilingual NLI dataset and discuss the challenges to scale monolingual annotations to multiple languages. We statistically observe interesting effects that the confluence of reasoning types and language similarities have on transfer performance.",
}
```

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

<!-- ## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies. -->
