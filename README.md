#include<iostream>
#include<windows.h>
using namespace std;
static	int single=50;
static	int doubl=80;
static	int quad=150;
static	int queen=250;
static	int king=400;
static	int party=250;
static	int A_party=350;
static	int wedding=15;
static	int function=250;
static	int events=200;
static	int concerts=600;
static	int exhibitions=500;
static	int business=500;
static	int conference=400;
class resort
{
	public:
		void booking();
		void menu();
};
void resort::booking()
{
		cout<<"\t\t\t\t"<<" BOOKINGS"<<endl;
		Sleep(1000);
		cout<<"1) ROOMS"<<endl;
		cout<<"2) HALLS"<<endl;
		cout<<"3) CONFERENCE HALLS"<<endl;
		Sleep(1000);
		cout<<"\n-> ROOMS"<<endl;
		cout<<"\n\t => Single \t\t\t "<<"  50$"<<" (per day)"<<endl;
		cout<<"\t => Double \t\t\t "<<"  80$"<<" (per day)"<<endl;
		cout<<"\t => Quad \t\t\t "<<" 150$"<<" (per day)"<<endl;
		cout<<"\t => Queen \t\t\t "<<" 350$"<<" (per day)"<<endl;
		cout<<"\t => King \t\t\t "<<" 450$"<<" (per day)"<<endl;
		Sleep(1000);
		cout<<"\n-> HALLS"<<endl;
		cout<<"\n\t => Party \t\t\t "<<" 250$"<< " (5:00 hours)"<<endl;
		cout<<"\t => After Party \t\t "<<" 350$"<<" (5:00 hours)"<<endl;
		cout<<"\t => Wedding Ceremony \t\t "<<"  15$"<<" (per head)"<<endl;
		cout<<"\t => Casual Functions \t\t "<<" 250$"<<" (5:00 hours)"<<endl;
		cout<<"\t => Relegious Events \t\t "<<" 200$"<<" (5:00 hours)"<<endl;
		cout<<"\t => Concerts \t\t\t "<<" 600$"<<" (per day)"<<endl;
		cout<<"\t => Exhibitions \t\t "<<" 500$"<<" (per day)"<<endl;
		Sleep(1000);
		cout<<"\n-> CONFERENCE HALLS"<<endl;
		cout<<"\n\t => Business Meetings \t\t "<<" 500$"<<" (3:00 hours)"<<endl;
		cout<<"\t => Conferences \t\t "<<" 400$"<<" (3:00 hours)"<<endl;
}
void resort::menu()
{
		cout<<"\t\t\t\t"<<"  FOOD MENU"<<endl;
		Sleep(1000);
		cout<<"-> BREAKFAST"<<endl;
		cout<<"\n\t => Omlet \t\t\t 0.75"<<" $"<<endl;
		cout<<"\t => Fried egg \t\t\t 0.75"<<" $"<<endl;
		cout<<"\t => Cheese \t\t\t 1.00"<<" $"<<endl;
		cout<<"\t => Butter \t\t\t 0.50"<<" $"<<endl;
		cout<<"\t => Jam \t\t\t 0.25"<<" $"<<endl;
		cout<<"\t => Tea \t\t\t 1.00"<<" $"<<endl;
		cout<<"\t => Slices \t\t\t 1.00"<<" $"<<endl;
		Sleep(1000);
		cout<<"\n-> LUNCH"<<endl;
		cout<<"\n\t => Plain Rice \t\t\t 2.00"<<" $"<<endl;
		cout<<"\t => Chicken Biryani \t\t 5.00"<<" $"<<endl;
		cout<<"\t => Chicken Qourma \t\t 6.00"<<" $"<<endl;
		cout<<"\t => Muttton Qourma \t\t 7.00"<<" $"<<endl;
		cout<<"\t => Vegetables \t\t\t 3.00"<<" $"<<endl;
		Sleep(1000);
		cout<<"\n-> DINNER"<<endl;
		cout<<"\n\t => Sindhi Biryani \t\t 5.00"<<" $"<<endl;
		cout<<"\t => Chicken BBQ \t\t 2.50"<<" $"<<endl;
		cout<<"\t => Mutton Chomps \t\t 6.00"<<" $"<<endl;
		cout<<"\t => chicken Kababs \t\t 3.00"<<" $"<<endl;
		cout<<"\t => Muttton Kababs \t\t 6.25"<<" $"<<endl;
		cout<<"\t => Beef Kababs \t\t 5.00"<<" $"<<endl;
		Sleep(1000);
		cout<<"\n-> DRINKS"<<endl;
		cout<<"\t => Mineral Water \t\t 0.50"<<" $"<<endl;
		cout<<"\t => Sprite/Fanta/Coke \t\t 1.50"<<" $"<<endl;
		cout<<"\t => Juice \t\t\t 0.75"<<" $"<<endl;
		cout<<"\t => Champagne \t\t\t 1.00"<<" $"<<endl;
		cout<<"\t => Beer \t\t\t "<<"2.00 $"<<endl;
		cout<<"\t => Wine \t\t\t 3.00"<<" $"<<endl;
}
int main()
{
	void singl();
	void part();
	void a_part();
	void wedd();
	void reli();
	void concert();
	void office();
	void cas();
	void exhi();
	void doub();
	void quad1();
	void queen1();
	void king1();
	void rooms();
	void halls();
	void conferenc();
	void rates();
	void registration();
	Sleep(1000);
	cout<<"\t\t\t"<<" *****************************"<<endl;
	Sleep(1000);
	cout<<"\t\t\t"<<"        LEGEND'S RESORT"<<endl;
	Sleep(1000);
	cout<<"\t\t\t"<<"   WELCOME TO LEGEND'S HOTEL"<<endl;
	Sleep(1000);
	cout<<"\t\t\t"<<" *****************************"<<endl;
	Sleep(1000);
	cout<<"\t"<<"1)  FOOD MENU"<<endl;
	Sleep(100);
	cout<<"\t"<<"2)  BOOKINGS"<<endl;
	Sleep(100);
	cout<<"\t"<<"3)  REGISTRATION"<<endl;
	Sleep(100);
	cout<<"\t"<<"4) (OFFICE WORK ONLY)";
	resort obj;
	retrn:	
	cout<<"\n\n"<<"Press 1 for FOOD MENU, 2 for BOOKINGS, 3 to REGISTER your order and 4 for OFFICE PURPOSES "<<endl;
	int a;
	cin>>a;
	if (a==1)
	{
		int clrscr();
		obj.menu();
	}
	else if (a==2)
	{	int clrscr();
		obj.booking();
	}
	else if (a==3)
	{
		int clrscr();
		registration();
	}
	else if (a==4)
	{
		int clrscr();
		office();
	}
	goto retrn;
}
void singl()
{
		int d,t;
		cout<<"Enter your duration in days: ";
		cin>>d;
		t=single*d;
		cout<<"Your bill for"<<" "<<d<<"days is"<<" "<<single<<"*"<<d<<" ="<<t<<"$"<<endl;
}
void doub()
{
		int a,r;
		cout<<"Enter your duration in days: ";
		cin>>a;
		r=doubl*a;
		cout<<"Your bill for"<<" "<<a<<"days is"<<" "<<doubl<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void quad1()
{
		
		int a,r;
		cout<<"Enter your duration in days: ";
		cin>>a;
		r=quad*a;
		cout<<"Your bill for"<<" "<<a<<"days is"<<" "<<quad<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void queen1()
{
		int a,r;
		cout<<"Enter your duration in days: ";
		cin>>a;
		r=queen*a;
		cout<<"Your bill for"<<" "<<a<<"days is"<<" "<<queen<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void king1()
{
		int a,r;
		cout<<"Enter your duration in days: ";
		cin>>a;
		r=king*a;
		cout<<"Your bill for"<<" "<<a<<"days is"<<" "<<king<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void part()
{
		
		int a,r;
		cout<<"Enter your duration in hours: ";
		cin>>a;
		r=party*a;
		cout<<"Your bill for"<<" "<<a<<"hours is"<<" "<<party<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void a_part()
{
		int a,r;
		cout<<"Enter your duration in hours: ";
		cin>>a;
		r=A_party*a;
		cout<<"Your bill for"<<" "<<a<<"hours is"<<" "<<A_party<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void wedd()
{
		
		int a,r;
		cout<<"Enter the amount of guests: ";
		cin>>a;
		r=wedding*a;
		cout<<"Your bill for "<<a<<" guests is"<<" "<<wedding<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void reli()
{
		int a,r;
		cout<<"Enter your duration in hours: ";
		cin>>a;
		r=events*a;
		cout<<"Your bill for"<<" "<<a<<"hours is"<<" "<<events<<" * "<<a<<" ="<<r<<"$"<<endl;
}
void exhi()
{
		int a,r;
		cout<<"Enter your duration in hours: ";
		cin>>a;
		r=exhibitions*a;
		cout<<"Your bill for"<<" "<<a<<"hours is"<<" "<<exhibitions<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void cas()
{
		int a,r;
		cout<<"Enter your duration in hours: ";
		cin>>a;
		r=function*a;
		cout<<"Your bill for"<<" "<<a<<"hours is"<<" "<<function<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void concert()
{
		int a,r;
		cout<<"Enter your duration in hours: ";
		cin>>a;
		r=concerts*a;
		cout<<"Your bill for"<<" "<<a<<"hours is"<<" "<<concerts<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void meeting()
{
		int a,r;
		cout<<"Enter your duration in hours: ";
		cin>>a;
		r=business*a;
		cout<<"Your bill for"<<" "<<a<<"hours is"<<" "<<business<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void conferences()
{
		int a,r;
		cout<<"Enter your duration in hours: ";
		cin>>a;
		r=conference*a;
		cout<<"Your bill for"<<" "<<a<<"hours is"<<" "<<conference<<"*"<<a<<" ="<<r<<"$"<<endl;
}
void halls()
{
		char sub;
		wrng:cout<<"Enter a right character"<<endl;
		cout<<"Press 'A' for Party \nPress 'B' for After party \nPress 'C  for Wedding ceremonies \nPress 'D' for Casual functions \nPress 'E' for Religious functions \nPress 'F' for Exhibitions \nPress 'G' for Concerts"<<endl;
		cin>>sub;
		wrong1:
switch (sub)
{
case 'A' : case 'a':
{
part();
break;
}
case 'B': case 'b':
{
a_part();
break;
}
case 'c': case 'C':
{
wedd();
break;
}
case 'd' : case 'D':
{
cas();
break;
}
case 'e' : case 'E':
{
	reli();
	break;
}
case 'f' : case 'F':
{
	exhi();
	break;
}
default:
{
goto wrng;
}
}
}
void conferenc()
{
		char sub;
		wrng:cout<<"Enter a right character"<<endl;
		cout<<"\nPress 'A' for Business meetings \nPress 'B' for Conferences"<<endl;
		cin>>sub;
		wrong1:
switch (sub)
{
case 'A' : case 'a':
{
meeting();
break;
}
case 'B': case 'b':
{
conferences();
break;
}
}
}
void rooms()
{
		char sub;
		wrng:cout<<"Enter a right character"<<endl;
		cout<<"Press 'A' for Single \n 'B' for Double \n 'C' for Quad \n 'D' for Queen and 'E' for King"<<endl;
		cin>>sub;
		wrong1:
switch (sub)
{
case 'A' : case 'a':
{
singl();
break;
}
case 'B': case 'b':
{
doub();
break;
}
case 'c': case 'C':
{
quad1();
}
case 'd' : case 'D':
{
	queen1();
	break;
}
case 'e' : case 'E':
{
	king1();
	break;
}
default:
{
goto wrng;
}
}
}
void registration()
{
	string fn,sn;
	string c;
	string id;
	int i=0;
	string num;
	cout<<"\t\t\t\t"<<" Customer order"<<endl;
	Sleep(1000);
	cout<<"Customer's first name: ";
	cin>>fn;
	cout<<"Customer's surname: ";
	cin>>fn;	
	cout<<"Customer's ID number: ";
	cin>>id;
	cout<<"Customer's contact number: ";
	cin>>num;
	cout<<"City name: ";
	cin>>c;
	cout<<"\n"<<"Select your desired option from following dialogues:"<<endl;
	wrong:
	cout<<"\n"<<"Enter 1 for ROOMS,2 for HALLS and 3 for CONFERENCE HALLS  "<<endl;
	cin>>i;
	if (i==1)
	{
		rooms();
	}
	else if (i==2)
	{
	halls();
	}	
	else if (i==3)
	{
	conferenc();
	}
	else
	goto wrong;
	string card;
	cout<<"\nEnter your credit card number: ";
	cin>>card;
	Sleep(2000);
	cout<<"Processing"<<endl;
	Sleep(2000);
	cout<<"Process has been completed"<<endl;
	Sleep (2000);
	cout<<"\t\t\t\t    BILL"<<endl;
	Sleep(2000);
	cout<<"\t\t\t"<<" ***************************"<<endl;
	cout<<"\t\t\t\t"<<"LEGEND's RESORT"<<endl;
	cout<<"\t\t\t"<<" ***************************"<<endl;
	cout<<"Customer name: "<<fn<<" "<<sn<<endl;
	cout<<"Customer ID: "<<id<<endl;
	cout<<"Customer contact number: "<<num<<endl;
	cout<<"Bill status:"<<"PAID"<<endl;
	Sleep(1000);
	cout<<"\n*************************"<<endl;
	cout<<"Thank you have a nice day";
	cout<<"\n*************************"<<endl;
	}
	void office()
{
string user_id;
	cout<<"Enter your user ID: ";
	cin>>user_id;
	cout<<"Enter password: ";
wrng2:
int password;

	cin>>password;

if (password==54321)
{
cout<<"WELCOME "<<user_id<<endl;
Sleep(2000);
cout<<"Do you want to change the rates? "<<endl;
Sleep(2000);
wrng4:

cout<<"Press 'Y' for yes and 'C' to cancel the request: "<<endl;
char chng;
cin>>chng;
if (chng=='y')
{
cout<<"For which item you want the rates? ";
Sleep(1000);
wrng3:
cout<<"Press '1' for Single size room \n '2' for Ddouble size room \n'3' for Quad size room \n '4' for Queen size room \n '5' for King size room \n";
cout<<" '6' for Party \n '7' for After party \n '8' for Wedding ceremony \n '9' for Casual functions \n '10' for Religious events\n";
cout<<" '11' for Exhibitions \n '12' for Business meetings \n '13' for Conferences \n";
int O;
cin>>O;
switch(O)
{
	case 1:
	{
		cout<<"Enter new value of Single sized room: ";
		cin>>single;
		break;
	}
		case 2:
	{
		cout<<"Enter new value of Double sized room: ";
		cin>>doubl;
		break;
	}
		case 3:
	{
		cout<<"Enter new value of Quad sized room: ";
		cin>>quad;
		break;
	}
		case 4:
	{
		cout<<"Enter new value of Queen sized room: ";
		cin>>queen;
		break;
	}
		case 5:
	{
		cout<<"Enter new value of King sized room: ";
		cin>>king;
		break;
	}
		case 6:
	{
		cout<<"Enter new value of hall for Party: ";
		cin>>party;
		break;
	}
		case 7:
	{
		cout<<"Enter new value of hall for After party: ";
		cin>>A_party;
		break;
	}
		case 8:
	{
		cout<<"Enter new value of hall for Wedding ceremony: ";
		cin>>wedding;
		break;
	}
		case 9:
	{
		cout<<"Enter new value of hall for Casual functions: ";
		cin>>function;
		break;
	}
		case 10:
	{
		cout<<"Enter new value of hall for Religious events: ";
		cin>>events;
		break;
	}	
		case 11:
	{
		cout<<"Enter new value of hall for Concerts: ";
		cin>>concerts;
		break;
	}	
		case 12:
	{
		cout<<"Enter new value of conference hall for Business meetings: ";
		cin>>business;
		break;
	}	
		case 13:
	{
		cout<<"Enter new value of conference hall for Conferences:";
		cin>>conference;
		break;
	}
	default:
	{
	goto wrng3;	
	}
}
}else
{
goto wrng4;
}
}
else 
{
	goto wrng2;
}
}




