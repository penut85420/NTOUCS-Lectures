# NTOUCS Lectures

## Table of Contents
- [NTOUCS Lectures](#ntoucs-lectures)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Usage](#usage)
  - [Branch](#branch)
  - [Contribution](#contribution)
  - [Contact Information](#contact-information)
  - [Copyright](#copyright)

## Introduction
+ 這裡是保存海大資工課程講義的 GitHub Repository
+ 我們將不同學期不同課程的講義放在不同的 Branch 裡面

## Usage
+ 新建一個資料夾
+ 進入資料夾後輸入以下指令
  ```bash
  git init
  git remote add origin https://github.com/penut85420/NTOUCS-Lectures.git
  git pull origin master
  ```
+ 選定一個目標 Branch
  + 例如 `1052-wbse` 代表「1052 網頁軟體工程」的課程講義
  + 輸入以下指令
    ```bash
    git branch 1052-wbse
    git checkout 1052-wbse
    git pull origin 1052-wbse
    ```
+ 打開資料夾就會看到講義被 Pull 下來了

## Branch
| Branch | Description |
| :----- | :---------- |
| `1052-wbse` | 1052 網頁軟體工程 |
| `1061-prob-final` | 1061 機率論期末考古題 |
| `1062-information-security` | 1062 資訊安全實務與管理 |
| `1071-bigdata` | 1071 大數據分析 |

## Contribution
+ 如果想要貢獻其他課程講義，請遵守以下步驟：
  + Fork 這個 GitHub Repository
  + 在本地端創建一個新的 Branch
    + 命名規則為 [學期]-[課程簡稱]，例如 `1052-wbse`
  + 將課程講義放在一個獨立的資料夾，命名為 `[學期]-[課程名稱]`，並確保專案路徑如下：
     ```
    ./NTOUCS-Lectures
    ├── .git
    ├── [學期]-[課程名稱]
    │   ├── Ch01.pdf
    │   ├── Ch02.pdf
    │   └── ...
    └── README.md
     ```
  + 在 `README.md` 內寫下課程相關資訊，範本可參考其他 Branch
    + 課程詳細資訊可以在教務處查到
      + [歷史資料](https://tinyurl.com/y7s9oarn)
      + [當期資料](https://tinyurl.com/y4p73gdd)
  + Commit Message 內容為 `Add [Branch-Name]`，例如 `Add 1052-wbse`
    + 若有新增講義，格式為 `Upload [File-Name]`，例如 `Upload Ch1.pdf`
    + 若有修改講義，格式為 `Modify [File-Name]`，例如 `Modify Appendix.docx`
    + 若有刪除講義，格式為 `Remove [File-Name]`，例如 `Remove Ch2Ch3_copy.pdf`
    + 唯一例外為更新 `README.md`，一律為 `Update README.md`
  + 完成後發送 Pull Request

## Contact Information
+ 如果有其他問題，歡迎發 Issue
+ Discord: PenutChen#2135
+ Email: penut85420@gmail.com

## Copyright
+ 所有課程講義的著作權屬於該課程教授所有，本專案僅作為學術交流分享用途
