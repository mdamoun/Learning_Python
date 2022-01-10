# Table of Contents

[1- Heading](#1-headings)\
[2- Block of Words/Citation](#2-block-of-wordscitation)\
[3- Line Break](#3-line-breaks)\
[4- Combining Two Things](#4-combining-two-things)\
[5- Text Formatting](#5-face-of-the-text-text-formating)\
[6- Creating Bullet Points and Number Lists](#6-creating-bullet-points-and-list)\
[7- Line Break or Page Break](#7-line-break-or-page-break)\
[8- Links and Hyperlinks in Markdown](#8-links-and-hyperlinks-in-markdown)\
[9- Images and Figures with Links](#9-images-and-figures-with-links)\
[10- How to add code within text or as a Code Block](#10-how-to-add-your-code-code-block-in-a-markdown-file)\
[11- Creating Tables](#11-creating-tables-in-your-markdown-file)\
[12- Installing usefull Markdown extentions for Visiual Studio Code](#12-installing-useful-markdown-extentions)\
[14- Creating this TOC](#13-creating-tables-of-contents-in-your-markdown-file)
___

# 1. Headings

How to create headings in markdown files?

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

^ There are 6 levels of Heading options available to be used.
___

# 2. Block of Words/Citation

How to add block of words in markdown document?

This is a notmal text in markdown document.

>This is a block of special text written in markdown document. You needt to open the .md file to see that a special character '>' is been used at the begining of the sentence to get this result.

> This is second line of special text created by using a *<b>double-return</b>* key to create a seprate block!
>
>To have the continutiy of this block with a new line of sentence,  use '>' at the begining of the empty space between these lines then followed by '>' at the begining of the next sentence.
>
> Still confused?
>
>Well, open the .md file and see how its been done. :)
___

# 3. Line Breaks

This is an intentional text line so that we can create a line break at the end of it.
Now this is a second line. I like you to notice something in the simple text editor. All the text written are in a single line unless "enter" key is been used to create a seprate line. So do observe that when you open a markdown file.

Now there is another way to create a "line break". And that is by using a "reverse slash"at the end of the sentence\.
___

# 4. Combining 'Two' Things

Lets combine <b> Blocks of words and heading</b>.

># You asked How?

>## Its actual quite simple

>Well we did that by using '>#' and '>##' signs at the begining. Its as simple as that. Do check it out.
>
___

# 5. Face of the text (Text Formating)

## Making text **Bold**

Now you asked how to make text **Bold**? Well there are actually two ways.

1. You can either add *double* asterisk at the begining and end like **this word**. Or
2. Using *double* underscore '__'__at the begning and the end of your text__. Or
3. By using html code. That is *bracketing*  your text between < b> and < /b> <b>just like this</b>. Remember not to have spaces inside the <>.

## Making text *Italic*

Now you asked how to make text *Italic*? Well there are two ways to do it.

1. You can either add *single* asterisk at the begining and end like *this word*. Or
2. Using *single* underscore '_'_at the begning and the end of your text_. Or
3. By using html code. That is *bracketting*  your text between < i> and < /i> <i>just like this</i>. Remember not to have spaces inside the <>.

## Making text both ***Bold and Italic***

1. Well you guessed it right *(If you did already)*. Used add *triple* asterisk at ***the beginning and at the end of the text you like to have***.
2. The second method is <b><i>combination of html code added at the both ends</i></b>.

Frankly using ***Asterisks*** are much easier and fun!
___

# 6. Creating bullet points and list

## Bullet Points

To create a bullet use '- ' i.e. a **hyphen and space** before your text.

- This is an example by using the instruction above.
  - You can further use ***Tab and '- '*** to create nested bullet point.
    - Here comes another one.
      - Lets see if there is one more. Yes we can do that but do notice that the shape of the bullet remains same as the third one above.
- Using ***'Shift + Tab' & 'Tab'*** on the next line makes you move in between the nested 'Bullet Points' while using the '- ' before your text.
- Well thats awsome!

- One thing more. This bullet was created using '* ' **asterisk and space**.

- And you can also create bullet using '+ ' **plus and space**.

>## Summary

> To create bullet points, you can use.\
> '- ' hypen with space\
>'* ' asterisk with space and\
>'+ ' plus sign with space

Now lets move to our next topic.

## Number List

To create a number listing use '1. ' i.e. a **hnumber, fullstop, and than space** before your text.

1. This is an example by using the instruction above.
2. We can continue making our list by adding next sequence of the number followed by fullstop and space before the text.
1. Now here is a surprise for you. You cannot see it here, but in the markddown file of this document, I have used 1. for the third line instead of 3. at the begining of the number list.
1. The fun part of using markdown is that irrepective this being the 4th line, I have still used 1. and the markdown interpretator has automatically fixed my mistake to the actual sequence of the order.
    1. Now in order to create a nested list, just use a tab and '1. ' i.e. a **hnumber, fullstop, and than space** before your text.
    2. Thats it!
    1. Its that simple.
    1. And the fun part.
    1. I am using "1. " since the 3rd nested list.
        1. May be one more example of nested number list.
        1. I guess this should be enough of it.
1. Again I have used ***'Shift + Tab' and Tab'*** to navigate through the list.
1. I guess we can conclude the *Number List* here. Hope you enjoyed it.

___

# 7. Line Break or Page Break

To create a page break one way is to press 'return' or 'enter' key twice (2) after the fullstop and then add three (3) consective hypens '---' between this line and the next one. Then another 'return' or 'enter' key to start the new line after the line break.

---
This is the second line after the page break.

Another way is to use three (3) consective underscore '___' on the next line instead of three (3) hyphens.
___
The third way is to use three (3) consective asterisk '***' on the next line instead of three (3) hyphens or three (3) underscore. Just like the one below.
***
This is pretty much it about the **Line Break** or **Page Break**.
___

# 8. Links and Hyperlinks in Markdown

## a. Hyperlink

To create a **hyperlink**, just put your link (web address) between the <>.\
Here is an example using the technique above to a create link to google.com. <https://www.google.com/>

## b. Link

To create a link with replaced text, you need to write [your text] in a square bracket immediately followed by the desired link in a round bracket (the correct http link).

Here is an example:

[To learn **FREE** Markdown and Python course in 40 days in Urdu language, click here!](https://www.youtube.com/watch?v=QvPekMN4F0w&list=PL9XvIvvVL50HVsu-Ao8NBr0UJSO8O6lBI) Courtesy of [Codanics](https://www.codanics.com/) by [Dr. Muhammad Aammar Tufail](https://www.linkedin.com/in/dr-muhammad-aammar-tufail-02471213b/).

## Creating a defined link to be recalled within the Markdown file

For that, use your [desired text] in square bracket immediately followed by colon':' followed by your hyperlink without any bracket. Below I have created an example visible to you.

[Codanic s] : <https://www.codanics.com/>

[Codanics]:https://www.codanics.com/

- In reality, once the link is been defined, it is not really visible while viewing the Markdown file.

But it can be recalled anywhere in the document as example below.

>Example

What you can see here is that I have created the following [link][Codanics] for you to visit.
___

# 9. Images and figures with links

To put an image in a markdown document is easy as a breeze. The concept is same as of putting a *link* or a *hyperlink* but more as of local one.

## a. Loading a local image

We start with an exclamation mark '!' immediately followed by a square bracket [with the desired name tag] followed by the (filename.ext) next to it. In this case I will make sure the image file is in the same folder as of the markdown file.

! [Given Tag name] ( imagename.ext )

Just make sure that all above are written without spaces inbetween them.

>Example

If you like to find out more about me, scan this QR code to visit my __Linkdin__ profile.

![QR](myLinkedinQR.png)

## b. Loading an online image

In the case of online image, everything is same as above except instead of the (filename.ext), we will use the url of that particular image in the round bracket.

! [Given Tag name] ( httpe://image/url/imagename.ext )

>Example

So here is the logo of univeristy I gratuated from. In this example, I used their logo https:// link to load it in this markdown file.

![MBCLogo](https://www.alliancembs.manchester.ac.uk/media/ambs/content-assets/images/alliance-manchester-business-school-1-1.png)

# 10. How to Add (Your) Code [CODE BLOCK] in a Markdown file

## a. Share a code in between your text

To start with lets say you like to share a code or refer a code in between your sentence for that you will use

" ` "  *inverse tick* on both sides of the code which will make the code color change.
>Example

Here is an example of displaying "Hello World!" by using the **print()** command in Python.

For that you need to write `print("Hello world!")` at the Python terminal.

This is how it will look like

| >>> `print("Hello world!")`\
| `Hello world!`

## b. Share a code in a Code Block

In order to do so, you need to use triple *inverse tick* at the begining and at the end of your code.

Use " ``` "  *inverse tick* before your code starts and below where your code ends.

>__IMPORTANT FEATURE:__
>
>In order to give a relavent code and fucntion color based on the programming language been used, write the name of the languge after the " ``` " *inverse tick* while opening for the box for your code.
>
>For example "```Python"

>
>**CODE BOX Example**

Here is a code to create a bar chart with Python using ***Seaborn*** library and using ***Titanic*** data installed with the ***Seaborn***.

>Example

```python
# Titanic Survivor Plot
# x- axis = sex, y-axis = survived

#Step:1 Import the graphic libraries
import seaborn as sns 
import matplotlib.pyplot as plt 

#Step:2 Set the theme
sns.set_theme(style="ticks", color_codes=True) 

#Step:3 import/loading the 'titanic' data installed with Seaborn
titanic = sns.load_dataset("titanic")

#Step:4 assigning specific columns in the 'titanic' data to various features of the graph; like the x-axis, y-axis, color(hue), type of graph to plot and the data source

sns.catplot(x="sex", y="survived", hue="class", kind="bar", data=titanic) 

#Step:5 Command to plot the graph
plt.show()
```

___

# 11. Creating Tables in your Markdown file

For creating tables in madrkdown, we use pipe '|' and hypen '-' to create box in a curde form. Make a crude column and rows and fill them in. Markdown will automatically create a presentable table for you. You can also use the text formating (what you have learned above) to get desired effect.

Here is how you can do it.
>Step 1: Create the Heading row as below:

| Heading 1 | Heading 2 | Heading 3 |...|
>Step 2: Create Colmun Row filled with "----" based on number of Headings underneath the Heading row. You can use as much as 'hyphen' as you like based on your esthatic sense. Three or four are enough for markdown to know.

| ---- | ----| --- |...|

>Step 3: Start filling the data based on the number of your Headings

| Data1 | 123.45| xyz |...|\
| Data2 | 123.45| xyz |...|\
| Data3 | 123.45| xyz |...|\
| Data4 | 123.45| xyz |...|\
| Data5 | 123.45| xyz |...|\
| Data6 | 123.45| xyz |...|\
........... and so on.

>Step 4: Data alignment in the columns

Remember we made a *"Column Row"* under the Headings in our Step 2? We will insert colon ':' on the extreme side of the 'hypen' to make the text under the heading ***Left***, ***Right***, and ***Center*** justified.

This is how you do it. Just notice the postion of the colon ':'.

| :---- | :----| :--- |...| <- All text below it will be Left Justified.

| :----: | :----:| :---: |...| <- All text below it will be Centered.

| ----: | ----:| ---: |...| <- All text below it will be Right Justified.

Do your own experiment to get the gist of it.

Now below is an example as how your table will look like once you put all of them together.

>**Working Example:** A 4 rows x 3 column Table

| Species        | Petal length | Sepal length |
| :------------- | :----------: | :----------: |
| **Virginica**  |     18.2     |     19.2     |
| **Setosa**     |     15.1     |     17.2     |
| **Versicolor** |     12.2     |     12.2     |

___

# 12. Installing useful Markdown *extentions*

Here are some useful Markdown extentions for your **Visiual Studio Code**

1. Markdown All in One
2. Markdown PDF
3. markdownlint
4. Markdown Shortcuts

# 13. Creating Tables of Contents in your Markdown file

Its time for you to open this Markdown file and find out how this Table of Content is been made.

# Table of Contents

[1- Heading](#1-headings)\
[2- Block of Words/Citation](#2-block-of-wordscitation)\
[3- Line Break](#3-line-breaks)\
[4- Combining Two Things](#4-combining-two-things)\
[5- Text Formatting](#5-face-of-the-text-text-formating)\
[6- Creating Bullet Points and Number Lists](#6-creating-bullet-points-and-list)\
[7- Line Break or Page Break](#7-line-break-or-page-break)\
[8- Links and Hyperlinks in Markdown](#8-links-and-hyperlinks-in-markdown)\
[9- Images and Figures with Links](#9-images-and-figures-with-links)\
[10- How to add code within text or as a Code Block](#10-how-to-add-your-code-code-block-in-a-markdown-file)\
[11- Creating Tables](#11-creating-tables-in-your-markdown-file)\
[12- Installing usefull Markdown extentions for Visiual Studio Code](#12-installing-useful-markdown-extentions)\
[14- Creating this TOC](#13-creating-tables-of-contents-in-your-markdown-file)
