# US AIRLINE PASSENGER SATISFACTION
The primary objective of this study was to accurately predict passenger satisfaction for an American airline, utilizing survey data from approximately 130,000 passengers. 
The survey considered various factors influencing satisfaction. This prediction task is crucial for the airline as it allows for targeted improvements in service quality, operational efficiency, and customer experience. 
Indeed, by understanding the key drivers of satisfaction, the airline can implement strategic changes to enhance passenger comfort, streamline processes, and ultimately increase customer loyalty and retention.

Initially, a data pre-processing phase was conducted to clean the dataset of any noise. Moreover, mutual information was applied in order to select the most influent features to take into account
during the training phase and then, various techniques such as cross-validation and grid search were employed to determine the optimal hyper-parameters for models deemed useful for the classification task. 
The robustness of these models was evaluated by applying metrics on means and standard deviations of each fold obtained by the cross validation step. 
Moreover, a T-test was also performed to define if any significant differences between models were present. 

Finally, the most performant models were selected with their tuned hyper-parameters, trained, and then evaluated exploiting confusion matrices, ROC and Precision-Recall curves to ensure robust performance.
In conclusion, to determine whether the hypothesis of considering only relevant features provided advantages, a comparative analysis was conducted between the application of this process on the
dataset containing only the relevant features and the original, complete dataset.
