#include <iostream>
using namespace std;

int main() {
    // Khai báo biến
    float soKg;
    int giaTien;

    // Nhập khối lượng cam mua
    cout << "Nhap so kg cam mua: ";
    cin >> soKg;

    // Tính giá tiền
    if (soKg < 5) {
        giaTien = soKg * 12000;
    } else {
        giaTien = soKg * 10000;
    }

    // Hiển thị số tiền phải trả
    cout << "So tien phai tra: " << giaTien << " dong" << endl;

    return 0;
}






Cách hoạt động:
	1.	Người dùng nhập số lượng cam mua (đơn vị: kg).
	2.	Chương trình kiểm tra:
	•	Nếu dưới 5kg, giá là 12.000 đồng/kg.
	•	Nếu từ 5kg trở lên, giá là 10.000 đồng/kg.
	3.	Số tiền được tính toán và in ra màn hình.

Hướng dẫn chạy:
	1.	Dán mã trên vào IDE Dev-C++.
	2.	Nhấn Compile & Run để chạy chương trình.
	3.	Nhập số kg cam cần mua và xem kết quả.

