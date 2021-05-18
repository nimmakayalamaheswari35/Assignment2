# Assignment2

This code helps to get a rectangular box with the help of (+ - | and space )like below
    
      +----------------------+
      |                      |
      |                      |
      |                      |
      |                      |
      |                      |
      |                      |
      +----------------------+
    
  This code will help in getting the layout
   
       for(int j=0;j<c;j++)
			{
				if((i==0&&j==0)||(i==0&&j==c-1)||(i==r-1&&j==0)||(i==r-1&&j==c-1))
				System.out.print("+");
				else if(i==0||i==r-1)
				System.out.print("-");
				else if(j==0||j==c-1)
				System.out.print("|");
   
   And in the above box we need to print the string in the last 2 columns and last 1 row and leaving the spaces after the name before reaching the edge(space occupied by string should be dynamic)
   
        else if(i==r-3&&j==c-(name.length()+2))
				{
					for(int k=0;k<name.length();k++)
					System.out.print(name.charAt(k));
          
					j=j+name.length()-1;
				}
				else
				System.out.print(" ");
				}
				System.out.println();
  
  This code helps to print the string
  
          +----------------------+
          |                      |
          |                      |
          |                      |
          |                      |
          |                mahi  |
          |                      |
          +----------------------+
 Output:
 
 ![2021-05-18](https://user-images.githubusercontent.com/84019315/118584849-6831f480-b7b5-11eb-9f2f-94cf13a28d4e.png)
 
