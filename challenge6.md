#Challenge 6: Run Batch Predictions

You can use a pipeline to run batch predictions from a file of data observations. This can be useful when you have to process a large number of input observations as a single job that would take too long to accomplish using a real-time service.
Prerequisites

Before starting this challenge, ensure you have the following prerequisite requirements in place:

- An Azure ML Workspace
- A model that you have created in the previous challenges
- The test data file from the Microsoft Malware Prediction Kaggle Competition

## Challenge

As a team, complete the following tasks:

- Create a batch scoring pipeline for your model.
- Use your batch scoring pipeline to infer predictions for the observations in the test.csv file.

## Hints

>Your scoring pipeline will need to include data preparation steps to match the expected input of your model.

## Success Criteria

To successfully complete this challenge, you must:

- Run a pipeline that generates predictions from your model based on the test data file provided in the Kaggle competition.

Resources

- [Running Batch Predictions on Large Data Sets](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-run-batch-predictions)

- [AML Batch Scoring Notebook](https://github.com/Azure/MachineLearningNotebooks/blob/master/how-to-use-azureml/machine-learning-pipelines/pipeline-batch-scoring/pipeline-batch-scoring.ipynb)
- [Deep Learning Batch Scoring Article ("Happy Path")](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/batch-scoring-deep-learning)
- [Reference Implementation of article](https://github.com/Azure/Batch-Scoring-Deep-Learning-Models-With-AML)
- [Batch Scoring Pipeline for Anomaly Detection](https://github.com/Microsoft/AMLBatchScoringPipeline)

## Optional Additional Tasks

If time permits:

- Submit your results to the Kaggle competition.

## Reflect

After completing this challenge, consider the following questions:

- In what customer scenarios do you envision Azure ML being used for model management and batch inference?
- How does Azure ML model management and batch inference compare to other solutions you've seen customers use for this functionality?
- If you could change one thing about Azure ML support for model management and batch inferencing, what would it be and why?