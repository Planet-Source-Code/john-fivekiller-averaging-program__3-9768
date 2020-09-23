<div align="center">

## Averaging Program


</div>

### Description

To make the task of averaging out numbers easy by using my programing skills
 
### More Info
 
It accepts only floating point numbers

Has not been debugged side effects unknown


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[john Fivekiller](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/john-fivekiller.md)
**Level**          |Beginner
**User Rating**    |4.0 (8 globes from 2 users)
**Compatibility**  |C, C\+\+ \(general\)
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/john-fivekiller-averaging-program__3-9768/archive/master.zip)





### Source Code

```
#include <iostream.h>
#include <stdlib.h>
float average(int number, float total)
{
  float average;
  average = total / number;
  return average;
}
int getnumber(void)
{
  int number;
  cout<<"Enter the total numbers\n";
  cin>>number;
  return number;
}
float getallnumbers (int amount)
{
  float input;
  int i = 0;
  cout<<"Enter All number to be divided\n";
  float allnumbers = 0.0;
  while (i < amount)
  {
  cin>>input;
  allnumbers = allnumbers + input;
  amount--;
  }
  return allnumbers;
}
using namespace std;
int main(int argc, char *argv[])
{
int number;
 number=getnumber();
float total;
 total=getallnumbers(number);
float theaverage;
 theaverage=average(number,total);
 cout<<"The average of the numbers are "<<theaverage<<endl;
 system("PAUSE");
 return 0;
}
```

