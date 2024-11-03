# GDG_lstm_prediction
GDG的上手用的機器學習小練習

我先建立虛擬環境安裝所需套件(詳情請見requirements.txt，安裝打pip install -r requirements.txt)，運行示範程式，
調整到適合版本後還修改了原先的舊模型儲存格式.h5為.keras，並修了點bug

之後使用Optuna來自動尋找最佳超參數，學習率使用Adam，學習率使用自然指數衰減來遞減，參數設定為initial_learning_rate = 0.001,decay_steps = 10000,decay_rate = 0.9

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/44017b12-56e6-4eae-8039-7470cfa6c9b0/e2049685-7e03-45a2-91e6-6f5478ec2bb4/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/44017b12-56e6-4eae-8039-7470cfa6c9b0/c275ce05-6640-48b0-a818-00a1977c67a0/image.png)
