# PyGeo Academy — GIS + Python + QGIS

Nền tảng E-Learning thực hành GIS và Python của Vietflexmap. Chương trình dành cho tất cả người học, kể cả người mới bắt đầu, theo tư duy **hiểu GIS → dùng QGIS → viết Python → tự động hóa bằng PyQGIS → ứng dụng dữ liệu không gian, viễn thám, GeoAI và WebGIS**.

## Định hướng học tập
- **GIS trước:** hệ tọa độ (CRS), vector, raster, topology, dữ liệu thuộc tính và nguyên tắc chất lượng dữ liệu.
- **QGIS để quan sát và kiểm chứng:** nạp lớp bản đồ, chuyển CRS, Processing Toolbox, xem bảng thuộc tính và đối chiếu kết quả.
- **Python để lập trình:** thao tác GeoPandas, Shapely, Rasterio, NumPy và tạo pipeline có thể tái lập.
- **PyQGIS để tích hợp:** chạy script trong QGIS Python Console, tự động hóa Processing và phát triển plugin.
- **Bài tập thực tế:** đối chiếu đầu ra Python với cùng bài toán thực hiện trên QGIS khi phù hợp.

## Lộ trình 15 bài
1. Bắt đầu với GIS + Python: Từ con số 0 đến bản đồ số
2. Thiết lập môi trường Python GIS
3. Dữ liệu vector với GeoPandas và đối chiếu QGIS
4. Buffer, Intersection, Union với Python và QGIS
5. Rasterio và lớp raster trong QGIS
6. Tự động hóa xử lý hàng loạt
7. Bản đồ tương tác với Folium và Leafmap
8. OpenStreetMap và Google Earth Engine
9. Nội suy và địa thống kê
10. Phân loại lớp phủ bằng Machine Learning
11. Chỉ số môi trường NDVI, NDWI
12. Big Data trong GIS
13. PyQGIS và plugin đơn giản
14. Phân tích mạng đường với NetworkX
15. Dashboard GIS với Dash và Plotly

## Chức năng
- Dashboard responsive, danh mục 15 bài trong 5 học phần, tìm kiếm và lộ trình.
- Nội dung lý thuyết, bảng kiến thức, ví dụ code, trắc nghiệm tự đánh giá.
- Code Lab để chỉnh sửa và sao chép ví dụ Python.
- Tiến độ học tập được lưu cục bộ bằng `localStorage`.
- Tài liệu nền tảng: [QGIS User Manual](https://docs.qgis.org/latest/en/docs/user_manual/), [PyQGIS Developer Cookbook](https://docs.qgis.org/latest/en/docs/pyqgis_developer_cookbook/), [Python docs](https://docs.python.org/3/), [GeoPandas](https://geopandas.org/).

## Chạy ứng dụng
Mở `index.html` trong trình duyệt, hoặc khởi động web server tĩnh: `python -m http.server 8000`.

## GitHub Pages
Repository → Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
Website: https://vietflexmap.github.io/pygeo/

## Giới hạn hiện tại
- Code Lab trên website là trình chỉnh sửa mẫu, **không chạy Python**. Thực thi trong Jupyter hoặc Python được cài đặt trên máy.
- Các thao tác PyQGIS phải chạy trong môi trường QGIS phù hợp.
- Chưa có đăng nhập nhiều người dùng, đồng bộ tiến độ xuyên thiết bị, bài thi chấm tự động hay chứng chỉ xác thực.
- Một số ví dụ cần thư viện ngoài, dữ liệu phù hợp, Internet hoặc tài khoản API. Kiểm tra CRS và chất lượng dữ liệu trước khi phân tích.

© Vietflexmap · Long Ngo 2026.
