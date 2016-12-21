# 写真ビューア

## 出来る事

* 写真撮影
* アルバムの写真表示
* 写真回転

## 対応プラットフォーム

* Android

* iOS

## 使い方

### 前準備

* [Android SDK](https://developer.android.com/studio/index.html?hl=ja#downloads)をインストール

* [NodeJS](https://nodejs.org/ja/)をインストール

* Cordovaをインストール
```
npm install -g cordova
```

### 動作確認

* git clone
```
git clone https://github.com/hitdev01/handson-monaca-easy01.git
```

* Cordovaで動作確認

for android

```
cd cordova/koma
cordova platform android
cordova plugin add cordova-plugin-camera
cordova run android
```

for ios

```
cd cordova/koma
cordova platform ios
cordova plugin add cordova-plugin-camera
cordova run ios
```
