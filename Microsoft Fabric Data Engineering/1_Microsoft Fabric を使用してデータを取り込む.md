[Microsoft Fabric を使用してデータを取り込む](https://learn.microsoft.com/ja-jp/training/paths/ingest-data-with-microsoft-fabric/)

1. Microsoft Fabric でデータフロー Gen2 を使用してデータを取り込む  
[Microsoft Fabric でデータフロー Gen2 を使用してデータを取り込む](https://learn.microsoft.com/ja-jp/training/modules/use-dataflow-gen-2-fabric/)  
**学習の目標**
- Microsoft Fabricのデータフロー機能について説明する
- データを取り込んで変換するためのデータフローソリューションを作成する
- パイプラインにデータフローを含める

1.1. はじめに  
データフローGen2は複数のソースからデータを取り込んで変換し、クレンジングされたデータを別の宛先に格納するために使用される。  
データパイプラインに組み込むこともBIのデータソースにすることもできる。  


1.2. Microsoft Fabric のデータフロー Gen2 について  
データフローGen2はPower Query Onlineを使用するETLツール  
データフローGen2も目的はETLタスクを実行するための簡単で再利用可能な方法を提供すること  
データの宛先を指定せず変換方法のみ定義した状態でパイプラインに追加し、後続のアクティビティに変換後の状態を渡すことも可能。  
パイプラインでレイクハウスにデータを読み込み、データフローで変換し、そのデータフローをセマンティックとしてレポートのデータソースにすることも可能。  

1.3. Microsoft Fabric のデータフロー Gen2 について詳しく確認する
行レベルセキュリティはサポートしていない。  
クエリの設定ペインに表示されるデータ宛先オプションは、レイクハウス・Warehouse・SQL database・Azure SQL database・Azure Data Explorer・Azure Synapse Analyticsを設定することができる。

1.4. Microsoft Fabric でデータフロー Gen2 とパイプラインを統合する
データフローGen2はパイプラインと組み合わせると変換されたデータに対して塚の操作を実行する必要がある場合に便利  
パイプラインに組み込みデータフローの完了後にスクリプト・ストアドプロシージャの実行・メタデータの取得など追加のアクティビティを実行することも可能。  
データパイプラインはデータフローを実行するためにスケジューリングすることもトリガーによって実行することも可能。パイプラインを使用してデータフローを実行することで手動で実行する必要がなくなる。