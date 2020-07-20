# 100 Days Of Code - Log

**Course Links**
* [2020 Python Bootcamp - Udemy](https://www.udemy.com/course/complete-python-bootcamp/)
* [Bioinformatics Algorithms - Stepik](https://stepik.org/course/2)

**My Repos**
* [Finding Ori](https://github.com/ClarissaPereira/Finding-Ori)

### Day 1: 11.07.2020

**Today's Progress**: 
* Learnt the basics of objects and data structures in Python
* Installed Anaconda and Jupyter
* Completed the first code challenge in the Bioinformatics Algorithms MOOC
  * Objective --> identify the number of times a k-mer appears in a base sequence when given the k-mer base sequence
* Wrote my first program in Python

**Thoughts** This is my first time coding. I spent many hours picking up the basic skills needed to approach and solve the bioinformatic code challenge. Finally solving the algorithm challenge was the perfect end to today.

**Link(s) to my work**
- [basic k-mer search function](https://github.com/ClarissaPereira/Finding-Ori/blob/master/basic%20k-mer%20search.py)

### Day 2: 12.07.2020

**Today's Progress**: 
* Learnt about Python arrays, lists, dictionaries, and tuples as part of the Udemy course
* Wrote a function that identifies the most common substrings (suspected DnaA boxes) in a genome base sequence
* Wrote a function that finds the location of a specific k-mer in a genome

**Thoughts** These coding challenges were built upon yesterday's knowledge so I found writing today's functions quite intuitive

**Link(s) to my work**
- [locating specific k-mers](https://github.com/ClarissaPereira/Finding-Ori/blob/master/find%20k-mer%20location.py)

### Day 3: 13.07.2020

**Today's Progress**: 
* Scored highly on the first Udemy course assessment
* Wrote a function that identifies the most common substrings (suspected DnaA boxes) in a genome base sequence

**Thoughts** I'm pleased with today's progress! I am now 1/4 of the way through the Bioinformatics Algorithms MOOC.

**Link(s) to my work**
- [finding most frequent k-mers when given k](https://github.com/ClarissaPereira/Finding-Ori/blob/master/find%20k-mer%20by%20k.py)

### Day 4: 14.07.2020

**Today's Progress**: 
* Wrote a function that finds the most frequent k-mers that cluster together into clumps in the genome
* Faced some technical issues and obstacles: 
  * Initially I wrote the function in a Jupyter notebook and it kept crashing 
  * I switched to Spyder and used file input to cut down on runtime
* Received a JetBrains IDE licence key from Stepik as a reward for solving a difficult code challenge

**Thoughts** I'm so delighted today - I did not expect the gift from Stepik! The satisfaction I feel after solving a difficult code challenge is a reward itself.

**Link(s) to my work**
- [finding frequent k-mers that cluster together into clumps](https://github.com/ClarissaPereira/Finding-Ori/blob/master/find%20k-mer%20clumps.py)

### Day 5: 15.07.2020

**Today's Progress**:
* Wrote a function that generates the reverse complement of a DNA strand (i.e. the strand that is created in DNA replication)
* Wrote a function that identifies the minima in a skew plot
* Wrote a function that calculates Hamming distance (a measure of how 'mismatched' two strings are) to identify mutations in a replicated strand of DNA
* Reviewed comparison operators and statements in Python 
* Practiced using nested for loops

**Thoughts** I was really productive today and I'm very proud of myself. I learnt a bit about information theory as part of researching Hamming Distance and I'm looking forward to putting all these skills into practice and working on larger data sets.

**Link(s) to my work**
- [reverse complement generator](https://github.com/ClarissaPereira/Finding-Ori/blob/master/reverse%20complement%20generator.py)
- [find the minima of a skew plot](https://github.com/ClarissaPereira/Finding-Ori/blob/master/find%20skew%20minima.py)
- [find the number of mutated bases in a replicated DNA strand](https://github.com/ClarissaPereira/Finding-Ori/blob/master/find%20mutated%20bases.py)

### Day 6: 16.07.2020

**Today's Progress**:
* Wrote a function that finds the most frequent k-mers in a base sequence (while also accounting for mismatches caused by mutations in replicated DNA)
* Wrote a function that generates a list of all possible k-mers using the Cartesian Product of 'AGCT' 

**Thoughts**  I've spent the past two days puzzling over the challenge of how to find all the possible nucleotide k-mers and how to identify imperfect k-mer matches. Today I felt the immense satisfaction of my program finally working! In the process, I learnt about Python modules, created my own functions, and persevered through endless errors. I'm really proud of myself!

**Link(s) to my work**
- [locate approximate k-mer matches](https://github.com/ClarissaPereira/Finding-Ori/blob/master/locate%20approximate%20k-mer%20matches.py)
- [generate all possible k-mers](https://github.com/ClarissaPereira/Finding-Ori/blob/master/all%20k-mers%20generator.py)

### Day 7: 17.07.2020

**Today's Progress**:
* Wrote a program which finally brings all my small functions together 
 * It identifies the most frequent k-mer clumps in the origin of replication region of the genome in several steps
* Tested my program on the Salmonella enterica genome and found the DnaA box to be TTATCCACA

**Thoughts**  Feeling ecstatic that my program works - [literature](https://www.uniprot.org/uniprot/G5S336) shows that the DnaA box is either TTATCCACA or TTATCAA!

**Link(s) to my work**
- [Final DnaA Box Finder](https://github.com/ClarissaPereira/Finding-Ori/blob/master/Final%20DnaA%20Box%20Finder.py)

### Day 8: 18.07.2020

**Today's Progress**:
* Learnt about GitHub and created my first repo
* Forked this repo & started backdating my log
* Combed through my code and made it more concise and added helpful comments

**Thoughts** GitHub wasn't as intimidating as I thought! I still have to learn how to committ files directly from the command line...

**Link(s) to my work**
- [Finding Ori Repo](https://github.com/ClarissaPereira/Finding-Ori)

### Day 9: 19.07.2020

**Today's Progress**: 
* Learnt how to use Matplotlib 
* Wrote a program that creates a G:C ratio skew plot
* Finished updating my repo

**Thoughts** Matplotlib was surprisingly easy to use but I need to spend more time working with it. I'll brainstorm ways to incorporate it into my nest project.

**Link(s) to my work**
- [skew plotter](https://github.com/ClarissaPereira/Finding-Ori/blob/master/skew%20plotter.py)

### Day 10: 20.07.2020

**Today's Progress**:
* Started Unit 2 of the Bioinformatics Algorithms course
* Created a new repo

**Thoughts** Feeling a bit frustrated trying to write a function that finds motifs in several strings of DNA - it's currently too inefficient so I need to find a way to cut down on runtime. I'm also certain that the way I'm going about it isn't as elegant as it could be but I felt it was important to just get some code out and I can improve it tomorrow. 

**Link(s) to my work**
- [new repo with biology notes and unfinished code](https://github.com/ClarissaPereira/Tick-TOC1)
