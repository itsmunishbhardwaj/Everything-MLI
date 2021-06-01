# Release Summary
> **NOTE: If you find an issue, then please make an issue and tag it to the current [sprint](https://github.com/h2oai/h2oai/projects/91) under the card `To do Testing`**

Go through [test plans](https://github.com/h2oai/mli-product/blob/master/qa/TEST_PLAN_MLI_E2E.md#manual-tests) before 1.10 LTS release & post results as a comment to this issue. Note, tag any newly created issues with this issue for better tracking.

## MLI Checklist
Please add your name against the test you perform

**Legend:**
|symbol|meaning|
|-------|---------|
|✅| All clear/No bugs found/LGTM|
|❌| Not clear/bugs reported|
|⚠️| Work in Progress|

### DAI experiment
|Overall Status|Tester|Test|No. of Bugs|Bug Status|
|--------------|------|-----|-----------|-----------|
||@kamilc|[Interpretation of Regression Test Plan](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_REGRESSION.md)|||
|-|@kamilc|[Interpretation of Binomial Classification Test Plan](https://github.com/h2oai/mli-product/blob/master/qa/test_plans/TEST_PLAN_BINOMIAL_CLASSIFICATION.md)|||
|-|@itsmunishbhardwaj|[Interpretation of Multinomial Classification Test Plan](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_MULTINOMIAL_CLASSIFICATION.md)|||
|-|@dvorka|[MLI for NLP Test Plan]||| 
|-|@itsmunishbhardwaj|[Interpretation of Time-series Test Plan]|||

### StandAlone MLI Models
(no DAI experiment is used, so only surrogate model checks are needed) 
|Overall Status|Tester|Test|No. of Bugs|Bug Status|
|--------------|------|-----|-----------|-----------|
||@kamilc|[Interpretation of Regression Test Plan](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_STANDALONE_REGRESSION.md)|||
||@rsujeevan|[Interpretation of Binomial Classification Test Plan](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_STANDALONE_BINOMIAL.md)|||
||@rsujeevan|[Interpretation of Multinomial Classification Test Plan](update/create link)|||

### Expert Settings
|Overall Status|Tester|Test|No. of Bugs|Bug Status|
|--------------|------|-----|-----------|-----------|
||@itsmunishbhardwaj|[Expert Settings Binomial](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_EXPERT_SETINGS_BINOMIAL.md)|||
||@itsmunishbhardwaj|[Expert Settings Multinomial](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_EXPERT_SETINGS_MULTINOMIAL.md)|||
||@itsmunishbhardwaj|[Expert Settings Regression](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_EXPERT_SETTINGS_REGRESSION.md)|||
||@itsmunishbhardwaj|[Expert Settings NLP](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_EXPERT_SETTINGS_NLP.md)|
||@itsmunishbhardwaj|[Expert Settings TS](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_EXPERT_SETTINGS_TS.md)|
|TO DO|@itsmunishbharwaj|[MLI Actions](add)|||

### Explainers
|Overall Status|Tester|Test|No. of Bugs|Bug Status|
|--------------|------|-----|-----------|-----------|
||@kamilc|[Disparate Impact Analysis Test Plan](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_MLI_DIA.md)|||
||@itsmunishbhardwaj|[Sensitivity Analysis Test Plan](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_MLI_SENSITIVITY_ANALYSIS_TESTS.md)|||
||@itsmunishbhardwaj|[Permutation-based Feature Importance Test Plan](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_EXPLAINER_PERMUTATION_BASED_FEATURE_IMPORTANCE.md)
||@rsujeevan|[Feature Importance Paging Test Plan](https://github.com/h2oai/mli-product/blob/master/qa/TEST_PLAN_FEATURE_IMPORTANCE_PAGING.md)|
||@rsujeevan|[Row Search Test Plan](https://github.com/h2oai/mli-product/blob/master/qa/TEST_PLAN_ROW_SEARCH.md)|
||@itsmunishbhardwaj |[DAI BYOR Test Plan](https://github.com/h2oai/mli-product/blob/munish/docs/qa/test_plans/TEST_PLAN_DAI_BYOR.md)|
||@navdeep-G|[MLI Dataset Sampling Test Plan](https://github.com/h2oai/mli-product/blob/master/qa/TEST_PLAN_DATASET_SAMPLING.md)|
||@navdeep-G| [Surrogates on Residuals Test Plan](https://github.com/h2oai/mli-product/blob/master/qa/TEST_PLAN_RESIDUALS.md) |
||@itsmunishbhardwaj|[MLI-BYOR](created test plan)|

Go through [test plans](https://github.com/h2oai/mli-product/blob/master/qa/TEST_PLAN_MLI_E2E.md#manual-tests) & post results as a comment to this issue. Note, tag any newly created issues with this issue for better tracking.


Be smart - breath first, rather then breath first testing - ensure that the following products aspects have coverage:
* sampling
* transformed features
* standalone / 3rd party
* regression / binomial / multinomial
* local explanations

For examples, see [past releases test reports](https://github.com/h2oai/mli-product/blob/master/qa/QA_AND_PERFORMANCE_DOCUMENT_MLI.md#testing).
