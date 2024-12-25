# 示例流程图
something here
```mermaid
flowchart TB

Ir[\"tasks,
    requirements..."\]--
1) collect magazine papers on this scenario
2) read pictures/summary texts/basic concepts
--> As([Know the general scenario])  
-- choose the suitable parts 
    and follow them
--> Aos    



Ir --
1) collect technical papers on this topic
2) read problem formulations/math notations
--> Apb([Know the general problem]) 
-- choose the suitable parts 
    and follow them
--> Aos  


Io[\"your own ideas,
sth you want to do..."\]--
1) Collect relevant technical reports/papers
2) Read the Abstract/Intro to understand the rationale
3) If match, understand the mathematical derivation
--> Aot([Know what new techniques to use]) 


Ir --
"1. Reread the technical papers on this topic
2. Read techniques and methods
3. Search and understand the rationale
4. Ignore the technical details"
--> At([Know the techniques used])    


Aos -- 
1) write your own solutions
2) state the background and problems
3) summarize your contributions
4) refine the writing 
--> Aopp

Aot -- 
new solutions naturally emerge
during integration
--> Aos([design your own technical solution]) -- 
1) choose suitable opensorce programs
2) run and understand their implementations
3) program your own parts
4) design new experiments 
   to show your advantages
--> Aopg



Aopg -->|adjust solutions
         based on results| Aos

At --
1) Reread the technical papers on this topic
2) read/summarize the comparative methods
3) read/summarize the datasets/simulation setting
4) read/summarize the main metric
5) read/summarize the experiment types
6) read/summarize the form of results
--> Ae([know the general experiment settings])
-- choose the suitable parts 
    and follow them
--> Aopg([program your own solutions 
        and conduct experiments])
    
Aopg --
1) choose the experiment results
2) show them in proper forms
--> Aopp([write your own papers])


Aopp --wait for months-->Aopps([Submit,
                     Reply to Reviews,
                     Publish])



