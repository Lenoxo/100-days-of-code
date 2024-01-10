# 100 Days Of Code - Log

<!--
## Examples section

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)

### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)
 -->

## Actual diary - Organized from newer to older dates, like a Stack

<img width="190px" src="https://ih1.redbubble.net/image.1438467887.4273/flat,750x,075,f-pad,750x1000,f8f8f8.u2.jpg">

### Day 18: January 9, 2024

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I did a recall session of the course, and identified that I had knowledge gaps in:
  - BubbleSort
  - QuickSort
  - BFS and DFS
  - heap and trie tree
  - graphs

**Thoughts**: Today I finished very late the recall session, because I had some incidentals that I only complete after late night. And since tomorrow, I'll start learning about Docker.

Also, I didn't write here almost anything today because currently I'm very tired after this day. Hope to get a good night sleep.


### Day 17: January 8, 2024

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Well, I finished this course, and yeah, I'll practice with neovim more after watching the last class. Today I implemented my first LRU cache and it was exciting.
  - **In summary:**
    - This are some notes I took today, hope it helps if you read this:
      <img width="700px" src="https://i.imgur.com/sRGnNQa.png">
    - If you want to build and LRU you would need to combine two data structures, DoublyLinkedList and Maps.
    - And if you need in some part to get a key by it's value (in this case, node) you need to add another map to the recipe.
  - As always, all the exercises I did today, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/15766854901f185d9700b7f9c9db416319149718)

**Thoughts**: I'm getting more comfortable with the pen tablet, my third day using it and at least, I write readable letters now, and I think it is a really good coincidence that the last message from the course by Prime, was my yesterday Thoughts, seek and improve using this tools, to create really good things, and using those great opportunities I have right now, for me, and also, taking into account that there are a lot of people that don't have such opportunities like I have.

I'm really grateful with that part of my life, in fact, without entering in too much details, I know a few people that are currently in a bad situation, for now I can't help them, but if I improve and get better in this field, I'll have resources and ways to help them.

And I think for me completing this course was a good challenge, because currently I still learning English by myself, and I didn't know anything about Typescript, never used it before. It took me more time than expected also because I had knowledge gaps in math, more related to how to manage all the variables using **BigO**. I identified what I would like to improve in Typescript and Math, so maybe I'll checkout the Typescript docs / algebra that I was missing and practice with them the next week.

Ah, yeah, I'll start improving my projects and building new ones while I learn about Docker since past tomorrow, but tomorrow, I'll dedicate to practice and recall the most difficult parts for me from the course.

### Day 16: January 7, 2024

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced two classes, where I implemented the Dijkstra's shortest path search in a Graph Adjacency list, also I learned just briefly what are maps, and how the would be working underneath the hood in JS.
  - **In summary:**
    - JS doesn't have a good way to represent how the work within, but you trust the abstraction of using `{}` and `new Map()`
    - They work using ArrayList and hashing for generating a way to insert data in the structure.
  - As always, all the exercises I did today, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/39d0b6d72b9cd3936911f93e435672fdb6020b51)

**Thoughts**: I'm getting more comfortable with the pen tablet, and I feel I need to seek a way to implement all these algorithms in my current and coming projects, and later on, search for a way to see how the maps work in js, not the abstracted way, but the raw way.

And I had a funny bug when I was implementing the Dijkstra algorithm, because I forgot to iterate and just put an if statement, so it was just pushing to `out, curr` one time, not the full `prev` path:
```js

    const out: number[] = [];
    let curr = sink;
    // right way
    while (prev[curr] !== -1) {
        out.push(curr);
        curr = prev[curr];
    }
    out.push(source);

    return out.reverse();
// --- ---- ---
    const out: number[] = [];
    let curr = sink;
    // wrong way
    if (prev[curr] !== -1) {
        out.push(curr);
        curr = prev[curr];
    }
    out.push(source);

    return out.reverse();
```

### Day 15: January 6, 2024

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced two classes, where I implemented the Breath First Search in a Graph Adjacency Matrix, also, a Depth First Search in a Graph Adjacency List and lastly, I learned what is the Dijkstra's shortest path search in graphs.
  - **In summary:**
    - When you do a DFS in a Graph List, you need to return the path of how you got to the node.
    - This path is not necessary the shortest one, but the first one built as I remember.
    - In Dijkstra shortest path, it iterates looking for the shortest (smaller sum of distance weights) path to the objective node.
  - As always, all the exercises I did today, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/73ac8b36616a1f3ffbbdeefa2998b60068fedd25)

**Thoughts**: Uff, I'm getting used to use the pen tablet but not as fast as I would like, it stills taking me a lot of time writting, drawing and even moving around with the pen. Just a matter of practice and patience for now.

Ah, and taking about the code itself, today I felt it was difficult to visualize how the Dijkstra shortest path works, but after rewatching last class more slowly, I figured out how to visualize it in my mind.

