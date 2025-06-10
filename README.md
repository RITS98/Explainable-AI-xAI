# Explainable-AI-xAI

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