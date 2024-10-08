---
sidebar_position: 80
---

# モーションレコーダー

モーションレコーダーを使用すると、キャラクターのアニメーションを記録し、FBX、BVH、もしくはWarudoのWANIM形式でアニメーションファイルを出力できます。

## 設定

録画したい **[キャラクター]** を選択します。 **[録画フレーム数]** と **[エクスポート形式]** を選択し、**[レコーディング開始]** をクリックして録画を開始します。**[レコーディング停止]** を押すといつでも録画を停止できます。

利用可能なエクスポート形式は3つあります。
* **FBX**: キャラクターのスケルトンとBlendShapeデータの両方を含むFBX形式でエクスポートします。
* **BVH**: キャラクターのスケルトンデータのみを含むBVH形式でエクスポートします。
* **WANIM**: キャラクターのスケルトンとBlendShapeデータ、および記録中にトリガーされたキャラクターの表情を含む、WarudoのWANIM形式でエクスポートします。Warudoでアニメーションを再生するだけの場合は、この形式が推奨されます。

:::caution
FBXエクスポートは実験的な機能であり、VRMモデルやMaya固有の機能 (例：IK、コンストレイントなど) を持たないFBXファイルからの `.warudo` モデルでは正常に動作しない可能性が高いことに注意してください。
:::

<AuthorBar authors={{
  creators: [
    {name: 'HakuyaTira', github: 'TigerHix'},
  ],
  translators: [
    {name: '星影月夜', github: 'unsolublesugar'},
  ],
}} />
