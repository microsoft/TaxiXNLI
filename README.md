# Project

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

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
