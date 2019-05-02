
# Challenge 5: Orchestrate ML Operationalization with a Pipeline

In the previous challenges, you've used various capabilities of Azure Machine Learning (Azure ML) to pepare data, train and deploy models, and use them to infer predictions from new data.

Now it's time to bring together the various tasks required to operationalize machine learning in a pipeline.

## Prerequisites

Before starting this challenge, ensure you have the following prerequisite requirements in place:

- An Azure ML Workspace
- The data files from the [Microsoft Malware Prediction Kaggle Competition](https://www.kaggle.com/c/microsoft-malware-prediction)

## Challenge

As a team, complete the following tasks:

- Create compute targets for the following steps in your machine learning pipeline:
    - Data preparation
    - Model training
- Define a pipeline that performs the steps above.
- Run your pipeline and monitor its status.

## Hints

- Use low-priority compute for all compute targets.

## Success Criteria

To successfully complete this challenge, you must:

- Demonstrate your pipeline running successfully.

## Resources

- [What are Machine Learning Pipelines?](https://docs.microsoft.com/en-us/azure/machine-learning/service/concept-ml-pipelines)
- [Create your first Pipeline](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-create-your-first-pipeline)
- [Machine Learning Pipelines notebooks](https://github.com/Azure/MachineLearningNotebooks/tree/master/how-to-use-azureml/machine-learning-pipelines)

## Optional Additional Tasks

If time permits:

- Schedule your pipeline to run automatically.
- Identify opportunities for more parallelism in the pipeline and implement them to reduce execution time.
- Run training on multiple compute targets concurrently, and compare training time and performance for each model created.

## Reflect

After completing this challenge, consider the following questions:

- How easy / difficult is it to adapt existing machine learning workflow processes and practices you've encountered to use Azure ML pipelines?
- What customer scenarios have you seen where Azure ML pipelines would present a good solution?
- If you could change one thing about Azure ML web pipelines, what would it be and why?

