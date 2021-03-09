# Clustering seed data with K-means <br>

## Data info
Use seeds data set from UCI : [data](https://archive.ics.uci.edu/ml/datasets/seeds) <br>
In data set, it has 3 types of wheat : Kama wheat seed, Rosa wheat seed and Canadian wheat seed with 210 row, 7 col data <br>

1. Area เป็นค่าบริเวณผิวของเมล็ด
2. Perimeter เป็นค่าเส้นรอบวงของเมล็ด
3. Compactness เป็นค่าความแน่นของเมล็ด
4. Length of kernel เป็นค่าความยาวของเนื้อในของเมล็ดคือส่วนความยาวเนื้อที่ที่อยู่ในเมล็ดอีกที่
5. Width of kernel เป็นค่าความกว่างของเนื้อใน
6. Asymmetry coefficient เป็นค่าสัมประสิทธิ์ความไม่สมมาตรของเมล็ด
7. Length of kernel groove เป็นค่าร่องความยาวของเนื้อใน

## Preprocessing
 * Check missing values if it missing replace with median data
 * Normalization data with Z-score

## Modeling
 * Use heatmap for find a relative data
 * Use Elbow Method for find best K in clustering
 * Use Cluster centers for cluster data
 * Summary Model 