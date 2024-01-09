# Classification-Model-For-NFL-Big-Data-Bowl-2024
Classification Model For NFL Big Data Bowl 2024

**Since 2017, the National Football League has collaborated with Amazon Web Services to collect instantaneous player location data, speed, and acceleration across every inch of the field. The NFL's Next Gen Stats have revolutionized football insights and analytics, largely concentrating on offensive metrics. This joint venture now employs machine learning to craft a new defensive measure assessing tackle probability.**

**Information was gathered from tracking data pertaining to the ball and defensive players during each play. Game event details helped identify the defensive team, while tackle data served as the primary outcome variable in a model aimed at predicting a defender's likelihood of executing a tackle.**
**Python was the tool of choice for data preparation and model construction. Various factors—such as player speed, acceleration, distance from the player to the football, player orientation concerning the football, and player direction in relation to the football—were utilized as features for prediction. Standard scaling was applied to render these features uniform in scale. The output was a binary classification indicating whether the defender successfully tackled or failed to do so. The data was randomly divided into training (80%) and testing (20%) sets. Further splitting of the training data into ten non-overlapping segments (90% training and 10% validation)ensuring optimized model parameters and guarding against overfitting.**
**Three distinct machine learning models Gradient Boosting, xgboost, and Custom Deep learning model—were constructed and evaluated to determine the most effective one. The Custom Deep learning model demonstrated superior performance and was thus chosen**.
