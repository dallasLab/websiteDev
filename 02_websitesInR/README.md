## Structure



Make a test directory and issue this R command after installing R and the blogdown package. 

```{r}
blogdown::new_site()
```


Explore the site structure. 




Serve the site to see the compiled html base 

```{r}
blogdown::serve_site()
```

Go through the `config.yaml` structure and the important bits. When you get to themes, show how easy it _can_ be to switch themes, but highlight how each theme will take different data from the yaml, so changes must be made. 

Show the structure of the posts folder and how the site is dynamically compiled to allow us to diagnose how things look and when they break. 


```{r}

blogdown::stop_server()

```


When working locally, keep the server running, so you can look for any breaking changes. If you run into a situation where the site is broken and you do not understand why, run 

```{r}
blogdown::check_site()
```



> More info on this can be found at https://bookdown.org/yihui/blogdown/static-sites.html (specifically chapters 1-2). 







## Resources

https://bookdown.org/yihui/blogdown/get-started.html
https://shilaan.rbind.io/post/building-your-website-using-r-blogdown/
https://www.storybench.org/how-to-build-a-website-with-blogdown-in-r/



