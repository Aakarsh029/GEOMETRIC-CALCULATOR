#include<iostream.h>
#include<math.h>
#include<conio.h>
void main()
{clrscr();
long int a,b,c,d,r,l,h,e,f,g,i,r1,r2,ir,fr,uc,lc,ic,max,p,m,comp,eng,u,grade;
long int bs,n,A1,A2,B1,B2,C1,C2,lowest;
float hia,da,ta,tax;
float area,vol,perimeter,per,t,x1,x2,total;
char s;
cout<<"\n enter 1 for area of all figures";
cout<<"\n enter 2 for volume of all figures";
cout<<"\n enter 3 for roots of quad equaton";
cout<<"\n enter 4 for perimetres of all figures";
cout<<"\n enter 5 for electricity bill ";
cout<<"\n enter 6 for telephone bill";
cout<<"\n enter 7 for calculator";
cout<<"\n enter 8 for report card";
cout<<"\n enter 9 for salary of person";
cout<<"\n enter 10 for reversing the number";
cout<<"\n enter 11 for greatest element";
cout<<"\n order please";
cin>>d;
switch(d)
{ case 1:
cout<<"enter 11 for area of triangle \n";
cout<<"enter 12 for area of circle \n";
cout<<"enter 13 for area of square\n";
cout<<"enter 14 for area of rectangle \n";
cout<<"enter 15 for area of llgm \n";
cout<<"enter 16 for area of trapezium \n";
cout<<"enter 17 for area of cuboid \n";
cout<<"enter 18 for area of cylinder \n ";
cout<<"enter 19 for area of hemisphere \n";
cout<<"enter 20 for area of cone \n ";
cout<<"order please \n";
cin>>e;
switch(e)
{
case 11:
cout<<"enter base and height of triangle";
cin>>a>>b;
area=0.5*a*b;
cout<<"area of triangle="<<area;
break;
case 12:
cout<<"enter radius";
cin>>r;
area=3.14*r*r;
cout<<"area of circle="<<area;
break;
case 13:
cout<<"enter side of square ";
cin>>a;
area=a*a;
cout<<"area of square="<<area;
break;
case 14:
cout<<"enter length and breadth";
cin>>l>>b;
area=l*b;
cout<<"area of rectangle="<<area;
break;
case 15:
cout<<"enter base and height";
cin>>b>>h;
area=b*h;
cout<<"area of llgm="<<area;
break;
case 16:
cout<<"enter sides and height of trapezium";
cin>>a>>b>>h;
area=0.5*h*(a+b) ;
cout<<"area of trapezium="<<area;
break;
case 17:
cout<<"enter sides of cuboid";
cin>>l>>b>>h;
area=2*h*(l+b);
cout<<"area of cuboid="<<area;
break;
case 18:
cout<<"enter radius and height of cylinder";
cin>>r>>h;
area=2*3.14*r*h;
cout<<"area of cylinder ="<<area;
break;
case 19:
cout<<"enter radius of hemisphere";
cin>>r;
area=2*3.14*r*r;
cout<<"area of hemisphere="<<area;
break;
case 20 :
cout<<"enter slant height and radius of cone";
cin>>l>>r;
area=3.14*r*l;
cout<<"area of cone ="<<area;
break;
}
break;
case 2:
cout<<"enter 21 for vol of cube \n";
cout<<"enter 22 for vol of cuboid \n";
cout<<"enter 23 for vol of cone \n";
cout<<"enter 24 for vol of cylinder \n";
cout<<"enter 25 for vol of sphere \n";
cout<<"enter 26 for vol of hemisphere \n";
cout<<"enter 27 for vol of frustum \n";
cout<<"order please \n";
cin>>f;
switch(f)
{ case 21:
cout<<"enter side of cube";
cin>>s;
vol=s*s*s;
cout<<"vol of cube"<<vol;
break;
case 22:
cout<<"enter sides of cuboid";
cin>>l>>b>>h;
vol=l*b*h;
cout<<"vol of cuboid"<<vol;
break;
case 23:
cout<<"enter height and radius of cone";
cin>>r>>h;
vol=0.3*3.14*r*r*h;
cout<<"vol of cone="<<vol;
break;
case 24:
cout<<"enter radius and height of cylinder";
cin>>r>>h;
vol=3.14*r*r*h;
cout<<"vol of cylinder"<<vol;
break;
case 25:
cout<<"enter radius of sphere";
cin>>r;
vol=(4*3.14*r*r*r)/3;
cout<<"vol of sphere="<<vol;
break;
case 26:
cout<<"enter radius of hemisphere";
cin>>r;
vol=(2*3.14*r*r*r)/3  ;
cout<<"vol of hemisphere="<<vol;
break;
case 27:
cout<<"enter radiuses and height of frustum";
cin>>r1>>r2>>h;
vol=0.3*3.14*h*(r1*r1+r2*r2+r1*r2)  ;
cout<<"vol of frustum="<<vol;
break;
}
break;
case 3:
cout<<"enter a,b,c";
cin>>a>>b>>c;
t=b*b-4*a*c;
x1=(-b+sqrt(t))/2*a ;
x2=(-b-sqrt(t))/2*a ;
cout<<"discriminant="<<t;
cout<<"roots of quad equation="<<x1;
cout<<"roots of quad equation="<<x2;
break;
case 4:
cout<<"enter 41 for perimeter of triangle";
cout<<"enter 42 for perimeter of square";
cout<<"enter 43 for perimeter of rectangle";
cout<<"enter 44 for perimeter of circle";
cout<<"enter 45 for peimeter of llgm";
cout<<"enter 46 for perimeter of rhombus";
cout<<"order please";
cin>>h;
switch(h)
{ case 41:
cout<<"enter 3 sides of triangle";
cin>>a>>b>>c;
perimeter=a+b+c;
cout<<"perimeter of triangle="<<perimeter;
break;
case 42:
cout<<"enter side of square";
cin>>a;
perimeter=a+a+a+a;
cout<<"perimeter of square"<<perimeter;
break;
case 43:
cout<<"enter length and breadth of rectangle";
cin>>l>>b;
perimeter=2*(l+b);
cout<<"perimeter of rectangle="<<perimeter;
break;
case 44:
cout<<"enter radius";
cin>>r;
perimeter=2*3.14*r;
cout<<"perimeter of circle="<<perimeter;
break;
case 45:
cout<<"enter sides of llgm";
cin>>b>>a;
perimeter=a+a+b+b;
cout<<"perimeter of llgm"<<perimeter;
break;
case 46:
cout<<"enter sides of rhombus";
cin>>a;
perimeter=a+a+a+a;
cout<<"perimeter of rhombus="<<perimeter;
break;
}
break;
case 5:
cout<<"enter initial and final reeding";
cin>>ir>>fr;
uc=fr-ir;
r=200;
if(uc<=100)
b=r;
else
if((uc>100)&&(uc<=500))
b=r+(uc-100)*4;
else
if(uc>500)
b=r+1600+(uc-500)*7;
cout<<"Your bill is equal to="<<b;
break;
case 6:
cout<<"enter normal and isd calls";
cin>>lc>>ic;
u=200;
if((lc<=100)&&(ic<=10))
b=u;
else
if ((lc>100)&&(ic>10))
b=u+(lc-100)*2+(ic-10)*10;
cout<<"your bill="<<b;
break;
case 7:
cout<<"enter inputs";
cin>>a>>b;
cout<<"enter of your choice";
cin>>s;
if(s=='+')
c=a+b;
else
if(s=='-')
c=a-b;
else
if(s=='*')
c=a*b;
else
if(s=='/')
c=a/b;
else
if(s=='%')
cout<<"your answer is equal ="<<c;
break;
case 8:
cout<<"enter marks";
cin>>p>>c>>m>>eng>>comp;
total=p+c+m+eng+comp;
per=total/5;
if(per>=95)
grade=A1;
else
if((per<95)&&(per>=90))
grade=A2;
else
if((per<90)&&(per>=85))
grade=B1;
else
if((per<85)&&(per>=80))
grade=B2;
else
if((per<80)&&(per>=75))
grade=C1;
else
if((per<75)&&(per>=70))
grade=C2;
else
if(per<70)
grade=lowest;
cout<<"total marks obtained ="<<total;
cout<<"percentage="<<per;
cout<<"grade="<<grade;
break;
case 9:
cout<<"enter basic salary";
cin>>bs;
if((bs>10000)&&(bs<=25000))
{ hia=bs*0.1;
da=bs*0.1;
ta=bs*0.1;
tax=bs*0.2 ;
}
else
if((bs>25000)&&(bs<=30000))
{ hia=bs*0.2;
da=bs*0.2;
ta=bs*0.2 ;
tax=bs*0.4;
}
else
if(bs>30000)
{ hia=bs*0.3;
da=bs*0.3;
ta=bs*0.3;
tax=bs*0.6;
}
cout<<"your salary is=";
cout<<"tax="<<tax;
cout<<"hia="<<hia;
cout<<"da="<<da;
cout<<"ta="<<ta;
break;
case 10:
cout<<"enter n=";
cin>>n;
int n1=n/10;
int r1=n%10;
int n2=n1/10;
int r2=n1%10;
int n3=n2/10;
int r3=n2%10;
int rev= r1*1000+r2*100+r3*10+n3;
cout<<"your reversed number is="<<rev;
break;
case 11:
cout<<"enter inputs";
cin>>a>>b>>c>>m>>r;
if((a>b)&&(a>c)&&(a>m)&&(a>r))
max=a;
else
if((b>a)&&(b>c)&&(b>m)&&(b>r))
max=b;
else
if((c>a)&&(c>b)&&(c>m)&&(c>r))
max=c;
else
if((m>a)&&(m>b)&&(m>c)&&(m>r))
max=m;
else
max=r;
cout<<"greatest element is="<<max;
break;
}}
