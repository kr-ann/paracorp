# paracorp
This project is created to distinguish trully parallel sentences from non parallel in a Russian-English parallel aligned corpus of poor quality. 

<b>The folder "data"</b> contains a small corpus of good quality on which our model is trained. A big corpus the model will be applied to, should be of the same <b>data format</b>: two files containing aligned sentences as lines.
During the program's performance many additional files are created - databases and excel files to store the intermediate results. <b>The output files</b> are the follows: non_parallel_en.txt and non_parallel_ru.txt contain sentences considered non parallel by our program, and parallel_en.txt and parallel_ru.txt, on the contrary, contain parallel sentences. 
