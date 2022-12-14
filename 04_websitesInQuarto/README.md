## Structure 

+ Quarto is a standalone approach to much of what blogdown and associated R packages are trying to do, which is give folks a way to build static sites that all use hugo or jekyll, but have a mask of R. Quarto files (`.qmd`) read the same as R markdown (`.Rmd`), which is simply markdown (which this document is written in), but which allows code chunks to be run and compiled into the document, which is then output as pdf/html/etc. A powerful tool, and happy to talk more about using R markdown for reproducible research (YouTube video from 2020 course here https://www.youtube.com/watch?v=lwe0y3ICDBs&list=PLGKQe3NU_VU05pjDL8QuklWRQ7N2t5e-0&index=3). 

+ Quarto offers a way to include code chunks in multiple languages apart from R (though this was also baked into Rmd), and probably other things? I am not fully convinced that Quarto is solving an inherent problem, but it does simplify things by reducing the number of different R packages needed to make websites, html slides, etc. etc. by placing everything in the same package (which is standalone and has an R package interface). 

+ Install Quarto 

+ Go through the steps of setting up a Quarto site the same as using blogdown. Note the similarities in structures and themes. 

+ 

```{ }
quarto create-project test --type website:blog
```

```{ }
quarto preview test
```

Go over structure of files. 







**Templating**

https://quarto.org/docs/websites/website-about.html









**A final word about Quarto** 
The documentation is pretty solid, so if you're interested in writing a book (e.g. https://r4ds.hadley.nz/), they got you covered (https://quarto.org/docs/books/), making presentations if you don't feel like being awesome and using beamer/LaTeX (https://quarto.org/docs/presentations/), analytical pipelines (https://quarto.org/docs/computations/r.html), or academic manuscripts (https://quarto.org/docs/output-formats/pdf-basics.html). Though it is important to note that it's not quarto doing the heavy lifting here, in the same way it's not R markdown doing heavy lifting. It all gets mashed through pandoc, a lovely open source document converter. Respect pandoc. 




## Resources
https://github.com/andreashandel/andreashandelwebsite
https://www.andreashandel.com/posts/2022-10-01-hugo-to-quarto-migration/
https://blog.djnavarro.net/posts/2022-04-20_porting-to-quarto/

https://quarto.org/docs/websites/website-blog.html
https://quarto.org/docs/websites/website-about.html