### Chuẩn bị
- cần tải các thư viện: pip install matplotlib,... như trong src
- tải graphviz (lên gg), và phải thêm Graphviz vào PATH môi trường thủ công nếu máy không tự tạo
- vd: Window
- download bản mới nhất 64-bit .exe
https://gitlab.com/api/v4/projects/4207231/packages/generic/graphviz-releases/12.2.1/windows_10_cmake_Release_graphviz-install-12.2.1-win64.exe
- Được lưu tại C:\Program Files\Graphviz\ hoặc C:\Program Files (x86)\Graphviz\
- Thêm Graphviz vào PATH nếu cần: 
- Windows + S -> Environment Variables: Edit the system environment variables
- Tìm: Environment Variables... -> Path -> Edit
- New và dán thư mục bin: C:\Program Files\Graphviz\bin -> OK
- Kiểm tra: dot -V trong Command Prompt (dưới quyền Administrator nếu không được)

