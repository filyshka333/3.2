#include <iostream>
using namespace std;
class Bimbam {
public:
	int kg;
	int result;
	void res()
	{
		cin >> kg;
		result = kg / 100;
		cout << result;
	}
};
int main()
{
	setlocale(LC_ALL, "Russian");
	Bimbam bim;
	bim.res();
	
}
