# M03W02_KNN-K-Means
Những kiến thức học được về KNN và K_Means

Sự khác nhau giữa KNN và KMeans

+ Loại học máy: KNN là học không giám sát, KMean là học có giám sát
+ Cách hoạt động: KNN tự động chia dữ liệu thành K cụm bằng cách tìm tâm cụm, còn K_Mean với 1 điểm mới tìm k điểm gần nhất trong tập huấn luyện để phân loại nhãn mới


<img width="792" height="354" alt="image" src="https://github.com/user-attachments/assets/a1eee649-2508-4512-9748-13669a7809a4" />

Đáp án là (64, 1, 2) (1,1,128) vì data1 thêm newaxis là thêm 1 cột 1, còn data2 thêm -1 tức là thêm sao cho phù hợp với tổng phần từ của data là 64*2 = 128 nên -1 sẽ thành 128


<img width="605" height="238" alt="image" src="https://github.com/user-attachments/assets/795463ee-52e8-4deb-bd49-3424b76e67d4" />

Với số lượng K nhỏ có thể gây ra hiện tượng Ovefit
- Ví dụ với K = 1, chỉ dựa vào 1 'hàng xóm' gần nhất, nếu 'hàng xóm' đó là nhiễu thì phân loại cũng là nhiễu gây ra dự đoán sai 

KNN với thuật toán KD-Tree : Phù hợp với bài toán có tập dữ liệu quá lớn

