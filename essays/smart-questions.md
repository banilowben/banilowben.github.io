---
layout: essay
type: essay
title: "The Good, the Bad and the Ugly of Stack Overflow"
# All dates must be YYYY-MM-DD format!
date: 2024-01-25
published: true
labels:
  - Stack Overflow
---

## First things first

As a first time user of Stack Overflow, I am mostly unaware of the normal proceedings and culture that is the norm for the website. (not counting googling a problem and having the top result be the exact issue answered on Stack Overflow) I also have never participated in a forum before, so this whole thing is unfamiliar to me. I am now tasked with understanding what is an acceptable or ‘smart’  question and what is a ‘not smart’ question (or a loser question). Lucky for me there is a guide by Eric Steven Raymond called “How To Ask Questions The Smart Way.”

[How it feels to read the article](https://www.youtube.com/watch?app=desktop&v=GlA35y0bGQc&embeds_referring_euri=http%3A%2F%2Fsmith-wessonforum.com%2F&feature=emb_imp_woyt)

After indulging in all 10,870 words I am left baffled by the tone of what I just read. This guy comes in hot with a disclaimer that he is NOT responsible for solving the world's technical problems… ok… then he gives us a peek into the demeanor of a real hacker, and what constitutes a loser (or luser). While I agree with the author that people who don’t attempt to try to solve a problem and just expect a free answer from a ‘hacker’ is annoying and a waste of time, the way it comes across is pretty funny. 

## The Ugly

The whole article is filled with details on what the author expects from the people who want help, but I will be listing the headings or a brief summary.

1. Before you ask, try it yourself
2. When you ask, make sure it's in the right forum
3. The same thing as 1
4. Web and IRC forums, go there if you are a newbie
5. As a second step, use project mailing lists
6. Use meaningful, specific subject headers
7. Make it easy to reply
8. Write in clear, grammatical, correctly-spelled language
9. Send questions in accessible, standard formats
10. Be precise and informative about your problem
11. Volume is not precision
12. Don't rush to claim that you have found a bug
13. Grovelling is not a substitute for doing your homework
14. Describe the problem's symptoms, not your guesses
15. Describe your problem's symptoms in chronological order
16. Describe the goal, not the step
17. Don't ask people to reply by private email
18. Be explicit about your question
19. When asking about code, don't just ask people to debug your code
20. Don't post homework questions
21. Prune pointless queries
22. Don't flag your question as “Urgent”, even if it is for you
23. Courtesy never hurts, and sometimes helps
24. Follow up with a brief note on the solution
25. How To Interpret Answers
26. On Not Reacting Like A Loser
27. Questions Not To Ask
28. Good and Bad Questions
29. If You Can't Get An Answer
30. How To Answer Questions in a Helpful Way

Now this may seem like a lot of guidelines to follow, but let's take a look at numbers 11 and 21 and apply them to the author's laundry list of guidelines. We can consolidate this list into 4 guidelines and a helpful tip. 
(Other uhhh tips from the author: [Wiki](https://en.wikipedia.org/wiki/Eric_S._Raymond#Political_beliefs_and_activism))

1. Try the problem before you ask for help
2. Use precise descriptions and stay on topic
3. Don’t harass people for help
4. Be nice
*Try other forums like IRC or mailing list

The nomenclature and flavor of writing described previously is still prevalent throughout some of the rules, however, it is definitely toned down. 

## The Good

Now after all that reading and confusion you might be wondering what kind of questions are on Stack Overflow. Well I am here to tell you that most people definitely did not read this article.

Not that the website isn’t full of great questions such as:

[https://stackoverflow.com/questions/34665134/es6-react-component-instance-method](https://stackoverflow.com/questions/34665134/es6-react-component-instance-method)

The user asks about creating a video component and embed that component into a parent component while still being able to call the play method on the video component. They then provide copy-able code for the video component and the parent component. Beyond that the user also posted a code block for an attempted solution that didn’t work along with its error. 

While these details ultimately didn’t affect the best answer much, which was that they shouldn’t call an instance method of a child component, and instead use an external service to manage that. It did apply to an alternative answer that uses refs to pass a method from a child to a parent, which would be feasible for smaller applications. Both answers benefitted from the additional detail as they both gave code examples that demonstrated the methods they answered with.

## The Bad

The website seems to have a lot more questions like this one than the former:

[https://stackoverflow.com/questions/77878790/divide-2-string-values-and-return-result-as-string](https://stackoverflow.com/questions/77878790/divide-2-string-values-and-return-result-as-string)

This user asks for help dividing 2 string values and returning the result as a string, and provides scant details on the input range, a question about a standard library function, their code and a vague question about the best way to do the problem. This ultimately does lead to a solution as someone just answers with the solution coded ready to be copy and pasted. This isn’t really ideal because most likely this is just a band aid solution and when the program starts bleeding again the user will probably repeat the same process. 

Link to [How To Ask Questions The Smart Way](http://www.catb.org/esr/faqs/smart-questions.html#intro)
