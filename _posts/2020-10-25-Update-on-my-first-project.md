## First training project

I decided to do a Linear Regression problem. Now I wasn't sure on what kind of a problem I should do... because I had never done a regression problem before. Luckily
it is possible to find project ideas, and I picked up one project from [here](https://study.com/academy/lesson/linear-regression-project-ideas.html). Tobegin with I 
was going to do "Rate of unemployment compared to average point gains in stock market". But I had some problems finding reliable source about points for Iceland (I am
fully aware that I might have searched wrong), so I ended up finding consumer price index for my country. Luckily I was able to find data on both from 1980 (even if 
consumer price index didn't occur here until 1981).

### Why doing a project like this?
I am new to using Pandas, Numpy, Matplotlib and all of the other modules used in ML. In order to increase my knowledge, I need to get my hands "dirty" and just do projects.
This will teach me very much about how to work with data, how to search problems, gives me experience on what works and what doesn't. 

On this project and upcoming projects it is OK to make mistakes. For all means make as many mistakes as possible.... as long as you take something from those mistakes, 
and that you will learn from these mistakes. So far I have made many mistakes, especially in working with my data. Is this going to be perfect? Heck NO, but the only thing 
that matters is to do the damn project.

### How is the project going?
Not great at the moment. I am completely stuck at the moment. It is the second time I get stuck. The first time I didn't know that a comma (,) would be a string even if 
the contet on the cells is numbers. I know why that is, and that is because where I live, we use comma as a decimal point. Small difference which isn't always apparent.
I have put up two questions on [StockOverflow](https://stackoverflow.com/), both of them because I had problem changing a column of objects to float. On the first problem 
I should have used `str.replace(',', '')` before using `astype(float)`. The second problem hasn't been sorted fully. The second problem is that pandas sees an empty string
in the column I am using. However, going through the data, there is no missing value or an empty string. Pandas can't at least find it, I can't find it in the excel sheet, 
and I am guessing it is not there. I have gotten a good answer on StackOverfrow, but I am not sure how to implement it. That specific answer turns my dataframe to dictionary, 
and I should be able to change the object value to float64. I am however not sure how to do that without changing **every** value in that column into float64. I have, 
however, just found [pandas pydata docs](https://pandas.pydata.org/pandas-docs/version/0.22/categorical.html) and I am sure I will be able to find the answer I am looking 
for over there. 

### What have I learned?
The data I am working on needs so much more work in order to be usable. I guess part of it is how the files I am using are processed before I download it and start working 
on it. I also shows me that I will need to be ready to do some serous digging for usable information. I have also leared that I need to communicate tomyself much better 
on my Jupyter notebook, because I tend to not write what I am doing and why. 

All of his is a project to better myself in doing ML projects. To be honest, it is fun to have project that is challenging, and I can't wait for it to be "not" challening
meaning I have learned something usefull. I know the road is long and windy, with many side roads, which I may and may not take. 

I am optimistic for the time being. I find it fun to learn new things, challenge myself, and staying active. I will post the whole process of this project here when it
is ready, with code. There I will talk about what challenges I had, and how I finally solved it. It will be very fun to see this project finish. 

Best Regards

Ólafur Víðir Guðbjargarson
