# Lecture 1: The Motivation & Applications of Machine Learning
### Instructor
Okay. Good morning. Welcome to CS229, the machine learning class. So what I wanna do today is just spend a little time going over the logistics of the class, and then we'll start to talk a bit about machine learning.

By way of introduction, my name's Andrew Ng and I'll be instructor for this class. And so I personally work in machine learning, and I've worked on it for about 15 years now, and I actually think that machine learning is the most exciting field of all the computer sciences. So I'm actually always excited about teaching this class. Sometimes I actually think that machine learning is not only the most exciting thing in computer science, but the most exciting thing in all of human endeavor, so maybe a little bias there.

I also want to introduce the TAs, who are all graduate students doing research in or related to the machine learning and all aspects of machine learning. Paul Baumstarck works in machine learning and computer vision. Catie Chang is actually a neuroscientist who applies machine learning algorithms to try to understand the human brain. Tom Do is another PhD student, works in computational biology and in sort of the basic fundamentals of human learning. Zico Kolter is the head TA — he's head TA two years in a row now — works in machine learning and applies them to a bunch of robots. And Daniel Ramage is — I guess he's not here — Daniel applies learning algorithms to problems in natural language processing.

So you'll get to know the TAs and me much better throughout this quarter, but just from the sorts of things the TA's do, I hope you can already tell that machine learning is a highly interdisciplinary topic in which just the TAs find learning algorithms to problems in computer vision and biology and robots and language. And machine learning is one of those things that has and is having a large impact on many applications.

So just in my own daily work, I actually frequently end up talking to people like helicopter pilots to biologists to people in computer systems or databases to economists and sort of also an unending stream of people from industry coming to Stanford interested in applying machine learning methods to their own problems.

So yeah, this is fun. A couple of weeks ago, a Studentactually forwarded to me an article in "Computer World" about the 12 IT skills that employers can't say no to. So it's about sort of the 12 most desirable skills in all of IT and all of information technology, and topping the list was actually machine learning. So I think this is a good time to be learning this stuff and learning algorithms and having a large impact on many segments of science and industry.

I'm actually curious about something. Learning algorithms is one of the things that touches many areas of science and industries, and I'm just kind of curious. How many people here are computer science majors, are in the computer science department? Okay. About half of you. How many people are from EE? Oh, okay, maybe about a fifth. How many biologers are there here? Wow, just a few, not many. I'm surprised. Anyone from statistics? Okay, a few. So where are the rest of you from?

### Student
iCME.
### Instructor
Say again?

### Student
iCME.

### Instructor
iCME. Cool.

### Student
*inaudible*

### Instructor
Civi and what else?

### Student
*inaudible*

### Instructor
Synthesis, *inaudible* systems. Yeah, cool.

### Student
Chemi.

### Instructor
Chemi. Cool.

### Student
*inaudible*

### Instructor
Aero/astro. Yes, right. Yeah, okay, cool. Anyone else?

### Student
*inaudible*

### Instructor
Pardon? MSNE. All right. Cool. Yeah.

### Student
*inaudible*

### Instructor
Pardon?

### Student
*inaudible*

### Instructor
Endo —

### Student
*inaudible*

### Instructor
Oh, I see, industry. Okay. Cool. Great, great. So as you can tell from a cross-section of this class, I think we're a very diverse audience in this room, and that's one of the things that makes this class fun to teach and fun to be in, I think.

So in this class, we've tried to convey to you a broad set of principles and tools that will be useful for doing many, many things. And every time I teach this class, I can actually very confidently say that after December, no matter what you're going to do after this December when you've sort of completed this class, you'll find the things you learn in this class very useful, and these things will be useful pretty much no matter what you end up doing later in your life.

So I have more logistics to go over later, but let's say a few more words about machine learning. I feel that machine learning grew out of early work in AI, early work in artificial intelligence. And over the last — I wanna say last 15 or last 20 years or so, it's been viewed as a sort of growing new capability for computers. And in particular, it turns out that there are many programs or there are many applications that you can't program by hand.

For example, if you want to get a computer to read handwritten characters, to read sort of handwritten digits, that actually turns out to be amazingly difficult to write a piece of software to take this input, an image of something that I wrote and to figure out just what it is, to translate my cursive handwriting into — to extract the characters I wrote out in longhand. And other things: One thing that my students and I do is autonomous flight. It turns out to be extremely difficult to sit down and write a program to fly a helicopter.