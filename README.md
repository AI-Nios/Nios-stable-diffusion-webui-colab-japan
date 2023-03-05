# stable-diffusion-webui-colab-japanese

### Google ColaboratoryでStable Diffusion WebUIと様々な学習済みcheckpointファイルを簡単に導入でき、日本人向けに使いやすくしたものです。
 Twitter→ https://twitter.com/ai_nios/status/1617901380370587654 <br>
 note→　https://note.com/ai_nios/n/n0826a33edc8a
## 🦒 Colab
| Colab Page 
| --- 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI-Nios/Nios-stable-diffusion-webui-colab-japan/blob/main/Nios_Model_Card_Selection.ipynb) Nios_Model_Card_Selection.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI-Nios/Nios-stable-diffusion-webui-colab-japan/blob/main/Nios_v2_update.ipynb) Nios_v2_update.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AI-Nios/Nios-stable-diffusion-webui-colab-japan/blob/main/Nios_v3.ipynb) Nios_v3.ipynb
【推奨ブラウザ】PC:Chrome, Edge スマホ: googleアプリ, safari

## 注意事項
###  生成した画像の利用については自己判断および自己責任でお願いします。

## 問題
頻繁にモデルを切り替えるとエラーが発生する<br>
Hires.fixで高い解像度の設定を行うとエラーが発生する<br>
ランタイムの変更でGPUクラスを標準/プレミアの選択でプレミアを選択、あるいはランタイムの仕様で標準/ハイメモリでハイメモリを選ぶとエラーが発生する<br>
ファイルサイズの大きいckptファイルに切り替えるとWebUIが停止する<br>

## Colab Pageの概要
### Nios_Model_Card_Selection.ipynb
使用方法:noteに記載 URL → https://note.com/ai_nios/n/n0826a33edc8a 
### Nios_v2_update.ipynb
より多くのcheckpointファイルを選択できます。
Nios_Model_Card_Selection.ipynbのプログラムコードに加え、公開されてる学習済みのLoRAやTextual InversionをColab上から選択してダウンロードできるプログラムコードを追加しています。<br>
ControlNetを使用できます。
### Nios_v3.ipynb
https://github.com/camenduru/stable-diffusion-webui-colab/tree/v2.0 のColabのソースコードに基づき、Nios_v2_update.ipynbと同じ感覚で使用できるようにしました。<br>

## 追加・変更のお知らせ
### 2023/02/05<br>
EasyNegative追加。ネガティブプロンプトにEasyNegativeといれることにより余計な否定プロンプトを書く必要がなくなりました。<br>
### 2023/02/10<br>
WebUI拡張機能 Aspect Ratio selectorの追加。画像のアスペクト比セレクターボタンを追加しました。 1:1,2:3,3:4,9:16など<br>
WebUI拡張機能 images-browserの追加。WebUI起動後から現在までに生成された画像を閲覧することができます。<br>
### 2023/02/18<br>
WebUI拡張機能 Push to 🤗 Hugging Faceの追加。WebUI上からモデルやVAE、LoRAを追加することができます。<br>
WebUI拡張機能 ControlNet追加しました。<br>

## 対応モデル名(Nios_v2_update.ipynb以降）<br>
### checkpointファイル<br>
"stable_diffusion_v1.5","stable_diffusion_v2.1","waifu_diffusion_v1.3","Openjourney","anything-v3.0","anything-v4.0","anything-v4.5","Counterfeit-V2.0","Counterfeit-V2.5","8528-diffusion","AbyssOrangeMix2","EerieOrangeMix2","trinart2_step115000","Eimis Anime Diffusion_1.0v","dreamlike-photoreal-2.0","Cyberpunk-Anime-Diffusion","Plat Diffusion v1.3.1","ACertainThing","pastel_mix","Basil_mix_fixed","Realistic Vision V1.3","SukiyakiMix-v1.0","7th_anime_v1.1", "7th_anime_v2_A", "7th_anime_v2_B", "7th_anime_v2_C", "7th_anime_v2_G", "7th_anime_v3_A", "7th_anime_v3_B", "7th_anime_v3_C","7th_anime_3.1_B","YuzuGinger_v4","YuzuLemonMilk_v1.5", "Defmix-v1.1","RDtMix","meadmix","Nabylon-v1.0","LonganMix","Corneo's 7th Heaven Mix", "Corneo's Shinra26 Mix","atwmix_test2","Graham_Special", "BalorV2featAbyssOrange2","Balor-V2.5featAOM3A3","ChilloutMix", "wd-1-5-beta2"

## WebUI拡張機能(Extensions)
･[Stable Diffusion WebUI Aspect Ratio selector(アスペクト比セレクター)](https://github.com/alemeliTwitters/sd-webui-ar)<br>
･[stable-diffusion-webui-images-browser(イメージ ブラウザ)](https://github.com/yfszzx/stable-diffusion-webui-images-browser)<br>
･[Push to 🤗 Hugging Face](https://github.com/camenduru/stable-diffusion-webui-huggingface)<br>
･[Booru tag autocompletion for A1111(タグのオートコンプリート)](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete)<br>
･[Dataset Tag Editor](https://github.com/toshiaki1729/stable-diffusion-webui-dataset-tag-editor)<br>
･[Merge Block Weighted - GUI](https://github.com/bbc-mc/sdweb-merge-block-weighted-gui)<br>
･[sd-civitai-browser](https://github.com/camenduru/sd-civitai-browser)<br>
･[Additional Networks for generating images](https://github.com/kohya-ss/sd-webui-additional-networks)<br>
･[Latent Couple extension (two shot diffusion port)](https://github.com/opparco/stable-diffusion-webui-two-shot)<br>
･[sd-webui-controlnet](https://github.com/Mikubill/sd-webui-controlnet)<br>
･[Openpose Editor](https://github.com/camenduru/openpose-editor)<br>
･[sd-webui-depth-lib](https://github.com/jexom/sd-webui-depth-lib)<br>
･[stable-diffusion-webui-chatgpt-utilities](https://github.com/hallatore/stable-diffusion-webui-chatgpt-utilities)（OpenAIの有料アカウントが必要）<br>
