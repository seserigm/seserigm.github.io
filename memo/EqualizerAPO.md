---
---

# Equalizer APO のすすめ

PCオーディオを自分好みの音で楽しみたい人へ、**Equalizer APO**のすすめ。

## 目次

1. [この記事の対象者と非対象者](#この記事の対象者と非対象者)
1. [Equalizer APOとは](#Equalizer-APOとは)
1. [導入と基本的な使い方](#導入と基本的な使い方)
1. [応用的な使い方](#応用的な使い方) **＊このページの目的＊**
    - 残響をミックスして立体的な音響にする
1. [知っておいたほうが良いかも知れないこと](#知っておいたほうが良いかも知れないこと)
    - 音の大きさによる聞こえ方の違い

なお、これより下のリンクはすべて外部サイトへのリンクです。

## この記事の対象者と非対象者

この記事は、以下のような人に向けて書いています。

- Windowsパソコンで再生する音を自分好みに調整したい人

対して、以下のような人には向けていません。

- ピュア志向の人
- Windowsパソコンで音楽を聞かない人
- ASIOまたはWASAPI排他モードを使いたい人
- 特定のソフトの音質だけを調整したい人

なお参考までに、この記事を書いた人の環境は以下のとおりです。

項目|記事を書いた人の環境
---|--:
OS|Windows 10 Pro
音楽再生アプリ|foobar2000
ヘッドフォン|ATH-A700X, ATH-M50, etc
ヘッドフォンアンプ|AT-HD26D

## Equalizer APOとは

Equalizer APO は、Windows Vista 以降で使えるイコライザアプリです。システムレベルで動作し、Windowsで再生するすべての音(\*)に対して適用されます。

[公式ページ](https://sourceforge.net/projects/equalizerapo/)

\* Windows Vistaで導入されたAPOという仕組みを利用して動作するため、ASIOやWASAPI排他モードなどAPOをバイパスして出力する音には適用されません。

## 導入と基本的な使い方

導入と基本的な使い方は、以下のサイトで丁寧に案内されています。  
英語ソフトですが日本語化せずとも使えるでしょう。

[イコライザーソフト「Equalizer APO」 | FreesoftConcierge](https://freesoft-concierge.com/media/equalizer-apo/)

## 応用的な使い方

### 残響をミックスして立体的な音響にする

残響を掛け合わせ（Convolution with impulse response）て、立体的な音響にする方法です。  
**＊これが書きたくてこの記事を作りました＊**

#### 用意するもの

- Impalse ResponseのWAVファイル

掛け合わせる残響のWAVファイルが必要です。無料で公開されているものがいくつかあります。周波数域等が選べる場合は、自身の環境にあったものを選んでください。

おすすめは、インターネットアーカイブに残る Bricasti M7 Impulse Response Library です。bit深度は最適なものがあればそれを選びます。合わなくても動作します。

- [Samplicity's Bricasti M7 Impulse Response Library v1.1 - Samplicity - web.archive.org](https://web.archive.org/web/20190201211631/http://www.samplicity.com/bricasti-m7-impulse-responses/)

## 知っておいたほうが良いかも知れないこと

### 音の大きさによる聞こえ方の違い

ラウドネス（Loudness）効果の話。

- [音の大きさ - Wikipedia](https://ja.wikipedia.org/wiki/%E9%9F%B3%E3%81%AE%E5%A4%A7%E3%81%8D%E3%81%95)
- [【Seminar】音量感の新基準！ラウドネスの基本を学ぶ｜サウンド＆レコーディング・マガジン2018年7月号より|PICK UP|リットーミュージック](https://www.rittor-music.co.jp/pickup/detail/15600/)
