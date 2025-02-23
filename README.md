# Fine-tune the RoBERTa-Kaz-Large model
## Overview 
This project is the solution for the hackathon "Datathon Hackathon 2024". This solution was awarded as one of the best solutions and took second place among more than 40 teams. The main goal was to optimize the model for the Question Answering (QA) task in the Kazakh language, focusing on enhancing key performance metrics such as F1 score and Exact Match (EM) score. Firstly, dataset was investigated without any changes. Further, I tried to implement some optimization techniques such as data cleaning and hyperparameter optimization. In the end, accuracy of the model was improved from 70.65 % to 77.89%.
## Features 
* Complex EDA
* Dataset cleaning (Replacing extra symbols such as "===", "&amp" and so on)
* Removing symbols that don`t have context information  ( such as ".", ",", ";" and so on)
* Hyperparameter optimization (Using optuna)
## Technologies used
* Python
* transformers, PyTorch,
* Optuna
* Pandas, numpy
## License
This project is licensed under the MIT License.

## Contacts
For any inquiries or contributions, reach out via email at srlk04@mail.ru or open an issue on GitHub.
