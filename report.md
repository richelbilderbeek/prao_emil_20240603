# Report


Goal of a PRAO is to find out how it is like to work at a certain place.

This PRAO has two parts:

- work: work on something yourself
- interviews: find out how others like the place

## Code

Here at NBIS and UPPMAX, we do many different things.
A thing I need is [select thing]:

- [X] Create a [flamegraph](images/example_flamegraph.png)
  of code runtime.
  Find/write an example of well-written Python code
  that shows a run-time speed bottleneck
  at an unexpected location.
  Adapt text at <https://uppmax.github.io/programming_formalisms/optimisation/runtime_speed_profiles/>

## Technical

### What is Python?

Python is a programming language.

### How does a simple Python program look like?

### What is a Python script?

A python script is a file where you can write your code in or copy one in.

### How to create a Python script?

search for an python code, copy the code ctrl c. write down somewhere for example in your termal: gedit (madeup code name).py
now once in the file you press ctrl v to paste in the code that you found then after that, you save the code and close the file.
### How to run a Python script?

 In termal to run the python script you write: pyhton3 (code name here).py

### What is a flamegraph?

A flamegraph shows what runs slow and what runs fast in your code.

### How does a flamegraph look like?



### Why use a flamegraph?

You can use a flamegraph to see what is slow in your code or whats fast so that you can fix it.

### Give an example code that gives a useful flamegraph

![image](https://github.com/richelbilderbeek/prao_emil_20240603/assets/171581052/cfd09afa-667c-4cbd-af66-9db4db01beed)

```python
import numpy as np

def make_big_array():
    return np.zeros((1024, 1024, 50))

def make_two_arrays():
    arr1 = np.zeros((1024, 1024, 10))
    arr2 = np.ones((1024, 1024, 10))
    return arr1, arr2

def main():
    arr1, arr2 = make_two_arrays()
    another_arr = make_big_array()
    # → Peak memory usage is here ←

main()

```

## How to make a flamgraph?

-first find a python code. python is a programming language. when you search ask: python code example

-once you found a python code, hold down the press key and drag it over the code so its blue. Copy the code and while the code is blue press ctrl, alt and c at the same time to copy it. Then hold down ctrl alt and T at the same time to start coding.

-Once in the termal write: gedit (madeup code name).py always put .py at the end of you madeup code name. 

-Once your in text editor press ctrl v to put in the code you copied. press save or do ctrl s to save. 

-Then exit and go back to termal and write: python3 -m cProfile -o myscript.prof (the code name you made).py

-Then write: python3 flameprof.py myscript.prof > output.svg 

-Then just go into your files and search output.svg and click on it.

-Now you should have a flamegraph that looks kinda like this:![](flamegraph_1.png)

most flamegraphs don't look the exact same, they are all diffrent.

## How to read/use a flamegraph?

In the flamegraph there are many different lengths on the horizontal bars, some are short and some long. The long ones are slow and the short ones are fast, so basically it shows what runs fast in your code and what runs slow.

## Interviews

Here at NBIS and UPPMAX, we do many different things,
done by a diverse group of people with different opinions.
These people have signed up to have a chat with you,
so you can find out.

Some colleagues have planned an activity to do,
so will improvise and discuss their work.

If there is time, try to answer these questions per person.

### Martin Dahlö

- What is his job title?

Job title is bioinformatician.

- What does he do?

he did do a little bit of working with computers and a little more with biotechnology but now hes working some more with computers.

- What did he do to get his job?

he did continuation of his ex-job.

- How much do you think you'd like his job?

i think this is a reasonable job, but threre are many jobs I would prefer above this one.


### Jason Hill

- What is his job title?

His job title is bioinformation

- What does he do?

He works with the data DNA, and understand what the code in the DNA is trying to tell us. Right now working with how to make a better breed of spruce tree with tree DNA.

- What did he do to get his job?

He sorta got his job by accident, since he came for biochemistry but they changed it to what he works with now bioinformation.

- How much do you think you'd like his job?

I liked this job a bit more, I think DNA and nature as in trees are intresting. Would like it a bit more as it is intressting, but i think this is alright.

### Jayant Jadav

- What is his job title?

The title is application expert

- What does he do?

He works with ai, an ai tool called whisper that converts audio into text for humanity researchers and social scientists. Is continuing with learning about whisper. He uses NER on documents to help humanity researchers and social scientists awnser questions from documents. He knew about NER before coming to sweden and the two months he has been here hes learned about whisper and still is.

- What did he do to get his job?

He got an PHD.

- How much do you think you'd like his job?

I like this job. its fun to help others.

### Chris Edrmamm
- What is his job title?

Head of open science

- What does he do?

He helps researchers sort out data, aswell as helping and giving them tips to find information

- What did he do to get his job?

at first he studied history, he also worked with a company about buildings. He found his job that he has now through network and had interviews that made him love the place because of the people.

- How much do you think you'd like his job?

As the other one i like helping people but not my thing with data. Its alright.

### Pavlin Madvin

-What is his job title? 

Application expert.

-What does he do? 

He helps mainly people from uppmax and not as often people from other places in sweden.

-How did he get his job?

he was researcher, at the chemstry department then some time later, he was offered to work halftime at uppmax. Now fulltime.

-How much do you think you'd like his job?

I dont really like this kind of work same with the other people that work with computer but i think helping others makes up for it so i think i'd like it a bit.

### Marcel Den Hoed

-What is his job title?

associate professer.

-What does he do?

he does research on fish right now, with a research group that he leads. He does mutations on the fish genes and finds out what happens if diffrent things in the genes does, so that he can then after find out why the human had his heart stop from out of nowhere.

-How did he get his job?

He studied 4 years in the netherlands and got an PHD that he studied on for another 4 years in the netherlands. Then he moved to England to study 3 years for him to then come to sweden 2012 and he does research till this day.

-How much do you think you'd like his job?

i think it would be fun to do some research.

### Kartik Nair

-What is his job title?

bioinformatician

-What does he do?

He does a DNA sequencing and is a system devoloper in which he makes softwares to put DNA samples in. 80% systemdeveloper 20% bioinformatics. First they get DNA samples sent from other countries, DNA from bone, bug and more. then with machines help they can see the DNA and what it has. But the DNA is hard to understand so Kartik made a software that helps with that.

-How did he get his job?

He fit into the criterias, knowing about math-statistics, biology and computer science.

-How much do you think you'd like his job?

it would be fun but at the same time I am not good with computers, the DNA part sounds fun though.
