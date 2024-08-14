#include <iostream>
using namespace std;

void displayTriangle(int side) {
    for (int i = 1; i <= side; ++i) {
        for (int j = 0; j < side - i; ++j) {
            cout << "  ";
        }
        for (int k = 0; k < 2 * i - 1; ++k) {
            cout << "* ";
        }
        cout << endl;
    }
}

int main() {
    int side;
    cout << "Enter the side length: ";
    cin >> side;
    displayTriangle(side);
    return 0;
}
