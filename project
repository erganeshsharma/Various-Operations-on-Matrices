//various operations on matrix
#include<stdio.h>
#include<conio.h>
#include<graphics.h>
void row(int a[][10],int,int);
int square(int a[][10],int,int);
void diagonal(int a[][10],int,int);
void scalar(int a[][10],int,int);
void unit(int a[][10],int,int);
void uppertriangular(int a[][10],int,int);
void lowertriangular(int a[][10],int,int);
madd()  //matrix addition function
{
 int a[10][10],b[10][10],x[10][10];
 int i,j,r,c,m,n;
 textbackground(7);
 textcolor(4);
 clrscr();
 printf("Enter the number of rows and columns of matix   a=\n\n");
 scanf("%d%d",&r,&c);
 printf("\nEnter the number of rows and columns of matrix   b=\n\n");
 scanf("%d%d",&m,&n);
 if((r==m) && (c==n))
 {
 printf("\nAddition of this two matrices is possible\n\n");
 printf("Enter below %d elements for matrix  a\n",r*c);
 for(i=0;i<r;i++)
 {
  for(j=0;j<c;j++)
  {
   printf("\n\tEnter value for  a (%d:%d)=",i+1,j+1);
   scanf("%d",&a[i][j]);
   }
  }
 printf("\nEnter below %d elements for matrix  b\n",m*n);
 for(i=0;i<r;i++)
 {
  for(j=0;j<c;j++)
  {
   printf("\n\tEnter value for b (%d:%d)=",i+1,j+1);
   scanf("%d",&b[i][j]);
   }
  }
  printf("\nEntered matrix  a=\n\n");
  for(i=0;i<r;i++)
  {
   for(j=0;j<c;j++)
   {
    printf("\t%d\t",a[i][j]);
    }
    printf("\n");
    }
    row(a,r,c);
   printf("\nEntered matrix  b=\n\n");
   for(i=0;i<m;i++)
   {
    for(j=0;j<n;j++)
    {
     printf("\t%d\t",b[i][j]);
     }
    printf("\n");
   }
   row(b,m,n);
   printf("\nThe result of addition of matrices =\n\n");
   for(i=0;i<r;i++)
    for(j=0;j<c;j++)
     x[i][j]=a[i][j]+b[i][j];
   for(i=0;i<r;i++)
   {
    for(j=0;j<c;j++)
    {
     printf("\t%d\t",x[i][j]);
    }
   printf("\n");
  }
  row(x,r,c);
 }
 else
 printf("\n\nAddition of this two matrices is not possible\n\n");
 return(0);
}
   msub()  //matrix subtraction function
   {
    int a[10][10],b[10][10],x[10][10];
 int i,j,r,c,m,n;
 textbackground(0);
 textcolor(2);
 clrscr();
 printf("Enter the number of rows and columns of matix   a=\n\n");
 scanf("%d%d",&r,&c);
 printf("\nEnter the number of rows and columns of matrix   b=\n\n");
 scanf("%d%d",&m,&n);
 if((r==m) && (c==n))
 {
 printf("\nSubtraction of this two matrices is possible\n");
 printf("\nEnter below %d  elements for matrix   a\n",r*c);
 for(i=0;i<r;i++)
 {
  for(j=0;j<c;j++)
  {
   printf("\n\tEnter value for a (%d:%d)=",i+1,j+1);
   scanf("%d",&a[i][j]);
   }
  }
 printf("\nEnter below %d elements for matrix   b\n",m*n);
 for(i=0;i<r;i++)
 {
  for(j=0;j<c;j++)
  {
   printf("\n\tEnter value for b (%d:%d)=",i+1,j+1);
   scanf("%d",&b[i][j]);
   }
  }
  printf("\nEntered matrix  a=\n\n");
  for(i=0;i<r;i++)
  {
   for(j=0;j<c;j++)
   {
    printf("\t%d\t",a[i][j]);
    }
    printf("\n");
   }
   row(a,r,c);
   printf("\nEntered matrix  b=\n\n");
   for(i=0;i<m;i++)
   {
    for(j=0;j<n;j++)
    {
     printf("\t%d\t",b[i][j]);
     }
    printf("\n");
   }
   row(b,m,n);
   printf("\n\nThe result of subtraction of matrices =\n\n");
   for(i=0;i<r;i++)
    for(j=0;j<c;j++)
     x[i][j]=a[i][j]-b[i][j];
   for(i=0;i<r;i++)
   {
    for(j=0;j<c;j++)
    {
     printf("\t%d\t",x[i][j]);
     }
    printf("\n");
   }
   row(x,r,c);
  }
  else
  printf("\n\nSubtraction of this two marices is not possible\n");
 return(0);
}
 mmul() //matrix multiplication function
 {
 int a[10][10],b[10][10],x[10][10];
 int i,j,k,r,c,m,n;
 textbackground(6);
 textcolor(1);
 clrscr();
 printf("Enter the number of rows and columns of matix   a=\n\n");
 scanf("%d%d",&r,&c);
 printf("\nEnter the number of rows and columns of matrix   b=\n\n");
 scanf("%d%d",&m,&n);
 if(c==m)
 {
  printf("\nMultiplication of this two matrices is possible\n");
  printf("\nEnter below %d elements for matrix  a\n\n",r*c);
  for(i=0;i<r;i++)
  {
   for(j=0;j<c;j++)
   {
    printf("\n\tEnter value for a (%d:%d)=",i+1,j+1);
    scanf("%d",&a[i][j]);
    }
   }
   printf("\nEnter below %d elements for matrix  b\n\n",m*n);
   for(i=0;i<m;i++)
   {
    for(j=0;j<n;j++)
    {
     printf("\n\tEnter value for b (%d:%d)=",i+1,j+1);
     scanf("%d",&b[i][j]);
     }
    }
    printf("\nEntered matrix  a=\n\n");
    for(i=0;i<r;i++)
    {
     for(j=0;j<c;j++)
     {
      printf("\t%d\t",a[i][j]);
      }
     printf("\n");
    }
    row(a,r,c);
    printf("\nEntered matrix  b=\n\n");
    for(i=0;i<m;i++)
    {
     for(j=0;j<n;j++)
     {
      printf("\t%d\t",b[i][j]);
      }
     printf("\n");
     }
     row(b,m,n);
     printf("\nResult of multiplication is as follows\n\n");
     for(i=0;i<r;i++)
      for(j=0;j<n;j++)
      {
       x[i][j]=0;
       for(k=0;k<c;k++)
	{
	 x[i][j]+=a[i][k]*b[k][j];
	 }
	}
       for(i=0;i<r;i++)
       {
	for(j=0;j<n;j++)
	{
	 printf("\t%d\t",x[i][j]);
	 }
	printf("\n");
       }
       row(x,r,n);
      }
      else
      printf("\n\nMultiplication of this two matrices is not possible\n");
    return(0);
  }
  mtrans() // matrix transpose function
  {
  int check=0;
  int a[10][10],x[10][10],i,j,m,n;
  textbackground(3);
  textcolor(4);
  clrscr();
  printf("Enter the order of the matrix m&n=\n");
  scanf("%d%d",&m,&n);
  printf("\nEnter %d elements for matrix a\n\n",m*n);
  for(i=0;i<m;i++)
  {
   for(j=0;j<n;j++)
   {
    printf("\n\tEnter value for a (%d:%d)=",i,j);
    scanf("%d",&a[i][j]);
     }
     printf("\n");
    }
    printf("\nEntered matrix a is as follows:\n\n");
    for(i=0;i<m;i++)
    {
     for(j=0;j<n;j++)
     {
      printf("\t%7d\t",a[i][j]);
      }
     printf("\n");
     }
     row(a,m,n);
     for(i=0;i<n;i++)
    {
     for(j=0;j<m;j++)
       x[i][j]=a[j][i];
     }
 printf("\n\nTranspose of above matrix:\n\n");
 for(i=0;i<n;i++)
 {
  for(j=0;j<m;j++)
  {
   printf("\t%d\t",x[i][j]);
   }
   printf("\n");
  }
  row(x,n,m);
 for(i=0;i<m;i++)
 {
  for(j=0;j<n;j++)
  {
   if(x[i][j]!=a[i][j])
   check=1;
   }
 }
 if(check==1)
  printf("\n\n\t\tMatrix is not symmetry\n\n");
  else
  printf("\n\n\t\tMatrix is  symmetry\n\n");
  return 0;
 }
 main()  // main program function
     {
     char c;
     int ch;
     int col=0;
     textbackground(col);
     textcolor(2);
     do
     {
      clrscr();
      printf("\n\n\n\n\n\n\n\n\n\n");
      printf("\t\t*============ PROJECT  DEVELOPED BY ============*\n\t\t*\t\t\t\t\t\t*\n");
      printf("\t\t*\t\t\t\t\t\t*\n");
      printf("\t\t*\t\tGANESH SHARMA\t\t\t*\n\t\t*\t\t\t\t\t\t*\n");
      printf("\t\t*\t\t\t\t\t\t*\n\t\t*\t\t\t\t\t\t*\n");
      printf("\t\t*\t\tPRANAB BARO\t\t\t*\n\t\t*\t\t\t\t\t\t*\n");
      printf("\t\t*\t\t\t\t\t\t*\n\t\t*\t\t\t\t\t\t*\n");
      printf( "\t\t*\t\tNABAJIT PATHAK\t\t\t*\n\t\t*\t\t\t\t\t\t*\n");
      printf("\t\t*\t\t\t\t\t\t*\n\t\t*\t\t\t\t\t\t*\n");
      printf("\t\t*===============================================*");
      printf("\n\n");
      printf("\n\t\t\tPRESS ANY KEY:");
      getch();
      textbackground(6);
      textcolor(4);
      clrscr();
    printf("\n\n\n\n\n");
    printf("\t*============ VARIOUS  OPERATIONS ON MATRIX ============*\n\t*\t\t\t\t\t\t\t*\n\t*\t\t\t\t\t\t\t*\n\t*\t\t\t\t\t\t\t*\n");
    printf("\t*\t\t1:Matrix Addition\t\t\t*\n");
    printf("\t*\t\t\t\t\t\t\t*\n\t*\t\t\t\t\t\t\t*\n");
    printf("\t*\t\t2:Matrix Subtraction\t\t\t*\n");
    printf("\t*\t\t\t\t\t\t\t*\n\t*\t\t\t\t\t\t\t*\n");
    printf("\t*\t\t3:Matrix Multiplication\t\t\t*\n");
    printf("\t*\t\t\t\t\t\t\t*\n\t*\t\t\t\t\t\t\t*\n");
    printf("\t*\t\t4:Matrix Transpose\t\t\t*\n");
    printf("\t*\t\t\t\t\t\t\t*\n\t*\t\t\t\t\t\t\t*\n");
    printf("\t*\t\t5:EXIT\t\t\t\t\t*\n");
    printf("\t*\t\t\t\t\t\t\t*\n\t*\t\t\t\t\t\t\t*\n");
    printf("\t*=======================================================*\n");
    printf("\n\t\t\tEnter your choice=");
    scanf("%d",&ch);
    switch(ch)
    {
     case 1:
	   madd();
	   break;
     case 2:
	   msub();
	   break;
     case 3:
	   mmul();
	   break;
     case 4:
	   mtrans();
	   break;
     case 5:
	   exit();
	   break;
     default :
	   printf("\n\n\t\tInvalid option\n\n");
     }
     printf("\n\t\tDO YOU WANT TO CONTINUE?(Y/N)");
     c=getch();
     }
     while(c=='y' || c=='Y');
  return(0);
 }
 void row(int a[][10],int r,int c)
 {
  int i,j,flag=1;

   if(r==1 && c!=1) //checking for row null matrix
    {

     printf("It is a row matrix\n");
     i=0;
      for(j=0;j<c;)
      {
       if(a[i][j]!=0)
       {
	flag=0;
	break;
	}
	j++;
	}
      if(flag==1)
       printf("It is also null matrix\n");
     }
   else
   if(c==1 && r!=1) //checking for column null matrix
   {
    printf("It is a column matrix\n");
    j=0;
   for(i=0;i<r;)
    {
     if(a[i][j]!=0)
     {
      flag=0;
      break;
      }
      i++;
     }
     if(flag==1)
     printf("It is also a null matrix\n");
     }
  else
  if(r==c)  //check for square matrix
  {
  printf("It is a %d * %d order square matrix\n",r,c);
  flag = square(a,r,c);
  if(flag==1)
    printf("It is also a null matrix\n");
  else
  {
   uppertriangular(a,r,c);
   lowertriangular(a,r,c);
   diagonal(a,r,c);
   }
  }
 else //checking for matrix which is not square
 {
   for(i=0;i<r;)
   {
    for(j=0;j<c;)
    {
     if(a[i][j]!=0)
      {
      flag=0;
      }
     j++;
    }
   i++;
  }
   if(flag==1)
     printf("It is a null matrix\n");
     else
    printf("It is a simple %d * %d order matrix\n",r,c);
   }
 }
 int square(int a[][10],int r,int c)  //checking for square null matrix
 {
  int i,j,flag=1;
  for(i=0;i<r;)
   {
    for(j=0;j<c;)
    {
     if(a[i][j]!=0)
     {
      flag=0;
      }
      j++;
     }
    i++;
   }
   return(flag);
 }
