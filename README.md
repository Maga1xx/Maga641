# #include <iostream>

using namespace std;

int main() {
    int sayi1 = 0;
    int sayi2 = 0;
    int secim = 0;
    cout << "Lütfen Seçim Yapınız: " << endl << "1 = Bölme" << endl << "2 = Toplama" << endl  << "3 = Çıkartma" << endl << "4 = Çarpma" << endl;
    cout << "Seçiminiz : ";
    cin >> secim;
    cout << "İlk Sayıyı Girin : ";
    cin >> sayi1;
    cout << "İkinci Sayıyı Girin : ";
    cin >> sayi2;
    switch (secim) {
        case 1://Bölme
            cout << "Sayıların Bölümü : " << (sayi1 / sayi2);
            break;
        case 2://Topla
            cout << "Sayıların Toplamı : " << (sayi1 + sayi2);
            break;
        case 3://Çıkartma
            cout << "Sayıların Farkı : " << (sayi1 - sayi2);
            break;
        case 4://Çarpma
            cout << "Sayıların Çarpımı " << (sayi1 * sayi2);
            break;
        default:
            cout << "işlem seçilmedi!";


    }

    return 0;
}
