#import 函式庫，包括 NumPy、Keras、matplotlib
#載入 MNIST 資料集，Keras 自動分為訓練組及測試組資料，
#建立簡單的線性模型(Sequential)，沒有分叉(If)，也沒有迴圈(loop)，只設一層隱藏層(Dense)。
#選擇損失函數(crossentropy)及優化方法(adam)及成效衡量方式(accuracy)，開始訓練。
#執行模型評估，計算模型參數，即W(i,j)及W(j,k)
#使用模型，預測新資料
