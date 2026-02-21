---
layout: default
title: Zotero 介紹
description: 一份關於 Zotero 的開源使用教學，採用 GPLv3 授權。
lang: zh-Hant
---

![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)

# Zotero 介紹

## 特點

這是一個

- 可導出相容於 **Word/LaTeX/Overleaf** 的文獻格式
- **跨平台**：Windows/MacOS/Linux/iOS/Android 都可以用
- **免費**且**開源**
- 可多裝置**同步**
- 可方便地在PDF檔案或是網頁上面註記
- 有很多開源且免費的插件可以擴充功能

的文獻管理軟體

## 有了 Zotero 能做什麼？

### 快速下載文獻

#### 以 [arxiv.org](https://arxiv.org/) 為例

一旦進入想下載的 paper 的頁面，[Zotero 瀏覽器插件](#zotero-電腦版與瀏覽器插件)會自動識別出這是 arxiv 上的文獻。 
點擊後 PDF 和該頁面的 html 快照會自動下載至 Zotero 當前的資料夾中。

![](attachment/2ddfda1f2a1f08bc7d3762d24ba0cb49.png)

![](attachment/970d5a13ab836cf84145a16a93fa9b6b.png)

回到 Zotero，即可看到文獻的詳細資料，相關附件也整齊地收納在這個物件底下。也就是說不再需要一個一個下載再放到同一個資料夾。

![](attachment/a1a9a5d82910311d8ae57747ec7a8aa9.png)

#### 以 [Medium](https://medium.com/) 為例

![](attachment/86db063106d035422cef740894d6a8ea.png)
  
### 文獻閱讀與筆記

#### 在 PDF 檔上做筆記

在 Zotero 中連點兩次該文獻會開啟閱讀板面。
此時可以在文獻上做筆記、註記，若有手寫筆也可以手寫！  

![](attachment/7db51b3362b6d6b2b1ba4f665c00b867.png)

#### 在網頁上做筆記

文章以網頁快照的方式存下後，同樣可以直接在上面註記

![](attachment/bdddd958a785e221f7601c552fe9113f.png)

可以放大縮小！

![](attachment/098cc9eaa2d0b27974c956a7e7955f17.gif)

#### 論文翻譯

[點我跳轉至教學](#translate-for-zotero)

![](attachment/bc720cf5d11ca765ba907379778ae510.png)

### 與 Word 連動

[點我跳轉至教學](#word)

選擇選單中的 Zotero 後，即可插入引用和新增參考文獻。

![](attachment/9a0a65cb0ec79023f1e919051159fca7.png)

### 導出 BibTeX for LaTeX  

[點我跳轉至教學](#overleaflatex)

在安裝 Better BibTeX 插件後，可以快速取得下方的引用資料，直接貼進 LaTeX/Overleaf 中

```bibtex
@misc{wang2022InterpretabilityWildCircuit,
  title = {Interpretability in the {{Wild}}: A {{Circuit}} for {{Indirect Object Identification}} in {{GPT-2}} Small},
  shorttitle = {Interpretability in the {{Wild}}},
  author = {Wang, Kevin and Variengien, Alexandre and Conmy, Arthur and Shlegeris, Buck and Steinhardt, Jacob},
  year = {2022},
  month = nov,
  number = {arXiv:2211.00593},
  eprint = {2211.00593},
  primaryclass = {cs},
  publisher = {arXiv},
  doi = {10.48550/arXiv.2211.00593},
  urldate = {2026-02-21},
  archiveprefix = {arXiv},
  langid = {american},
}
```


### 複製格式化後的引用資料

Zotero 內建了很多不同的引用標準。
這邊以IEEE標準為例，結果如下：

```txt
[1]

K. Wang, A. Variengien, A. Conmy, B. Shlegeris, and J. Steinhardt, “Interpretability in the Wild: a Circuit for Indirect Object Identification in GPT-2 small,” Nov. 01, 2022, _arXiv_: arXiv:2211.00593. doi: [10.48550/arXiv.2211.00593](https://doi.org/10.48550/arXiv.2211.00593).
```


## 安裝

### Zotero 電腦版與瀏覽器插件

進入[Zotero 官網](https://www.zotero.org/)後，點選中央紅色的 Download 會跳轉至下載頁面。

![](attachment/fc47308839cb9cb762f969dd9d565d18.png)

左邊是下載對應作業系統的版本，右邊是瀏覽器插件。兩個都裝可以讓 Zotero 發揮最強大的能力！

![](attachment/a8da04808c405359e7875c4857cbbaa9.png)

### Zotero on 手機/平板

## 基礎使用

### 1. 新增 Collection

在左上角有一個像資料夾的圖示，相當於幫 project 或是正在撰寫的論文開一個資料夾，來存放和它相關的文獻。
點進去這個 collection 後，任何從 [Zotero Connector(瀏覽器插件)](#zotero-電腦版與瀏覽器插件) 下載的文件會自動收納在這個 collection 底下。

![](attachment/a8ef82a45616dd3a1778acdfbb586148.png)

### 2. 新增文獻

除了[直接從瀏覽器導入](#快速下載文獻)之外，也可以把電腦上的檔案拖進 collection 中，會自動嘗試抓取metadata 和 PDF。
如果有抓取成功，就可以讓 Zotero 自動格式化引用。
導入後原本的那個檔案可以刪掉，因為 Zotero 已經複製一份存放在安全的地方了。

![](attachment/1910d57f9804f75c4a2137f0f6b71fe3.gif)

### 3. 在文獻上做筆記

請參考[這一節](#文獻閱讀與筆記)。若想使用 Zotero 來做筆記，請開啟設定 (MacOS快捷鍵：`command` + `,`)，並將 Reader 中的 `Open PDFs using` 以及 `Open snapshots using` 設定成 `Zotero`。
相反地，若想用電腦上的預設應用程式開啟，請選擇 `System Default`。

![](attachment/654c795737b512fe09682972cae4e7bc.png)

### 4. 引用文獻

#### Word

開啟 Word 後會出現 Zotero 選單。
進入 Zotero 選單，游標點在想要的位置後

1. 點擊左上角 `Add/Edit Citation`

   ![](attachment/dd80dd7ecd31f1ea53c9c7a262e280b8.png)
2. 選擇要引用的文獻，可以複選，選好後按 `Enter`

   ![](attachment/1712b4ed2b380d2adef689a0f681ed98.png)
3. 成功引用

   ![](attachment/9590dbd8057f8934c7c99a717c34c0b6.png)
4. 點選「參考文獻」的位置後，再點選選單中的 `Add/Edit Bibliography` (在剛剛`Add/Edit Citation` 的右邊)

   ![](attachment/9804f8e8e88334a3333635b7764c0c4d.png)
   
   就會自動把參考資料依照設定好的格式填上：
   
   ![](attachment/d160f611950b2b059d54d9a400977b65.png)
5. 之後引用其它文獻時，會自動更新參考文獻：

   ![](attachment/47f42917c91caa08e8543213c73cd31a.gif)

#### Overleaf/LaTeX {#overleaflatex}

以在Overleaf上編輯 `.bib` 檔為例。請先[下載 Better BibTeX 插件](#better-bibtex)。
接著，對想引用的文獻 `右鍵 -> Better BibTeX -> copy BibTeX to clipboard`

![](attachment/37357a8526bc0e11c1a2ebb9e59388d8.png)

回到 Overleaf 貼上：

![](attachment/6795697e94c1b597a1f016bf687a4d42.png)

### 5. 匯出檔案

`右鍵 ->  Show in Finder` (MacOS) 可以查看原始檔案存放的位置。

![](attachment/edf7c60879c55560044f02cd15464092.png)

![](attachment/d8bfb2a909699cd12d6348abc7917149.png)

這是匯入文獻當下Zotero自己產生的副本。點開會發現上面並沒有註記，這是因為Zotero並不會直接去更改原始檔。若想與他人分享筆記，請回到 Zotero 點選想匯出的 PDF，並選擇 `File -> Export PDF...`

![](attachment/dcd677bf58274cbaebb437db39ef5583.png)

就可以匯出帶有註記的 PDF 檔並分享檔案給他人。

![](attachment/27ae0f309fd59ad42525fd73631cf136.png)

## 相關插件

Zotero有許多開源的插件，絕大部分的原始碼可以在GitHub上看到，並有很多網友一同檢視其安全性問題和功能的更新。

> [!caution] 關於第三方插件
> 雖然絕大多數的插件皆開源且免費取用，但仍有部分插件有付費後才會開放的功能。
> 
> 另外，有一些插件需要提供API Keys或是其它私人資訊，請先看過GitHub頁面相關的討論來判斷此插件是否安全。

以下以 Better BibTeX 插件為例，示範如何安裝插件。

### Better BibTeX

[GitHub 頁面](https://github.com/retorquere/zotero-better-bibtex)

1. 進入GitHub頁面後點擊 `Releases` (紅框處)

   ![](attachment/b4e5445e354ee6af2468e589e189405a.png)
2. 找到後綴 `.xpi` 的檔案並下載。如果使用 Firefox 瀏覽器，需要 `右鍵 -> Save Link As...`

   ![](attachment/33065e9aa06130ace38d1c2503eefdae.png)
3. 回到 Zotero，點選 `Tools -> Plugins`

   ![](attachment/b2b81a9da055c2da99e487f46f132960.png)
4. 在右上角的齒輪中選 `Install Plugin From File...`

   ![](attachment/9093dfe0812f71f53234f2aebce29253.png)
5. 選擇剛剛的 `.xpi` 檔就會安裝

   ![](attachment/f668afc23dc53b1121792aa002962cd4.png)
6. 安裝好後若想設定它，進 Zotero 的設定 (MacOS 快捷鍵 `command` + `,`) 即可。

### Translate for Zotero

安裝插件方式請參考[以安裝 Better BibTeX 為例的教學](#better-bibtex)

- [GitHub 頁面](https://github.com/windingwind/zotero-pdf-translate#readme)
- 若想使用自己的API key用ChatGPT來翻譯，請去Zotero 的設定 (MacOS 快捷鍵 `command` + `,`) 輸入 key

  ![](attachment/8f73a005230f49f20c1708c4f2a1cc90.png)

### Obsidian Notes for Zotero

- [Github 頁面](https://github.com/PKM-er/obsidian-zotlit)
- 如果有使用 Obsidian 來做筆記的話，經過設定可以做到
	- 從 Zotero 中建立筆記至 Obsidian
	
	  ![](attachment/eeced7c278b0a1a28b618ef27e1d9195.gif)
	- 將 Zotero 中的註記直接拖入 Obsidian 中
	
	  ![](attachment/a0282c922c684785a4fd254269cc5352.gif)
- 請參考插件作者寫的[文件](https://zotlit.aidenlx.top/)來設定


---
## 授權條款 (License)
本專案筆記採用 [GNU General Public License v3.0 (GPLv3)](LICENSE) 授權開放。
任何人皆可自由引用、修改，但請務必保留此版權聲明，並以相同授權開放。
