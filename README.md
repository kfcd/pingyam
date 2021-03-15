# 粵語拼音轉換表

## 說明

本表根據[開放詞典網](https://kaifangcidian.com/)數據，對照粵語（白話/廣東話/廣州話）的各種拼音系統之間的轉換關係，以便於提供多元化的拼音轉換功能。2009年起，[開放粵語詞典](https://kaifangcidian.com/han/yue)便以此表標出搜索結果的拼音信息。

其特點在於每個音都標出所有可能的調值，亦儘量收錄“有音無字”的音節，以正確顯示轉寫方式之間在實用情況下的差異（類似拼音表一般標音不標調）。

## 粵文轉寫

與漢語/普通話不同，粵語的拼音轉寫方案繁多，其中未有一套學者、官方、母語者、和外國人都一致使用的標準，所以出現一種“因地而異，因書而異，因人而異”的標音情況。

本表已有Ruby、JS等語言的實現示例，希望以此便利學者等無障礙地拼寫粵語，同時減少世人學習和使用粵語時會遇到的相關麻煩。

## 包含轉寫方案

* [耶魯拼音](https://zh.wikipedia.org/wiki/耶魯拼音) (數字)
* 耶魯拼音 (調符)
* [教院式拼音](https://zh.wikipedia.org/wiki/教育學院拼音方案)
* [黃錫凌羅馬拼音](https://zh.wikipedia.org/wiki/黃錫凌羅馬拼音) (數字)
* 黃錫凌羅馬拼音 (調符)
* [國際音標](https://zh.wikipedia.org/wiki/國際音標)
* [粵拼](https://zh.wikipedia.org/wiki/香港語言學學會粵語拼音方案) (香港語言學學會粵語拼音方案)
* [廣州拼音](https://zh.wikipedia.org/wiki/廣州話拼音方案) (廣州話拼音方案)
* [劉錫祥拼音](https://zh.wikipedia.org/wiki/劉錫祥拼音)
* [粵語拼音字](https://zh-yue.wikipedia.org/wiki/廣東話拼音) (數字) (廣東話拼音、_Penkyamp_)
* 粵語拼音字 (調符)


### 轉寫方案一覽

耶魯 (數) | 耶魯 (調) | 教院 | 黃錫凌 (數) | 黃錫凌 (調) | 國際音標 | 粵拼 | 廣州拼音 | 劉錫祥 | 粵語拼音字 (數) | 粵語拼音字 (調)
-------- | -------- | ---- | ---------- | ---------- | ------- | ---- | ------- | ----- | ------------- | -------------
ping1 | pīng | ping1 | pɪŋ¹ | 'pɪŋ | pʰɪŋ˥ | ping1 | ping1 | ping¹ | penk1 | pënk

## 實現示例

* Ruby: [pingyam-rb](https://github.com/dohliam/pingyam-rb)
* JavaScript: [pingyam-js](https://github.com/dohliam/pingyam-js)
* Lingvo DSL 詞典格式

## 待處理

* 反切
* 漢字示例
* 港府方案
* 粵語羅馬字

## 另見

* [漢語拼音轉換表](https://github.com/kfcd/pinyin)
* [閩南語拼音轉換表](https://github.com/kfcd/pheng-im)

## 版權

© 2015 [開放詞典](https://www.kaifangcidian.com)

本倉庫內容依照創作共用（創用CC/知識共享）姓名標示（署名）協議發佈。

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="創用 CC 授權條款" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a><br />本著作係採用<a rel="license" href="https://creativecommons.org/licenses/by/3.0/">創用 CC 姓名標示 3.0 未本地化 授權條款</a>授權.
