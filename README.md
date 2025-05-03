# HW3 README
Part 1:


![image](https://github.com/user-attachments/assets/cf4f2b13-c125-40cd-bf81-9179f879ca86)


chosen_model = model_tanh if np.mean(rmse_tanh) < np.mean(rmse_relu) else model_relu

Model Chosen: Tanh

Predicted word 1: days

Predicted word 2: time


When including stopwords the RMSE seemed to be higher as opposed to without, which shows more accurate predictions when stopwords are excluded. The quality of prediction was also much better without stopwords because the models predicted more context specific words rather than common words as filler
