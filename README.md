# calender
calender by using c language (1900 - 2050)


// [7:37 am, 12/05/2022] DEEPALI THAKUR😊
#include<stdio.h>
#include<string.h>
#include<stdlib.h>
#define c ' '
void first(int,int);
void second(int,int);
void third(int,int);
void fourth(int,int);
void fifth(int,int);
void sixth(int,int);
void seventh(int,int);
void first(int y,int k)
{
    char array[][50]={"Mon","Tue","Wed","Thr","Fri","Sat","Sun"};
    int n;
    if(k==1||k==3||k==5||k==7||k==8||k==10||k==12)
    {
        n=31;
    }
    else if(k==4||k==6||k==9||k==11)
    {
        n=30;
    }
    else
    {
        if(y%4==0&&k==2)
        {
            n=28;
        }
        else
        {
            n=29;
        }
    }
    for(int j=0;j<7;j++)
    {
        printf("%s ",&array[j][0]);
    }
    printf("\n");
    for(int i=1;i<=n;i++)
    {
        if(i<10)
        {
            printf("%c",c);
        }
        printf("%d%2c",i,c);
        if(i%7==0)
        {
            printf("\n");
        }
    }
}
void second(int y,int k)
{
    char array[][50]={"Mon","Tue","Wed","Thr","Fri","Sat","Sun"};
    printf("\n");
    int n;
    if(k==1||k==3||k==5||k==7||k==8||k==10||k==12)
    {
        n=31;
    }
    else if(k==4||k==6||k==9||k==11)
    {
        n=30;
    }
    else
    {
        if(y%4==0&&k==2)
        {
            n=28;
        }
        else
        {
            n=29;
        }
    }
    for(int j=0;j<7;j++)
    {
        printf("%s ",&array[j][0]);
    }
    printf("\n");
    printf("%4c",c);
    for(int i=1;i<=n;i++)
    {
        int g=7*i-1;
        if(i<10)
        {
            printf("%c",c);
        }
        printf("%d%2c",i,c);
        if(i==6||i==13||i==20||i==27)
        {
            printf("\n");
        }
    }
}
void third(int y,int k)
{
    char array[][50]={"Mon","Tue","Wed","Thr","Fri","Sat","Sun"};
    printf("\n");
    int n;
    if(k==1||k==3||k==5||k==7||k==8||k==10||k==12)
    {
        n=31;
    }
    else if(k==4||k==6||k==9||k==11)
    {
        n=30;
    }
    else
    {
        if(y%4==0&&k==2)
        {
            n=28;
        }
        else
        {
            n=29;
        }
    }
    for(int j=0;j<7;j++)
    {
        printf("%s ",&array[j][0]);
    }
    printf("\n");
    printf("%8c",c);
    for(int i=1;i<=n;i++)
    {
        int g=7*i-1;
        if(i<10)
        {
            printf("%c",c);
        }
        printf("%d%2c",i,c);
        if(i==5||i==12||i==19||i==26)
        {
            printf("\n");
        }
    }
}
void fourth(int y,int k)
{
    char array[][50]={"Mon","Tue","Wed","Thr","Fri","Sat","Sun"};
    printf("\n");
    int n;
    if(k==1||k==3||k==5||k==7||k==8||k==10||k==12)
    {
        n=31;
    }
    else if(k==4||k==6||k==9||k==11)
    {
        n=30;
    }
    else
    {
        if(y%4==0&&k==2)
        {
            n=28;
        }
        else
        {
            n=29;
        }
    }
    for(int j=0;j<7;j++)
    {
        printf("%s ",&array[j][0]);
    }
    printf("\n");
    printf("%12c",c);
    for(int i=1;i<=n;i++)
    {
        int g=7*i-1;
        if(i<10)
        {
            printf("%c",c);
        }
        printf("%d%2c",i,c);
        if(i==4||i==11||i==18||i==25)
        {
            printf("\n");
        }
    }
}
void fifth(int y,int k)
{
    char array[][50]={"Mon","Tue","Wed","Thr","Fri","Sat","Sun"};
    printf("\n");
    int n;
    if(k==1||k==3||k==5||k==7||k==8||k==10||k==12)
    {
        n=31;
    }
    else if(k==4||k==6||k==9||k==11)
    {
        n=30;
    }
    else
    {
        if(y%4==0&&k==2)
        {
            n=28;
        }
        else
        {
            n=29;
        }
    }
    for(int j=0;j<7;j++)
    {
        printf("%s ",&array[j][0]);
    }
    printf("\n");
    printf("%16c",c);
    for(int i=1;i<=n;i++)
    {
        int g=7*i-1;
        if(i<10)
        {
            printf("%c",c);
        }
        printf("%d%2c",i,c);
        if(i==3||i==10||i==17||i==24)
        {
            printf("\n");
        }
    }
}
void sixth(int y,int k)
{
    char array[][50]={"Mon","Tue","Wed","Thr","Fri","Sat","Sun"};
    printf("\n");
    int n;
    if(k==1||k==3||k==5||k==7||k==8||k==10||k==12)
    {
        n=31;
    }
    else if(k==4||k==6||k==9||k==11)
    {
        n=30;
    }
    else
    {
        if(y%4==0&&k==2)
        {
            n=28;
        }
        else
        {
            n=29;
        }
    }
    for(int j=0;j<7;j++)
    {
        printf("%s ",&array[j][0]);
    }
    printf("\n");
    printf("%20c",c);
    for(int i=1;i<=n;i++)
    {
        int g=7*i-1;
        if(i<10)
        {
            printf("%c",c);
        }
        printf("%d%2c",i,c);
        if(i==2||i==9||i==16||i==23)
        {
            printf("\n");
        }
    }
}
void seventh(int y,int k)
{
    char array[][50]={"Mon","Tue","Wed","Thr","Fri","Sat","Sun"};
    printf("\n");
    int n;
    if(k==1||k==3||k==5||k==7||k==8||k==10||k==12)
    {
        n=31;
    }
    else if(k==4||k==6||k==9||k==11)
    {
        n=30;
    }
    else
    {
        if(y%4==0&&k==2)
        {
            n=28;
        }
        else
        {
            n=29;
        }
    }
    for(int j=0;j<7;j++)
    {
        printf("%s ",&array[j][0]);
    }
    printf("\n");
    printf("%26c",c);
    for(int i=1;i<=n;i++)
    {
        int g=7*i-1;
        if(i<10)
        {
            printf("%c",c);
        }
        printf("%d%2c",i,c);
        if(i==1||i==8||i==15||i==22||i==29)
        {
            printf("\n");
        }
    }
}
int main()
{
    printf("******WELCOME TO MY PERPECTUAL CALENDER******\n");
    int year,mon;
    printf("enter year:");
    scanf("%d",&year);
    if(year<1900 ||year>2050)
    {
        printf("please enter the any year between 1900 and 2050....try again");
        exit(1);
    }
    else if(year%4==0)
    {
        int i=0;
        int lyear1[]={1928,1956,1984,2012,2040}, lyear2[]={1904,1932,1960,1988,2016,2044}, lyear3[]={1908,1936,1964,1992,2020,2048};
        int lyear4[]={1912,1940,1968,1996,2024}, lyear5[]={1916,1944,1972,2000,2028}, lyear6[]={1920,1948,1976,2004,2032};
        int lyear7[]={1924,1952,1980,2008,2036};
        while(1)
        {
            if(year==lyear1[i])
            {
                printf("\nenter month:");
                scanf("%d",&mon);
                if(mon==1||mon==4||mon==7)
                {
                    seventh(year,mon);
                }
                else if(mon==3||mon==8)
                {
                    third(year,mon);
                }
                else if(mon==4||mon==11)
                {
                    fourth(year,mon);
                }
                else if(mon==10)
                {
                    first(year,mon);
                }
                else if(mon==5)
                {
                    second(year,mon);
                }
                else if(mon==6)
                {
                    fifth(year,mon);
                }
                else
                {
                    sixth(year,mon);
                }
            }
            else if(year==lyear2[i])
            {
                printf("\nenter month:");
                scanf("%d",&mon);
                if(mon==5)
                {
                    seventh(year,mon);
                }
                else if(mon==6)
                {
                    third(year,mon);
                }
                else if(mon==9||mon==12)
                {
                    fourth(year,mon);
                }
                else if(mon==2||mon==8)
                {
                    first(year,mon);
                }
                else if(mon==3||mon==11)
                {
                    second(year,mon);
                }
                else if(mon==1||mon==4||mon==7)
                {
                    fifth(year,mon);
                }
                else
                {
                    sixth(year,mon);
                }
            }
            else if(year==lyear3[i])
            {
                printf("\nenter month:");
                scanf("%d",&mon);
                if(mon==3||mon==11)
                {
                    seventh(year,mon);
                }
                else if(mon==1||mon==7)
                {
                    third(year,mon);
                }
                else if(mon==10)
                {
                    fourth(year,mon);
                }
                else if(mon==6)
                {
                    first(year,mon);
                }
                else if(mon==9||mon==12)
                {
                    second(year,mon);
                }
                else if(mon==5)
                {
                    fifth(year,mon);
                }
                else
                {
                    sixth(year,mon);
                }
            }
            else if(year==lyear4[i])
            {
                printf("\nenter month:");
                scanf("%d",&mon);
                if(mon==9||mon==12)
                {
                    seventh(year,mon);
                }
                else if(mon==5)
                {
                    third(year,mon);
                }
                else if(mon==2||mon==8)
                {
                    fourth(year,mon);
                }
                else if(mon==1||mon==4)
                {
                    first(year,mon);
                }
                else if(mon==10)
                {
                    second(year,mon);
                }
                else if(mon==3||mon==11)
                {
                    fifth(year,mon);
                }
                else
                {
                    sixth(year,mon);
                }
            }
            else if(year==lyear5[i])
            {
                printf("\nenter month:");
                scanf("%d",&mon);
                if(mon==10)
                {
                    seventh(year,mon);
                }
                else if(mon==3||mon==11)
                {
                    third(year,mon);
                }
                else if(mon==6)
                {
                    fourth(year,mon);
                }
                else if(mon==5)
                {
                    first(year,mon);
                }
                else if(mon==2)
                {
                    second(year,mon);
                }
                else if(mon==12)
                {
                    fifth(year,mon);
                }
                else
                {
                    sixth(year,mon);
                }
            }
            else if(year==lyear6[i])
            {
                printf("\nenter month:");
                scanf("%d",&mon);
                if(mon==2||mon==8)
                {
                    seventh(year,mon);
                }
                else if(mon==9||mon==12)
                {
                    third(year,mon);
                }
                else if(mon==1||mon==4||mon==7)
                {
                    fourth(year,mon);
                }
                else if(mon==10)
                {
                    first(year,mon);
                }
                else if(mon==6)
                {
                    second(year,mon);
                }
                else if(mon==3||mon==11)
                {
                    fifth(year,mon);
                }
                else
                {
                    sixth(year,mon);
                }
            }
            else if(year==lyear7[i])
            {
                printf("\nenter month:");
                scanf("%d",&mon);
                if(mon==6)
                {
                    seventh(year,mon);
                }
                else if(mon==10)
                {
                    third(year,mon);
                }
                else if(mon==5)
                {
                    fourth(year,mon);
                }
                else if(mon==9||mon==12)
                {
                    first(year,mon);
                }
                else if(mon==1||mon==4||mon==7)
                {
                    second(year,mon);
                }
                else if(mon==2||mon==8)
                {
                    fifth(year,mon);
                }
                else
                {
                    sixth(year,mon);
                }
            }
            if(i==6)
            {
                break;
            }
            else
            {
                i++;
            }
        }
    }
    else
    {
        int year1[]={1903,1914,1925,1931,1942,1953,1959,1970,1981,1957,2009,2015,2043};
        int year2[]={1909,1915,1926,1937,1943,1954,1965,1971,1982,1993,1999,2010,2021,2027,2038,2049}; 
        int year3[]={1910,1921,1927,1938,1949,1955,1956,1977,1983,1994,2005,2011,2022,2033,2039,2050};
        int year4[]={1901,1907,1918,1927,1935,1946,1957,1963,1974,1985,1991,2002,2013,2019,2030,2041,2047};
        int year5[]={1902,1913,1919,1930,1941,1947,1958,1969,1975,1986,1997,2003,2014,2025,2013,2045};
        int year6[]={1905,1911,1922,1933,1939,1950,1961,1978,1989,1995,2006,2017,2023,2034,2045};
        int year7[]={1900,1906,1917,1923,1934,1945,1951,1962,1973,1979,1990,2001,2007,2018,2029,2035,2046};
        int i=0;
        printf("enter mon:");
            scanf("%d",&mon);
        while(1)
        {
            if(year==year1[i])
            {
                if(mon==6)
                {
                    first(year,mon);
                }
                else if(mon==9||mon==12)
                {
                    second(year,mon);
                }
                else if(mon==4||mon==7)
                {
                    third(year,mon);
                }
                else if(mon==1||mon==10)
                {
                    fourth(year,mon);
                }
                else if(mon==5)
                {
                    fifth(year,mon);
                }
                else if(mon==8)
                {
                    sixth(year,mon);
                }
                else
                {
                    seventh(year,mon);
                }
            }
            else if(year==year2[i])
            {
                if(mon==2||mon==3||mon==11)
                {
                    first(year,mon);
                }
                else if(mon==6)
                {
                    second(year,mon);
                }
                else if(mon==9||mon==12)
                {
                    third(year,mon);
                }
                else if(mon==4||mon==7)
                {
                    fourth(year,mon);
                }
                else if(mon==1||mon==10)
                {
                    fifth(year,mon);
                }
                else if(mon==5)
                {
                    sixth(year,mon);
                }
                else
                {
                    seventh(year,mon);
                }
            }
            else if(year==year3[i])
            {
                if(mon==8)
                {
                    first(year,mon);
                }
                else if(mon==2||mon==3||mon==11)
                {
                    second(year,mon);
                }
                else if(mon==6)
                {
                    third(year,mon);
                }
                else if(mon==12||mon==9)
                {
                    fourth(year,mon);
                }
                else if(mon==4||mon==7)
                {
                    fifth(year,mon);
                }
                else if(mon==1||mon==10)
                {
                    sixth(year,mon);
                }
                else
                {
                    seventh(year,mon);
                }
            }
            else if(year==year4[i])
            {
                if(mon==4||mon==7)
                {
                    first(year,mon);
                }
                else if(mon==1)
                {
                    second(year,mon);
                }
                else if(mon==5)
                {
                    third(year,mon);
                }
                else if(mon==8)
                {
                    fourth(year,mon);
                }
                else if(mon==2||mon==3||mon==11)
                {
                    fifth(year,mon);
                }
                else if(mon==6)
                {
                    sixth(year,mon);
                }
                else
                {
                    seventh(year,mon);
                }
            }
            else if(year==year5[i])
            {
                if(mon==9||mon==12)
                {
                    first(year,mon);
                }
                else if(mon==4)
                {
                    second(year,mon);
                }
                else if(mon==1||mon==10)
                {
                    third(year,mon);
                }
                else if(mon==5)
                {
                    fourth(year,mon);
                }
                else if(mon==8)
                {
                    fifth(year,mon);
                }
                else if(mon==2||mon==3||mon==11)
                {
                    sixth(year,mon);
                }
                else
                {
                    seventh(year,mon);
                }
            }
            else if(year==year6[i])
            {
                if(mon==5)
                {
                    first(year,mon);
                }
                else if(mon==8)
                {
                    second(year,mon);
                }
                else if(mon==2||mon==3||mon==11)
                {
                    third(year,mon);
                }
                else if(mon==6)
                {
                    fourth(year,mon);
                }
                else if(mon==9||mon==12)
                {
                    fifth(year,mon);
                }
                else if(mon==4||mon==7)
                {
                    sixth(year,mon);
                }
                else
                {
                    seventh(year,mon);
                }
            }
            else if(year==year7[i])
            {
                if(mon==1||mon==10)
                {
                    first(year,mon);
                }
                else if(mon==5)
                {
                    second(year,mon);
                }
                else if(mon==8)
                {
                    third(year,mon);
                }
                else if(mon==2||mon==3||mon==11)
                {
                    fourth(year,mon);
                }
                else if(mon==6)
                {
                    fifth(year,mon);
                }
                else if(mon==9||mon==12)
                {
                    sixth(year,mon);
                }
                else
                {
                    seventh(year,mon);
                }
            }
            if(i==16)
            {
                break;
            }
            i++;
        }
    }
    return 0;
}

