# APPENDFILE
APPENDING A FILE
// FileInput.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include <iostream>
#include <fstream>
#include <cstdlib>
#include <string>

using namespace std;

int main()
{
	
	ofstream OutP("Jonathan.txt",ios::app);
	
	if (!OutP)
	{
		cerr << " Uh Oh there is a error opening this file!" << endl;
		exit(1);
	}

	
	
		
		
		OutP << "This is line 3!" << endl;
		OutP << "This is line 4!" << endl;

	

    return 0;
}
