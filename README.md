# Explainable-AI-xAI

Very Important Link (Must Read) - [Interpretable ML](https://christophm.github.io/interpretable-ml-book/)

- Explainable AI (xAI) enhances transparency and trust by making complex models more interpretable, crucial for accountability and bias detection in regulated industries.

- It aids in debugging, legal compliance, and balancing accuracy with interpretability, proving essential in fields like healthcare, finance, and autonomous vehicles. 

## xAI Methods Categorization

1. **Agnosticity**
    - Model Agnostic (Ex - LIME, SHAP, Partial Dependence Plots)
    ![Image](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*a3XvSs14zWXx_B6Z7NnrBw.png)


    - Model Specific Techniques (Ex - Attention mechanisms, Tree interpreters, CNN visualizers)
    ![Image](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*eGp1stwcUI9saJcr41NaPQ.png)


2. **Scope**
    - Local Explanation<br>
        Focuses on explaining individual predictions, revealing why specific decisions were made for particular input instances. Techniques include LIME ,local surrogate models and instance-based explanations.
    
    - Global Explanation<br>
        Analyzes overall model behavior across the entire dataset, identifying general trends, feature importance rankings, and model dynamics that apply broadly. Methods include feature importance analysis, SHAP (SHapley Additive exPlanations), and model-specific weight analysis.

3. **Explanation Type**
    - Visual explanations<br>
    These use visualizations to illustrate how models arrive at decisions, such as heatmaps highlighting important areas in images.
    
    - Feature importance<br>
    This type identifies which features or inputs have the most significant impact on model predictions, aiding in understanding model behavior.

    - Data point explanations<br>
    They focus on explaining individual predictions by highlighting relevant data points or factors influencing specific outcomes.

    - Surrogate/simple models<br>
    These are simplified versions of complex models that are easier to interpret, providing insights into decision-making processes without the complexity of the original model.

    ![Image](https://miro.medium.com/v2/resize:fit:2612/format:webp/1*IxE7up7fX7dTx7SE3FCDfg.png)

4.  **Data Type**<br>
    <img width="642" alt="Image" src="https://github.com/user-attachments/assets/63319e6b-40d6-4799-bd47-104beae7811f" />


## Some notable xAI Methods

- **LIME (Local interpretable model-agnostic explanations):** Explains individual predictions by locally learning an interpretable model, applicable in healthcare diagnostics and finance.
- **SHAP (Shapley Additive Explanations):** Assigns feature importance values for specific predictions, crucial in credit scoring and fraud detection.
- **Partial Dependence Plots (PDP):** Shows how features impact predictions, useful in pricing models and retail analytics.
- **Tree Interpreter:** Analyzes decision trees to understand feature contributions, valuable in insurance risk assessment.
- **CNN Visualizations:** Visualizes CNNs to interpret image data, essential for autonomous driving and medical imaging.
- **Permutation Feature Importance:** Measures feature importance by shuffling values, beneficial in customer churn prediction.
- **Counterfactual Explanations:** Generates alternative instances to understand decision boundaries, significant in loan approvals and criminal justice.


## Qualitative Comparision

|   Technique   |   Model Agnostic  |   Data Type   |   Local/Global    |   Explanation Type    |
|---------------|-------------------|---------------|-------------------|-----------------------|
|   LIME        |       Yes         |   Text/Tabular/Image  |   Local   |   Surrogate Model     |
|   SHAP        |       Yes         |   Text/Tabular/Image  |   Local/Global    |   Feature Importance  |
|   Partial Dependence Plots (PDP)  |   Yes     |   Tabular |   Global  |   Visual  |
|   Tree Interpreter    |   No      |   Tabular |   Local   |   Feature Importance  |
|   CNN Visualizer      |   No      |   Image   |   Local   |   Visual  |
|   Permutaion Feature Importance   |   Yes     |   Tabular/Image   |   Global  |   Feature Importance  |
|   Counterfactual Explanation  |   Yes |   Text/Tabular/Image  |   Local   |   Data Types      |