#include <iostream>
using namespace std; 
int main() {
            double numbers[] = {8, 127 , 920, 2, 6570};
double maximum = numbers[0];
double minimum = numbers[0];
for (int i=1 ; i<2; ++i) {
     if (numbers[i] > maximum) {
          maximum = numbers[i];
         }
     if (numbers[i] < minimum){
       minimum = numbers[i];
          }
     cout << "maximum number is:"
     <<maximum << endl;
     cout << "minimum number is:"
     <<minimum << endl; 

       return0;
}