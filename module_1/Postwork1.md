# Postwork

## Instructions

Please follow the instructions below to complete the assignment:

1. Read the Whiskas case description provided.
2. Run the provided code snippets, `WhiskasModel1` and `WhiskasModel2`, related to the Whiskas problem.
3. Answer the questions based on the code snippets and the Whiskas case.

## Whiskas Case Description

Whiskas cat food, shown above, is manufactured by Uncle Ben’s. Uncle Ben’s wants to produce their cat food products as cheaply as possible while ensuring they meet the stated nutritional analysis requirements shown on the cans. The main ingredients of Whiskas cat food are chicken, beef, mutton, rice, wheat, and gel. Each ingredient contributes to the total weight of protein, fat, fiber, and salt in the final product.

The costs of the ingredients per gram are as follows:

- Chicken: $0.013
- Beef: $0.008
- Mutton: $0.010
- Rice: $0.002
- Wheat: $0.005
- Gel: $0.001

The nutritional analysis per gram of ingredient is as follows:

| Ingredient | Protein | Fat   | Fiber | Salt  |
| ---------- | ------- | ----- | ----- | ----- |
| Chicken    | 0.100   | 0.080 | 0.001 | 0.002 |
| Beef       | 0.200   | 0.100 | 0.005 | 0.005 |
| Mutton     | 0.150   | 0.110 | 0.003 | 0.007 |
| Rice       | 0.000   | 0.010 | 0.100 | 0.002 |
| Wheat      | 0.040   | 0.010 | 0.150 | 0.008 |
| Gel        | 0.000   | 0.000 | 0.000 | 0.000 |

## WhiskasModel1 - Simplified Whiskas Model

The `WhiskasModel1` snippet provides a simplified formulation of the Whiskas problem using the PuLP Modeller. This code defines the decision variables, objective function, and constraints, and solves the problem to find the optimal solution. It also displays the resolved optimum values for the variables and the total cost of ingredients per can.

## WhiskasModel2 - Full Whiskas Model

The `WhiskasModel2` snippet presents a more comprehensive formulation of the Whiskas problem using the PuLP Modeller. This code represents the ingredients, costs, and nutritional percentages using dictionaries. It then defines the decision variables, objective function, and constraints. The problem is solved, and the optimal solution, variable values, and total cost of ingredients per can are displayed.

## Assignment Rubric

Please refer to the following table for the rubric that will be used to evaluate your assignment:

| Criteria                    | Points |
| --------------------------- | ------ |
| Correct answers             | 80     |
| Clear and concise reasoning | 20     |

## Submission

- Answer the questions based on the provided code snippets and the Whiskas case.
- Submit your answers as a Markdown document in a Github Repository.
- Make sure to write clear and concise explanations for your answers.

Good luck!
"""

# Question set

1. What is the objective of the problem defined in code1?
2. How is the total cost of ingredients per can calculated in the objective function of code1?
3. Explain the constraint "PercentagesSum" in both code1 and code2.
4. Compare the formulation of the "ProteinRequirement" constraint in code1 and code2.
5. What are the decision variables in code2, and how are they defined?
6. How are the costs of ingredients and nutritional percentages represented in code2?
7. What is the significance of using dictionaries in code2 to represent the costs and nutritional percentages?
8. Compare the output file name and format in code1 and code2.
9. What does the solution status from LpStatus[prob.status] represent in both code1 and code2?
10. OPTIONAL - (5/100 Extra Points for Final Test) Write all your answers as a markdown document (.md) and upload it to your github account.

## Additional Materials

[Mini_Case.pdf](minicase1.pdf)
