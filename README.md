# Average-of-n-num
#include &lt;stdio.h> int main()  {    int i,a[10],n,av,s=0,c=0;    printf("enter num\n");    scanf("%d",&amp;n);    for(i=0;i&lt;n;i++)    {      scanf("%d",&amp;a[i]);      s=s+a[i];      if (a[i]&lt;40)      {        c++;      }    }    av=s/n;    printf("Av=%d\n",av);    printf("fail=%d",c);        return 0;  }
