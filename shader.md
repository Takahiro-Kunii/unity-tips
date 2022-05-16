ビルトインレンダーパイプラインは3つ。以下の順に特化性が上がる

* ビルトインレンダーパイプライン
* ユニバーサルレンダーパイプライン(URP)
* HD レンダーパイプライン(HDRP)

カスタムレンダーパイプラインを用意することも可能(C# コードで行うことも可能)

* [レンダーパイプライン設定方法](https://docs.unity3d.com/ja/2021.2/Manual/srp-setting-render-pipeline-asset.html)

#### レンダーパイプラインの主ステップ

![](https://docs.unity3d.com/ja/2021.2/uploads/Main/BestPracticeLightingPipeline3.svg)

* ジオメトリックシェーダーが提供されているが、Metalでは使えない
* [ビルトインレンダーパイプラインの使用](https://docs.unity3d.com/ja/2021.2/Manual/built-in-render-pipeline.html)
* [カスタムレンダーパイプラインの作成](https://docs.unity3d.com/ja/2021.2/Manual/srp-custom.html)


[Universal Render Pipeline overview](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@12.1/manual/index.html)

プロジェクトのマテリアルをビルトインレンダーパイプラインから HDRP か URP に変換するのは、

1. Edit > Render Pipeline > Upgrade… 
2. マテリアルコンバーター

不可逆的な操作であることに注意


図は[unity documentation](https://docs.unity3d.com/ja/2021.2/Manual/BestPracticeLightingPipelines.html)より


URPシェーダーサンプル
https://gist.github.com/shivaduke28/b224ebaebf4d70b7bd7ad396ecf2af31
