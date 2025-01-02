# glue-benchmark
Code for benchmarking BERT and MABEL models using the Trainer module on al the tasks from General Language Understanding Evaluation (GLUE) dataset. It uses the Trainer API from the Hugging Face Transformers library to streamline training, evaluation, and logging from the Transformers library. 

# GLUE Tasks Supported
* CoLA
* SST-2
* MRPC
* STS-B
* QQP
* MNLI
* QNLI
* RTE

#  Notes
1. For optimal results, fine-tune and evaluate each model to select the best parameters.
2. SUPER-GLUE can also be benchmarked using this code.
3. The code was executed on Kaggle and required approximately 6-7 hours to complete all tasks for each model using GPU.
