# 題目

台灣指數期貨大幅漲跌前輪廓分析、策略設計與實證

# 摘要

本研究採取資料導向(Data Driven)的策略開發方式，藉由台灣指數期貨價格的未來發展，

依據出場方式，定義出不同進場時點的「多空評分值」(定義未來漲跌)，

並藉此廣泛搜尋與之高度相關的單一或多重綜合指標(輪廓分析)，藉此形成策略，

並以此策略作樣本外測試，以驗證依據此法發展出的策略，是否能預測指數期貨未來價格的走勢。

**實證結果發現：**

(1) 三種交易模型(分別為做多、做空、多空雙向操作)中，
    以多空雙向操作最能反應趨勢，進而有更好的獲利；

(2) 從樣本內來看，與進場評分指標相關程度越高的指標，
    回溯測試的績效越好，但樣本外測試卻不能延續績效，可能受到市場趨勢結構改變的影響之故；

(3) 運用倒傳遞類神經網路綜合高相關度的指標形成複合指標，確能提升相關程度及交易績效，
    但仍然無法在樣本外延續績效。

關鍵詞：資料導向、回溯測試、類神經網路

# 程式碼

[論文code](./wk_13-New/wk_13-New.md)