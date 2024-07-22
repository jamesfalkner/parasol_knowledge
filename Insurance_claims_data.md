**Introduction:**  
In the insurance industry, accurately predicting the likelihood of claims is essential for risk assessment and policy pricing. However, Parasol insurance claims datasets frequently suffer from class imbalance, where the number of non-claims instances far exceeds that of actual claims. This class imbalance poses challenges for predictive modeling, often leading to biased models favoring the majority class, resulting in subpar performance for the minority class, which is typically of greater interest.

**Parasol Insurance Claims data features:**
The dataset holds the following information
1.  **Policyholder Information:** This includes demographic details such as age, gender, occupation, marital status, and geographical location.
2.  **Claim History:** Information regarding past insurance claims, including claim amounts, types of claims (e.g., medical, automobile), frequency of claims, and claim durations.
3.  **Policy Details:** Details about the insurance policies held by the policyholders, such as coverage type, policy duration, premium amount, and deductibles.
4.  **Risk Factors:** Variables indicating potential risk factors associated with policyholders, such as credit score, driving record (for automobile insurance), health status (for medical insurance), and property characteristics (for home insurance).
5.  **External Factors:** Factors external to the policyholders that may influence claim likelihood, such as economic indicators, weather conditions, and regulatory changes.

**How to use the Parasol Insurance Claims data:**
The data can be used for the following types of application and queries.
1.  **Risk Assessment:** Assessing the risk associated with insuring a particular policyholder based on their characteristics and historical claim behavior.
2.  **Policy Pricing:** Determining appropriate premium amounts for insurance policies by estimating the expected claim frequency and severity.
3.  **Fraud Detection:** Identifying fraudulent insurance claims by detecting anomalous patterns in claim submissions and policyholder behavior.
4.  **Customer Segmentation:** Segmenting policyholders into distinct groups based on their risk profiles and insurance needs to tailor marketing strategies and policy offerings.

Following are some commonly used terms for Insurance claims data.

policy id:  is a Unique identifier for the insurance policy.
subscription: is the duration for which the insurance policy is active.
customer:
customer age: is the age of the insurance policyholder, which can influence the likelihood of claims.
vehicle age: is the age of the vehicle insured, which may affect the probability of claims due to factors like wear and tear.
model: is the model of the vehicle, which could impact the claim frequency due to model-specific characteristics.
fuel type: is the type of fuel the vehicle uses (e.g., Petrol, Diesel, CNG), which might influence the risk profile and claim likelihood.
max torque: describes the Engine performance characteristics that could relate to the vehicle’s mechanical condition and claim risks. 
max power: describes the Engine performance characteristics that could relate to the vehicle’s mechanical condition and claim risks. 
engine type: is the type of engine, which might have implications for maintenance and claim rates.
cylinder: describes the specifications related to the engine size and construction, affecting the vehicle’s performance and potentially its claim history.
region code: is the code representing the geographical region of the policyholder, as claim patterns can vary regionally.
region density: shows the population density of the policyholder’s region, which could correlate with accident and claim frequencies.
airbags: The number of airbags in the vehicle, indicating safety level which can influence claim probability.
claim status: Indicates whether a claim was made (1) or not (0), which is the dependent variable the model aims to predict.
