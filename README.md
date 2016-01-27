# Market-Model
既存の実績ある人工市場モデルに高頻度取引を行う個体を追加して分析した
###CSVファイルの名前は以下のルールに従っている．
(1)最初に市場の数を書く("1mar_"or"2mar_")  
(1.5)市場が2つある場合はどちらの市場のものかを書く("1_"or"2_")  
(2)次に使用したモデルを書く("sty_"or"maker_"or"all_")  
(3)注文の貯め方を書く("auc"or"yose")  
(4)同一条件において何回目の実験かを書く("01","02",...)  
(5)表しているデータを書く(価格の推移を表すprices，執行された注文を記録したhistory，実験終了時に残っていた売買それぞれの注文を記録したbuy_ordersおよびsell_ordersの4種がある)
