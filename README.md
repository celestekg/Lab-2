# Lab-2: This program will read the radius of a sphere, calculate the volume using the formula 4/3*PI*r^3, calculate the surface area using the forumla 4*PI*r^2, and print the radius, volume, and surface area.

#include <iostream>
#include <cmath>
#include <iomanip>
using namespace std;

int main()
{
	const double PI = 3.1416;
	double radius, volume, surface;

	cout << "Enter sphere radius: ";
	cin >> radius;

	volume = 4.0 / 3.0 * PI * pow(radius, 3);
	surface = 4 * PI * pow(radius, 2);
	cout << endl;

	cout << "Radius = " << radius << endl;
	cout << "Volume = " << volume << endl;
	cout << "Surface Area = " << surface << endl;

	cout << fixed << endl;
	cout << "Radius = " << radius << endl;
	cout << "Volume = " << volume << endl;
	cout << "Surface Area = " << surface << endl;

	cout << setprecision(3) << endl;
	cout << "Radius = " << radius << endl;
	cout << "Volume = " << volume << endl;
	cout << "Surface Area = " << surface << endl;

	cout << scientific << setprecision(4) << endl;
	cout << "Radius = " << radius << endl;
	cout << "Volume = " << volume << endl;
	cout << "Surface Area = " << surface << endl;
	cout << endl;

	system("PAUSE");
	return 0;
}
