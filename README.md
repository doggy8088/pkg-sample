# pkg-sample

這是一個簡單的 `pkg` 使用範例，使用 [zeit/pkg](https://github.com/zeit/pkg) 建立一個 Node.js 專案為跨平台的可執行檔。

## 建置專案的方式

```
# 安裝 pkg 套件
npm i -g pkg

# 建置步驟
git clone https://github.com/doggy8088/pkg-sample.git
cd pkg-sample
pkg . --out-dir output
```

# 建置結果大小 (使用 pkg@3.0.0-beta.33 版本)

```
33,240K pkg-sample-linux
33,512K pkg-sample-macos
20,944K pkg-sample-win.exe
```
