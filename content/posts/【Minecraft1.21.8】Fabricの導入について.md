---
title: "【Minecraft1.21.8】 Modの導入について（Fabric編）"
date: 20250621
draft: false
ShowToc: False
---
# はじめに
この記事ではMinecraft1.21.8にて、modローダー「Fabric」を使ったシェーダーとMODの導入手順について詳解して行きます。
# 影Mod導入まで
## 必要ファイルのダウンロード
以下のリンクから必要となる
## MOD用のディレクトリを新規に作成
- C:\Users\<Windowsのユーザー名>\AppData\Roamingにある.minecraftフォルダを名前を変えてコピー（例：.minecraft_fabric_1.21.8)
## Modローダー「Fabric」の導入  
- [Fabric Installer-1.1.0.exe]を起動し、以下の設定をしてインストールする。
 - 「バージョン」：いまから入れようとしているバージョン
 - 「ローダーバージョン」：基本的に<最新のもの>を選択。
 - 「インストール先：」に<手順1で作ったフォルダ>を指定。
 - 「起動構成を作成」にチェックを入れる

## シェーダー「Iris」と軽量化MOD「Sodium」の導入
※この２つは切っても切り離せない、セットのようなもの
- [Iris-Installer-3.2.1.jar]を起動し、以下の設定をしてインストールする。
 - 「Select Game Version」：今入れようとしているバージョンを指定
 - 「Installation Type」：「Iris Only」を選択。
 - 「Installation Directory」：<手順1で作ったフォルダ>を指定。
この手順が終わった段階で、「Fabric」「Iris Shaders」「Sodium」が環境に入っているはず。

## シェーダーの導入とMinecraftの起動
- 任意のシェーダーパック（.zip形式）をダウンロード
- ダウンロードしたものを「C:\Users\<Windowsのユーザー名>\AppData\Roaming\.minecraft_fabric_1.21.8\shaderpacks」フォルダに入れる。
- [Minecraft Lancher]を起動する。
- 「Iris & Sodium for <version>」という起動構成ができているので、それを起動。
- Minecraftが正常についたら導入成功。
- Minecraftホーム画面の「設定>ビデオ設定>シェーダーパック」を開く
- 表示されているシェーダーを選択して、設定を適用して見た目が変わったら導入成功

## 前提Mod「Fabric API」の導入
-
- Iris Installersでコピーしたディレクトリを指定してIris Shadersを入れる
- Mniecraft Lancherで起動構成を作成する
 （このとき、Versionは[fabric]がついているものがあるのでそれを選択すること） 


 （コピーしたディレクトリを指定すること）
