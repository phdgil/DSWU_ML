# 덕성여자대학교 기계학습 강의 자료

이 저장소는 덕성여자대학교 기계학습 수업에서 사용하는 강의 슬라이드와 실습용 Jupyter Notebook 자료를 모아 둔 곳입니다. 수업은 Python, Jupyter, pandas, 기계학습의 기본 개념에서 시작하여, 분자 데이터와 RDKit을 활용한 신약개발 AI 실습으로 확장됩니다.

학생들은 각 주차별 노트북을 직접 실행하면서 데이터 확인, 전처리, 분자 descriptor 생성, feature selection, 모델 학습, 하이퍼파라미터 튜닝, 결과 시각화, 모델 저장 및 AutoML까지 하나의 기계학습 흐름을 경험하게 됩니다.

PDF 파일은 강의 자료 열람용이고, PPTX 파일은 강의자가 수정할 수 있는 원본 슬라이드입니다.

## 수업에서 다루는 내용

- Python과 Jupyter Notebook 기본 사용법
- 기계학습 개념과 실습 환경 구성
- pandas를 이용한 데이터 불러오기, 확인, 필터링, 정리
- 중복 데이터 확인과 데이터 품질 점검
- RDKit을 이용한 분자 구조 처리
- molecular fingerprint와 descriptor 생성
- descriptor 전처리와 모델 입력 데이터 준비
- feature selection, SVM, tree model, ensemble model, XGBoost
- 모델 실험 결과 정리와 시각화
- 학습한 모델 저장 및 다시 불러오기
- Optuna를 이용한 하이퍼파라미터 최적화
- FLAML을 이용한 AutoML 실습
- 기말고사 및 프로젝트용 데이터/모델 파이프라인 작성

## 파일별 설명

