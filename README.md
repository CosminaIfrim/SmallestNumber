# SmallestNumber
#include <iostream>
using namespace std;

int smallestNumber(int a, int b);

int main()
{
    int a, b;

    for (int sn = 0; sn < 3; sn++)
    {
        std::cout << "Input a number." << std::endl;

        std::cin >> a;

        std::cout << "Input another number." << std::endl;

        std::cin >> b;

        std::cout << "The smallest number is: " << smallestNumber(a, b) << std::endl;
    }

}

int smallestNumber(int a, int b)
{
    if (a > b)
    {
        return b;
    }
    else
    {
        return a;
    }

}
