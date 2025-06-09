# Machine-Learning-Anomaly-Detection
## Mattia Presta 239051

DRÆM: https://arxiv.org/pdf/2108.07610


EfficientAD: https://arxiv.org/pdf/2303.14535

## Confronto Modelli per Datasets

|        | **Img-AUROC** | **Img-F1** | **Pixel-AUROC** | **Pixel-F1** |
|-----------------|--------------|------------|-----------------|--------------|
| **_MVTec_**       |              |            |                 |              |
| DRÆM           | 0.69         | 0.86       | 0.69            | 0.21         |
| EfficientAD    | **0.94**     | **0.92**   | **0.94**        | **0.60**     |
| **_ViSa_**       |              |            |                 |              |
| DRÆM           | 0.74         | 0.77       | 0.78            | 0.11         |
| EfficientAD    | **0.89**     | **0.84**   | **0.97**        | **0.37**     |
| **_WFDD_**       |              |            |                 |              |
| DRÆM           | **0.87**     | 0.81       | 0.59            | 0.08         |
| EfficientAD    | 0.84         | **0.82**   | **0.84**        | **0.36**     |



## Confronto velocità media di inferenza per Dataset e Modello

|          | **Time/Image (s) ↓** | **Throughput (img/s) ↑** | **Total Time (s) ↓** | **Images** |
|-----------------|----------------------|--------------------------|----------------------|------------|
| **_MVTec_**       |                      |                          |                      |            |
| DRÆM           | 0.18                 | 5.58                     | 308.30               | 1,721      |
| EfficientAD    | **0.1522**           | **6.57**                 | **261.95**           | 1,721      |
| **_ViSa_**       |                      |                          |                      |            |
| DRÆM           | 0.1072               | 9.33                     | 115.96               | 1,082      |
| EfficientAD    | **0.0734**           | **13.62**                | **79.47**            | 1,082      |
| **_WFDD_**       |                      |                          |                      |            |
| DRÆM           | 0.1338               | 7.47                     | 24.63                | 184        |
| EfficientAD    | **0.1222**           | **8.18**                 | **22.49**            | 184        |



## EfficientAD
![EfficientAD](https://imgur.com/v6dsAjG.png)



## DRÆM
![DRÆM](https://imgur.com/na5ep1M.png)
