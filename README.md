README.md

# 【ユニティちゃんトゥーンシェーダー Ver.2.0.7】
「ユニティちゃんトゥーンシェーダー」は、セル風3DCGアニメーションの制作現場での要望に応えるような形で設計された、映像志向のトゥーンシェーダーです。  

ユニティちゃんトゥーンシェーダーVer.2.0では、従来の機能に加えて大幅な機能強化を行いました。  
Ver.1.0でできる絵づくりをカバーしつつ、さらに高度なルックが実現できるようになっています。  

● **[日本語マニュアル（v.2.0.7版）](https://github.com/unity3d-jp/UnityChanToonShaderVer2_Project/blob/master/Manual/UTS2_Manual_ja.md)が提供されています。合わせてご利用ください。**  


## 【Unity-Chan Toon Shader Ver.2.0.7】
Unity-Chan Toon Shader is a toon shader for video and images that is designed to meet your needs when creating cel-shaded 3DCG animations.  

We have greatly enhanced the performance and features in Unity-Chan Toon Shader Ver. 2.0.  
It still has the same rendering capabilities as Ver. 1.0, but now you can give your creations an even more sophisticated look.  

● **[English manual for v.2.0.7](https://github.com/unity3d-jp/UnityChanToonShaderVer2_Project/blob/master/Manual/UTS2_Manual_en.md) is available now.**  



----
## 【重要】v.2.0.4.3p1から、直接v.2.0.7へバージョンアップをする場合の注意
* 内部パラメタの名前変更のために、すでに設定されているマテリアルから、BaseMapが外れる可能性があります。外れてしまった場合、お手数ですが再設定をお願いします。  
* HiColor_Powerのスライダの感度調整をしました。Is_SpecularToHighColor=OFF/Is_BlendAddToHiColor=0FFの場合、HiColor_Powerの値を再調整する必要があります。Is_SpecularToHighColor=ONで利用している場合には、特に修正する必要はありません。  

### 【Important】 Notes on upgrading from v.2.0.4.3p1 directly to v.2.0.7
* There is a possibility that BaseMap may be removed from material already set because of renaming internal parameters. If it has come off, sorry to trouble you but please set it again.  
* Adjusted the sensitivity of the slider of HiColor_Power. If Is_SpecularToHighColor = OFF / Is_BlendAddToHiColor = 0FF, you need to readjust the value of HiColor_Power. If Is_SpecularToHighColor = ON is used, there is no need to modify it in particular.  

-----
## 【ターゲット環境】
Unity5.6.x もしくはそれ以降が必要です。  
Unity 2018.2.21f1からUnity 2019.2.0a9までの動作確認が終了しています。  
Unity 2017.4.15f1 LTSを含む、Unity 2017.4.x LTSでの動作確認済み。  
本パッケージは、Unity5.6.7f1で作成されています。  

### 【Target Environment】
Requires Unity 5.6.x or higher.  
The operation check from Unity 2018.2.21f1 to Unity 2019.2.0a9 has been completed.  
It has been tested on Unity 2017.4.x LTS, including Unity 2017.4.15f1 LTS.  
This pack was created in Unity 5.6.7f1.  


-----
## 【提供ライセンス】
「ユニティちゃんトゥーンシェーダーVer.2.0」は、UCL2.0（ユニティちゃんライセンス2.0）で提供されます。  
ユニティちゃんライセンスについては、以下を参照してください。  
http://unity-chan.com/contents/guideline/

### 【License】
Unity-Chan Toon Shader 2.0 is provided under the Unity-Chan License 2.0 terms.  
Please refer to the following link for information regarding the Unity-Chan License.  
http://unity-chan.com/contents/guideline_en/


-----
## 【プロジェクト全体のダウンロード/Download whole project】
### [UnityChanToonShaderVer2_Project (Zip)](https://github.com/unity3d-jp/UnityChanToonShaderVer2_Project/archive/master.zip)  


-----
## 【インストールの注意】
### [UTS2_ShaderOnly_v2.0.7_Release.unitypackage](https://github.com/unity3d-jp/UnityChanToonShaderVer2_Project/blob/master/UTS2_ShaderOnly_v2.0.7_Release.unitypackage)  

新規インストールは、Unityにそのまま本パッケージをD&Dすればインストールされます。  
上書きインストール時には、コードが改修されていますので、注意が必要です。  
1. 元のプロジェクトのバックアップをとっておく  
2. Unityでプロジェクトを開き、新規シーンを作成して開いておく。  
3. 元のトゥーンシェーダーが入っているフォルダ（Assets/Toon/Shader）をUnity上から削除する。  
4. 本パッケージをUnityにD&Dする。  

まず元のシェーダーを消した後で、すぐに新しいシェーダーをインストールすれば、既存のマテリアルへのリンクは途切れないので、そちらでやってみてください。  

個人でみられる範囲でバグチェックはしていますが、何か不具合があったらご連絡よろしくお願いします。

### 【Installation】
### [UTS2_ShaderOnly_v2.0.7_Release.unitypackage](https://github.com/unity3d-jp/UnityChanToonShaderVer2_Project/blob/master/UTS2_ShaderOnly_v2.0.7_Release.unitypackage)  
When installing for the first time, simply drag and drop this package into Unity to begin the installation process.  

When over-writing a previous version, the code will be revised, so please take the following precautions:  
1. Back-up all previous projects.  
2. When opening a project in Unity, create a new scene beforehand.  
3. Erase the folder containing previous versions of the toon shader (Assets/Toon/Shader) from within Unity.  
4. Drag and drop this pack into Unity.  

We recommend first erasing the previous shader then installing the new shader, to preserve existing links between materials.   

Please contact us if you have any issues. 


-----
## 【サンプルシーンについて】  
プロジェクトを開くと、`Sample Scenes`フォルダに以下のサンプルシーンがあります。  

・BoxProjection.unity：Box Projection を使った暗い部屋のライティング  
・ToonShader.unity：イラストルックのシェーダー設定  
・ToonShader_CelLook.unity：セルルックのシェーダー設定  
・ToonShader_Emissive.unity：エミッシブを使ったシェーダー設定  
・ToonShader_Firefly.unity：ビルトインライトと複数のリアルタイムポイントライト  
・Baked Normal/Cube_HardEdge.unity：Baked Normalの参考  
・Sample/Sample.unity：UTS2の基本シェーダーの紹介  
・ShaderBall/ShaderBall.unity：シェーダーボールを使ってUTS2を設定する  
・PointLightTest/PointLightTest.unity：ポイントライトを使ったセルルック表現のサンプル  
・SSAO Test/SSAO.unity：SSAO in PPSのテスト用  
・LightAndShadows/LightAndShadows.unity：Standard ShaderとUST2の比較  
・AngelRing/AngelRing.unity：「天使の輪」および ShadingGradeMap を使ったキャラクターのサンプル  
・MatCapMask/MatCapMask.unity：MatcapMaskのサンプル  
・EmissiveAnimation/EmisssiveAnimation.unity：EmissiveAnimationのサンプル  


各シーンは、シェーダーやライティングの設定の参考用です。  
作りたいルックやシーンの参考に役立つと思います。  

### 【About Sample scenes】  
When you open this project, there are the following sample scenes in `Sample Scenes` Folder  

・BoxProjection.unity: For lighting settings to dark room using Box Projection  
・ToonShader.unity: Illustration-like shader settings  
・ToonShader_CelLook.unity: Cellook Shader settings  
・ToonShader_Emissive.unity: Shader settings using Emissive  
・ToonShader_Firefly.unity: built-in light and multiple real-time point lights  
・Baked Normal/Cube_HardEdge.unity: Reference of Baked Normal  
・Sample/Sample.unity: Introduction of basic shaders of UTS2  
・ShaderBall/ShaderBall.unity: Set UTS2 using shader ball  
・PointLightTest/PointLightTest.unity: Sample of CelLook style using point lights  
・SSAO Test/SSAO.unity: For testing SSAO in PPS  
・LightAndShadows/LightAndShadows.unity: Comparison between Standard Shader and UST2  
・AngelRing/AngelRing.unity: Sample of "Angel's Ring" and ShadingGradeMap  
・MatCapMask/MatCapMask.unity: Sample of MatcapMask  
・EmissiveAnimation/EmisssiveAnimation.unity：Sample of EmissiveAnimation  


Each and every scenes are for reference of shader and lighting settings.  
They will be useful for reference of the look and scene you want to make!  

-----
## 【Version】
### 2019/03/23：2.0.7 Release：リリース版  
* 以下の新規機能を追加しました。  

#### 新規機能
* Emissive Animation機能を追加しました。  
* 本バージョンよりVulkan対応をしました。ただし、DX11 Tessellation版UTS2には対応していません。  

#### 機能強化
* Angel Ring Camera Rolling Stabilizerを搭載しました。（常にONです）  
* 全てのバージョンのUnityで、鏡に映るMatCapの像とCamera Rolling Stabilizerが正しく機能するようになりました。  


### 2019/03/23: 2.0.7 Release: Release version  
* The following new features have been added.  

#### New Features
* Added Emissive Animation function.  
* Vulkan support has been added from this version. However, DX11 Tessellation version UTS2 is not supported.  

#### Enhancement
* Equipped with Angel Ring Camera Rolling Stabilizer. (Always on)  
* In all versions of Unity, the MatCap image in the mirror and the Camera Rolling Stabilizer now work properly.  


---
### 2019/02/28：2.0.6 Release：修正リリース版  
* 「UTS2カスタムインスペクター」のデザインを再調整しました。合わせてマニュアルも更新しました。  

### 2019/02/21：2.0.6 Release：リリース版  
* 以下のバグフィックスと新規機能を追加。さらに一部機能の強化を行いました。  

#### 新UIを搭載  
* ShaderGUIベースの専用ユーザーインタフェース「UTS2カスタムインスペクター」を搭載しました。マニュアルも一新されています。  

#### バグフィックス  
* MatCapの合成モードが乗算（Is_BlendAddToMatCap = OFF）の時、リムライトが反映されてなかったのを修正しました。  
* MatCapの合成モードが乗算（Is_BlendAddToMatCap = OFF）の時、シャドウマスクとの順番が正しくなかったのを修正しました。  
* アウトラインモード/ポジションスケーリング方式の面判定を微調整しました。  

#### 新規機能  
* カメラのローリングに対してMatCapが回転してしまうのを抑止する Activate CameraRolling_Stabilizer を搭載しました。本機能は、TwitterID：@ShowBuyS さんのコントリビューションにより実現しました。  
* MatCap_Sampler に、Mip Mapに基づくぼかし機能 Blur Level of MatCap_Sampler を追加しました。  
* MatcapMaskテクスチャを反転する Inverse_MatcapMask を追加しました。  
* ShadingGradeMap機能を強化しました。レベル補正を行う Tweak_ShadingGradeMapLevel を追加した他、Mip Mapに基づくぼかし機能 Blur Level of ShadingGradeMap を追加しました。  

#### 機能強化  
* システムシャドウによるレシーブシャドウとシェーディングを馴染ませる Tweak_SystemShadowsLevel 機能を強化しました。  
* PointLights HiCut_Filter (ForwardAdd Only) = OFF の時、リアルタイムポイントライトにハイカラーが追加されるようにしました。  
* テッセレーションシェーダーのプロパティをわかりやすくした他、DX11 Tess : Extrusion Amount を調整しやすいようにスライダー化しました。  
* GIの強さを設定する GI_Intensity を機能強化しました。GIをUTS2マテリアルに反映させたい時には、まず GI_Intensity = 1 に設定してみてください。Standard Shaderとほぼ同様の明るさで反映されます。  
* ノーマルマップにバンプスケールを追加しました。  
* Transparent系シェーダーにデプスバッファの書き込み処理を追加しました。  

#### 変更  
* Unlit_Intensity の最大値を2から4へ変更しました。  

---
### 2019/02/28: 2.0.6 Release: Fixed release version
* We re-adjusted the design of "UTS2 Custom Inspector". Together we updated the manual as well.  

### 2019/02/21: 2.0.6 Release: Release version  
* Added following bug fixes and new features.  

#### New UI installed
* ShaderGUI based user interface "UTS 2 custom inspector" was installed. The manual has also been updated and redesigned.  

#### Bug Fix  
* Fixed that the rimlight was not reflected when the blend mode of MatCap was multiplying (Is_BlendAddToMatCap = OFF).  
* When the color blend mode of MatCap is multiplication (Is_BlendAddToMatCap = OFF), the order of shadow masks was incorrect was corrected.  
* Fine adjustment of surface judgment of outline mode / position scaling method.  

#### New Features  
* The new feature "Activate Camera Rolling_Stabilizer" which suppresses rotation of MatCap against the rolling of the camera was carried. This function was realized by Contribution of TwitterID: @ShowBuyS.  
* The new feature "Blur Level of MatCap_Sampler" based on Mip Map has been added to MatCap_Sampler.  
* The new function "Inverse_MatcapMask" to invert texture for MatcapMask was added.  
* The ShadingGradeMap function has been enhanced. In addition to adding "Tweak_ShadingGradeMapLevel" for level correction, "Blur Level of ShadingGradeMap" based on Mip Map has been added.  

#### Enhancements  
* Enhanced the Tweak_SystemShadowsLevel function to adapt to receive shadows and shading with system shadows.  
* When "PointLights HiCut_Filter (ForwardAdd Only) = OFF", high color is added to real time point light.  
* In addition to making the properties of tessellation shaders easy to use, "DX 11 Tess: Extrusion Amount" was made slidable for easy adjustment.  
* Improved the GI_Intensity to set the strength of GI. If you want GI to reflect on UTS2 material, please first set "GI_Intensity = 1". It is reflected at almost the same brightness as Standard Shader.  
* Bump scale added to normal map.  
* Depth buffer write processing has been added to Transparent shaders.  

#### Change  
* The maximum value of Unlit_Intensity has been changed from 2 to 4.


---
## 【過去の修正履歴】
2019/01/07：2.0.5 Release：macOS / Unity 2018.3.0f2上でプロジェクトを開くと不正終了するのを修正  
2018/11/22：2.0.5 Release：リリース版  
2018/11/17：2.0.5 Test07：バグ修正  
2018/11/16：2.0.5 Test06：SceneLights Hi-Cut_Filterを搭載。VR Chat対応完了  
2018/11/11：2.0.5 Test05：カメラ補正付きMatCapを搭載 
2018/11/08：2.0.5 Test04：リアルタイムポイントライト使用時のセルルック品質向上
2018/11/06：2.0.5 Test03：機能追加  
2018/10/31：2.0.5 Test02：機能追加  
2018/10/06：2.0.5 Test：BaseMapの内部変数名を変更。Built-in Light Directionを追加  
2018/09/10：2.0.4.3 Release Patch 1：バグフィックス版  
2018/09/05：2.0.4.3 Release：VRChat向けに便利な機能を搭載。アンビエントライトブレンディングなど  
2018/08/21：2.0.4.2 Release：バグフィックス版  
2018/08/16：2.0.4.2 Release：MatcapMaskを追加  
2018/07/04：2.0.4.1 Release：Unlit_Intensityプロパティを追加  
2018/05/04：2.0.4 Release：ターゲット環境をUnity5.6.x以降に。DX11 Phong Tessellation対応。VR Chat対応を開始  
2017/06/19：2.0.3：Set_HighColorMask、Set_RimLightMaskの追加  
2017/06/09：2.0.2：Nintendo Switch、PlayStation 4に正式対応  
2017/05/20：2.0.1：トランスペアレント系シェーダーを２つ追加  
2017/05/07：2.0.0：最初のバージョン  

### 【Version Update History】
2019/01/07: 2.0.5 Release: Fixed illegal termination when opening the project on macOS / Unity 2018.3.0f2.  
2018/11/22: 2.0.5 Release: Release version.  
2018/11/16: 2.0.5 Test07: Bugfix.  
2018/11/16: 2.0.5 Test06: SceneLights Hi-Cut_Filter. VR Chat ready!  
2018/11/11: 2.0.5 Test05: MatCap with camera skew correction.  
2018/11/08: 2.0.5 Test04: Cel-look quality when using real-time point lights has improved.  
2018/11/06: 2.0.5 Test 03: Added some features.  
2018/10/31: 2.0.5 Test 02: Added some features.  
2018/10/06: 2.0.5 Test: The internal variable name of BaseMap had been changed. Add Built-in Light Direction.  
2018/09/10: 2.0.4.3 Release Patch 1: Bugfix.  
2018/09/05: 2.0.4.3 Release: Added useful features for VRChat users. Ambient light blending.  
2018/08/21: 2.0.4.2 Release: Bugfix.  
2018/08/16: 2.0.4.2 Release: Added MatcapMask.  
2018/07/04: 2.0.4.1 Release: Added Unlit_Intensity property.  
2018/05/04: 2.0.4 Release: Set Unity5.6.x and later versions as the target environment. DX11 Phong Tessellation support. Started VR Chat support.  
2017/06/19: 2.0.3: Added Set_HighColorMask and Set_RimLightMask.  
2017/06/09: 2.0.2: Official support for Nintendo Switch and PlayStation 4.  
2017/05/20: 2.0.1: Added 2 transparent shaders.  
2017/05/07: 2.0.0: Initial version   


-----
最新バージョン：2.0.7 Release  
最終リリース日：2019/03/23  
カテゴリー：3D  
形式：zip/unitypackage  

Latest Version: 2.0.7 Release  
Update: 2019/03/23  
Category: 3D  
File format: zip/unitypackage  
