 #include <iostream>

using namespace std;

template <typename Iterator, typename T>
auto find_two_elements_with_sum(Iterator first, Iterator last, T c)
{
	bool T_F = false;
	int arr[10] = {0,1,2,3,4,5,6,7,8,9};
		while(first!=last)
		{
			int Summ = arr[first] + arr[last];

			if(Summ < c)
				first++;
			else if(Summ > c)
				last--;
			else
			{
				T_F = true;
				cout << "bool = " << T_F << endl;
				cout << "iterators: " << first << " " << last << endl;
				break;
			}
		}
		cout << "not found" <<endl;
	
	return 0;
}

int main()
{
	int X;
	cin >>  X;

	find_two_elements_with_sum(0, 9, X);

}
