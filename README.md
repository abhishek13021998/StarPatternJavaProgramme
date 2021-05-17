# StarPatternJavaProgramme
In this we draw a java Pattern programme

        *
       * *
      *   *
     *     *
    *       *
   *         *
  *           *
 *             *
*****************

first we put int put which is an odd number given by
   int n = sc.nextInt();
          for no of rows we take i as rows number and given by
          for (int i=1; i<= n; i++)
          
          for printing a space we take n becasue intitally it start with n number of space
           for (int i=1; i<= n; i++)
            {
                for (int j = i; j < n; j++) {
                    System.out.print(" ");
                } 
for printing start we have either print k=1 or k=i or k=2*i-1 and in between them we have to put spaces for this we apply
   for (int k = 1; k <= (2*i -1) ;k++) {
                    if( k==1 || i == n || k==(2*i-1)) {
                        System.out.print("*");
                    }
                    else {
                        System.out.print(" ");
                    }
                }
                
                in this way it work![Screenshot (986)](https://user-images.githubusercontent.com/84003456/118447306-3e71c280-b70e-11eb-940e-14c8ae1e247e.png)
![Screenshot (987)](https://user-images.githubusercontent.com/84003456/118447316-42054980-b70e-11eb-8cdb-4975baffdccb.png)

