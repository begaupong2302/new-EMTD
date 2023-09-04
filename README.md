Malware Detection by HTTPS Traffic

## Dataset
Android Malware Dataset (CIC-AndMal2017)

[Link](https://www.unb.ca/cic/datasets/andmal2017.html)

Android Malware Dataset (CIC-AndMal2019)

[Link](https://www.unb.ca/cic/datasets/invesandmal2019.html)

MCFP 
[Link](https://mcfp.felk.cvut.cz/publicDatasets/)

## Lựa chọn đặc trưng
Chỉnh sửa và lựa chọn đặc trưng dựa theo bài báo

[Link](https://arxiv.org/abs/2203.09332)

## Phương pháp huấn luyện, các thuật toán và phép đo độ chính xác
Sử dụng cross-validation với k-fold = 5

Các thuật toán: XGBoost, Random Forest, SVM

Các phép đo độ chính xác: accuracy, precision, recall, roc_auc
