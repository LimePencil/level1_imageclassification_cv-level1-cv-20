# [CV] 일자별 제출현황

## 🔥10/26 제출 상황
| 제출순서 |      기준      | 작성자 |            모델            |   전처리   | 후처리 |   하이퍼 파라미터   | f1_score | Accuracy |
| :------: | :------------: | :----: | :------------------------: | :--------: | :----: | :-----------------: | :------: | :------- |
|    1     |     Custom     | 서원준 |         Resnet-50          | centercrop |   -    |          -          |  0.0483  | 12.3175  |
|    2     |     Custom     | 서원준 |         Resnet-50          | centercrop |   -    |          -          |  0.0495  | 12.3016  |
|    3     | 1일차 Baseline | 신재영 |         Resnet-50          |     -      |   -    |      epoch 30       |  0.5682  | 66.4286  |
|    4     | 1일차 Baseline | 신재영 |         Resnet-50          |     -      |   -    | epoch 30~100 어디쯤 |  0.5883  | 66.6349  |
|    5     | 1일차 Baseline | 신재영 |         Resnet-50          |     -      |   -    |     epoch  100      |  0.5972  | 66.3968  |
|    6     | 1일차 Baseline | 신재영 |   beit_large_patch16_512   |     -      |   -    |      epoch  11      |  0.5817  | 67.7302  |
|    7     | 1일차 Baseline | 이영섭 |      Wide_ResNet101_2      |     -      |   -    |      epoch 50       |  0.5895  | 70.4444  |
|    8     |     Custom     | 서원준 | vit-base-patch16-224-in21k | centercrop |   -    |      epoch 10       |  0.5925  | 68.7778  |

## 🔥10/27 제출 상황
| 제출순서 |         기준          | 작성자 |            모델            |   전처리   | 후처리 | 하이퍼 파라미터 | f1_score | Accuracy |
| :------: | :-------------------: | :----: | :------------------------: | :--------: | :----: | :-------------: | :------: | :------- |
|    1     |    1일차 Baseline     | 이영섭 |        EfficientNet        |     -      |   -    |    epoch 50     |  0.3980  | 49.6508  |
|    2     |        Custom         | 서원준 | vit-base-patch16-224-in21k | centercrop |   -    |    epoch 10     |  0.5925  | 68.7778  |
|    3     | 1일차 Baseline custom | 전지용 |        vit-base-16         |     -      |   -    |    epoch 100    |  0.4357  | 51.2698  |
|    4     |   CustomBaselineV1    | 신재영 |           ResNet           |            |        |    epoch 10     |  0.578   | 64.4     |
|    5     | 2일차 Baseline | 이영섭 | Wide_ResNet101_2 |    -    |    -    |   epoch 50   |  0.5734   |  68.0000  |
|    6     | 2일차 Baseline | 이영섭 | Wide_ResNet101_2 |  centercrop  |    -    |   epoch 50   |  0.4462   |  52.3175  |




## 📌 주의 사항
* 제출은 팀당 10회 제한이니 팀원에게 알리고 제출하기✨
