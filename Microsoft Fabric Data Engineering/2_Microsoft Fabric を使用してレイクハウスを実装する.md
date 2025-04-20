[Microsoft Fabric を使用してレイクハウスを実装する](https://learn.microsoft.com/ja-jp/training/paths/implement-lakehouse-microsoft-fabric/)  

1. Microsoft Fabric を使用したエンドツーエンドの分析の概要  
[Microsoft Fabric を使用したエンドツーエンドの分析の概要](https://learn.microsoft.com/ja-jp/training/modules/introduction-end-analytics-use-microsoft-fabric/)    
**学習の目標**
- Fabricエンドツーエンドの分析について説明する  

1.1. はじめに  
Fabricはエンドツーエンドの分析プラットフォーム、単一環境でのデータの取り込み、格納、処理、分析が可能な一連の統合サービスが用意されている。  

1.2. エンドツーエンドの分析を調べる  
全てのデータがOneLakeに1つのオープン形式で格納されている。  
OneLakeには、プラットフォーム内の全ての分析エンジンからアクセスできる。  
OneLakeはAzure Data Lake Storage(ADLS)上に構築され、Delta, Parquet, CSV, JSONなど任意のファイル形式でデータを格納できる。  
OneLakeのショートカット機能は、既存のクラウドデータを素早くソース化でき、同じソースからデータを派生させることができる。  

1.3. データチームとMicrosoft Fabric  
データエンジニア：複雑なデータ処理を実施  
データアナリスト：ビジネスに適したデータを効果的に表示できるようにデータソースをキュレーションして提供  
従来の開発プロセスでは、この2者の役割の違いにより多くのコミュニケーションコストがかかる  
Fabricは開発プロセスを変革して、ロール間での作業の重複を避けつつ、必要なスキルを柔軟に実行できるようになる  
