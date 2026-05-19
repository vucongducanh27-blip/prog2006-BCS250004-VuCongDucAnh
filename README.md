# prog2006-BCS250004-VuCongDucAnh

bai 1

#include <iostream>

using namespace std;

int main() {

    int n ;
    
    cout << "nhap n:";
    
    cin >> n;
    
    if (n% 2 == 0) {
    
        cout << n << "la so chan" << endl;
        
    } else {
    
        cout << n << "la so le" << endl;

    }
    
   return 0 ;
    
}<img width="1907" height="1004" alt="Ảnh chụp màn hình 2026-05-19 120117" src="https://github.com/user-attachments/assets/c82ba70f-789e-409e-ae26-264c084cf2b7" />

bai 2

#include <iostream>

using namespace std;

int main () {

    double w;
    
    cout << "nhap W:";
    
    cin >> w;
    
    double h;
    
    cout << "nhap H:";
    
    cin >> h;
    
    double s = w * h;
    
    cout << "dien tich la:"<< s << endl;
    
    return 0;
    
}

<img width="1919" height="1008" alt="Ảnh chụp màn hình 2026-05-19 121046" src="https://github.com/user-attachments/assets/192fbe4f-0098-400d-8b5c-210024347984" />

bai3

#include <iostream>

using namespace std;

int main() {

    int n;
    
    cout<< "nhap n";
    
    cin>>n;
    
    for (int i = 0; i < n; i++) {
    
        if (i==n) {
        
            break;
            
        }
        
        cout << i;
        
    }
    
    return 0;
    
}

<img width="1919" height="1005" alt="Ảnh chụp màn hình 2026-05-19 143449" src="https://github.com/user-attachments/assets/274a6357-06cd-49bb-82e5-c89b9f1eadef" />

bai4

#include <iostream>

using namespace std;

int main() {

   int a;
   
   cout<<"nhap a";
   
   cin >> a;
   
   int b;
   
   cout<<"nhap b";
   
   cin >> b;
   
   if (a==0) {
   
      if (b==0) {
      
         cout<<"phuong trinh co vo so nghiem"<< endl;
         
      } else {
      
         cout<<"phuong trinh vo nghiem"<< endl;
         
      }
      
   }else {
   
      double x = - b / a;
      
      cout << " nghiem cua phuong trinh x = " << x << endl;
      
   }

   return 0;

   <img width="1918" height="1008" alt="Ảnh chụp màn hình 2026-05-19 151717" src="https://github.com/user-attachments/assets/33b703e4-c74e-4de0-90be-7c1c9eebe72e" />

}
