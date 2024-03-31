#include<iostream>
using namespace std;
class Doctor{
	public:
		string name[6]={"Dr.Chandrasakhar Jana","Dr.Goutam Jana","Dr.Nibadita Roy"," Dr.Goutam Pradhan","4. Dr.Ashis Pramanik","5. Dr.Anjan Dey "};
		static int sum,sum1,sum2,t,t1,t2,j,j1,j2,f,f1,f2,y,y1,y2,r,r1,r2;
		string a;
		int b;
		void get()
		{
			cout<<"|-----------------------------------------------"<<endl;
			cout<<"| Enter your Name: ";
			cin.ignore();
			getline(cin,a);
			cout<<"| Enter Your Age: ";
			cin>>b;
			cout<<"|-----------------------------------------------"<<endl;
		}
		void all()
		{
			cout<<"| Your Name: "<<a<<endl;
			cout<<"| Your Age: "<<b<<endl;
		}
		void first()
		{
	        cout<<"| Doctor name:"<<name[0]<<endl;
	        cout<<"| Timing--7.30am-10.30am \n";
	        all();
		}
		void second()
		{
			cout<<"| Doctor name:"<<name[1]<<endl;
			cout<<"| Timing--10.30am-1.30am\n";
			all();
		}
		void third()
		{
			cout<<"| Doctor name:"<<name[2]<<endl;
			cout<<"| Timing--7.30am-10.30am \n";
			all();
		}
		void four()
		{
			cout<<"| Doctor name:"<<name[3]<<endl;
			cout<<"| Timing--6.30pm-9.30pm \n";
			all();
		}
		void five()
		{
			cout<<"| Doctor name:"<<name[4]<<endl;
			cout<<"| Timing--10.30am-1.30am \n";
			all();
		}
		void six()
		{
			cout<<"| Doctor name:"<<name[5]<<endl;
			cout<<"| Timing--3.30pm-6.30pm \n";
			all();
		}
		void Patient(int c)
		{
			switch(c)
			{
				case 1:
					int d;
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| On this day, the doctor came to the clinic:\n| 1.Monday--(Available slot is "<<(15-t)<<")\n| 2.Wednessday--(Available slot is "<<(15-t1)<<")\n| 3.Saturday--(Available slot is "<<(15-t2)<<")\n";
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| Choose This Day:  ";
					cin>>d;
					cout<<"|=============================================================\n\n";
					switch(d)
					{
						case 1:
							if(t<=15)
								{
							        t=t+1;
							        cout<<"| Your booking is done on monday\n";
							        first();
									cout<<"| Your Serial Number: "<<t<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}							
							break;
						case 2:
								if(t1<=15)
								{
							        t1=t1+1;
							        cout<<"| Your booking is done on Wednessday\n";
							        first();
									cout<<"| Your Serial Number: "<<t1<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						case 3:
								if(t2<=15)
								{
							        t2=t2+1;
							        cout<<"| Your booking is done on Saturday\n";
							        first();
									cout<<"| Your Serial Number: "<<t2<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						default:
							cout<<"| Invalid Input!Please Try again!\n";
							Choose();
							break;
			            	 }
				    break;	
				case 2:
					int d1;
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| On this day, the doctor came to the clinic:\n| 1.Monday--(Available slot is "<<(15-sum)<<")\n| 2.Tursday--(Available slot is "<<(15-sum1)<<")\n| 3.Saturday--(Available slot is "<<(15-sum2)<<")\n";
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| Choose This Day:  ";
					cin>>d1;
					cout<<"|=============================================================\n\n";
					switch(d1)
					{
						case 1:
							if(sum<=15)
								{
							        sum=sum+1;
							        cout<<"| Your booking is done on monday\n";
							        second();
									cout<<"| Your Serial Number: "<<sum<<endl;
									cout<<"\n|============================================================\n";
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}							
							break;
						case 2:
								if(sum1<=15)
								{
							        sum1=sum1+1;
							        cout<<"| Your booking is done on Thursday\n";
							        second();
									cout<<"| Your Serial Number: "<<sum1<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						case 3:
								if(sum2<=15)
								{
							        sum2=sum2+1;
							        cout<<"| Your booking is done on Saturday\n";
							        second();
									cout<<"| Your Serial Number: "<<sum2<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						default:
							cout<<"| Invalid Input!Please Try again!\n";
							Choose();
							break;
			     	    }
						    break;
				case 3:
					int d2;
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| On this day, the doctor came to the clinic:\n| 1.Wednessday--(Available slot is "<<(15-f)<<")\n| 2.Thursday--(Available slot is "<<(15-f1)<<")\n| 3.Friday--(Available slot is "<<(15-f2)<<")\n";
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| Choose This Day:  ";
					cin>>d2;
					cout<<"|=============================================================\n\n";
					switch(d2)
					{
						case 1:
							if(f<=15)
								{
							        f=f+1;
							        cout<<"| Your booking is done on Wednessday\n";
							        third();
									cout<<"| Your Serial Number: "<<f<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}	
							break;
						case 2:
								if(f1<=15)
								{
							        f1=f1+1;
							        cout<<"| Your booking is done on Thursday\n";
							        third();
									cout<<"| Your Serial Number: "<<f1<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						case 3:
								if(sum2<=15)
								{
							        f2=f2+1;
							        cout<<"| Your booking is done on Friday\n";
							        third();
									cout<<"| Your Serial Number: "<<f2<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						default:
							cout<<"| Invalid Input!Please Try again!\n";
							Choose();
							break;
			     	}
				    break;
				case 4:
					int d3;
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| On this day, the doctor came to the clinic:\n| 1.Sunday--(Available slot is "<<(15-y)<<")\n| 2.Wednessday--(Available slot is "<<(15-y1)<<")\n| 3.Friday--(Available slot is "<<(15-y2)<<")\n";
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| Choose This Day:  ";
					cin>>d3;
					cout<<"|=============================================================\n\n";
					switch(d3)
					{
						case 1:
							if(y<=15)
								{
							        y=y+1;
							        cout<<"| Your booking is done on Sunday\n";
							        four();
									cout<<"| Your Serial Number: "<<y<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						case 2:
								if(y1<=15)
								{
							        y1=y1+1;
							        cout<<"| Your booking is done on Wednessday\n";
							        four();
									cout<<"| Your Serial Number: "<<y1<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						case 3:
								if(y2<=15)
								{
							        y2=y2+1;
							        cout<<"| Your booking is done on Friday\n";
							        four();
									cout<<"| Your Serial Number: "<<y2<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						default:
							cout<<"| Invalid Input!Please Try again!\n";
							Choose();
							break;
			     	}
				    break;
				case 5:
					int d4;
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| On this day, the doctor came to the clinic:\n| 1.Tuesday--(Available slot is "<<(15-r)<<")\n| 2.Tursday--(Available slot is "<<(15-r1)<<")\n| 3.Saturday--(Available slot is "<<(15-r2)<<")\n";
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| Choose This Day:  ";
					cin>>d4;
					cout<<"|=============================================================\n\n";
					switch(d4)
					{
						case 1:
							if(r<=15)
								{
							        r=r+1;
							        cout<<"| Your booking is done on Tuesday\n";
							        five();
									cout<<"| Your Serial Number: "<<r<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						case 2:
								if(r1<=15)
								{
							        r1=r1+1;
							        cout<<"| Your booking is done on Thursday\n";
							        five();
									cout<<"| Your Serial Number: "<<r1<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						case 3:
								if(r2<=15)
								{
							        r2=r2+1;
							        cout<<"| Your booking is done on Saturday\n";
							        five();
									cout<<"| Your Serial Number: "<<r2<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						default:
							cout<<"| Invalid Input!Please Try again!\n";
							Choose();
							break;
			     	}
				    break;
				case 6:
					int d5;
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| On this day, the doctor came to the clinic:\n| 1.Tuesday--(Available slot is "<<(15-j)<<")\n| 2.Friday--(Available slot is "<<(15-j1)<<")\n| 3.Sunday--(Available slot is "<<(15-j2)<<")\n";
					cout<<"|-----------------------------------------------"<<endl;
					cout<<"| Choose This Day:  ";
					cin>>d5;
					cout<<"|=============================================================\n\n";
					switch(d5)
					{
						case 1:
							if(	j<=15)
								{
							        j=j+1;
							        cout<<"| Your booking is done on Tuesday\n";
							        six();
									cout<<"| Your Serial Number: "<<j<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}							
							break;
						case 2:
								if(j1<=15)
								{
							        j1=j1+1;
							        cout<<"| Your booking is done on Friday\n";
							        six();
									cout<<"| Your Serial Number: "<<j1<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						case 3:
								if(j2<=15)
								{
							        j2=j2+1;
							        cout<<"| Your booking is done on Sunday\n";
							        six();
									cout<<"| Your Serial Number: "<<j2<<endl;
									cout<<"\n|============================================================\n";	
							    }
							    else
							    {
							    	cout<<"| Doctor Patient Set is fool \n";
								}
							break;
						default:
							cout<<"| Invalid Input!Please Try again!\n";
							Choose();
							break;
			     	}
				    break;
				default:
					cout<<"| Invalid Input!Please Try Again!\n";
					Choose();
		    }	
		}
		void Choose()
		{
			while(true){
				int c;
				cout<<"!-------------------------------!-----------------------!-----------------------!-----------------------!-------------------------------!"<<endl;
				cout<<"|\t\t\t\t\t\t\t   Welome to my clinik\t\t\t\t\t\t\t\t|\n";
				cout<<"!-------------------------------!-----------------------!-----------------------!-----------------------!-------------------------------!"<<endl;
				cout<<"| Dr.name\t\t\t|\tSpcalizaton\t|\tFees\t\t|\tdate\t\t|\t\tTime\t\t|\n";
				cout<<"!-------------------------------!-----------------------!-----------------------!-----------------------!-------------------------------!"<<endl;
				cout<<"| 1. Dr.Chandrasakhar Jana  \t|   .Neurologist      \t|   .fees--600     \t|   sat,mon,wed   \t|   .time--7.30am-10.30am   \t|\n| 2. Dr.Goutam Jana  \t\t|   .Gynecologist   \t|   .fees--500     \t|   mon,thu,sat   \t|   .time--10.30am-1.30am \t|\n| 3. Dr.Nibadita Roy  \t\t|   .Veterinarian   \t|   .fees---700  \t|   wed,thu,fri   \t|   .time--7.30am-10.30am  \t|\n| 4. Dr.Goutam Pradhan  \t|   .homeopathy \t|   .fees--500  \t|   sun,wed,fri   \t|   .time--6.30pm-9.30pm     \t|\n| 5. Dr.Ashis Pramanik  \t|   .Oncologist  \t|   .fees---350    \t|   tus,thu,sat   \t|   .time--10.30am-1.30am    \t|\n| 6. Dr.Anjan Dey  \t\t|   .General Physician \t|   .fees---400     \t|   tus,fri,sun   \t|   .time--3.30pm-6.30pm    \t|\n";
				cout<<"!-------------------------------!-----------------------!-----------------------!-----------------------!-------------------------------!"<<endl;
				cout<<"| Choose A doctor: ";
				cin>>c;
				get();
				if (c >= 1 && c <= 6) 
				{
				    Patient(c);   
				} 				
			}
	 }
};
int Doctor::sum=0;
int Doctor::sum1=0;
int Doctor::sum2=0;
int Doctor::t=0;
int Doctor::t1=0;
int Doctor::t2=0;
int Doctor::r=0;
int Doctor::r1=0;
int Doctor::r2=0;
int Doctor::f=0;
int Doctor::f1=0;
int Doctor::f2=0;
int Doctor::j=0;
int Doctor::j1=0;
int Doctor::j2=0;
int Doctor::y=0;
int Doctor::y1=0;
int Doctor::y2=0;
int main()
{
	Doctor D;
	D.Choose();	
}
