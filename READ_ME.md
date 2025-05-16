frieren-rpg/
├── assets/                 # Hình ảnh, âm thanh, font chữ,...
├── bin/                    # File .exe sau compile
├── build/                  # File .exe và các file do compiler tạo ra
├── docs/                   # Ghi chú thiết kế,..
├── include/                # Gọi các thư viện có sẵn của C/C++,..
├── src/                    # Source files (.cpp)
│   ├── core/               # Khởi tạo trò chơi, hệ thống, xử lý input, output màn hình,..
│   ├── entities/           # Nhân vật, NPC, quái
│   ├── world/              # Thế giới, (trạng thái, thời tiết,..)
│   ├── systems/            # Dữ liệu, chỉ số, inventory, quest (nói chung là database)
│   └── utils/              # Các hàm tiện ích tự cài
├── tests/                  # Các test (nếu có)
├── CMakeLists.txt / Makefile  # Build config
├── LICENSE                 # Chưa biết dùng gì
└── README.md
