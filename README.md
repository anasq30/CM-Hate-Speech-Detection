# CM-Hate-Speech-Detection : LLM

Detecting and flagging hate speech and abuse on social media platforms is an important and time sensitive task. While supervised learning approaches have been successful in identifying hate speech in English and some other high-resource languages, this is not the case for code-mixed text, which is a common way of communication for many bilingual people. In this project, we evaluate the effectiveness of Large Language Models for the task of Hindi-English code mixed hate speech detection, and compare this to existing BERT-based models on an existing "Hinglish" Indian Politics hate speech dataset. Additionally, we evaluate the generalization capabilities of these models on a custom Hindi-English code- mixed hate speech dataset. We find that smaller specialized finetuned models such as Hing-RoBERTa outperform both prompted and finetuned LLaMa-2 on the existing Hinglish Indian Politics dataset, and also generalize better to our newly collected dataset.

![pipeline](https://github.com/anasq30/CM-Hate-Speech-Detection/assets/108400927/2732b6c7-604f-4506-be22-9f1e5c78566c)

## Insights

* Evaluated the effectiveness of Large Language Models for the task of Hindi-English code mixed hate speech detection, and compare this to existing BERT-based models on an        existing "Hinglish" Indian Politics hate speech dataset.
* Fine-tuned multilingual and code-mixed BERT-based models like HingRoBERTa and XLM-RoBERTa, explored prompting methods utilizing the LLaMa 70B Chat model in a zero-shot setting, employing in-context learning and chain of thought reasoning
* Concluded that smaller fine tuned models such as HingRoBERTa pretrained on more relevant data trump general LLMs on this niche task of Hindi-English hate speech detection with macro F-1 score of  81.97.
