# Research Workflow
This repository presents and organizes workflows for young researchers conducting their studies. 
It includes detailed goals and the steps. 
These ideas come from my reflections as a PhD candidate on how to approach research effectively. 
Fellow researchers are welcome to share their workflows and propose possibilities for 
improving these processes.

## Basic Elements
The complete research process includes:

1. **Restrictive Known Conditions**  
   The tasks or requirements, shown as *prisms*.

2. **Intermediate Targets**  
   The detailed goal or target, shown as a *rounded-corner matrix*.

3. **Multiple Steps**  
   Multiple necessary steps needed to achieve each target, represented by *text on arrows*.

Below is a visual representation of the basic elements:
```mermaid
flowchart LR
I[\inputs\]--multiple steps-->A([target])
```
---
## Technological Innovation Workflow
For junior researchers (e.g., PhD candidates), the research work starts with *some given project requirements* and 
ends with *the publication of a paper*. Innovations and contributions primarily lie in technical solutions.

I reflected on and summarized my workflow, as shown below. 
Interestingly, the flowchart takes on a shape that’s wide in the middle and narrow at both ends. 
This shape reflects the essence of my work: starting with one or two compelling ideas, 
diving into extensive research, brainstorming, designing, and experimenting, 
and finally distilling everything into a polished paper.

The journey is long, often involving repeated steps. 
It can be fun at times, tedious at others, and occasionally challenging. 
Yet, I find myself traversing this path over and over.
In this journey, I often grapple with feelings of spiritual loneliness and a sense of being lost. 
Yet, when I take a moment to pause and reflect on the path I’ve traveled and the progress I’ve made, 
a sense of relief washes over me. 
It’s in these moments of clarity that I find renewed courage and 
determination to continue moving forward.

I'm always curious about how others do research and look for possibilities to improve productivity. 
So, welcome to share.

```mermaid
flowchart TB

Ir[\tasks,
    requirements...\]--
1.collect magazine papers on this scenario
2.read pictures/summary texts/basic concepts
--> As([Know the general scenario])  
-- choose the suitable parts 
    and follow them
--> Aos    



Ir --
1.collect technical papers on this topic
2.read problem formulations/math notations
--> Apb([Know the general problem]) 
-- choose the suitable parts 
    and follow them
--> Aos  


Io[\"your own ideas,
    sth you want to do..."\]--
1.Collect relevant technical reports/papers
2.Read the Abstract/Intro to understand the rationale
3.If match, understand the mathematical derivation
--> Aot([Know what new techniques to use]) 


Ir --
1.Reread the technical papers on this topic
2.Read techniques and methods
3.Search and understand the rationale
4.Ignore the technical details
--> At([Know the techniques used])    


Aos -- 
1.write your own solutions
2.state the background and problems
3.summarize your contributions
4.refine the writing 
--> Aopp

Aot -- 
new solutions naturally 
emerge during integration
--> Aos([design your own technical solution]) -- 
1.choose suitable opensorce programs
2.run and understand their implementations
3.program your own parts
4.design new experiments 
   to show your advantages
--> Aopg

Aopg -->|adjust solutions
         based on results| Aos

At --
1.Reread the technical papers on this topic
2.read/summarize the comparative methods
3.read/summarize the datasets/simulation setting
4.read/summarize the main metric
5.read/summarize the experiment types
6.read/summarize the form of results
--> Ae([know the general experiment settings])
-- choose the suitable parts 
    and follow them
--> Aopg([program your own solutions 
        and conduct experiments])
    
Aopg --
1.choose the experiment results
2.show them in proper forms
--> Aopp([write your own papers])


Aopp --wait for months-->Aopps([Submit,
                     Reply to Reviews,
                     Publish])
```
Even with the exact same steps, different researchers will produce completely different results. 
Each step is a different experience for the individual. 
Therefore, the uniqueness of research can be reflected in all aspects of a research work. 
As a young researcher, I think an important lesson is to see yourself at every step.

Email: suemonsuemon@gmail.com
