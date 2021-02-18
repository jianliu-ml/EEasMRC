1) Question Generation

Clone https://github.com/facebookresearch/XLM to the project.

Follow `QuestionGeneration/data_preparation.py` to prepare the training data: `train_source_example_inputs.txt` gives sample in the source side; `train_target_what_questions.txt` and `train_target_when_questions.txt` show samples in the target side.

Train back-translation model to learn the mapping. `generated_questions.txt' gives the examples of the generated data.


2) Question Answering

Follow `model_train_progressly.py' to preprocess the datasets and train the final model.

