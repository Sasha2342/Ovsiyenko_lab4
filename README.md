# Ovsiyenko_lab4

#include <iostream>

int main(){
    
    int arr[15]={2,4,0,1,12,23,0,6,8,11,0,6,0,45,22};
    
    std::cout<<"Масив після видалення нульових елементів:";
    
    for(int i=0;i<15;++i){
        if (arr[i]!=0){
            std::cout<<arr[i]<<" ";
        }
    }
    
    std::cout<<std::endl;

    return 0;
}
