# Hackerearth-Palindromic-solution
My cpp code for the Palindromic hackerearth solution

#include<iostream>
#include<string.h>

using namespace std;
int main()
{
	char string1[100]={};
	int k = 0;
	cin>>string1;
	int len = strlen(string1);
	for(int i=0;i<len;i++)
	{
		if(string1[i] != string1[len - i - 1])
		    {
            k = 1;
		    break;
		    }
			else
			continue;
	}
    (k == 1) ?cout<< "NO" : cout<< "YES";
	return 0;
}

by VISHAL RAJ
CONTRIBUTER
