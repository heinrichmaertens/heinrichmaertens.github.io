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

### Suboptimal phrasing

It's essential to ask for help clearly and concisely, or you may face several potential downsides. If you ask a question that is too broad or general, it can be a frustrating experience for both you and the person answering your question. They may have to spend an excessive amount of time trying to understand what you're asking, and as a result, provide you with an answer that is not relevant to your needs. Additionally, if your question is not clear or concise, the person answering your question may have to ask you for clarification, leading to misunderstandings and wasting time. Lastly, if you ask a question that has already been answered, you're not only wasting the time of the person answering your question, but you're also making it more difficult for others to find the answer to their question in the future. Search engines often rank previously answered questions lower than unanswered ones, so it's important to ask questions that have not been addressed before.


#### [One example such negative example can be found under the title: "Sort a list in python"](https://stackoverflow.com/questions/19199984/sort-a-list-in-python)

The forum participant in this question is asking: 
> I have this list
> ```python
> [1,-5,10,6,3,-4,-9]
> ```
> But now I want the list to be sorted like this:
> ```python
> [10,-9,6,-5,-4,3,1]
> ```
> As you can see I want to order from high to low no matter what sign each number has, but keeping the sign, is it clear?


Firstly, we can see that respondents in this forum are all very friendly; multiple users provided a working solution to the exact query. Here is the most upvoted response:
> Use `abs` as key to the `sorted` function or `list.sort`:
> ```python
> >>> lis = [1,-5,10,6,3,-4,-9]
> >>> sorted(lis, key=abs, reverse=True)
> [10, -9, 6, -5, -4, 3, 1]
> ```

A second respondent even posted a link to the Python documentation's corresponding page:
> See [here](https://docs.python.org/3/howto/sorting.html) for more details.

Overall, while this post got some great responses, it could have been solved more effectively if the user had navigated directly to the Python documentation. 


### How to do it right

#### [A recent well written question can be found under the title: "Error: LinkageError occurred while loading main class com.android.sdklib.tool.sdkmanager.SdkManagerCli"](https://stackoverflow.com/questions/76882205/error-linkageerror-occurred-while-loading-main-class-com-android-sdklib-tool-sd)

The user complained about an error he was recieving in VSCode:
> I am trying to set up flutter with VS Code in Ubuntu. I have followed the installation guide and have installed the latest cmdline tools as required by the flutter doctor.
> Now this is the output I get on running flutter doctor again
> ```perl
>     ✗ Android license status unknown.
>       Run `flutter doctor --android-licenses` to accept the SDK licenses.
>       See https://flutter.dev/docs/get-started/install/linux#android-setup for more details. 
> ```
> ...
> I tried upgrading to Java 17 using sudo apt install openjdk-17-jdk and set up the environment variables but the problem still persists.


In this second post, we can see that the forum user provided all the relevant console extracts and some troubleshooting steps they had attempted.  They listed their environment, and some settings they thought were relevant. Along with the title, the post's formatting proved quite effective as it received five thousand views within the month that it has been up, meaning that lots of people were likely able to benefit from the community's feedback. 

The feedback from other users was also highly detailed, with screenshots and exact steps walking through the steps to solve the issue. 

> I was able to resolve this issue on Windows 10 with these steps
> 
>  <img src="https://i.stack.imgur.com/mppWQ.jpg" alt="postScreenshot" width="500"/>
> 
>  1. Using the Android Studio SDK manager, install Android SDK Command-line Tools 8.0. You may need to toggle the checkboxes highlighted in green to see the older versions like 8.0.
> 2. Using windows explorer, navigate to the `Sdk/cmdline-tools` folder. On my system it's located at `C:\Users\<USER_NAME>\AppData\Local\Android\Sdk\cmdline-tools`.
> 3. Rename the `8.0` folder to `latest`
> 4. Run `flutter doctor --android-licenses`.



