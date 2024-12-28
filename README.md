Il y a 13 variables dans cet ensemble de données donc:

8 variables catégorielles,
4 variables continues, et
1 variable pour s'adapter à l'identifiant du prêt.

Objectifs du projet
Ce projet vise à analyser ce jeu de données pour identifier les mesures de tendance centrale et de dispersion, en utilisant des bibliothèques populaires de data analysis comme pandas, numpy, et matplotlib. 
Apprendre à manipuler les données, effectuer des analyses statistiques de base et création des visualisations pour mieux comprendre la distribution des données.

Voici la structure de l'ensemble de données.

Variable Name	Description	Sample Data
Loan_ID	Loan reference number
(unique ID)	LP001002; LP001003; ...
Gender	Applicant gender
(Male or Female)	Male; Female
Married	Applicant marital status
(Married or not married)	Married; Not Married
Dependents	Number of family members	0; 1; 2; 3+
Education	Applicant education/qualification
(graduate or not graduate)	Graduate; Under Graduate
Self_Employed	Applicant employment status
(yes for self-employed, no for employed/others)	Yes; No
ApplicantIncome	Applicant's monthly salary/income	5849; 4583; ...
CoapplicantIncome	Additional applicant's monthly salary/income	1508; 2358; ...
LoanAmount	Loan amount	128; 66; ...
Loan_Amount_Term	The loan's repayment period (in days)	360; 120; ...
Credit_History	Records of previous credit history
(0: bad credit history, 1: good credit history)	0; 1
Property_Area	The location of property
(Rural/Semiurban/Urban)	Rural; Semiurban; Urban
Loan_Status	Status of loan
(Y: accepted, N: not accepted)	Y; N
