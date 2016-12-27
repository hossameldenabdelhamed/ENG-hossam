 int x=1;
            int y=2;
            int s=0;
            int z=0;
            while (y <= 4000000)
            {
                s = x + y;
                if (y%2==0)
                {
                    z += y;
                    x = y;
                    y = s;
          
                }
            }
            Console.WriteLine(z);
            Console.ReadKey();
