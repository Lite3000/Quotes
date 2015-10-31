#include <iostream>
using namespace std;

class Sayings{
    public:
        void saying1(){
            cout << "Preachin' to the choir!\n";
        }
        void saying2(){
            cout << "Cool guys don't look at explosions." << endl;
        }
        void saying3(){
            cout << "A quarrelsome man has no good neighbours.\n";
        }
        void saying4(){
            cout << "How can this get 438,000 views when there's only 700 people on Earth?\n";
        }
        void saying5(){
            cout << "Women and Cats will do as they please. Dogs and men need to get used to that.\n";
        }
        void saying6(){
            cout << "The art of acting consists in keeping people from coughing.\n";
        }
        void saying7(){
            cout << "Acting is not being emotional, but being able to fully express emotion.\n";
        }
        void saying8(){
            cout << "Postpone today's anger until tomorrow.\n";
        }
        void saying9(){
            cout << "Clouds gather before a storm.\n";
        }
        void saying10(){
            cout << "Anger is one letter short of danger.\n";
        }
        void saying11(){
            cout << "The buyer needs a hundred eyes, the seller but one.\n";
        }
        void saying12(){
            cout << "It's better to be thought a fool, than to open your mouth and remove all doubt.";
        }
        void saying13(){
            cout << "If you fear nothing, then you are not brave. You are merely too foolish to be afraid.\n";
        }
        void saying14(){
            cout << "Everyone is the age of their heart.\n";
        }
        void saying15(){
            cout << "The pen is mightier than the sword.\n";
        }
        void saying16(){
            cout << "Worthless people blame their karma.\n";
        }
        void saying17(){
            cout << "You'll never do anything behind you that won't come up in front of you.\n";
        }
        void saying18(){
            cout << "Worldly prosperity is like writing on water.\n";
        }
        void saying19(){
            cout << "Fortune favors the prepared mind.\n";
        }
        void saying20(){
            cout << "An hour may destroy what an age was building.\n";
        }
        void saying21(){
            cout << "Every man for himself.\n";
        }
};

int main(){
    Sayings BO;
    int y;
    cout << "Type a number 1-21!\n";
    cin >> y;
    
    if(y==1){
        BO.saying1();
    }
    else if(y==2){
        BO.saying2();
    }
    else if(y==3){
        BO.saying3();
    }
    else if(y==4){
        BO.saying4();
    }
    else if(y==5){
        BO.saying5();
    }
    else if(y==6){
        BO.saying6();
    }
    else if(y==7){
        BO.saying7();
    }
    else if(y==8){
        BO.saying8();
    }
    else if(y==9){
        BO.saying9();
    }
    else if(y==10){
        BO.saying10();
    }
    else if(y==11){
        BO.saying11();
    }
    else if(y==12){
        BO.saying12();
    }
    else if(y==13){
        BO.saying13();
    }
    else if(y==14){
        BO.saying14();
    }
    else if(y==15){
        BO.saying15();
    }
    else if(y==16){
        BO.saying16();
    }
    else if(y==17){
        BO.saying17();
    }
    else if(y==18){
        BO.saying18();
    }
    else if(y==19){
        BO.saying19();
    }
    else if(y==20){
        BO.saying20();
    }
    else if(y==21){
        BO.saying21();
    }
    return 0;
}
