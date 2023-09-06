# Finetune LLMs

## Cost Analysis: Finetune vs Prompt Engineering

[CostAnalysis.ipynb](CostAnalysis.ipynb) provides a comprehensive mathematical analysis to compare the cost implications of two distinct approaches to model usage with [OpenAI Pricing](https://openai.com/pricing) on finetuning and prompt engineering.

### Contents:

1. **Mathematical Model**:
   
   Introduces a mathematical framework to compare the costs associated with choosing the finetuning approach against the prompt engineering approach for a given operational period.

2. **Finetuning**:
   
   Breaks down the cost components for the finetuning process. This includes factors such as the number of tokens in the training dataset, the number of training epochs, and the unit cost of training.

3. **Finetuned Model Usage**:
   
   Details the costs associated with using a finetuned model. Factors considered include the number of tokens for input and output and their respective unit costs.

4. **Prompt Engineering Model Usage**:
   
   Describes the costs associated with using a foundation model with prompt engineering. This section discusses the number of tokens for input and output when using the foundation model and their respective unit costs.

5. **Key Conditions**:
   
   Investigates the conditions under which the cost of using the finetuning approach is less than or equal to that of the prompt engineering approach. It particularly focuses on parameters such as the number of operational days and the number of tokens in the training dataset.

6. **Sampling and Calculations**:
   
   Conducts sampling based on the parameters from the previous sections and computes relevant cost metrics.

7. **Data Filtering**:
   
   Processes and filters the calculated results to trim outliers and prepare the data for subsequent analysis or visualization.

### Usage:

To run the notebook, ensure you have the necessary libraries installed and execute each cell in sequence. Adjust parameters as needed to suit different scenarios or datasets.
