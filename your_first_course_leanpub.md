# Simple guide to publish your first course on Leanpub

Leanpub started as a online publishing platform with the philosophy of making it easier to publish, to publish early and publish often. It's said that one of the advantages of Leanpub is that authors don't have to sweat the mistakes. They can continuely edit and improve their book by publishing newer editions of the book.

They have recently added Leancourses which is a MOOC version of their book publishing arm with having some courses specifically designed for as online course such as quizzes, exercises, and certificates.

What is good about Leanpub and Leancourses is that creating a book or couses is as easy as creating an account, starting a book or course by linking it to a Dropbox folder (or equivalenty a Github repository) that has the content and executing it as a book or course. In the following sections we'll go over some of the basics of creating a course on Leanpub courses.

## How to create a new course

Assuming you have authoring access on your Leanpub account, you can click on your account and choose Courses under Author like below.

![Courses](./img/leanpub_courses/00_courses.png)

In the following page, click on "Create another Course" which then opens a new page where you should enter course information such as the title, url, etc. You need to enter the following information:
- Choose a title
- Enter the url of the course (choose something that is good for SEO purposes: introduction_to_molecular_biology instead of my_first_course)
- Select language
- Select how you want to write the course.

For the last step, you should choose an option based on how comfortable you are with writing in plain text markup languages or Github. If you have worked with Github, it's better to link your course content with a Github repo for versioning purposes. Otherwise you can choose to link to the content on Dropbox. If you don't know much about Markdown, you can write your course in Leanpub's own Markua editor.

We suggest to spend half hour to learn Markdown (yes, it's that easy!) instead of Word documents. To add more features for MOOCs, Leanpub has added a few more typesets and features to Markdown and they call it Markua. Leanpub courses are written using [Markua](http://markua.com). You can read the relevant section of the Markua specification document [here](https://leanpub.com/markua/read#leanpub-auto-quizzes-and-exercises).


You can find more information on creating a course or MOOC [here](https://leanpub.com/markua/read#leanpub-auto-creating-a-course-or-mooc-from-a-markua-document).


## Linking to Dropbox or Github

If you're using Dropbox or GitHub, create the file in the `manuscript` folder for this course. Then open the `Book.txt` file you'll find in the `manuscript` folder, and type in the name of your new file, including its file extension (like the `.txt` in `Book.txt`) **on a line by itself**. That way, the next time you create a preview of your course, the new file will be included.


## Quiz Example

Here is a brief example of a multiple choice question in a quiz. The correct answer is the one with an upper-case letter, in this case `B)`.

{quiz, id: quiz1}
? How many letters are in the word Markua?

a) 5
B) 6
c) 7
{/quiz}

Here is an example of a question where the student types their answer. You indicate the answer by typing `!` and then a space, and then the answer.

{quiz, id: quiz2}

? How many unique letters are in the word Markua?

! 5
{/quiz}

## Exercise Example

Here is an example of a multiple choice question in an exercise.

{exercise, id: exercise1}
? How many letters are in the word Markua?

a) 5
B) 6
c) 7





While Markdown files generally end in .md, you actually save the content in a text file - .txt
It really helps if you use a good text editor for editing text and Markdown. I personally use Sublime, because I'm comfortable with it, but there are many products out there - most are free.
As you'll see in Leanpub's guide, you create the table of contents and layout of the book in simple text file called Book.txt, which is part of the Dropbox manuscript folder that houses all of the actual book content.
In the leanpub account itself, the action tab allows you to do things like generate previews, create samples, and also to publish live copies.
As noted above, the final book is never really final. You can edit, and notify users of book updates, meaning you can publish regularly after pushing out an early draft.
You get to set a range of prices for the product you sell ... I priced my book at $1.99 - $39.99.
Any other questions? Feel free to get in touch with me :)