- š Hi, Iām @Stride99
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Stride99/Stride99 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<stdio.h>
#include<time.h>
#define pr(TYPE) printf("Size of %s:%ld\n",#TYPE,sizeof(TYPE))
int main()
{
    pr(char);
    pr(short);
    pr(short int);
    pr(int);
    pr(long int);
    pr(unsigned int);
    pr(void *);
    pr(size_t);
    pr(float);
    pr(double);
    pr(int8_t);
    pr(int16_t);
    pr(int32_t);
    pr(int64_t);
    pr(time_t);
    pr(clock_t);
    pr(struct tm);
    pr(NULL);
    return 0;
}
