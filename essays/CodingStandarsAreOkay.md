---
layout: essay
type: essay
title: Coding Standards Are Okay
# All dates must be YYYY-MM-DD format!
date: 2019-09-26
labels:
  - Coding Standards
---

<p style=" 
  text-align: justify;
  text-justify: inter-word">
<span style="margin-left:2em"></span>
	Today makes the eighty-seven days that I still have not adapted my coding formatting to the coding standards. Every time I wake up I think to myself, should I change my coding standards? Are my coding standards good enough? Should I just create my own coding standards instead of learning other people’s standards? To this day, these questions still remain unanswered.

	To give you a perspective of what I do everyday, I am a backend developer. Everyday I go to work, I need to deal with naming conventions for the tables, columns and procedures that our server uses. Everytime I create something, my supervisor tells me to change my coding standards to the point I lost track of how many times I have changed my code. When I started, I would write a simple piece of code.
    
<br/><br/></p>

```sql
select Grade
From ICS314Tbl
INNER JOIN OkayStudentTbl
On ICS314Tbl.StudentID = OkayStudentTbl.StudentID
```


<p style=" 
  text-align: justify;
  text-justify: inter-word">
<br/><span style="margin-left:2em"></span>
My supervisor will tell me to change my code like this:
<br/><br/></p>


```sql
SELECT
	Grade
FROM ICS314Tbl
-------------------------------------------------
INNER JOIN GradeAStudentsTbl ON
-------------------------------------------------
      ICS314Tbl.StudentID = OkayStudentTbl.StudentID
```


<p style=" 
  text-align: justify;
  text-justify: inter-word">
<br/><span style="margin-left:2em"></span>
	At the start I wondered why the way I wrote would not be that useful in the long run; then I realize that my code would be readable if is a small piece of code; however, if it is like 4000 line of code, the way my supervisor advise to code, it will be way more easier to read. Thus, I decided to adopt it.

	I do not always follow the coding standards. Sometimes, I just do not like the coding standards that people are trying to push onto me. For example, in JavaScript, I would write this:
<br/><br/></p>


```javascript
function NotSoSmartProgrammer () {
	console.log("Frendy");
}
```


<p style=" 
  text-align: justify;
  text-justify: inter-word">
<br/><span style="margin-left:2em"></span>
	If I follow the ESLint coding standard; the above code would be wrong because I used “Tab” to indent my code. The proper way would be using four spaces for each indentation.
<br/><br/></p>


```javascript
function NotSoSmartProgrammer () {
    console.log("Frendy");
}
```


<p style=" 
  text-align: justify;
  text-justify: inter-word">
<br/><span style="margin-left:2em"></span>
	In my opinion, four spaces and a tab are basically the same. When I am writing code, I do not think I would have the patience to click space four times. Thus, I decided to not use four spaces, and just keep using tab.

	To end this small journey that you had with me; I just want to tell you that I do think that coding standards are useful; but, not necessary. I think people should write their code in a way that is readable for any person, not only for yourself. If the code you write is not readable by any other person, then I am sorry to tell you, that you should start changing the way you do your coding standards; go on the web and learn some coding standards.
</p>
