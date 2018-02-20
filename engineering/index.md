### Engineering Steps

Every engineering process consists of several steps:

 1. **<u>Define</u>** a general problem or issue to be solved
 1. **<u>Analyze</u>** the problem in detail, identify the root cause
 1. **<u>Investigate</u>** and **<u>Evaluate</u>** all available solutions
 1. **<u>Select</u>** the best solution, or propose a new one if none of the existing solutions can be applied
 1. **<u>Implement</u>** selected solution

This simple and quite boring process of problem solving is the core principle of **engineering**. In many cases, this process is not intuitive and very hard to follow. If a solution was used everywhere for too long, nobody has the incentive to start looking for alternatives. For new, important, long-term projects, this should be different. Current solutions should always be questioned, challenged, evaluated and improved upon.

#### Simple example of engineering:

1. **Define** the problem in general:
  * It's dark at night, people can't work
1. **Analyze** and identify the root of the problem:
  * Artificial light source is needed, to emulate the function of sun at night
1. **Investigate** and **Evaluate**:
  * As available solutions, people use candles and petrol lamps. They have some disadvantages:
        1. Limited brightness of emitted light
        1. Lot of regular maintenance needed
        1. Bad smell
        1. Every now and then a house burns down and people die
  * Is it possible to make an efficient workarounds for these disadvantages?
        1. The light intensity of a candle can not be pumped up very much
        1. Burned candles need to be replaced, petrol lamps need petrol. No workaround.
        1. Petrol stinks. Filling a lamp with whisky is unacceptable.
        1. You might make fire escapes mandatory, but that's about it
1. **Select** or propose a better solution:
  * Create new artificial light source without all these disadvantages: a device that burns bright, while preventing the actual fire, e.g. by the lack of oxygen
1. **Implement** the selected solution

### Problem Definition

Simple description of the problem in general. This might not be specific enough to be directly solved, or any possible solution might not be obvious at first. This definition needs to be further analyzed in detail and elaborated on, see **Analyze** below. To this category belong problems like: "Earth gets warmer every year", "Energy production does not fit the demand curve", or "Computers start too slow".

### Analyze

More detailed look at the problem at hand. Find a root cause of the problem, before trying to find a solution. An nice example of this step is shown in the documentary "[Freakonomics](http://www.imdb.com/title/tt1152822/)", looking at root causes of high crime rate in the USA. Result of this step should be a formulation of the problem in a way that is solvable, like "The level of greenhouse gasses is too high", "Produced energy needs to be efficiently stored until required", or "Computer boot stage needs to be parallelized for speed".

### Evaluation

The _investigation_ and _evaluation_ of problem solutions is at the center of engineering. It is the most important, and the most neglected part of the engineering process. It is unlikely for anyone to implement a better solution, without knowing everything about **all** existing applicable ones. For complex problems, proper investigation might become extremely hard. This boring, lengthy, non-productive investigation/evaluation process ist the root cause of failed projects, when not done properly. 

Computer software, as every other result of engineering, is made to solve a particular problem. Something that is an issue for many people, for a company, or for you personally. What parameters for new solutions are usually **evaluated by engineers**? When comparing software, that usually means:

 * Safety
 * Stability
 * Reliability
 * Efficiency
 * Maintainability
 * Internal design
 * Cost
 * ...

This implies a high level of knowledge for all evaluated systems. Since it is hard to learn and compare everything this way, **non-engineers** often use much simpler reasons when choosing technology, like:

 * It came preinstalled
 * It intuitively fells right
 * This is what I know
 * This is what I've always used
 * This is what everybody else is using
 * This is what somebody on the forum recommended
 * ...

Unfortunately, these reasons are not good enough to make a meaningful choice. Not even all of them together. While this way you might end up with a sufficient solution, it would probably be far from optimal.

### Selection

Based on previous evaluation, one solution has to be selected for implementation. Alternatively, a new solution can be proposed. Given the complexity of the problem, analyze and evaluation, this might be a real challenge. While perfect or optimal solution is hard to achieve, it is always important to strive for perfection:

