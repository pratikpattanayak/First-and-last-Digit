# First-and-last-Digit
This code calculates the sum of first and last digit of a given number
 
 
 
 #include <iostream>
using namespace std;

int main() {
    int T;std::cin >> T;
    while(T--)
    {
        int N;std::cin >> N;
        int fd=N%10;
        int ld;
        while(N>=10)
        {
            N=N/10;
        }
        ld=N;
        std::cout << fd+ld << std::endl;
        
        
    }

	return 0;
}
