# Graphs: DSA Review

> [Back to Home](../README.md)

## 7 tips to ace a programming interview

1. Take a few minutes:

```1
Don’t waste precious minutes trying to fill the silence by saying everything you’re thinking, while simultaneously trying to solve the problem in your head.

instead, wait until the interviewer is done explaining the problem. Ask any clarifying questions, and then tell your interviewer:

“Okay, got it. If it’s okay with you, I’m just going to take a minute or two here and think about the problem, and then I’ll start talking.”
```

2. Write down the steps of the solution.

```2
Even after you have an idea of how to attack the problem, don’t start writing code down. Write down the general steps of how you will solve it on one side of the whiteboard, where it’s visible but won’t get in the way. You don’t need to be verbose, just get the steps in order and somewhat readable.

//Start at middle of array.
//Keep variables tracking left and right boundaries of search area.

//If value equal to search_val, return true.
//If left and right boundaries are adjacent, return false.
//If value bigger than search_val, go halfway towards left boundary, and move the right boundary along with us.
//If value smaller than search_val, go halfway towards right boundary, and move the left boundary along with us.
```

3. Write pseudocode first.

4. Don’t sweat the small stuff.

```md
Programming interviews are not about how well you’ve remembered your semicolons, nor are they about being able to remember all of the flags on a TCP packet. They’re about demonstrating depth and breadth of knowledge, personality strengths, and problem-solving abilities. If you make a mistake, it’s okay. Brush it off and move on.

If you can’t remember something like this, it’s often acceptable to say that you’d look it up.

> Let’s be honest, half of being a programmer is knowing how to Google stuff and how to interpret search results. We use the internet as a giant cache for all the information that we “almost” remember but don’t bother to, since we can just look it up at any time. It’d be hard to fault an answer like the one above. So don’t waste time memorizing keywords in your interview prep. Focus on the big picture.
```

5. Sit down. Be humble.

```3
A programming interview isn’t just a written exam. It’s an assessment of your programming abilities, and there are plenty of things that fall into that category beyond mere coding prowess. For example:

Are you able to express your ideas and solutions clearly and effectively?
Do you treat the interviewer with respect?
How do you accept criticism (technical, constructive or otherwise)?
Are you able to collaborate with others to come up with solutions?
Do you communicate in a way that demonstrates empathy?
Are you honest (especially about yourself)?
If you are given criticism in an interview, you need to take it and be grateful for it. No snide remarks, no “oh, I was gonna do that in a second anyway”, no anger or raised voice. The interviewer has their opinion, and they didn’t have to share it — they could’ve just written it down silently and rejected you as a candidate later. They’ve given you a chance to correct course because they think you’re worth it, and they’ve extended an opportunity for you to demonstrate how you accept feedback from your peers. Don’t waste it.
```

6. Come prepared.

7. Review your work.

```4
You won’t always finish questions in the time permitted, but occasionally you’ll have extra time after coming up with a solution. If this happens, it’s tempting to say “Well, I’m done!”. Interviews are stressful and we want them to be over as fast as possible. This is reasonable, but:

Think about how silly you look if your solution is not right.

In particular, focus on these two areas, as they receive heavy scrutiny in interviews:

Algorithmic efficiency. Have you found the fastest and most optimal solution given the requirements? Take some time and consider other approaches. It’s worth noting two things here: 1) If the problem involves a sorted dataset, you can bet your pants there’s a solution involving ` O(log(n)) lookup time (even if there’s additional cost, the total complexity will still contain the log(n), for example, O(n * log(n)) if iterating over an array, as sorting algorithms do), and 2) For a disgustingly large number of programming interview questions, the answer involves a hash table and O(1) lookup time — so if you’re seeking a better algorithm, try a hash table.
Correctness. Sure, you’ve solved for the simple, easy use case, but have you checked for edge cases? Off-by-one errors? Issues with negative numbers or empty arrays or missing keys or strings with weird patterns of characters? Maybe you won’t find all of them, but failing to at least LOOK for edge cases before declaring your solution to be correct is a pretty hefty mistake in an interview.

```

> [Back to Home](../README.md)