>"Perfection is attained not when there is nothing more to add, but when there is nothing more to remove."
>
><cite> - Antoine de Saint Exupéry, Terre des Hommes (1939) [quote](https://en.wikiquote.org/wiki/Antoine_de_Saint_Exup%C3%A9ry)</cite>

Simply put, **perfection** is a process of stripping away the unnecessary stuff. In software engineering, this process is closely bound to the main Unix rule: "do one thing, do it well". That translates to the smallest possible amount of functionality in a single program, so that the result can independently perform only a single task. Keeping pieces of software clearly separated and independent on each other helps other engineers and developers to understand it and reuse it. This [modularity](https://en.wikipedia.org/wiki/Modular_programming) has the effect of stability, reliability, code readability and maintainability.

To _select_ and properly _describe_ a software solution is in essence represented by [requirements engineering](https://en.wikipedia.org/wiki/Requirements_engineering). Ideally, the result of the _analyze_, _investigation_, _evaluation_ and _selection_ steps should form a base of a [requirement specification](https://en.wikipedia.org/wiki/Software_requirements_specification), as an ideal form of input for _implementers_/_developers_.

### Implementation

The _implementation_ process is least relevant to engineering. While "_implementing_" usually means doing something new, exciting and cool, sometimes even [animals](https://www.psychestudy.com/behavioral/learning-memory/trial-error-learning) (or [Edison](https://www.uky.edu/~eushe2/Pajares/OnFailingG.html)) can implement a solution by [trial and error](https://en.wikipedia.org/wiki/Trial_and_error) given the proper boundaries defined by previous engineering steps. This creative, fun, "hands-on" part of engineering can be seen as a separate process. It does not necessarily involve engineers, but is often done by experts specifically trained to _develop_ and _implement_ solutions. In the world of IT, these specialists are commonly referred to as _software developers_.

## Skills

#### Developer education

In a _software developer_ training, you learn how to use a programming language to _implement_ a solution: make a "[hello world](https://helloworldcollection.github.io)", sort an array, process user input, handle errors... This learning process is important to know your tools, to work efficiently, to get a feeling for what is actually possible. Talented developers learn to write cleaner, readable, [modular](https://en.wikipedia.org/wiki/Modular_programming), better documented code, implement more efficient algorithms, master more programming languages... Without this knowledge, creating high quality software would be impossible.

#### Engineer education

While some developer training is always a part of software engineering education, this is later expanded. Instead of just implementing a given solution, you are given a problem to _solve_. You are expected to _analyze_ the problem and _find_ a solution first, before you proceed with implementation. If you studied engineering of any sort, or wrote any academic paper, you know that there is a certain procedure that has to be followed. What is the problem you are trying to solve? What other solutions are available? What properties do they have? Why is your solution necessary, wouldn't something else be better? To proceed without answering these questions will surely make you fail. It is not good enough to say what path did you choose, you have to _explain_ why that makes sense.

## Conclusion

Wikipedia defines **development** as:
>"Software **development** in a broader sense may include any activities that result in software products"<sup>([1](https://en.wikipedia.org/wiki/Software_development))</sup> 

and also **engineering** as:
>"Software **engineering** is an engineering discipline that is concerned with all aspects of software production"<sup>([2](https://en.wikipedia.org/wiki/Software_engineering))</sup>

The usual definitions are rather confusing, blending _development_ and _engineering_ together. While both engineers and developers play equally important role, and big part of their knowledge base overlap, every group is better suited for a specific task. Many times the difference in training and skills is not properly recognized by product owners and team leaders, not just by Wikipedia. Consequently, engineering jobs are wrongly assigned to developers, resulting in whole teams working on solutions that are not optimal, or obsolete before they even started.

To illustrate the main difference between **software engineering** and **development**: when faced with general problems like "What programming language should I choose?", "What [init system](/init) should I use?", or "What webserver is the best?", a software **engineer** follows the simple [process](#engineering-steps) to get an optimal answer. Software **developer** immediately [implements](#implementation) a very smart, cool, even elegant solution, possibly solving things that were never a problem, introducing new issues on the way (see [systemd](/init/#systemd) as an example). This creates frustration on both developers and users side, completely unnecessarily.

<a href="https://creativecommons.org/licenses/by/4.0/"><img src="../cc-by.png" align="right" style="padding:30px;"></a><br>
<p class="footer">
cloux@rote.ch (2018)
</p>
