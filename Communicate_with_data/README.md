# Prosper Loans Dataset
## by Franck Loïc NOUMOU TCHOMEGNI


## Dataset

Cet ensemble de données contient 113 937 prêts avec 81 variables sur chaque prêt. Aux fins de cette enquête, j'ai pris les variables suivantes : `Term, LoanStatus, BorrowerAPR, BorrowerRate, ProsperRating (Alpha), ProsperScore, ListingCategory (numeric), EmploymentStatus, DelinquenciesLast7Years, StatedMonthlyIncome, TotalProsperLoans , LoanOriginalAmount, LoanOriginationDate, Recommendations, Investors`. Après ajustement, l'ensemble de données contenait 25 938 lignes de données.


## Summary of Findings

- Les `ProsperRating (Alpha)` sont presque normalement distribuées. La distribution de `StatedMonthlyIncome` est très variée : avec de nombreuses valeurs aberrantes et une très large plage de valeurs. La plupart des prêts sont inférieurs à 15 000 $, il semble que la plupart des prêts soient des tranches de 5 000 $. La note de prospérité D est la note la plus fréquente parmi les crédits **Defaulted**.

- Les crédits **Defaulted** ont tendance à être accordés aux personnes ayant une cote inférieure. **Business** et **Home Improvement** semblent représenter un risque plus élevé. Le `BorrowerRate` a tendance à être plus élevé pour les crédits **Defaulted**. Les crédits à long terme (60 mois) sont plus risqués que les crédits à court terme (12 mois). Le **BorrowerRate** pour les personnes à faible notation est plus élevé. Un `StatedMonthlyIncome` élevé correspond à une note plus élevée. Le `EmploymentStatus` des personnes ayant des cotes inférieures tend à être **Not employed**, **Self-employed**, **Retired** ou **Part-time**.

- Les crédits **Defaulted** ont tendance à être plus importants que **Completed** pour toutes les cotes Prosper, à l'exception des plus basses.


## Key Insights for Presentation

J'ai choisi des tracés clés avec un rapport données/encre élevé pour la présentation. Les graphiques que j'ai choisis montrent la distribution des principales variables, `LoanStatus`, `StatedMonthlyIncome`, `ProserRating (Alpha)` et j'ai essayé de raconter une histoire quels sont les principaux prédicteurs de `LoanStatus` et de `ProserRating (Alpha)`.