Bộ dữ liệu phần mềm độc hại Android của đại học Tezpur, còn được gọi là TUANDROMD, là một tập hợp các ứng dụng Android thường được sử dụng cho mục đích nghiên cứu trong lĩnh vực an ninh mạng. Các nhà nghiên cứu tại Đại học Tezpur ở Ấn Độ đã tạo ra một bộ dữ liệu có 4465 ứng dụng Android, bao gồm cả ứng dụng độc hại và lành tính. TUANDROMD, một công cụ phát hiện phần mềm độc hại, đã được sử dụng trong các nghiên cứu để đánh giá các kỹ thuật, phân tích các đặc điểm của phần mềm độc hại và hiểu hành vi của nó trên thiết bị Android

Đánh giá kết quả
| **Chỉ số**                         | **KNN** | **SVC** | **RF**  |
|-----------------------------------|--------:|--------:|--------:|
| Precision                         | 0.920   | 0.862   | 0.962   |
| Recall                            | 0.697   | 0.758   | 0.758   |
| F1-score                          | 0.763   | 0.806   | 0.847   |
| Accuracy                          | 0.910   | 0.910   | 0.932   |
| AUC (ROC)                         | 0.90    | 0.93    | 0.94    |
| Average Precision (AP)           | 0.81    | 0.84    | 0.89    |
| Dương tính giả (False Positives) | 2       | 4       | 1       |
| Dương tính thật (True Positives) | 23      | 25      | 25      |
| Âm tính giả (False Negatives)    | 10      | 8       | 8       |
| Âm tính thật (True Negatives)    | 98      | 96      | 99      |
