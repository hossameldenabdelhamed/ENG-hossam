 int j = 0;          
                for (int i = 0; i <1000; i++)
                {
                    if ((i % 3 == 0) ||( i % 5 == 0))
                    {
                        j+=i;
                    }
            }
                Console.WriteLine("the sumtion =" + j);
                Console.ReadKey();      
