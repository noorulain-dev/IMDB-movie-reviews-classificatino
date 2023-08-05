# IMDB-movie-reviews-classificatino
Fine-tuning three different pre-trained models, namely Small Bert H-526 A-4, Electra base, and Small_Bert H-768_A-12, on the IMDB movie review dataset for sentiment analysis
The goal was to fine-tune three different pre-trained models, namely Small Bert H-526 A-4, Electra base, and Small_Bert H-768_A-12, on the IMDB movie review dataset for sentiment analysis. The pre-processing steps for all three models were similar, including tokenization, padding, and creating training and testing datasets.

After pre-processing, each model was trained, and the evaluation metrics, including loss and accuracy, were calculated for the test dataset. The evaluation metrics were used to compare the performance of the models.

The output of the Small Bert H-526 A-4 model showed a loss of 0.4198 and an accuracy of 0.8008. The accuracy of this model was the lowest among the three models, and the loss was also relatively high. This suggests that this model did not perform as well as the other two models on the IMDB dataset.

The output of the Electra base model showed a loss of 0.3653 and an accuracy of 0.9087. The accuracy of this model was the highest among the three models, and the loss was also the lowest. This suggests that this model performed the best on the IMDB dataset compared to the other two models.

The output of the Small_Bert H-768_A-12 model showed a loss of 0.4088 and an accuracy of 0.8864. The accuracy of this model was the second-highest among the three models, and the loss was also relatively low. This suggests that this model performed better than the Small Bert H-526 A-4 model but slightly worse than the Electra base model on the IMDB dataset.

In summary, the Electra base model performed the best on the IMDB dataset for sentiment analysis, as it had the highest accuracy and the lowest loss. The Small Bert H-768_A-12 model performed second-best, followed by the Small Bert H-526 A-4 model, which had the lowest accuracy and highest loss among the three models.

