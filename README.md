# Gasoline.cpp

#include <iostream>

using namespace std;

int main()

{

    char type,choice;
    float price1=2.89,price2=3.09,price3=3.39,subtotal,carwash,gallons,cw1,cw=1.25;

    cout<<"            ******************************************"<<endl;
    cout<<"            *******                            *******"<<endl;
    cout<<"            ****** Gas-N-Clean Service Station  ******"<<endl;
    cout<<"            *******                            *******"<<endl;
    cout<<"            ******        March 2, 2004         ******"<<endl;
    cout<<"            *******                            *******"<<endl;
    cout<<"            ******************************************"<<endl;
    cout<<""<<endl;
    cout<<""<<endl;

    cout<<"Enter the R for regular, P for premium, S for Super, or N for No purchase. \n";
    cout<<""<<endl;
    cin>>type;
    cout<<""<<endl;
    cout<<"Enter how many gallons\n";
    cout<<""<<endl;
    cin>>gallons;
    cout<<""<<endl;
    cout<<"Do You Want a Car Wash? Enter Y for yes or N for No\n";
    cout<<""<<endl;
    cin>>choice;
    cout<<""<<endl;
    cout<<""<<endl;

        if (choice=='y'||choice=='Y')
            cw1=cw;
        else if (choice=='n'||choice=='N')
            cw1=0;
        else
            cout<<"Wrong Input!"<<endl;

    if(type=='r'||type=='R')
        {
          cout<<""<<endl;
          cout<<"---------------------------------------------------- "<<endl;
          cout<<"       Amount Gasoline Purchases:      "<<gallons<<" Gallons"<<endl;
          cout<<""<<endl;
          cout<<"       Price Pre Gallon:             $ "<<price1<<endl;
          cout<<""<<endl;
          cout<<"       Total Gasoline Cost:          $ "<<price1*gallons<<endl;
          cout<<""<<endl;
          cout<<"       Car Wash Cost:                $ "<<cw1<<endl;
          cout<<""<<endl;
          cout<<"       Total due:                    $ "<<price1*gallons+cw<<endl;
          cout<<"-----------------------------------------------------"<<endl;
          cout<<""<<endl;
          cout<<""<<endl;
          cout<<"*********          Thank You For Stopping!         ********"<<endl;
          cout<<""<<endl;
          cout<<"*********             Please Come Again!           ********"<<endl;
          cout<<""<<endl;
          cout<<"*********  Remember to buckle up and drive safely  ********"<<endl;
          cout<<""<<endl;
          cout<<""<<endl;
          return 0;
        }

        else if(type=='p'||type=='P')

        {
          cout<<"Amount Gasoline Purchases:      "<<gallons<<" Gallons"<<endl;
          cout<<""<<endl;
          cout<<"Price Pre Gallon:             $ "<<price2<<endl;
          cout<<""<<endl;
          cout<<"Total Gasoline Cost:          $ "<<price2*gallons<<endl;
          cout<<""<<endl;
          cout<<"Car Wash Cost:                $ "<<cw1<<endl;
          cout<<""<<endl;
          cout<<"Total due                     $ "<<price2*gallons+cw1<<endl;
          cout<<""<<endl;
          cout<<""<<endl;
          cout<<"*********          Thank You For Stopping!         ********"<<endl;
          cout<<""<<endl;
          cout<<"*********             Please Come Again!           ********"<<endl;
          cout<<""<<endl;
          cout<<"*********  Remember to buckle up and drive safely  ********"<<endl;
          return 0;

        }
        else if(type=='s'||type=='S')

        {
          cout<<"Amount Gasoline Purchases:      "<<gallons<<" Gallons"<<endl;
          cout<<""<<endl;
          cout<<"Price Pre Gallon:             $ "<<price3<<endl;
          cout<<""<<endl;
          cout<<"Total Gasoline Cost:          $ "<<price3*gallons<<endl;
          cout<<""<<endl;
          cout<<"Car Wash Cost:                $ "<<cw1<<endl;
          cout<<""<<endl;
          cout<<"Total due                     $ "<<price3*gallons+cw1<<endl;
          cout<<""<<endl;
          cout<<""<<endl;
          cout<<"*********          Thank You For Stopping!         ********"<<endl;
          cout<<""<<endl;
          cout<<"*********             Please Come Again!           ********"<<endl;
          cout<<""<<endl;
          cout<<"*********  Remember to buckle up and drive safely  ********"<<endl;
          return 0;
        }

}

