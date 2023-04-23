# CNN_assignment_melanoma

# Melanoma detection:
The objective of this assignement was to use ~2000 images pre-classified as types of melanoma and setup a CNN which can
appropriately categorize the validation data set into it's appropriate type of melanoma.

# Challenges:
The first model was sub-par and rapidly overfit, so the data was augmented with slight rotations to help prevent overfitting
The second model was better but still overfit, so a dropout layer was added after the largest dense layer
The third model was even better but slightly overfit still, so the data was augmented with 500 more samples of each category
The fourth model appropriately categorized 60% of the validation set, however it was not fully trained yet.
If the fourth model was trained for perhaps 150 epochs the model could have seen 70%+ accuracy. Not bad for a CNN

# Credits:
This was a solo project so I would like to thank myself
Also an honorable mention goes to upgrad for creating the course and assigning the project as well as creating easy to understand
instructions on how to complete the objective.
