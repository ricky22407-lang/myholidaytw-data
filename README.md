# MyHoliday TW Research — 開放資料集 Open Datasets

[MyHoliday 旅遊攻略誌](https://www.myholidaytw.com)（MyHoliday TW Research）發布的台灣旅遊產業研究報告開放資料集鏡像。

Open datasets from [MyHoliday TW Research](https://www.myholidaytw.com/research-lab) — research source corpora behind our Taiwan travel-industry reports.

## 內容 What's inside

每份產業報告對應一組資料檔（`data/` 目錄）：

- `{slug}.json` — 完整資料集：報告 metadata、研究方法、來源語料庫（產業來源 + 社群討論，含平台、標題、URL、蒐集日期）
- `{slug}.csv` — 同內容的表格版（UTF-8 BOM，Excel 可直接開啟）

資料為**真實搜尋結果快照**（Google SERP via Serper API + PTT/Dcard/Reddit 社群討論），不含任何模型生成的數字。各報告的完整分析請見對應的報告頁。

## 報告列表 Reports

| 資料集 | 報告全文 |
|---|---|
| 2026年旅遊保險市場需求分析產業如何發展？數據驅動分析報告 | https://www.myholidaytw.com/reports/lv-you-bao-xian-xu-qiu-fen-xi-market |
| 民宿短租Airbnb市場分析市場研究：2026台灣旅遊業必看的 5 大訊號 | https://www.myholidaytw.com/reports/min-su-duan-zu-market-analysis |
| 【產業報告】亞洲廉價航空市場競爭分析：2026年最新趨勢分析 | https://www.myholidaytw.com/reports/ya-zhou-lian-jia-hang-kong-jing-zheng-fen-xi-market |

完整與最新列表：https://www.myholidaytw.com/reports

## 授權 License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — 註明出處即可自由使用、改作與再散布。

引用格式 / Suggested citation：

```
MyHoliday TW Research (2026). 《報告標題》. https://www.myholidaytw.com/reports/{slug}
```

研究方法論：https://www.myholidaytw.com/research-methodology

## 同步機制 Sync

本 repo 由 GitHub Actions 每週自動從 [myholidaytw](https://github.com/ricky22407-lang/myholidaytw) 主站鏡像最新資料集。
