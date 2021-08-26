# Skill Diary Database Vöcklabruck
## Informational Stuff
The trainers of CODERS.BAY decided to let you write a documentation of what you have learned. 

Please keep this as your diary and write a short summary with code snippets and some theoretical topics daily in the last half an hour of the day.

Just to let you know this will be your personal reference book. 

You are going to have three GIT Repositories where you document your progress of the course.

In this Repository we are gonna collect all information of the database classes. 

I'm going to give you all reviews in the form of issues every week, where I'm going to review your documentary by the following criteria:
- code quality
- quality of content 
- totality of your documentation.

As it is a personal documentation the styling and structure is up to your personal preferences.

## Markdown Cheatsheet
### Headlines

<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      # TEXT
    </td>
    <td>
      <h1> This is a H1 </h1>
    </td>
  </tr>
  <tr>
    <td> 
      ## TEXT
    </td>
    <td>
      <h2> This is a H2 </h2>
    </td>
  </tr>
  <tr>
    <td> 
      ### TEXT
    </td>
    <td>
      <h3> This is a H3 </h3>
    </td>
  </tr>
  <tr>
    <td> 
      #### TEXT
    </td>
    <td>
      <h4> This is an H4 </h4>
    </td>
  </tr>
  <tr>
    <td> 
      ##### TEXT
    </td>
    <td>
      <h5> This is an H5 </h5>
    </td>
  </tr>
  <tr>
    <td> 
      ###### TEXT
    </td>
    <td>
      <h6> This is an H6 </h6>
    </td>
  </tr>
</table>

### Emphasis
#### Italic
<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      *This text will be italic*
    </td>
    <td>
      <i> This text will be italic </i>
    </td>
  </tr>
  <tr>
    <td> 
       _This text will be italic too_
    </td>
    <td>
      <i> This text will be italic too</i>
    </td>
  </tr>
</table>

#### Bold
<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      *This text will be bold*
    </td>
    <td>
      <b> This text will be bold </b>
    </td>
  </tr>
  <tr>
    <td> 
       __This text will be bold too__
    </td>
    <td>
      <b> This text will be bold too</b>
    </td>
  </tr>
</table>

### Lists
#### Unordered
<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      * Item 1 <br/>
      * Item 2 <br/>
      TAB * Item 2a <br/>
      TAB * Item 2b <br/>
    </td>
    <td>
      <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <ul>
          <li>Item 2a</li>
          <li>Item 2b</li>
        </ul>
      </ul>
    </td>
  </tr>
</table>

#### Ordered

<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      1. Item 1 <br/>
      2. Item 2 <br/>
    </td>
    <td>
        <ol>
        <li>Item 1</li>
        <li>Item 2</li>
      </ol>
    </td>
  </tr>
</table>

### Images
<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      ![GitHub Logo](/images/logo.png)<br/>
      Format: ![Alt Text](url)
    </td>
    <td>
      Displays the image in folder images which is called logo.png
    </td>
  </tr>
</table>

### Links


