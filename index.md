This is the content I want to display on the main page of my site.
---
title: "My Fancy Presentation"
author: "Lester B."
date: "2/25/2021"
output: ioslides_presentation
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE)
```

## My New Slide

Some Content


***
Slide without a title


## Mt Title
### A top level subheading
- Bullet one
- Bullet two

1. Item a
2. Item b

#### A second level subheading

Plain text

*italicized text*

**Bold Text**

***

Use accent marks for code  
`This is code`  

Run some code  
```{r}
head(mtcars)
```

***
Without comment marks  
```{r, comment="", echo=TRUE, }
head(mtcars)
```

***
A chart  
```{r, echo=FALSE}
plot(mtcars$wt, mtcars$mpg, xlab="Weight", ylab="MPG")
```

***
Make a gh branch

https://seankross.com/slides/Developing_Data_Products/R_Markdown/R_Markdown.html#1



## R Markdown

This is an R Markdown presentation. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document.

## Slide with Bullets

- Bullet 1
- Bullet 2
- Bullet 3

## Slide with R Output

```{r cars, echo = TRUE}
summary(cars)
```

## Slide with Plot

```{r pressure}
plot(pressure)
```

