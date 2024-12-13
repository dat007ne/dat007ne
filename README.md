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
