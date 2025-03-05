#include <iostream>
using namespace std;
int main() {
    int N;
    cout << "Nhap N (N >= 10): ";
    cin >> N;
    if (N < 10) {
        cout << "N phải lớn hơn hoặc bằng 10!" << endl;
        return 1;  // Thoát chương trình nếu N < 10
    }
    int sum = 0;

    for (int i = 1; i <= N; ++i) {
        sum += i * 11;  // Cộng thêm i * 11 vào tổng
    }
    cout << "Tong S = " << sum << endl;
    return 0;
}
