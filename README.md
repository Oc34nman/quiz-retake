# quiz-retake
#include<iostream>
using namespace std;

float PyramidVolume(int length, int width, int height);

int main() {
	cout << PyramidVolume(2, 3, 4);
}

float PyramidVolume(int length, int width, int height) {
	return (length * width * height) / 3;

}


#include<iostream>
using namespace std;

bool isapple(string bob);

int main() {
	
	
	cout << isapple("apple");
}

bool isapple(string bob) {
	if (bob == "apple")
		return true;
	else
		return false;
}
#include<iostream>
using namespace std;

void Dessert();

int main() {
	Dessert();
}

void Dessert() {
	int num = rand() % 100;
	if (num < 20)
		cout << "icecream" << endl;
	else if (num < 30)
		cout << "pie" << endl;
	else if  (num < 50)
		cout << "cake" << endl;


}
