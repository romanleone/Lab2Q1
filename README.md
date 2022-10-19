#include <msp430.h> 

float j = 5;

int main(void)
{
	WDTCTL = WDTPW | WDTHOLD;	
	
	unsigned char a = 0x0f;
	unsigned char b = 0x05;

	unsigned char andRes;
	unsigned char orRes;

	int i = 3;
	i+=1; //increment
	j-=1; //decrement

	orOpResult = a||b;
	andOpResult = a&&b;

	return 0;
}
