# #include <iostream>

using namespace std;

int main() {
    int sayi1 = 0;
    int sayi2 = 0;
    int secim = 0;
    cout << "Ədədi qeyd edin: " << endl << "1 = Bölme" << endl << "2 = Toplama" << endl  << "3 = Çıxma" << endl << "4 = Hasil" << endl;
    cout << "Seçiminiz : ";
    cin >> secim;
    cout << "İlk Ədədi Girin : ";
    cin >> sayi1;
    cout << "İkinci Ədədi Girin : ";
    cin >> sayi2;
    switch (secim) {
        case 1://Bölme
            cout << "Sayıların Bölünməsi : " << (sayi1 / sayi2);
            break;
        case 2://Topla
            cout << "Sayıların Cəmi : " << (sayi1 + sayi2);
            break;
        case 3://Çıxma
            cout << "Sayıların Fərqi : " << (sayi1 - sayi2);
            break;
        case 4://Vurma
            cout << "Sayıların Hasili " << (sayi1 * sayi2);
            break;
        default:
            cout << "işlem seçilmedi!";


    }

    return 0;
}
