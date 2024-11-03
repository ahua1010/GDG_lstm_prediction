# GDG_lstm_prediction
GDG的上手用的機器學習小練習

我先建立虛擬環境安裝所需套件(詳情請見requirements.txt，安裝打pip install -r requirements.txt)，運行示範程式，
調整到適合版本後還修改了原先的舊模型儲存格式.h5為.keras，並修了點bug

之後使用Optuna來自動尋找最佳超參數，學習率使用Adam，學習率使用自然指數衰減來遞減，參數設定為initial_learning_rate = 0.001,decay_steps = 10000,decay_rate = 0.9

![image](https://github.com/user-attachments/assets/96b267c8-6192-4b89-99c4-5cda6469524c)

![Uploading image.png…]()
