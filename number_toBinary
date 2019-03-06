//
//  main.cpp
//  HW2pt2
//
//  Created by Anisha Yerramilli on 1/25/18.
//  Copyright © 2018 Anisha Yerramilli. All rights reserved.
//

#include <iostream>

class zip{
public:
    zip(int zip){
        zipcode=zip;
    }
    zip(std::string bar){
        barcode=bar;
    }
        std::string num2binary(int num){
        
        if (num==1){
            return "00011";
        }
       else if (num==2){
            return "00110";
        }
       else if (num==3){
            return "00110";
        }
       else if (num==4){
            return "01001";
        }
        if (num==5){
            return "01010";
        }
        if (num==6){
            return "01100";
        }
        if (num==7){
            return "10001";
        }
        if (num==8){
            return "10010";
        }
        if (num==9){
            return "10100";
        }
        if (num==0){
            return "11000";
        }
        else{
            return "00011"; //default value set to 1
        }

    }
    std::string get_barcode(){
        std::string newString="";
    
        int first=(zipcode/10000);
        newString+=num2binary(first);//fix rest
        int second=((zipcode/1000)%10);
        newString+=num2binary(second);
        int third=((zipcode/100)%10);
        newString+=num2binary(third);
        int fourth=((zipcode/10)%10);
        newString+=num2binary(fourth);
        int fifth=(zipcode%10);
        newString+=num2binary(fifth);
       
        return newString;
    }
        //put first into function
        //then add to new string
    
            // return val string
            //concatenate diff strings into one
            
    
        // if else or switch stetements
        
        void zipCode(std::string bar, int arr[],int size){
            std::string bar1="";
            std::string bar2="";
            std::string bar3="";
            std::string bar4="";
            std::string bar5="";
            for(int i = 0; i < bar.length(); i++){
                if (i < 5){
                    bar1 += bar[i];
                }
                if(i>4 && i<10){
                    bar2 += bar[i];
                }
                
                if(i>9 && i<15){
                    bar3 += bar[i];
                }
                if(i>14 && i<20){
                    bar4+=bar[i];
                }
                if(i>19 && i<25){
                    bar5+=bar[i];
                    
                }
                
                
            }
           
            
        for(int i = 0; i < size; i++){
            if (bar1=="00011"){
                arr[i]= 1;
            }
            else if (bar1=="00110"){
                arr[i]= 2;
            }
            else if (bar1=="00110"){
                arr[i]= 3;
            }
            else if (bar1=="01001"){
                arr[i]= 4;
            }
            else if (bar1=="01010"){
                arr[i]= 5;
            }
            else  if (bar1=="01100"){
                arr[i]= 6;
            }
            else if (bar1=="10001"){
                arr[i]= 7;
            }
            else if (bar1=="10010"){
                arr[i]= 8;
            }
            else if (bar1=="10100"){
                arr[i]= 9;
            }
            else if (bar1=="11000"){
                arr[0]= 0;
            }
            else{
                arr[0]= 1;
            }

        }
        
        if (bar2=="00011"){
            arr[1]= 1;
        }
        else if (bar2=="00110"){
            arr[1]= 2;
        }
       else if (bar2=="00110"){
            arr[1]= 3;
        }
        else if (bar2=="01001"){
            arr[1]= 4;
        }
        else if (bar2=="01010"){
            arr[1]= 5;
        }
        else if (bar2=="01100"){
            arr[1]= 6;
        }
        else if (bar2=="10001"){
            arr[1]= 7;
        }
        else if (bar2=="10010"){
            arr[1]= 8;
        }
        else if (bar2=="10100"){
            arr[1]= 9;
        }
        else if (bar2=="11000"){
            arr[1]= 0;
        }
        else{
            arr[1]= 1;
        }

        if (bar3=="00011"){
            arr[2]= 1;
        }
        else if (bar3=="00110"){
            arr[2]= 2;
        }
        else if (bar3=="00110"){
            arr[2]= 3;
        }
        else if (bar3=="01001"){
            arr[2]= 4;
        }
        else if (bar3=="01010"){
            arr[2]= 5;
        }
        else if (bar3=="01100"){
            arr[2]= 6;
        }
        else if (bar3=="10001"){
            arr[2]= 7;
        }
        else if (bar3=="10010"){
            arr[2]= 8;
        }
        else if (bar3=="10100"){
            arr[2]= 9;
        }
        else if (bar3=="11000"){
            arr[2]= 0;
        }
        else{
            arr[2]= 1;
        }
        
        if (bar4=="00011"){
            arr[3]= 1;
        }
        else if (bar4=="00110"){
            arr[3]= 2;
        }
        else if (bar4=="00110"){
            arr[3]= 3;
        }
        else if (bar4=="01001"){
            arr[3]= 4;
        }
        else if (bar4=="01010"){
            arr[3]= 5;
        }
        else if (bar4=="01100"){
            arr[3]= 6;
        }
        else if (bar4=="10001"){
            arr[3]= 7;
        }
        else if (bar4=="10010"){
            arr[3]= 8;
        }
        else if (bar4=="10100"){
            arr[3]= 9;
        }
        else if (bar4=="11000"){
            arr[3]= 0;
        }
        else{
            arr[3]= 1;
        }

        if (bar5=="00011"){
            arr[4]= 1;
        }
        else if (bar5=="00110"){
            arr[4]= 2;
        }
        else if (bar5=="00110"){
            arr[4]= 3;
        }
        else if (bar5=="01001"){
            arr[4]= 4;
        }
        else if (bar5=="01010"){
            arr[4]= 5;
        }
        else if (bar5=="01100"){
            arr[4]= 6;
        }
        else if (bar5=="10001"){
            arr[4]= 7;
        }
        else if (bar5=="10010"){
            arr[4]= 8;
        }
        else if (bar5=="10100"){
            arr[4]= 9;
        }
        else if (bar5=="11000"){
            arr[4]= 0;
        }
        else{
            arr[4]= 1;
        }
            

    }
    
private:
    int zipcode;
    std::string barcode;
    
};

int main() {
    zip x(99956);
    zip y("0101001100100010100111000");
    int arrMain[5];
   std::cout<< x.get_barcode()<<std::endl;
    y.zipCode("0101001100100010100111000", arrMain, 5);
    for(int i=0; i<5; i++){
        std::cout<< arrMain[i];
    }
    std::cout<<" "<<std::endl;
    return 0;
}
