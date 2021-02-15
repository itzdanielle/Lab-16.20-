# Lab-16.20-
#include <iostream>
#include <string>
using namespace std;

void name(string firstName, string lastName) 
{
  cout << "Hello " << firstName << " " << lastName << "!\n";
}

int main() {
  string first;
  string last;
  cout << "Enter your first name\n";
  cin >> first;
  cout << "Enter you last name\n";
  cin >> last;
  name (first, last);
}

