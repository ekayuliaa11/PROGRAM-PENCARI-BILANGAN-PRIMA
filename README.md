# PROGRAM-PENCARI-BILANGAN-PRIMA




    #include <iostream>
    #include <conio.h>

    using namespace std;
    int main ()
    {
    int i,j,k;

    for (i=1;i<=100;i++){
        k=0;
        for(j=1;j<=i;j++){
            if(i%j==0){
                k+=1;
            }
        }
        if(k==2){
            cout<<i<<"";
        }
    }
        return 0;
    }

![img](https://github.com/ekayuliaa11/PROGRAM-PENCARI-BILANGAN-PRIMA/blob/master/bilangan%20prima.png?raw=true)