void diagonal(int a[][10],int r,int c) //checking for diagonal matrix
 {
  int i,j,flag=1;
   for(i=0;i<r;)
   {
    for(j=0;j<c;)
    {
     if(a[i][j]==0 && i!=j)
	flag=0;
     else
      if(a[i][j]!=0 && i==j)
	flag=0;
      else
      {
       return;
	}
	j++;
       }
      i++;
     }

     if(flag==0)
      {
       printf("It is also a diagonal matrix\n");
       scalar(a,r,c);
       }
      }
 void scalar(int a[][10],int r,int c)  //checking for scalar matrix
 {
  int i,j,k,flag=1;

  for(i=0;i<r;)
   {
    for(j=0;j<c;)
    {
     if(i==0 && j==0)
       k=a[0][0];
      else
      {
      if(a[i][j]==0 && i!=j)
	flag=0;
      else
      if(a[i][j]!=0 && i==j && a[i][j]==k)
	flag=0;
      else
      {
       return;
       }
      }
      j++;
     }
    i++;
   }
   if(flag==0)
   {

    printf("It is also a scalar matrix\n");
    unit(a,r,c);
    }
 }
 void unit(int a[][10],int r,int c)  //checking for unit matrix
 {
  int i,j,g,flag=1;
   for(i=0;i<r;)
   {
    for(j=0;j<c;)
    {
     if(i==0 && j==0)
      g=a[0][0];
      else
      {
       if(g==1 && a[i][j]!=0 && i==j && a[i][j]==g)
	flag=0;
       else
       if(a[i][j]==0 && i!=j)
	flag=0;
     else
     {
      return;
       }
      }
      j++;
     }
    i++;
   }
   if(flag==0)
     printf("It is also a unit matrix\n");
  }
 void uppertriangular(int a[][10],int r,int c)  //checking for upper triangular matrix
  {
  int i,j,flag=1;
   for(i=0;i<r;)
   {
    for(j=0;j<c;)
    {
     if(a[i][j]==0 && i>j)
      flag=0;
     else
     if(a[i][j]!=0 && i<=j)
      flag=0;
     else
     {
      return;
      }
      j++;
     }
    i++;
   }
    if(flag==0)
     printf("It is also a upper triangular matrix\n");
    }
 void lowertriangular(int a[][10],int r,int c)  //checking for lower triangular matrix
 {
  int i,j,flag=1;
   for(i=0;i<r;)
   {
    for(j=0;j<c;)
    {
     if(a[i][j]==0 && i<j)
      flag=0;
     else
     if(a[i][j]!=0 && i>=j)
      flag=0;
     else
     {
      return;
      }
      j++;
     }
    i++;
   }
   if(flag==0)
    printf("It is also a lower triangular matrix\n");
  }