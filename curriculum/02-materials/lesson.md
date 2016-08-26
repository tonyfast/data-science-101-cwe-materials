---
title: Data Science 101
duration: "2:50"
creator:
    name: J Rogel-Salazar
    city: LDN
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Data Science 101

### LEARNING OBJECTIVES
*After this lesson, you will be able to:*

- Explain the field of data science, defining common roles, benefits, and trends.
- Explore some popular tools and resources to visualize,  analyze, and model data.
- Recognize the different types of problems that can be solved by data scientists.
- Apply the data science workflow to provide real world recommendations.
- Create a custom learning plan to help you continue to build fundamental data science skills after this workshop.

### STUDENT PRE-WORK
*Before this lesson, you will need to:*
- Bring a laptop with [Anaconda](https://www.continuum.io/downloads) installed. Scroll to your operating system version and click on the install button for ***Anaconda with Python 2.7***. We'll be using Python version 2.7 in this workshop.
- We will be using Jupyter Notebooks as our main IDE for the workshop. If you've downloaded Anaconda (with Win, Mac or Linux), you are ready to go! 

### INSTRUCTOR PREP
*Before this lesson, instructors will need to:*

- Review & modify lesson plan & slide deck
- Write learning objectives & relevant information on board
- Review student roster
- Prepare handout to distribute to students

### WORKSHOP AGENDA
| TIMING  | TYPE  | TOPIC  |
|:-:|---|---|
| 10 min  | [Opening](#opening)  | Greetings + The GA Experience  |
| 10 min  | [Introduction and Guided Practice](#intro1)   | Why Data Science? What Can Data Science Do For Me? |
| 5 min  | [Independent Practice](#demo0)   | Data Science Skill Assessment |
| 20 min  | [Demo](#demo1)  | Visualizing the Data Science Workflow  |
| 20 min  | [Introduction](#intro2)  | Exploring the Data Science Toolkit |
| 20 min  | [Guided Practice](#guided2)  | Explore Some Data! |
| 10 min  | [Independent Practice](#ind-1)  | Practice Exploring Data |
| 5 min  | BREAK  |   |
| 10 min  | [Introduction](#intro2)   | What's an Algorithm, Anyway? |
| 15 min  | [Demo](#demo2)  | Algorithms in Action  |
| 10 min  | [Introduction](#intro3)  | Algorithms & Machine Learning  |
| 15 min  | [Guided Practice](#guided-practice2)  | Thinking Logically  |
| 20 min  | [Independent Practice](#ind-practice2)  | Data Science Case Study |
| 10 min  | [Conclusion](#conclusion) | Review + Recap |
| 10 min  | [Takeaways](#takeaway) | Learning Plan + Q&A |


---

<a name="opening"></a>
## Opening (10 mins)

> Note: Let people know where restrooms and kitchen are located, as needed.

Goals:
- Welcome students and discover their interests
- Review current lesson objectives

#### Instructor Bio

Welcome to Data Science 101! Here's a bit about me:
> Provide your name and brief bio, including things like: your background in data science, any experience you've had with GA, and one "fun fact" about yourself.

#### Introduce Yourselves

Before we dive in, let's hear a bit about you!

> Have students introduce themselves: name, what brings them to GA (ask for their current career & any specific goals), & one "fun fact".

> **Example Exercise**: *Have students write these on a Google doc or in a Google poll. Instructor can briefly **demonstrate** data science by categorizing data, merging into CSV file,  pulling out features, etc.*


#### Our Expectations

- You're ready to take charge of your learning experience.
- You're curious and excited about data science!
- You've already installed [Anaconda with Python 2.7](https://www.continuum.io/downloads).

> Instructor Note: Check that all laptops have a *Python 2.7* distribution (materials for this workshop have not been tested against Python 3.x).


#### Our Objectives

> Note: Write workshop objectives on board before class


* What we’ll cover:
	* Why Data Science & what it can do for me?
	* Data Science skills
	* Explore the Data Science Toolkit
	* Analyze data
	* Algorithms in action
* Why this topic matters:
	* Data Science is a sought-after skill 
	* Python as a core data science skill
* Why this topic rocks:
	* Data Science opens up doors to a variety of opportunities
	* Data Science has been dubbed the “Sexiest job of the 21st century”!

> Note: Tailor any additional objectives to student interests. In general, reference student backgrounds and goals throughout the lesson. 
***

<a name="intro1"></a>
## Introduction: Why Data Science? What Can Data Science Do For Me? (15 mins)

First, we should start with some basic definitions. Just what IS Data Science, Anyway?

**Data Science**: A set of tools and techniques used to extract useful information from data!

- An interdisciplinary, problem-solving oriented subject.
- The application of scientific techniques to practical problems.
- A rapidly growing field.

#### Qualities of a data scientist

- Programming skills (Python or R)
- Knowledgable in algebra and statistics (analyzing and modeling data)
- Business acumen (how to work with stakeholders)
- Industry expertise (for the type of field you're working within)
- Communication skills (visualize data, tell stories)

**Your Turn:**
Let's talk through the following questions as a group: 

- What do you think are the most important qualities for a data scientist?
- Can you think of any other quality/skill we have not mentioned?

#### Question Time
- What is your field of expertise?
- Have you heard of or worked with tools such as Excel, R, or Python? 
- What are your interests? What data would you want to work with?

> Instructor Note: The discussion for this part of the lesson can be used to prompt the students to self-assess areas where they are strong or weak. This will help them start to shape their "Learning Plan".

#### What Can Data Science Do For Me?

* Ask good questions! First and foremost, a data scientist asks a lot of questions. Such as:
	* What is required? (understanding a problem)
	* How are results evaluated? (measuring of success)
	* What do we currently know? (reviewing existing data)
	* What has happened? (applying descriptive analytics)
	* What will happen (if)? (applying predictive analytics)
	* What should we do to achieve what we require? (making recommendations)

Here are some common tasks performed by data scientists:

* Define and test a hypothesis/run experiments
* Aquire relevant business data
* Manipulate, clean, and organize data
* Visualize data to understand relationships
* Program algorithms to learn from that data
* Create products from algorithms that deliver actionable insight
* Tell relevant business stories from data
 
***

<a name="demo0"></a>
## Independent Practice: Assess Your Data Science Skills

> Instructor note: For the following task, create a quick google doc and share with the class. Populate one column with the skills above. Ask students to use an "incognito" window in Chrome to anonymously self-report, creating a new column for their individual skill-assessment. 

Let's do some quick and dirty data science. Here's a table with some of the basic data science skills we just reviewed.  

Using a Chrome "incognito" browser window, create a column and give yourself an honest ranking for each skill. We will use this data to demonstrate some simple statistics as part of the data science workflow.

Example:

| Skill | Student 1 | Student 2 | ... | Average| 
|:-:|---|---|---|---|
| Programming | score 1 | score 2 | ... | Average| 
| Math | score 1 | score 2 | ... | Average| 
| Statistics | score 1 | score 2 | ... | Average| 

> Note: After students complete their entries, perform some quick summary statistics. Gauge the class to see how well they understand basic descriptive statistics. If you have time, try showing off a bit - pull the data into pandas, do some light regression, etc.

***

<a name="demo1"></a>
## Demo: Visualizing the Data Science Workflow (20 mins)

Next, we're going to walk through what we call the "Data Science Workflow". 

#### Work-what? 
> Instructor Note: Make sure to emphasize that the workflow is an iterative process and not necessarily a linear one.

The data science workflow is a way of describing the approach that *most* data scientists take when working on a project. It's not always cut and dry, but in general, the process looks something like this:

![](./data-science-workflow-example.jpeg)

* Identify the problem
	* Identify business/product objectives
	* Identify and hypothesize goals and criteria for success
	* Create a set of questions for identifying correct dataset
* Acquire the data
	* Identify the "right" dataset(s)
	* Import data and set up local or remote data structure
	* Determine most appropriate tools to work with data
* Parse the data
	* Read any documentation provided with the data
	* Perform exploratory data analysis
	* Verify the quality of the data
* Mine the data
	* Determine sampling methodology and sample data
	* Format, clean, slice and combine data (in Python)
	* Create necessary derived columns from the data (new data)
* Refine the data
	* Identify trends and outliers
	* Apply descriptive and inferential stats
	* Document and transform data
* Build a data model
	* Select appropriate model
	* Build model
	* Evaluate and refine model
* Present results
	*  Summarize with narrative, storytelling techniques
	*  Present limitations and assumptions of your analysis
	*  Identify follow up issues for future analysis
*  Deploy and validate
	*  Write unit tests and documentation
	*  Deploy stable production-ready code
	*  Retrain and validate models over time

#### Applying the Data Science Workflow

Let's take a business problem and think about how we would apply our new workflow. Let's assume that you are a junior data scientist at Amazon. Your boss asks you to identify the leading indicators that suggest a user is about to make a new online purchase. How would you go about solving this question?

**The Question:** "What are the leading indicators that a user is about to make a new online purchase?"

ChecK: How would we go about solving this question?

> Note: Don't answer for them! Let them think about it. Table any incorrect responses. Once they generate something from the workflow, write it down on the board as part of the sequence.

> * Identify the problem
	* Identify business/product objectives
	* Identify and hypothesize goals and criteria for success
	* Create a set of questions for identifying correct dataset
* Acquire the data
	* Identify the "right" dataset(s)
	* Import data and set up local or remote data structure
	* Determine most appropriate tools to work with data
* Parse the data
	* Read any documentation provided with the data
	* Perform exploratory data analysis
	* Verify the quality of the data
* Mine the data
	* Determine sampling methodology and sample data
	* Format, clean, slice and combine data (in Python)
	* Create necessary derived columns from the data (new data)
* Refine the data
	* Identify trends and outliers
	* Apply descriptive and inferential stats
	* Document and transform data
* Build a data model
	* Select appropriate model
	* Build model
	* Evaluate and refine model
* Present results
	*  Summarize with narrative, storytelling techniques
	*  Present limitations and assumptions of your analysis
	*  Identify follow up issues for future analysis
*  Deploy and validate
	*  Write unit tests and documentation
	*  Deploy stable production-ready code
	*  Retrain and validate models over time

> If students are stumped or get stuck, break them into smaller groups and challenge them to define the steps and come up with some guiding questions for each step. Then discuss the process as a class.

Here's a high level example of how we might walk through such a challenge:

- **Identify Problem**: What is our problem? What is our goal? Do we understand these correctly?
- **Acquire Data**: What could we do first here? What are some considerations we should make? 
- **Parse Data**: Ok, you've collected some data. Now what?
- **Mine / Refine**: Is the raw data enough? What would you need to do next?
- **Model**: Sure, you've built a nice model. But does it work? How would you know?
- **Present**: Think back to the original question. What do you think your boss wants to see?

> Instructor Note: Here are some suggested talking points you could review. Again, focus the discussion on high level strategy until students are comfortable. Don't spend a lot of time on specific techniques unless your class is comfortable with math/stats:
* Collect data around user retention, user actions within the product, potentially find data outside of company
* Extract aggregated values from raw data
  * How many times did a user share through social media? Within what time frame?
  * How often did they open emails or click on advertisements?
* Examine data to find common distributions and correlations
* Extract new meaning to predict if user would purchase again

***

<a name="intro2"></a>
## Introduction: Exploring the Data Science Toolkit (10 mins)

Ok great. We've discussed some of the strategies a data scientist might apply when approaching a real world business problem. But how would you actually **DO** any of these steps?

In order to answer that question, let's review some common tools used by Data Scientists.

**Code**

While data science is a relatively new field, math and statistics have been around for a while. In fact, most early data scientists were trained as statisticians. But the world of programming opened up new ways to work with data, using code to perform repetitive tasks quickly and efficiently. That's why most modern data scientists combine both math and programming skills to solve problems.

There are lots of programming languages out there, but we're going to be focusing on **Python**.

> Note: Feel free to add in R or other elements here, but the focus should be on how they compare or relate to Python, and why Python is so widely used.

Python is a great programming language for working with data. Here are just a few reasons why it's so popular today:

- Python is extremely fun to develop in! It's fast and highly expressive.
- Python code is an elegant, highest level object-oriented language.
- Everything can be done with Python! And if something can't be done, you can easily create an extension for it :)
- Everything can not only be done, but it can be done quickly! For example, a program that takes you weeks in C++ might only take you a day to write in Python.
- Python is well documented and has anestablished and growing community of supporters.
- Finally, because Python comes with "batteries included", i.e. packages that help you do whatever you want!

#### What's a Package?

Packages are libraries of code written to solve a particular set of problems. In other words, when you're working on a problem using Python, you hardly every have to start from scratch. There are tons of libraries and tools that can help you be more efficient.

Here are some extremely common packages relevant to data science: pandas, Scikit-learn, NumPy, etc.

* pandas
	* Ever used Excel? How would you like working with data structured in a similar way, but without the irritation of formatting, long formulas, and better graphics? Try *pandas*!
* SciPy/NumPy
	* Does your application require the use of advanced mathematical functions or numerical operations, using arrays, vectors, or matrices? Try *SciPy* (scientific python) or *NumPy* (numerical python).
* Scikit-Learn
	* Are you interested in using python in a data science workflow and exploiting the use of machine learning in your applications? Well, look no further than *Scikit-learn*.
* matplotlib
	* Are you tired of the boring-looking charts produced with Excel? Are you frustrated looking for the right menu to move a label in your plot? Take a peek at the visuals offered by *matplotlib*.
* statsmodels
	* Is your boss asking about significance testing and confidence intervals? Are you interested in statistical tests, plotting functions, and descriptive statistics? Well *statsmodels* offers you all that and more!
* Beautiful Soup
	* Let's face it, all the data you require is available freely on the web... but there's not always a download button. Luckily, you can extract data directly from HTML pages using *Beautiful soup*.

Check: So what are some common tools used by data scientists? Why are these useful?


<a name="guided2"></a>
## Guided Practice: Exploring some Data (20 mins)

In this guided practice, we'll explore a sample dataset to carry out some descriptive analytics using the `pandas` library.

> Instructor Note: You should show the following commands and concepts using a **Jupyter notebook**. Open the [part 1 guided practice code and walk students through the notebook](./code/DataScience101_Part1_GuidedPractice.ipynb).

#### Instructions for students
We recommend using a Jupyter notebook for this guided practice. This makes it easier for all as it is homogenous for various environments (mac, win, linux).

#### Accessing Files

**OPTION 1** - Accessing Files with **Dropbox**
> Instructor Note: If you use Dropbox to get the material to your students follow these steps:

The link provided has a Zip file with the materials for the class. 

1. Unzip the file downloaded in a known location in your file system
2. Locate the file called [DataScience101_Part1_GuidedPractice.ipynb](./code/DataScience101_Part1_GuidedPractice.ipynb) 
3. To start Jupyter: Open a terminal 

	- **Mac**: Using spotlight search for "Terminal" 
	- **Windows**: Click the "Start" button and type "cmd"
	- In the terminal type: `jupyter notebook`
	
4. Navigate to the folder where you have saved the file in step 1
5. Open the file from the Jupyter interface
6. Voilà, you are ready to go!


**OPTION 2** - Accessing Files via **GITHUB**
> Instructor Note: If you use GitHub to get the material to your students, follow these steps:

To get the starter code, you'll need to download these materials.

1. First, visit this page: [https://github.com/generalassembly-studio/data-science-101-cwe-materials](https://github.com/generalassembly-studio/data-science-101-cwe-materials)
2. Then, click on the "Clone or Download" button, and click "Download ZIP"
3. Unzip the file downloaded in a known location in your file system
4. Locate the file called [DataScience101_Part1_GuidedPractice.ipynb](./code/DataScience101_Part1_GuidedPractice.ipynb) 
5. Open Jupyter: Open a terminal 

	- **Mac**: Using spotlight search for "Terminal" 
	- **Windows**: Click the "Start" button and type "cmd"
	- In the terminal type: `jupyter notebook`
	
6. Navigate to the  folder where you have saved the file in step 3
7. Open the file from the Jupyter interface
8. Voilà, you are ready to type the commands we will cover below!

> Reminder: Once students have the notebooks, open the [guided practice code for part 1](./code/DataScience101_Part1_GuidedPractice.ipynb) and walk through it with the students.

***

<a name="ind-1"></a>
## Independent Practice: Practice Exploring Data (10 mins)

> Instructor Note: Using a second dataset, ask the students to carry out a similar analysis. This should be a pair programming activity, depending on the size of the class and on baseline abilities. Make sure to discuss results with the entire class afterward.

## Now You Try!

First, let's get into pairs. Now let's assume you are a both business intelligence managers at a fast moving startup breaking into the flower delivery space. You need to analyze some data for iris flowers of three different species.

You've received a sample dataset for the following three "iris" species:

- Verginica
- Setosa
- Versicolor

Your job is to use some basic Python (and hint: Pandas) to help your company differentiate between the three species.

#### Access Instructions

Follow the same procedure from before to access materials, this time opening the file called [DataScience101_Part1_IndPractice.ipynb](./code/DataScience101_Part1_IndPractice.ipynb)


> **Solutions**: You can find [a Jupyter notebook with solutions to the independent practice exercise here](./code/DataScience101_Part1_IndPractice_Solutions.ipynb).

***

**BREAK** (5 mins)

***

<a name="intro2"></a>
## Introduction: What's an Algorithm, Anyway? (10 mins)

> Instructor Note: Before re-starting the class, check for any questions the students may have about the first part of the workshop.

## Discussion

What comes to mind when you hear the word **algorithm?**

> Instructor Note: Write down descriptions on the whiteboard. Goal is to amass a list of different descriptions from students, then use that to lead to the information below.

#### Definition:

1. *Algorithm*: A set of steps to accomplish a task. 
2. Algorithms provide instructions for processing these steps in a particular order.

#### Exercise: Let's create an algorithm for getting dressed in the morning:

What would come first? Second? 
But wait, does order matter?

- What if you put on your shoes before your socks? 
- What if you put on your jacket before your shirt?

When you write an algorithm, **the order of the instructions is very important**. In computer science, algorithms are a formal set of instructions for carrying out series of precisely defined tasks.

And guess what? Computers are *very good* at carrying out series of precisely defined tasks.

#### Criteria of a "good" algorithm

A. **Unambiguous**: An algorithm is an **unambiguous description** that makes clear what has to be implemented. For example, consider the following recipes:

- Recipe 1: Put food in oven. Turn on. Bake until done.
- Recipe 2: Open oven tray, place food on tray, withdraw hand, close oven. Set oven to 375 on timer for approximately 10 minutes.

Similarly, in a computational algorithm, a step such as “Choose a large number” is too vague. How does the computer know what "large" is? Does the number have to be different each time, or can the same number be used every time?

B. **Definitions**: A good algorithm clearly defines a set of inputs. For example, it might require two numbers where both numbers are greater than zero. Or it might require a word, or a list of zero or more numbers. An algorithm also produces a defined set of **outputs**. It might output the larger of the two numbers, an all-uppercase version of a word, or a sorted version of the list of numbers. Constraints and criteria for both **inputs** and **outputs** need to be defined.

C. **Constraints**: A good algorithm must be defined so that it terminates after a set period or as the result of a set output. An algorithm that isn't explicitly told this could potentially run forever, which wouldn’t be very useful - you might never get an answer!


> Check: What are the criteria of a good algorithm? Why are these important?

At its simplest, an algorithm is a model that takes in specifically defined data and transforms it following a series of clearly defined instructions, generating a clearly defined output that fulfills some termination criteria. 

> EXAMPLE OVER-SIMPLIFIED ON PURPOSE
```
Data In -> Change! -> New Data Out
```

#### Discussion

> Instructor Note: Divide the class in three groups and ask students to list the steps they follow to achieve an every-day task. Students should break down these steps into the smallest, discrete, sequential items.

Let's put this into practice! Get into groups and create your own algorithm using *pseudocode*. In other words, your group will write down a series of steps using "fake code" that simply outlines the logic for an everyday task. Choose your own task and create your own algorithm, remembering to include all the criteria above!

Example Group Topics:
- Making breakfast
- Commuting to work
- Brewing a cup of coffee
- Brushing teeth


Remember to break down your steps into the smallest discrete, logically sequential items you can think of!

> Note: Afterward, ask groups to share their "algorithms" with the rest of the class. Ask if other students can follow the directions precisely - what happens? Were all steps described successfully?


***

<a name="demo2"></a>
## Demo: Algorithms in Action (15 mins)

Now that you've got a good understanding of what an algorithms **IS**, we'll look at how to write one in Python.

> Check: Based on what you've learned about Python so far, why do you think Python is might be good for writing algorithms?


#### Sketching Algorithms in Pseudocode

**Problem**: Given a list of positive numbers, return the largest number on the list.

**Inputs**: A list `L` of positive numbers. This list **must** contain at least one number. 

> Check: Why? Because asking for the largest number in a list of 0 numbers is not a meaningful question :)

**Outputs**: A number `n`, which will be the largest number of the list.


> Check: How would we go about this? What do you think this would look like?

#### Example:

1. Set the variable `max` to 0.
2. For each number `x` in the list `L`, compare it to `max`. If `x` is larger, set `max` to `x`.
3. `max` is now set to the largest number in the list.


Here is the Python implementation:

```python
def find_max(L):
    max = 0
    for x in L:
        if x > max:
            max = x
    return max
```

#### Discussion

Does the algorithm above meet the criteria for being an algorithm?

<details>
<summary>
* Is it unambiguous? 
</summary>
Yes. Each step of the algorithm consists of primitive operations, and translating each step into Python code is very easy.
</details>

<details>
<summary>
* Does it have defined inputs and outputs? What are they?
</summary>
Yes. X and L
</details>

<details>
<summary>
* Is it guaranteed to terminate? 
</summary>
Yes. The list L is of finite length, so after looking at every element of the list the algorithm will stop.
</details>

<details>
<summary>
* Does it produce the correct result? 
</summary>
Yes. In a formal setting you would also provide a careful proof of correctness.
</details>


<a name="intro3"></a>
## Algorithms in the context of Machine Learning (10 min)

Python algorithms are the ingredients in **machine learning**, which is at the heart of data science. Machine learning is a branch of artificial intelligence concerned with the construction and study of systems that can learn from data. In other words, systems (of algorithms!) that take in data, transform it, and can make decisions based on the outputs.

The core of machine learning deals with representation and generalization.

- **Representation**: *extracting structure* from data. Much like a puzzle, data typically has to be cleaned, filtered, and reorganized before it can present a complete picture.
- **Generalization**: *making predictions* from data. In other words, looking for statistically significant patterns and trends that can used to inform future behavior. 


#### Types of Machine Learning Problems

As you can imagine, there are many different ways to apply machine learning to real world problems. These depend on the types of data and types of problems involved, but generally, machine learning problems fall into a few categories:

#### **Supervised Learning Problems**: Making predictions (generalization)

For example, suppose you want to predict whether someone will make a purchase the week after they visit your site. You have a set of data on previous customers, including age, interests, previous purchases, time of visit, etc. 

You know whether the previous customers made a purchase within a week of their last visit. So, the problem is combining all the existing data into a model that can accurately predict whether a *new* person will make a purchase within a week or not.

Based on that prediction, you might then take action and send them a reminder or suggest a discount, etc.

> Check: Can you think of any companies that do something like this?

Amazon, Netflix, and many others use this very data - customer history - to make predictions that inform their actions.

Supervised learning is a big category of machine learning that includes tons of different kinds of algorithms, including:
 - linear regression (remember high school algebra?)
 - decision trees (think of an organized flowchart)
 - neural networks (as in, artificial intelligence)

However, before you can make predictions on your data, sometimes you need to sort and analyze that data. That's where the category of unsupervised learning problems comes in.

#### **Unsupervised Learning Problems**: Extracting structure (representation)

Suppose you want to better understand your customer base so that you can produce appropriate segments to target during your next marketing campaign.

You have a set of data about your customers, including age, location, previous purchases, time of visit, etc - but you don't know which set of characteristics you should focus on, or how they relate together. You want to sort this data in order to segment your customers into groups, in order to provide them with specifically tailored messaging.

In order to create these groups, you would need to **extract structure** from this data to identify similarities and differences. You could then take action and make them an offer or recommend a product!

> Check: Can you think of any companies that do something like this? Hint: anyone trying to sell you anything :)

Some popular unsupervised learning algorithms include:
	- clustering 
	- anomaly detection
	- principal component analysis

> Check: Let's recap! What do we mean when we talk about "machine learning?" What is the difference between supervised and unsupervised learning? How do these solve different problems?

***

<a name="guided-practice2"></a>
## Guided Practice: Thinking Logically (15 mins)

All right. So far you've learned about algorithms, pseudocode, and machine learning at a high level. Now let's practice putting some of these elements together. 

> Instructor Note: Run through the example and ask students to draw a decision tree based on the "business rules" below, in pseudocode.

Let's review the following example and apply a type of *supervised* learning model called a "decision tree" to generalize and make predictions:

#### EXAMPLE

During a doctor's examination, some patients show the following symptoms:

```
	X1: temperature
	X2: coughing
	X3: reddening throat
```

The doctor suggests the following `Y` outcomes for the patients:

```
	W1: cold
	W2: tonsillitis
	W3: flu
	W4: pneumonia
	W5: healthy
```

The doctor is required to find a diagnosis for `Y` based on the symptoms `X` presented by the patient. We can understand the range of possible outcomes as `Y = {W1, W2, W3, W4, W5}`.

What rules do you think we could come up with to explain these different possible outcomes? Don't worry about writing real code, just work through it logically.

> Check: Ask students to work in pairs and come up with 2-3 examples, then review as a class.

<summary>
<details>
The rules below illustrate such a model:

1. If `X1 < 98` , `Y`="is healthy".
2. If `X1` has values between `[98]` and `102`="there is no reddening of throat", then `Y`="cold";
3. If `X1` has values between `[98]` and `102`="there is reddening of throat", then `Y`="tonsillitis";
4. If `X1 > 100` and `X2`="there is no cough", then `Y=`"flu";
5. If `X1 > 100` and `X2`="there is cough", then `Y`="pneumonia";

</details>
</summary>

Using these rules, we can not only describe the current patients, we can also apply these same rules to make predictions for new patients!

***

<a name="ind-practice2"></a>
## Independent Practice: Data Science Case Study (20 mins)

Activity:

Using the dataset(s) from [Part 1 - Guided Practice](#guided-practice1) or [Part 1 - Independent Practice](#ind-practice1), pair up and review the decision tree algorithm. This model is created using *scikit-learn*. Can you understand the code? If so, can you implement it? Work in pairs and review the [scikit learn documentation](http://scikit-learn.org/stable/modules/tree.html) to assist you! 

Afterward, we'll come back and discuss this as a class.

> Instructor Note: Remind the students of what scikit-learn is used for, referring to the discussion from the [Guided Practice](#guided-practice1). Emphasize the importance of learning to look up documentation when they encounter something new!

For this exercise, you'll need to download the [DataScience101_Part2_DecisionTree.ipynb](./code/DataScience101_Part2_DecisionTree.ipynb) and the [Iris dataset](./code/data/iris.csv).

> Make sure to help students access a copy of the notebook [DataScience101_Part2_DecisionTree.ipynb](./code/DataScience101_Part2_DecisionTree.ipynb) and the [Iris dataset](./code/data/iris.csv). If they have trouble accessing on Github, use Dropbox and provide students with a link.

> Note: As a reminder, students have not had an opportunity to demo the library or the decision tree model yet. Therefore, provide them with the complete notebook and ask students to work in pairs to run and discuss the code. Then bring the class back together to explain the code and allow for questions.


***

<a name="conclusion"></a>
## Conclusion: Review + Recap Topics (10 mins)

> Review Deliverables & Topics Covered

Ok, let's review! In this workshop, we've covered the following topics:

- Why data science?
- What can data science do for me?
- What is the data science workflow?
- What tools are commonly used to analyze and visualize data using Python (pandas, matplotlib, NumPy, etc.)
- How to define algorithms and their role in different types of machine learning
- How to begin applying these concepts to make real world predictions

***

<a name="takeaway"></a>
## Takeaways: Learning Plan + Q&A (10 mins)

> Instructor Note: Encourage the students to continue learning by producing a plan based on the skills discussed in [Part 1 - Introduction](#intro1).
> 
> Refer back to the student poll from the [Introduction](#intro1) and reference their specific goals. 

Now that you've got a great start to your learning journey, take the time to outline some next steps. Your learning plan should outline at least 3 possible resources and a relevant goal for each. 

#### What Should You Do Next?

Remember the data science skill assessment we discussed earler?

- Programming skills (Python or R)
- Knowledgable in algebra and statistics (analyzing and modeling data)
- Business acumen (how to work with stakeholders)
- Industry expertise (for the type of field you're working within)
- Communication skills (visualize data, tell stories)

Refer back to your earlier self-assessment. 

1. Which skills do you want to improve first? Which ones are you most interested in learning about? 
2. Rank these and identify the top three focus areas.
3. For each focus area, identify *at least* one possible resource and a related goal.
4. If you get stuck, check out our suggested resources and ask your instructor for ideas!

## Suggested Resources

#### Books:
	- [**Data Analysis with Open Source Tools**, P. K. Jannert](https://www.amazon.com/Data-Analysis-Open-Source-Tools/dp/0596802358?ie=UTF8&camp=1789&creative=9325&creativeASIN=0596802358)
	- [**Data Science for Business**, F. Provost and T. Fawcett](https://www.amazon.com/Data-Science-Business-Data-Analytic-Thinking/dp/1449361323?ie=UTF8&camp=1789&creative=9325&creativeASIN=1449361323)
	- [**Pattern Recognition and Machine Learning**, C. Bishop](https://www.amazon.com/Pattern-Recognition-Learning-Information-Statistics/dp/0387310738?ie=UTF8&camp=1789&creative=9325&creativeASIN=0387310738)
	- [**Data Science and Analytics with Python**, J Rogel-Salazar](https://www.crcpress.com/Data-Science-and-Analytics-with-Python/Rogel-Salazar/p/book/9781498742092)
	- [An Introduction to Statistical Learning with Applications in R](http://www-bcf.usc.edu/~gareth/ISL/) (free PDF)
	* [Elements of Statistical Learning](http://www-stat.stanford.edu/~tibs/ElemStatLearn/) (free PDF)
	* [Think Stats](http://www.greenteapress.com/thinkstats/) (free PDF or HTML)
	* [Mining of Massive Datasets](http://www.mmds.org/) (free PDF)

#### MOOCs
	- Andrew Ng's Machine Learning Class on Coursera [link](https://www.coursera.org/course/ml)
	- MIT's Artificial Intelligence course [link](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-034-artificial-intelligence-fall-2010/)
	- Johns Hopkins' Data Analysis Methods [link](https://www.coursera.org/course/dataanalysis)
	- Cal Tech's Learning from Data course [link](http://work.caltech.edu/lectures.html)

#### Blogs:
	- FiveThirtyEight [link](http://fivethirtyeight.com)
	- Data Science & Psychology [link](http://www.polipsych.com/)
	- Inherent Uncertainty [link](http://www.inherentuncertainty.org/)

#### Twitter
	- Hillary Mason ([@hmason](https://twitter.com/hmason)): Data Scientist in Residence at Accel and Scientist Emeritus at bitly.
	- Dj Patil ([@dpatil](https://twitter.com/dpatil)): VP of Product at RelateIQ.
	- Jeff Hammerbacher ([@hackingdata](https://twitter.com/hackingdata)): Founder and Chief Scientist at Cloudera and Assistant Professor at the Icahn School of Medicine at Mount Sinai.
	- J Rogel-Salazar ([@quantum\_tunnel](https://twitter.com/quantum_tunnel)): Data scientist at IBM and GA instructor
	- Peter Skomoroch ([@peteskomoroch](https://twitter.com/peteskomoroch)): Equity Partner at Data Collective, former Principal Data Scientist at LinkedIn.
	- Drew Conway ([@drewconway](https://twitter.com/drewconway)): Head of Data at Project Florida


#### Aggregators

	* [DataTau](http://www.datatau.com/): Like [Hacker News](https://news.ycombinator.com/), but for data
	* [MachineLearning on reddit](http://www.reddit.com/r/MachineLearning/): Very active subreddit
	* [Quora's Machine Learning section](http://www.quora.com/Machine-Learning): Lots of interesting Q&A
	* [Quora's Data Science topic FAQ](https://www.quora.com/What-is-the-Data-Science-topic-FAQ)
	* [KDnuggets](http://www.kdnuggets.com/): Data mining news, jobs, classes and more

#### Other Resources

	* [Open Source Data Science Masters](https://github.com/datasciencemasters/go): Huge list of resources
	* [Data Science Trello Board](https://trello.com/b/rbpEfMld/data-science): Another list of resources
	* [The Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/): Online guide to understanding Python and getting good at it
	* [Python Reference](https://github.com/rasbt/python_reference): Python tips, tutorials, and more
	* [videolectures.net](http://videolectures.net/Top/Computer_Science/): Tons of academic videos
	* [Metacademy](http://www.metacademy.org/list): Quick summary of many machine learning terms, with links to resources for learning more
	* [Terms in data science defined in one paragraph](https://github.com/rasbt/pattern_classification/blob/master/resources/data_glossary.md)

#### Data Science at GA

At GA, we offer part time and immersive courses in data science! Some of the topics we cover in our courses include:

- Statistical analysis & python programming
- Common supervised & unsupervised learning algorithms
- Natural language processing
- Time series analysis
- Applying the data science workflow to real world problems
- And more!


To qualify for our courses, you'll want to dig into some basic summary statistics and introdcutory python programming fundamentals beforehand!

#### Q & A

> Instructor Note: Encourage the students to share any final thoughts or questions.

***

<a name="resources"></a>
## ADDITIONAL RESOURCES
- [Sorting algorithms](https://www.toptal.com/developers/sorting-algorithms)
- [15 sorting algos in 6 min](https://www.youtube.com/watch?v=kPRA0W1kECg)
- [Decision trees in scikit-learn](http://scikit-learn.org/stable/modules/tree.html)
- [Decision trees tutorial](http://www.analyticsvidhya.com/blog/2016/04/complete-tutorial-tree-based-modeling-scratch-in-python/)
