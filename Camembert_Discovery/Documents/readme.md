

|Action|Retour|Définition| Type de modèle à fournir|Eléments à fournir|Modèles disponibles
|--|--|--|--|--|--|
| Feature-extraction  | FeatureExtractionPipeline | Extrait les états cachés du transformateur de base, qui peuvent être utilisés comme fonctionnalités dans les tâches en aval. | Model | phrase | [https://huggingface.co/models](https://huggingface.co/models) |
| Sentiment-analysis | TextClassificationPipeline | Classer les séquences selon des sentiments positifs ou négatifs | ModelForSequenceClassification | phrase | [https://huggingface.co/models?filter=text-classification](https://huggingface.co/models?filter=text-classification) |
| NER | NerPipeline | Named Entity Recognition : prédit les classes de certains mots dans une phrase : personne, organisation, emplacement ou divers | ModelForTokenClassification | phrase | [https://huggingface.co/models?filter=token-classification](https://huggingface.co/models?filter=token-classification) |
| Question-answering | QuestionAnsweringPipeline | Réponds aux questions dans un contexte précis | ModelForQuestionAnswering | question & context | [https://huggingface.co/models?filter=question-answering](https://huggingface.co/models?filter=question-answering) |
| Fill-mask | FillMaskPipeline | Prédit les mots masqués (mask) d'un phrase. | ModelWithLMHead | phrase + <mask> | [https://huggingface.co/models?filter=lm-head](https://huggingface.co/models?filter=lm-head) |
| Summarization | SummarizationPipeline | Résume les articles de presse et autres documents | Model ? | phrases | [https://huggingface.co/models?filter=summarization](https://huggingface.co/models?filter=summarization) |
| Translation_xx_to_yy | TransformationPipeline | Translates from one language to another | Model ? | phrase type pipeline : translation_en_to_fr | https://huggingface.co/models?filter=translation |
