# CSE6250_bd4h_project
## Requirements:
Python == 3.9.7

Pytorch == 1.13.0

## Steps to run the code for model training:
1. download the project code/data "bd4h_project_main.zip"
2. unzip "bd4h_project_main.zip" if needed, navigate into the unzipped file where folder "code" exists.
3. all required data for running this pipeline is available in /data. 
4. run python train_GAMENet.py --model_name GAMENet --ddi (with DDI knowledge)
5. run python train_GAMENet.py --model_name GAMENet --ddi --resume_path Epoch_{}_JA_{}_DDI_{}.model --eval (testing with DDI knowledge)
6. run python train_GAMENet.py --model_name GAMENet (without DDI knowledge)
7. run python train_GAMENet.py --model_name GAMENet --resume_path Epoch_{}_JA_{}_DDI_{}.model --eval (testing without DDI knowledge)
