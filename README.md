# Particle Motion Analysis with Python & Machine Learning

修士研究をベースにした就活向けポートフォリオです。  
**Pythonによる粒子運動シミュレーション → 特徴量抽出 → 機械学習による識別** まで一連の流れをまとめています。

## 使用技術
- Python, NumPy, Pandas, Matplotlib
- tsfresh (特徴量抽出)
- XGBoost, scikit-learn (分類)

## 成果 (研究から得られた知見)
- 粒子の「壁面吸着あり/なし」をシミュレーション
- tsfreshで **700+特徴量** を抽出
- XGBoostで分類精度 **F1スコア90%以上** を達成
- 新しい指標（区間ごとの二乗和比率）を導入し識別性能を改善

## ディレクトリ構成
- `simulation/` … 粒子シミュレーションのPythonコード
- `feature_extraction/` … tsfreshによる特徴量抽出
- `ml_classification/` … XGBoostによる分類コード
- `results/` … 可視化画像
- `thesis_summary.pdf` … 修論のサマリー (自作要約)

## References
- Itsuo Hanasaki, Satoyuki Kawano (2013). *Evaluation of bacterial motility from non-gaussianity...*
- T. Chen, C. Guestrin (2016). *XGBoost: A Scalable Tree Boosting System.*
