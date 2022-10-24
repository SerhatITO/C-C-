#include <stdio.h>

int main(void){
	
    char cdizi[40];
    int id[50];
    int x,y,z,b;
	
	for(x=0;x>-1;x++){
		
		printf("Durdurmak icin 0 giriniz , lutfen sayi giriniz %d. sira:",x);
		scanf("%d",&id[x]);
		
		if(0==id[x]){
			break;
		}
	}
	
	for(y=0;y<x;y++){
		for(z=0;z<(x-1)-y;z++){
			if(id[z]>id[z+1]){
				int degisken = id[z];
				id[z] = id[z+1];
				id[z+1] = degisken;
			}
		}
	}
	for(b=0;b<x;b++){
		printf("%d\n",id[b]);
	}

    return 0;
}
