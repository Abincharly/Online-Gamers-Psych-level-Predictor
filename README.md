# Psych-level-Predictor
ML techniques to predict anxiety levels and overall satisfaction with life among online gamers

developing machine learning models that can predict the psychology level of online
gamers based on their responses to standardized questionnaires. The questionnaire
consists of several sets of questions as asked as a part of psychological study. Most of the
questionnaires correspond to different scoring criteria used in psychology like GAD
(General Anxiety Disorder), SWL (Satisfaction with Life) and SPIN (Social Phobia Inventory)
scores. Here we are using Generalized Anxiety Disorder Assessment (GAD-7) and
Satisfaction with Life Scale (SWLS) questionnaires to assess anxiety symptoms and life
satisfaction, respectively.
Generalized Anxiety Disorder Assessment (GAD-7) is a self-reported questionnaire used to
assess the severity of anxiety symptoms. It consists of seven items, each with a score of 0
to 3, resulting in a total score ranging from 0 to 21. The higher the score, the more severe
the anxiety symptoms. The Satisfaction with Life Scale (SWLS) is a self-reported questionnaire used to assess life
satisfaction. It consists of five items, each with a score of 1 to 7, resulting in a total score
ranging from 5 to 35. The higher the score, the higher the life satisfaction. 

To develop a machine learning model to predict the psychology level of online gamers,
data is collected through questionnaires. The questionnaire consists of 55 features and
13464 observations. The collected data would be preprocessed, which involves cleaning,
transforming, and normalizing the data. The preprocessed data would be divided into
training and testing datasets. The training dataset would be used to train the machine
learning model, while the testing dataset would be used to evaluate the performance of
the model.
The model would be trained to predict the psychology level of online gamers based on the
GAD-7 and SWLS scores. The model's performance would be evaluated based on metrics
such as accuracy, precision, recall, and F1-score. Once the model is trained and evaluated,
it could be used to predict the psychology level of online gamers in real-time. This could
be done by collecting GAD-7 and SWLS scores from online gamers and inputting the scores
into the model. The model would then output a prediction of the gamer's psychology
level, indicating the likelihood of depression. If the prediction indicates a high likelihood of
depression, appropriate interventions could be provided, such as counseling or mental
health support.
