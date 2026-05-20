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

bai 5

#include<iostream>

using namespace std;

int main() {

    int n;
    
    cout<<"nhap so phan tu";
    
    cin>>n;
    
    int scores [n];
    
    cout<<"nhap phan cac tu";
    
    for(int i=0;i<n;i++) {
    
        cin>>scores [i];
        
    }
    
    int maxval = scores [0];
    
    for (int i = 1; i < n ; i++) {
    
        if ( scores [i] > maxval) {
        
            maxval = scores [i];
            
        }
        
    }


   cout<< " gia lon nhat la "<< maxval<<endl;
   
   return 0;

}

<img width="1917" height="1003" alt="Ảnh chụp màn hình 2026-05-20 141400" src="https://github.com/user-attachments/assets/da164635-6c7c-40f8-9f6b-844150888470" />

bai 6

#include <iostream>

using namespace std;

int main() {

    int ngay;
    
    cout<< " nhap so tu 1 - 7: ";
    
    cin>>ngay;
    
    switch(ngay) {
    
        case 1:
        
            cout << " thu 2"<<endl;
            
            break;
            
        case 2:
        
            cout<< " thu 3"<<endl;
            
            break;
            
        case 3:
        
            cout<<" thu 4"<<endl;
            
            break;
            
        case 4:
        
            cout << " thu 5 "<<endl;
            
            break;
            
        case 5:
        
            cout<<" thu 6 "<<endl;
            
            break;
            
        case 6:
        
            cout<<" thu 7"<<endl;
            
            break;
            
        case 7:
        
            cout << " chu nhat"<<endl;
            
            break;
            
        default:
        
            cout << " khong hop le vui long nhap so tu 1- 7"<<endl;

    }
    
    return 0;
    
}

<img width="1919" height="1013" alt="Ảnh chụp màn hình 2026-05-20 141329" src="https://github.com/user-attachments/assets/a26013ee-8b79-4c4f-8a6d-21de6261f88a" />

bai 7

#include<iostream>

using namespace std;

int main() {

    int n;
    
    cout<<"nhap so phan tu";
    
    cin>>n;
    
    int arr[n];
    
    cout<<"nhap cac phan tu";
    
    for (int i = 0; i < n; i++) {
    
        cin>>arr[i];
        
    }
    
    int S = 0;
    
    for (int i = 0; i < n; i++) {
    
        S += arr[i];
        
    }
    
    cout<< "tong cac so  la: "<<S<<endl;
    
    return 0;
    
}

<img width="1918" height="1009" alt="Ảnh chụp màn hình 2026-05-20 141303" src="https://github.com/user-attachments/assets/86d8a69c-a02e-4cda-a7f4-cd4ca46507f5" />
