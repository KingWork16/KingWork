#include <iostream>

int main(){
    //Code to calculate percentager from your Marks
    std::string ch = "y";
    //While loopis used to Ask user if want t o continue
    while (ch == "y")
    {
    std::cout << "---------------PERCENEGE CONVERTER---------------"<<'\n';
    double totalmarks = 550;
    double outofmarks ;
    double percentage;
    //Asking input of Out Of Marks from the user
    std::cout << "Enter Your Out Of Marks : ";
    std::cin >> outofmarks;

    //calculating percentage
    percentage = outofmarks/totalmarks*100;
    
    if (percentage > 90)
    {
        std::cout << "Congratulation You Really Got Marks : "<<percentage <<'\n';
    }
    else if (percentage > 70)
    {
        std::cout << "Congratulation you are pass,Keep it up : "<<percentage <<'\n';
    }
    else if (percentage > 65)
    {
        std::cout << "You have to improve : "<< percentage <<'\n';
    }
    else if(percentage > 45)
    {
        std::cout << "Tooo Bad,You need to do hard work : "<< percentage <<'\n';
    }
    else 
    {
        std::cout << "You Failed : "<< percentage <<'\n';
    }
    std::cout << "-------------------------------------------------"<<'\n'; 
    std::cout << "Want to continue Y/N : ";
    std::cin >> ch;
    } 
    
    
    return 0;
}