| 파일 | 설명 |
|---|---|
| [`w1_python_jupyter.ipynb`](<w1_python_jupyter.ipynb>) | Python, Jupyter, pandas, matplotlib를 처음 실습하며 기본적인 데이터 분석 흐름을 익히는 노트북입니다. |
| [`W1-1 ML intro.pdf`](<W1-1 ML intro.pdf>) | 기계학습 개념, AI 리터러시, 기계학습을 배우는 이유를 소개하는 1주차 강의 PDF입니다. |
| [`W1-1 ML intro.pptx`](<W1-1 ML intro.pptx>) | 1주차 기계학습 소개 강의의 수정 가능한 PowerPoint 원본입니다. |
| [`W1-2 ML data.pdf`](<W1-2 ML data.pdf>) | Anaconda, Jupyter, pandas, scikit-learn, matplotlib, RDKit, Optuna 등 수업 실습 환경과 주요 도구를 설명하는 PDF입니다. |
| [`W1-2 ML data.pptx`](<W1-2 ML data.pptx>) | 1주차 데이터 및 실습 환경 강의의 수정 가능한 PowerPoint 원본입니다. |
| [`w2-1 ML pandas.pdf`](<w2-1 ML pandas.pdf>) | 반복 가능한 데이터 선택, 필터링, 전처리를 위해 pandas를 사용하는 이유와 기본 사용법을 설명하는 PDF입니다. |
| [`w2-1 ML pandas.pptx`](<w2-1 ML pandas.pptx>) | pandas 강의의 수정 가능한 PowerPoint 원본입니다. |
| [`w2-2_dataset_check.ipynb`](<w2-2_dataset_check.ipynb>) | 데이터셋의 컬럼, 결측치, 라벨 분포 등을 확인하고 모델링 전에 데이터 상태를 점검하는 노트북입니다. |
| [`w3-1_data_duplicated.ipynb`](<w3-1_data_duplicated.ipynb>) | 중복 데이터를 찾고, 중복이 데이터 품질과 모델 평가에 어떤 영향을 주는지 확인하는 노트북입니다. |
| [`w4-1_rdkit.ipynb`](<w4-1_rdkit.ipynb>) | RDKit을 이용해 SMILES와 분자 객체를 다루고 기본적인 cheminformatics 작업을 실습하는 노트북입니다. |
| [`w4-2_fp_descriptors.ipynb`](<w4-2_fp_descriptors.ipynb>) | 분자 fingerprint와 descriptor를 생성하여 기계학습 feature로 사용하는 과정을 실습하는 노트북입니다. |
| [`w5-1_descriptor_preprocessing.ipynb`](<w5-1_descriptor_preprocessing.ipynb>) | descriptor 테이블의 결측치 처리, feature 필터링, 모델 입력 데이터 준비를 다루는 노트북입니다. |
| [`w9-1_feature_selection_and_svm.ipynb`](<w9-1_feature_selection_and_svm.ipynb>) | feature selection과 support vector machine(SVM) 모델 학습을 실습하는 노트북입니다. |
| [`w9-1_feature_selection_and_svm_review.ipynb`](<w9-1_feature_selection_and_svm_review.ipynb>) | feature selection과 SVM 모델링 흐름을 복습하기 위한 노트북입니다. |
| [`w9-2_model_result_summary_and_visualization.ipynb`](<w9-2_model_result_summary_and_visualization.ipynb>) | 여러 모델 실험 결과를 정리하고 성능을 시각화하는 방법을 실습하는 노트북입니다. |
| [`w9-2_model_result_summary_and_visualization_after_course.ipynb`](<w9-2_model_result_summary_and_visualization_after_course.ipynb>) | 수업 후 보완된 모델 결과 요약 및 시각화 실습 노트북입니다. |
| [`w10-1_tree_models_and_ensemble.ipynb`](<w10-1_tree_models_and_ensemble.ipynb>) | decision tree, ensemble, random forest, XGBoost, grid search, 모델 비교를 다루는 노트북입니다. |
| [`w11_save_and_load_model.ipynb`](<w11_save_and_load_model.ipynb>) | 학습된 모델을 파일로 저장하고 다시 불러와 재사용하는 방법을 실습하는 노트북입니다. |
| [`w11-2_optuna.ipynb`](<w11-2_optuna.ipynb>) | Optuna를 이용해 하이퍼파라미터를 자동으로 탐색하고 최적화하는 방법을 실습하는 노트북입니다. |
| [`w13-1_automl_flaml.ipynb`](<w13-1_automl_flaml.ipynb>) | FLAML을 이용한 AutoML 기본 흐름을 실습하는 노트북입니다. |
| [`기말고사_template1_data_pipeline.ipynb`](<기말고사_template1_data_pipeline.ipynb>) | 기말고사 또는 프로젝트에서 데이터 전처리 파이프라인을 작성하기 위한 템플릿입니다. |
| [`기말고사_template2_ml_model_pipeline.ipynb`](<기말고사_template2_ml_model_pipeline.ipynb>) | 기말고사 또는 프로젝트에서 기계학습 모델 파이프라인을 작성하기 위한 템플릿입니다. |
| [`덕성여대_신약개발AI활용_국문영문_final.pdf`](<덕성여대_신약개발AI활용_국문영문_final.pdf>) | 신약개발에서 AI를 어떻게 활용할 수 있는지 설명하는 국문/영문 PDF 자료입니다. |

## 사용 방법

노트북 파일은 JupyterLab, Jupyter Notebook, 또는 VS Code의 Jupyter 확장에서 열 수 있습니다. 후반부 실습에는 주제에 따라 RDKit, XGBoost, Optuna, FLAML 등의 추가 패키지가 필요할 수 있습니다.

수업을 처음 듣는 학생은 1주차 자료부터 순서대로 실행하는 것을 권장합니다. 각 노트북의 코드를 직접 실행하고 결과를 확인하면서 데이터 전처리부터 모델 평가까지의 전체 흐름을 익히는 것이 목표입니다.
