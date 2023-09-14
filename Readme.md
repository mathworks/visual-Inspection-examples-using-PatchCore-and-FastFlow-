# PatchCoreとFastFlowを使った外観検査AIモデル開発のサンプル

## About this sample
このサンプルは2023年3月30日に実施したWebinar[「いまからでも遅くない外観検査〜ワークフロー概説と最新アルゴリズム適用例」](https://jp.mathworks.com/videos/visual-inspection-workflow-overview-and-the-case-study-of-patchcore-1680631379552.html)の後半のセッション「外観検査を効率化する最新アルゴリズム “PatchCore”の原理と適用例」
で紹介したPatchCoreのサンプル、そしてFastFlowのサンプルです。
元のサンプルである「[Detect Image Anomalies Using Explainable FCDD Network](https://www.mathworks.com/help/deeplearning/ug/detect-anomalies-using-single-class-classification.html)
」から最低限の変更に留めて作成していますので、解説のテキストとコードが一致していない箇所がある点ご留意ください。
変更点はWebinar中に明示していますので参考にしてください。

## How to run samples
PatchCoreのサンプル  
MATLAB同梱のPillデータセットを使って、PatchCoreによる外観検査AIモデルを学習、検証することができます。  
Demosフォルダにある"[PatchCore_using_Pill_data_Example.mlx](Demos/PatchCore_using_Pill_data_Example.mlx)"を開いて、実行してください。  
  
FastFlowのサンプル  
お手持ちのデータを使ってFastFlowによる外観検査AIモデルを学習、検証することができます。  
Demosフォルダにある"[FastFlow_using_mydata_Example.mlx](Demos/FastFlow_using_mydata_Example.mlx)"を開いて、dataDirやimageDirを適宜変更し実行してください。  
変更箇所はWebinarを参考にしてください。  
  
## Recording
[MathWorks&reg; Webinar いまからでも遅くない外観検査〜ワークフロー概説と最新アルゴリズム適用例アーカイブページ](https://jp.mathworks.com/videos/visual-inspection-workflow-overview-and-the-case-study-of-patchcore-1680631379552.html)  

## Required Products

Products:  
- MATLAB&trade;  
- Image Processing Toolbox&trade;  
- Computer Vision Toolbox&trade;  
- Deep Learning Toolbox&trade;  
（※いずれもR2023a以降）  
  
Add-on:  
- Computer Vision Toolbox Automated Visual Inspection Library（Computer Vision Toolboxのライセンスがあれば無償ダウンロード可能です）  
- Deep Learning Toolbox Model for ResNet-18 Network  

## References
PatchCore: proposed in Roth et al. (2021), [Towards Total Recall in Industrial Anomaly Detection](https://arxiv.org/abs/2106.08265)  
FastFlow: proposed in Yu et al. (2021), [FastFlow: Unsupervised Anomaly Detection and Localization via 2D Normalizing Flows](https://arxiv.org/abs/2111.07677)  
