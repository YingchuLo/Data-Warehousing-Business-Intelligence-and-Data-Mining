# Case 5:					


Goal: Find the people who may become a buyer after receiving a discount


Dataset: Enriched Smartpartyware dataset.
Model: Ensemble Model (Neural Network + Decision Tree)
Software: JMP
Result: 


Summary:
The model proposed, named ensemble model, combined a neural network and a decision tree models. From a neural network perspective, we used only most statistical relevant variables, which are Recency, Income, Gender, New_State, Block_Party, and Art_Party. By using these variables and a two-layer model, we believe that we were able to build a model that takes into consideration if a customer is male or female, is located in the west coast, has an income higher than 150,000, bought the product in the last 12 months, so this customer would probably buy the product again, making business sense.
From a decision tree perspective, first, we split based on the state, because we could observe, analyzing the geographic map chart, distinct patterns of income among the states. Second, we used the specific split suggested by the software to identify the best type of party. Finally, we select the variable Recency, since that from a business point of view makes sense to assume that a customer who bought party products recently has a higher propensity to repurchase them in the future.
Furthermore, we also consider additional criteria to score and evaluate our best model. In the following sections, we will dive deep into those criteria. Primarily, our best model considers variables statistically significant; the expected profit is around $1,65 million -the highest total profit achieved and optimized the number of packages sent.



