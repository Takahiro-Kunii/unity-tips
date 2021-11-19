ビルトインレンダーパイプラインは3つ。以下の順に特化性が上がる

* ビルトインレンダーパイプライン
* ユニバーサルレンダーパイプライン(URP)
* HD レンダーパイプライン(HDRP)

カスタムレンダーパイプラインを用意することも可能(C# コードで行うことも可能)

* [レンダーパイプライン設定方法](https://docs.unity3d.com/ja/2021.2/Manual/srp-setting-render-pipeline-asset.html)

#### レンダーパイプラインの主ステップ

![](https://docs.unity3d.com/ja/2021.2/uploads/Main/BestPracticeLightingPipeline3.svg)

#### ライティングパイプライン


![](https://docs.unity3d.com/ja/2021.2/uploads/Main/BestPracticeLightingPipeline15.svg)

* ジオメトリックシェーダーが提供されているが、Metalでは使えない


図は[unity documentation](https://docs.unity3d.com/ja/2021.2/Manual/BestPracticeLightingPipelines.html)より