### Day 14: January 5, 2024

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced two classes, where I learned how are graphs commonly represented and how to implement a Breath First Search in a Graph Matrix.
  - **In summary:**
    - Ways to represent a graph:
      - Adjacency List
      - Adjacency Matrix
    - BFS and DFS works very similar in graphs.
    - In BFS, you need to return a path of how you got to the needle, so you need to save your seen indexes and previous indexes to nodes.
  - As always, all the exercises I did, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/d980f47413f7ef40b423840eb74c76b464137104)

**Thoughts**: Today was a challenging day, because I am currently learning how to use a tablet to take notes, but no the one that has screen, I'm taking about the screen less tablet, for now, it's taking me so much time to get used to it.

And also, I had a confusion when I was trying to implement the BFS, and it was a fun mistake when I look back, because I was engaged with the way adjs indexes where looked, I firstly thought that you used adjs indexes **values** to get the prev and seen index in this code.

But later on, I noticed that it wasn't that way, just using the iteration variable `i`, you use that to get the index of the related node.

Here I attach part of today's notes to show this:
<img width="690px" src="https://i.imgur.com/qfj7cot.png">

### Day 13: January 3, 2024 - Happy New Year!

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced one class, where I learned about what are graphs (every tree is a graph, but not every graph is a tree), and key terminology to work with them.

**Thoughts**: Today because I had some private problems, I didn't manage to save time to practice in the morning, I would like to try it tomorrow or past tomorrow to make it work.

### Day 12: January 2, 2024 - Happy New Year!

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced two classes, where I implemented a heap and lastly, learned about tries, and how they are often used for building autocompletion programs.
  - As always, all the exercises I did, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/7ee7cda9807556e4e7cc93ace8440b282db67ebf)

**Thoughts**: Well, yesterday I spent all my time with my family so, my bad, I should save some more time to practice this programming skill.

### Day 11: December 31, 2023

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced one class, where I learned what is a heap, and how they change how you reference your parent and child nodes, without doing it using references like a linked list, but more like an ArrayList.
- Also, I didn't manage to complete the implementation part, so I hope tomorrow I finish it.
- **You can say, priority queue**

**Thoughts**: Today was very difficult to find this hour to practice, every 3 to 4 minutes were interruptions, but I understand why, so no problem, for today I did my best.

### Day 10: December 30, 2023

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced five classes, where I learned how to implement Depth First Search in Binary Search Trees, and the basic theory behind how to find values, insert new nodes and remove them from the binary tree.
  - **Bottom Line:**
    - In a binary search tree a rule that always has to be true, is that the nodes at the left of the current node, should have values <= to the current node value. And the right nodes values, should be > the current node value.
  - As always, all the exercises I did, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/e5164b0b3f20788a9302cb8a2a695e21f54b7b40)

**Thoughts**: Today I had even less time than yesterday, just an hour, but enough time to complete today's challenge, so, I'm happy with it.
### Day 9: December 29, 2023

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced four classes, where I learned what is Search by Breath First in Binary Trees, how to implement it, how to consider using this one or Depth First Search in Binary Trees, and lastly, how to compare binary trees both in structure and values.
  - **Bottom Line:**
    - `In Depth First Search:` You're implicitly using a Stack, so it preserves the shape / order of the structure.
    That makes it perfect to compare by shape Binary Trees.
    - `In Breath First Search:` You're using implicitly a Queue, so it doesn't preserve shape like a Stack would.
  - As always, all the exercises I did, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/a2b36b999d7db7572eddc88fe51cfbc3d8114c40)

**Thoughts**: Today I had less time but advanced all I could, and after I finish this course, I want to implement all of this in my current and coming projects, this last part about Depth and Breath search in Binary Trees captured my attention.

### Day 8: December 28, 2023

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced five classes, where I learned a bit of how to debug a a **DoublyLinkedList**. Also, I learned about what is a tree, what is a traverse a tree, and how to implement tree different ways to traverse a binary tree by depth first:
  - **PreOrder Traverse**, **In Order Traverse** and **PostOrder Traverse**
  - As always, all the exercises I did, are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/33f9ecde3a6b06470d8b8cf91db01194a69f08ee)

**Thoughts**: Today I advanced more, also, I had a bit of time where I organized my notes and also did a bit of priming for the next DS I'll be learning during the next days, if I have more time, I'll organize more my other repos following day 3 advice.

### Day 7: December 27, 2023

**Today's Progress**:

- [**"The Last Algorithm Course You'll Need"**](https://frontendmasters.com/courses/algorithms/): Today I advanced two classes in where I learned how to implement a **DoublyLinkedList**, but I wasn't able to finish today the implementation part. So, it's for tomorrow.
  - Also, I did a brief recall of some stuff I was forgetting, like BinarySearch, the changes are in one of my repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/tree/108ce293120b1d5d352be00f9bccd3c8902ead9e/src/DSA-challenges)

**Thoughts**: I finally understood how recursion works in a basic level, with that being said, I have to admit that one of the things that slows me down for now is also learning how to use vim motions, but I'm getting used to them pretty quickly during these last couple of hours.

