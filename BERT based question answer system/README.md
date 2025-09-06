# BERT-based-question-answer-system

## Demo

### Provide context from which we will ask the questions<br>
For example I am providing paragraph from plot of the 3 idiots movie and storing it in variable named data3.<br>
``` python
data3 = """In their first year of college, students Farhan Qureshi and Raju Rastogi join the prestigious Imperial College of Engineering (ICE) in Delhi and meet Ranchhoddas Shamaldas Chanchad aka Rancho, their roommate, who is passionate about experimenting with different things, and consequently tops the class. Rancho's carefree approach to education results in him being at odds with the college's director, Dr. Viru Sahastrabuddhe (nicknamed "Virus" by the students), who believes in a strict and competitive education system.."""
```

### Enter the question:

Let's say we entered - what is full name of rancho ?

### Output

After entering the context and question code will call ```answer_question()``` in which question and context will be passed. Then we will get the following output:<br><br>
![BERT res](https://user-images.githubusercontent.com/70089229/210487877-6d0674d5-9ace-45d7-8815-14915892521f.png)
