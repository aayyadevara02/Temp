# HW3 README


## Part 1:


![image](https://github.com/user-attachments/assets/cf4f2b13-c125-40cd-bf81-9179f879ca86)


chosen_model = model_tanh if np.mean(rmse_tanh) < np.mean(rmse_relu) else model_relu

Model Chosen: Tanh

Predicted word 1: days

Predicted word 2: time


When including stopwords the RMSE seemed to be higher as opposed to without, which shows more accurate predictions when stopwords are excluded. The quality of prediction was also much better without stopwords because the models predicted more context specific words rather than common words as filler.


## Part 2:


![image](https://github.com/user-attachments/assets/f06b8c94-ec02-44a9-bb55-cfd22bb65b2d)



Although both histogram plots are similar, BERT seems to have the slight edge. There are a lot more predictions clustered around the 1.0 as well as more perfect predictions. GPT performed well, but is slightly more variable with a higher chance of predicting a word that is not very similar. Due to that reasoning, I would choose BERT as the better performance in this scenario.
