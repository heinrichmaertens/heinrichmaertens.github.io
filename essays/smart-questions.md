---
layout: essay
type: essay
title: "Online Forum Etiquette: Asking Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2023-09-08
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart-questions/rtfm.png">

## Tips from the community


This post covers some of the concepts discussed in Eric Steven Raymond's (also known as ESR) "[How To Ask Questions The Smart Way](http://www.catb.org/esr/faqs/smart-questions.html)."  Some of the precepts listed in this essay include:


- Do your homework before asking a question. This means searching for answers on your own, reading documentation, and trying to understand the problem on your own.
- Be specific and concise in your question. The more specific you can be, the easier it will be for people to help you.
- Avoid asking questions that are too broad or general.
- Be polite and respectful when asking questions. Remember that the people who are helping you are volunteers.
- Follow up with a brief note on the solution once you have solved your problem. This will help others who may have the same problem in the future.

While ESR's description may be very blunt in how he phrases advice to people using open-source forums - our professor felt more comfortable categorizing less optimal questions as “not so smart” -  he also seems genuinely interested in improving current help forums by making them more accessible through improving reader's question-asking skills. 


## Example Questions from StackOverflow

# Suboptimal phrasing
[https://stackoverflow.com/questions/19199984/sort-a-list-in-python](https://stackoverflow.com/questions/19199984/sort-a-list-in-python)

The forum participant in this question is asking: 
> I have this list


```python
[1,-5,10,6,3,-4,-9]
```

> But now I want the list to be sorted like this:


```python
[10,-9,6,-5,-4,3,1]
```

> As you can see I want to order from high to low no matter what sign each number has, but keeping the sign, is it clear?


Firstly, we can see that respondents in this forum are all very friendly; multiple users provided a working solution to the exact query. Here is the most upvoted response:
> Use `abs` as key to the `sorted` function or `list.sort`:


```python
>>> lis = [1,-5,10,6,3,-4,-9]
>>> sorted(lis, key=abs, reverse=True)
[10, -9, 6, -5, -4, 3, 1]
```


A second respondent even posted a link to the Python documentation's corresponding page:
> See [here](https://docs.python.org/3/howto/sorting.html) for more details.

# How to do it right

