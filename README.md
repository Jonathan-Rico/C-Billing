// HW CH3 Billing.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include <iostream>
#include <string>
using namespace std;

class Bills {
	public:
	double total, charge;

	double subtotal(int hours) {
		return (30 * hours);
	}
	double subtotal1(int min){
		return ( ((min*30)/60));
	}
	double getpartcost(int num){
		return(0); //????
	}
	double repair(int parts, int labor){
		return (parts+labor);
	}
	double tax(double cost){
	return (cost * .0825);
	}
	int checkinput(string line) {
		return(0);                         
	}
	void getinput(int totalnumparts, int totalmins){
		numParts = totalnumparts;
		numMins = totalmins;
	}
	private:
		int numParts, numMins;
};

int _tmain(int argc, _TCHAR* argv[])
{
	Bills myFirstbill;
	
	return 0;
}

