#include <iostream>
using namespace std;
class Trans_system  //Class 1
{
 protected :
 string choice;
 string stu_name;
 string stu_age;
 string stu_id;
 string stu_address;
 public :
 void GetData()
 {
	 cout<<"\n\t\t\t\t\t<<<<< STUDENT LOGIN >>>>>";
	 cout <<"\n\t\tEnter Student Name : ";
	 cin>>stu_name;
	 cout <<"\n\t\tEnter the Age : ";
	 cin>>stu_age;
	 cout <<"\n\t\tEnter ID : ";
	 cin>>stu_id;
	 cout <<"\n\t\tEnter Address : ";
	 cin>>stu_address;
			
 }

 void display ()
{
cout<<"\n\t\tStudent Name   : " <<stu_name << endl;
cout<<"\t\tID      : "<<stu_id << endl;
cout<<"\t\tAge     : "<<stu_age << endl;
cout<<"\t\tFrom Address :"<<stu_address << endl; }
};
class Getnum : public Trans_system
{
 private :
 int num;
 public :

 void Get_num()
 {
 cout << "\n\t\tEnter Student's transport number: " ;
 cin >>num; 
 }

 void display_num()
 {
 cout<<"\n\t\tTransport number: " <<num ;
 }

};
//class2
class Trans_system2
{
 protected :
 string choice;
 string tec_name;
 string tec_age;
 string tec_id;
 string tec_address;
 public :
 void GetData2()
 {
	 cout<<"\n\t\t\t\t\t<<<<< TEACHER LOGIN >>>>>";
	 cout <<"\n\t\tEnter Teacher Name : ";
	 cin>>tec_name;
	 cout <<"\n\t\tEnter the Age : ";
	 cin>>tec_age;
	 cout <<"\n\t\tEnter ID : ";
	 cin>>tec_id;
	 cout <<"\n\t\tEnter Address : ";
	 cin>>tec_address;
 }
 void displayinfo ()
{
 cout<<"\n\t\tTeacher Name   : " <<tec_name << endl;
 cout<<"\t\tID      : "<<tec_id << endl;
 cout<<"\t\tAge     : "<<tec_age << endl;
 cout<<"\t\tFrom Address :"<<tec_address << endl;
}
};
class Getnum2 : public Trans_system2
{
 private :
 int tec_num;
 public :

 void Getinfo()
 {
 cout << "\n\t\tEnter Teacher's transport number: " ;
 cin >>tec_num; 
 }
 void display_num2()
 {
 cout<<"\n\t\tTransport number: " <<tec_num ;
 }
};
 //Class 3
 class Getcomp : public Trans_system2
 {
 	public:
 		string complaint;
 		void Get_comp()
 		{
 			cout<<"\t\t\t\t\t--------< Enter Your Complaint Here >---------" <<endl ;
 			cin>>complaint;
		 }
 };
 //Class 4
  class Getexit: public Trans_system2
 {
 	public:
 		void Get_exit()
 		{
 			cout<<"\n\t\t\t\t******** You are Exit the System **********";
		 }
 };
int main()
{

 cout<<"\t\t\t~~~~~~~~~ WELCOME TO SCHOOL TRANSPORT MANAGEMENT SYSTEM ~~~~~~~~~~~~\n" <<endl;
 cout << "\t\t\t\t\t  1 --> STUDENT LOGIN  " << endl <<"\t\t\t\t\t  2 --> TEACHER LOGIN  "<< endl <<"\t\t\t\t\t  3 --> COMPLAINT    " <<endl <<"\t\t\t\t\t  4 --> EXIT" <<endl;
 
 int choice;
 cout<<"\n\t\t\t\t\tEnter the Choice: ";
 cin>>choice;
 if(choice==1)
 {
 Getnum p1;
 p1.GetData();
 p1.Get_num();
 cout <<"\n\t\t-------- Display Information of Student -----------\n " <<endl ;
 p1.display_num();
 p1.display();
 }
 else if(choice==2)
 {
 Getnum2 p2;
 p2.GetData2() ;
 p2.Getinfo() ;
 cout <<"\n\t\t-------- Display Information of Teacher -----------\n" <<endl ;
 p2.display_num2();
 p2.displayinfo() ;
 }
 else if(choice==3)
 {
 Getcomp p3;
 p3.Get_comp() ;
 }
 else
 {
 Getexit p4;
 p4.Get_exit();
 }
 return 0;
}
