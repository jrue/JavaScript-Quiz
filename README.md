JavaScript-Quiz
===============

A simple quiz template written in js/jquery and is responsively designed.

In the future, I will add a generator to add questions, etc.

To use, open the file in a plain text editor such as [TextMate (Mac)](http://macromates.com/) or [Notepad++ (PC)](http://notepad-plus-plus.org/) or any other text editor and edit the data at the top of the document.

Use the quiz.html or to save space, you can use the minified version which compresses the non-editable code.

```javascript
var quiz = [
    {
        "question"      :   "Q1: Who came up with the theory of relativity?",
        "image"         :   "http://upload.wikimedia.org/wikipedia/commons/thumb/d/d3/Albert_Einstein_Head.jpg/220px-Albert_Einstein_Head.jpg",
        "choices"       :   [
                                "Sir Isaac Newton",
                                "Nicolaus Copernicus",
                                "Albert Einstein",
                                "Ralph Waldo Emmerson"
                            ],
        "correct"       :   "2",
        "explanation"   :   "Albert Einstein drafted the special theory of relativity in 1905.",
    },
    {
        "question"      :   "Q2: Who is on the two dollar bill?",
        "image"         :   "http://upload.wikimedia.org/wikipedia/commons/thumb/9/94/US_%242_obverse-high.jpg/320px-US_%242_obverse-high.jpg",
        "choices"       :   [
                                "Thomas Jefferson",
                                "Dwight D. Eisenhower",
                                "Benjamin Franklin",
                                "Abraham Lincoln"
                            ],
        "correct"       :   "0",
        "explanation"   :   "The two dollar bill is seldom seen in circulation. As a result, some businesses are confused when presented with the note.",
    },
    {
        "question"      :   "Q3: What event began on April 12, 1861?",
        "image"         :   "",
        "choices"       :   [
                                "First manned flight",
                                "California became a state",
                                "American Civil War began",
                                "Declaration of Independence"
                            ],
        "correct"       :   "2",
        "explanation"   :   "South Carolina came under attack when Confederate soldiers attacked Fort Sumter. The war lasted until April 9th 1865.",
    },

];
```

Correct is the index from list of 'choices'. Index starts from 0. 

Images are optional, but you should keep the empty quotes. Every item must be proceeded by a comma except for the last item in a set.

To add an additional question, copy the entire curly bracket block:
```javascript
{
    "question"      :   "Q3: What event began on April 12, 1861?",
    "image"         :   "",
    "choices"       :   [
                            "First manned flight",
                            "California became a state",
                            "American Civil War began",
                            "Declaration of Independence"
                        ],
    "correct"       :   "2",
    "explanation"   :   "South Carolina came under attack when Confederate soldiers attacked Fort Sumter. The war lasted until April 9th 1865.",
},
```
There is also a variable at the top to add the quiz title.
