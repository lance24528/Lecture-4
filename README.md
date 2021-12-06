# Lecture-4

#include <iostream>
#include <string>
#include <iomanip>
#include <array>
#include <math.h>
using namespace std;

int main() {// Possible Data Types

	int firstNumber = 1;
	bool iCanCode = true;
	char hopefulGrade = 'a';
	double myDecimal = 1.0;
	string minimalSentence = "y";
	int keyMash = 13213123;
	float mysteryDataType = 5.6f; 
	cin.get(); 
	return 0;

}
int main() {//Division Fix

	double numberOne = 50;
	double numberTwo = 7;
	cout << numberOne/numberTwo << endl;
	cin.get(); //keeps console window open in Visual Studio 
	return 0;

}  
int main() {//Untidy Code
	
	int number = 6;
	cout << "This is an untidy code.\n\n";
	cout << "I'm surprised it works.\n\n";	
	cout << "It has " << number << " lines of code\n\n";
	cout << "each more hideous than the last. \n\n";
	cout << "You probably should add some line breaks in the text too\n\n" << endl;
	cin.get();  
	return 0;

}  
int main() {//USB Shopper
	
	int money = 50; int usbCost = 6; 
	int usbStick = money / usbCost; int change = money % usbCost * 100;
	cout << "The girl can buy " << usbStick << "  USB sticks and her change is " << change << " Fils or 2 Dirhams" << endl;

}      
int main() {// Declaration and Initialization 
	
	int v1 = 8; int v2 = 10; int sum = v1 + v2;
	cout << v1 << " + " << v2 << " = " << sum << endl;

}