### Day 6: December 26, 2023

**Today's Progress**:

- **The Last Algorithm Course You'll Need**: Today I advanced one class in "The Last Algorithm Course You'll Need" and learned the basics of how to use quick sort.

**Thoughts**: Now it's a bit easier for me to visualize how do recursive calls happen, but I still feel that need some practice to fully understand it.

### Day 5: December 25, 2023

**Today's Progress**:

- **The Last Algorithm Course You'll Need**: I dedicated today to practice and understand better recursion, and now I feel that, in an easy problem I understand how to apply it, also, all the exercises I did with it, are in one of my github repos: [click](https://github.com/Lenoxo/HTML-CSS-JS-challenges/blob/main/src/JS-challenges/recursion.js)
  - Resources I used today:
    - [Google DataStructures and Algorithms free course](https://techdevguide.withgoogle.com/paths/data-structures-and-algorithms/#sequence-9)
    - [¿Qué es la Recursividad?](https://www.youtube.com/watch?v=YwRjEOFxvO0)
    - chatgpt for creating some of the challenges.

**Thoughts**: I really feel that is difficult for now to visualize how the functions recurse themselves in every case, I still don't get it for now.

### Day 4: December 24, 2023 - Merry Christmas!

**Today's Progress**:

- **The Last Algorithm Course You'll Need**: Today I advanced just one class, and also, because currently, after doing the exercise, I'm even more confused about how to implement recursion, so, later or next day, I'll practice some time with other resources to understand better how recursion works.

**Thoughts**: Yesterday, I missed a day, for something that was out of my control at that time, more specifically, working and helping with a relative throw all day, and when I finished, I just had time to go to sleep and that's it.

Now, I think I could handle it better, waking up earlier to practice 1 hour before anything else in my day.

### Day 3: December 22, 2023

**Today's Progress**:

- **The Last Algorithm Course You'll Need**: Today I advanced three classes; Data Structures Q&A, Recursion and Path Finding: Base Case. (Which is the first part of recursion implementation)

  - Also, in this same topic, I found a great playlist in YouTube where a developer explains how different Data Structures are implemented in Typescript: [DataStructures List](https://www.youtube.com/playlist?list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd)

- **Improving my current projects**: According to an excellent video I've seen today: [Link to the video](https://www.youtube.com/watch?v=N7pXEy5i-Vs), now I'll be improving continuously all my current projects adding / setting up this:

  1. Code clarity: Making consistent the way I format code

  - Unit testing: Just for the critical features.

  2. Good branching: Using an issues / functionalities based branching and PR
  3. Good issue management: Using mainly Github Projects
  4. CI / CD: In some projects I have this already

  - Today, I advanced with that issue management in [DevShop API](https://github.com/Lenoxo/DevShop)

**Thoughts**: Today I advanced more than yesterday, and also learned how, a project is managed professionally, thanks to a great resource by Bob Fornal, he always has something valuable to teach.

Well, other thing I would like to mention is that I'm still kind a newbie with Twitter. So 1 step at a time.

### Day 2: December 21, 2023

**Today's Progress**:

- **The Last Algorithm Course You'll Need**: Today I advanced one class; ArrayBuffer or also called Ring Buffers.

**Thoughts**: Today I did two things:

- Accidentally erased my last week notes from the course and restoring them from scratch took me most of today's hour.
  - It happened because I forgot to save a backup of the .mozilla folder
- Trying to understand how that recycle of space works on the Ring Buffers, actually, I still don't understanding it well, so I'll search more about them tomorrow.
  Also, I really wanted to advance more but today I didn't manage well my time, so, I know what I have to prioritize.

### Day 1: December 20, 2023

**Today's Progress**:

- **Async-Landing**: Add links to my updated social media, own website and improving navbar links.
- **The Last Algorithm Course You'll Need**: Today I advanced two classes; Arrays vs Linked Lists and ArrayList.

**Thoughts** I wonder if I should share my current notes taken in Draw.io, because until I finish a course, they're really changing every single class / research I made.

### Day 0: December 18, 2023

**Today's Progress**: Set up the learning plan, I'll do the following during the next 100 days:

1. **Learning about DSA**: Using the free course from Frontend Masters [The Last Algorithm Course You'll Need](https://frontendmasters.com/courses/algorithms/)
2. **Learning about Docker**: Using the Platzi's Docker course [Curso de Docker](https://platzi.com/cursos/docker/)
3. **Learning about Typescript**: Using mainly Typescript docs and other resources if I hit a hard problem [Typescript Docs](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
4. **Building side projects**: This one is hard to predict, because I have some ideas but none of them concrete, so during the above learning phase, I'll use some time to search for ideas of projects that could be a rewarding challenge to build.

   - **A webchat app**: Because currently I don't know how to work with websockets.
   - **Improving my current projects**: There are things I can improve of how I tackle new problems and issues.

**Thoughts:** I know that I don't need a perfect plan from day 0, but a flexible one, due to my current schedule.
