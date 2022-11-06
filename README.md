# learn
#include <iostream>
#include <iomanip>
using namespace std;
int main( )
{
    unsigned char c[16] = {0};
    void *p;
    p = c;
    cin >> *(long double*)p;
    cout << "byte sequence(long double) = 0x" ;
    for (int i=15;i>=0;i--)
    cout << setfill('0') << setw(2) << hex << uppercase << (int)((unsigned char*)p)[i] ;
}
    //