<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      ![GitHub](https://www.github.com)<br/>
      Format: ![Alt Text](url)
    </td>
    <td>
      <a href = "https://www.github.com">GitHub</a>
    </td>
  </tr>
</table>

### Backslash Escape
If you need the characters, which are already used as special characters in Markdown you can use them if you put an \\ before the character. For example you have to write ```\*``` to use a \*

### Using code in Markdown
Markdown coverts text with four leading spaces into a code block; with GFM you can wrap your code with \`\`\` to create a code block without the leading spaces. Add an optional language identifier and your code will get syntax highlighting.



![CodeSnippet](/Codesnippet.png)

### Tables
You can create tables by assembling a list of words and dividing them with hyphens \- (for the first row), and then separating each column with a pipe \| 
<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      First Header | Second Header<br/>
      ------------ | ------------- <br/>
      Content cell 1 | Content cell 2 <br/>
      Content column 1 | Content column 2
    </td>
    <td>
      <table>
        <thead>
            <td> 
               First Header
            </td>
            <td>
              Second Header
            </td>
       </thead>
       <tbody>
         <tr>
          <td> 
            Content cell 1
          </td>
          <td>
            Content cell 2
          </td>
        </tr>
         <tr>
          <td> 
            Content column 1
          </td>
          <td>
            Content column 2
          </td>
        </tr>
       </tbody>  
      </table>
    </td>
  </tr>
</table>


# DIARY

## 11.6.2021

First we introduced ourselves and got an impression of the course.

Then we talked about databases in general and what they are used for.

__Benefits of DB__:
* no loss of data
* access for several users possible
* structured deposit of data

There are nine requirements for DB's, the so-called *Codd’s rules*.

We were told about the __Entity Relationship Model (ERM)__ which draws objects (entities), the relationships between one to another and their attributes.

The *Chen-Notation* is the graphical notation of the ERM named after it’s inventor Peter Chen.

Values are described with data types like INT, CHAR, TIME,...

Attributes describe entities or relations and have to be assigned with a data type.

Key attributes identify the entities. If there are more than one the __primary key has to be underlined.__

Relations differ in their degree which can be binary (two entities), ternary (three entities) or unary (one entity).

__Cardinalities__ describe relations more detailed, like a mother (1) and child (N) which means a child can only have one mother, but a mother can have more children (= 1:N). Further forms are 1:1, N:1 and M:N.

## 18.6.2021

First we talked about our homework from last week, which was an ERM about Codersbay.

Therefore we corrected the example of one of our colleagues.

Then the upcoming module system of the course was explained to us and we planned the course of our process though the next months on our own.

At last we started with an ERM about a hotel.

## 25.6.2021

At first we repeated the subject matter from our previous lessons.

Then Matthias taught us about the __(min, max)-Notation__ which gives the relations more information and limits instances with minimum and maximum values.

__Foreign keys__ of a table can be used to refer to another (or the same) table.

A goal for relation models is to avoid redundancies which costs unnecessary storage space and is harder to maintain.

Another goal is to avoid anomalies which can be:

* update anomaly
* insertion anomaly
* deletion anomaly

__Normal forms__ define properties of relation schemas, prohibit certain combinations in relations and should avoid redundancies and anomalies.

There are three forms:

__1NF:__ A relation schema is in 1. normal form if it's ranges of values are atomic.

__2NF:__ A relation schema is in 2nd normal form if it is in 1st normal form and each non-key attribute is fully functional dependent from primary key.

__3NF:__ A relation scheme is in 3rd normal form if it is in 2nd normal form, and no non-key attribute dated primary key is transitively dependent.

In the end we did some exercises on our own.

# REPORT

__CW27: Java__
```
Mon-Tue: Unit testing (Apps: Person management, Dictionary, Calculator)
Tue-Fri: Object-oriented programming I (Apps: Person management, Linked list part I)
```
__CW28: Java__
```
Mon-Thu: Object-oriented programming II (Apps: Linked list part II)
Thu-Fri: Inheritance (Apps: RP game part I)
```
__CW29: Java__
```
Mon-Tue: Inheritance (Apps: RP game part I, Cars)
Tue-Fri: File input/output & exceptions (Apps: RP game part II)
```
__CW30: Databases__
```
Mon-Thu: SQLI - insert, update, delete, select (Exercises: Airways, HR department I, HR department II)
Thu-Fri: SQLII - subselect, join (Exercises: Tennis)
```
__CW31: Databases__
```
Mon-Fri: SQLII - subselect, join (Exercises: Tennis, Parts, HR department I, HR department II)
```
__CW32: Web__
```
Mon-Fri: JavaScript I - introduction, loops, branches, functions, variables, error handling, browser events, window object, DOM, edit forms, predefined objects (Exercises: JavaScript text page I, JavaScript test page II, Rock Paper Scissors)
```
__CW33: Web__
```
Mon: JavaScript I - introduction, loops, branches, functions, variables, error handling, browser events, window object, DOM, edit forms, predefined objects (Exercises: Black Jack)
Tue-Fri: JavaScript II - jQuery & dara storage (Exercises: jQuery test page, Cookie test page I, Cookie test page II, The Math Quiz)
```
__CW34: Web__
```
Mon: Boorstrap - introduction
Mon-Wed: PHP I - introduction, link with HTML, variables, operations, arrays, loops, functions incl. transfer- and return values, read and save data (Exercises: PHP test page I, PHP test page II, PHP test page III)
Thu: Career orientation - learning techniques
Fri: PHP I - introduction, link with HTML, variables, operations, arrays, loops, functions incl. transfer- and return values, read and save data (Exercises: Competence check)
```
__CW35: Web__
```
Mon-Fri: PHP II - data access with MySQLi & PDO (Exercices: Ticketing System, Customer Management System)
```
__CW36:__
```

```
__CW37:__
```

```
__CW38:__
```

```
__CW39:__
```

```
__CW40:__
```

```
__CW41:__
```

```
__CW42:__
```

```
__CW43:__
```

```
__CW44:__
```

```
