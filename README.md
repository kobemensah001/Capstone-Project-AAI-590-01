The primary objective of this project is to develop a predictive model that can accurately determine whether a loan applicant at Home Credit will repay a loan on time or will face repayment difficulties. This supervised classification task categorizes outcomes as either '0', indicating the loan was repaid on time, or '1', indicating difficulties in repayment. Successfully predicting loan repayment can significantly impact the financial sustainability of lending institutions while also assisting unbanked populations by facilitating more responsible lending.

This project is critical as it addresses the financial risks associated with lending by predicting potential loan defaults before they occur. For Home Credit, a company that serves unbanked populations, understanding the risk profile of each applicant helps in making informed lending decisions. This not only reduces the financial risks but also enhances customer satisfaction by ensuring loans are provided to those who are most capable of repaying them. Economically, it helps maintain the balance between profitable lending and social responsibility.
The end users of this Machine Learning or Artificial Intelligence model are the decision-makers and loan approval officers at Home Credit. By integrating the predictive model into their decision-making process, these professionals can assess loan applications more efficiently, backed by data-driven insights. This enhances the loan approval process, making it faster, more accurate, and less prone to human error.

The model will utilize several key datasets from Home Credit, including main datasets containing information on each loan application, records from other financial institutions about the client's previous credits, monthly updates on previous credits, data on previous loan applications made by the client at Home Credit, information on previous point-of-sale or cash loans, details on previous credit card balances, and historical payment data for past loans. In a live system, this data would be continuously gathered and updated from Home Credit’s transactional systems and external credit bureaus to keep the model's predictions relevant and accurate.

The ultimate goal of this project is to deploy a robust machine learning model that can be used in real-time to predict loan repayment outcomes. This will not only reduce the number of non-performing loans but also enable the expansion of credit services to lower-income consumers more securely. The high-level hypothesis is that features derived from an applicant’s financial history, previous loan performance, and current application details can effectively predict their likelihood of loan repayment. This hypothesis will be tested using various statistical and machine learning techniques to ensure the model’s accuracy and reliability. By meeting its objectives, this project will provide Home Credit with a powerful tool to enhance its lending practices, thereby supporting sustainable business growth and extending financial inclusion to underserved populations.

Files 
1.	KMENSAH_HOME_CREDIT_DEFAULT_RISK_EDA_V3_APRIL_8 – Notebook used to create EDA
2.	KM_CAPSTONE_NB_1 – Notebook used to Model Random Forest, XGBoost, LightGBM, and four DNN Models.
3.	KM_CAPSTONE_NB_2_9000 – Notebook used for Random Forest Modelling using dataset enriched with features from pervios_application dataset. 9000 selections were randomly selected from the previous_application dataset.
4.	KM_CAPSTONE_NB_3_60000 - Notebook used for Random Forest Modelling using dataset enriched with features from pervios_application dataset. 60000 selections were randomly selected from the previous_application dataset.
5.	KM_CAPSTONE_NB_4_150000 - Notebook used for Random Forest Modelling using dataset enriched with features from pervios_application dataset. 150000 selections were randomly selected from the previous_application dataset.
6.	KM_CAPSTONE_NB_5_300000 - Notebook used for Random Forest Modelling using dataset enriched with features from pervios_application dataset. 300000 selections were randomly selected from the previous_application dataset.

