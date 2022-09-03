# hyperstep

Process and Agent Based Music.
## [Agent Self Regulation](https://github.com/a-sumo/hyperstep/blob/main/agent_self_regulation.ipynb)
  In this notebook, I attempt to recreate organic temporal patterns and syncopation by modeling composition as an agent regulating internal properties through a set of sound-associated actions. The key insight is to assign opposite effects to kicks and snare/claps.
  
 The direction of these effects has been determined arbitrarily, although I believe there is a *algebra of processes* that can be derived from real-world observations.  
 I have done my best to derive the magnitude of the actions' effects through the analysis of audio features. 
 
 The direction and magnitude of the actions' effects can be greatly improved by integrating algorithms that estimate impact forces from sound such as Diffimpact. [[3](#diffimpact)]
  
Here are some of the model's outputs:
<details>
  <summary>Examples:</summary>
  
   [Example 1](https://user-images.githubusercontent.com/75185852/174502800-3452d939-b6da-4998-90c9-3c02c7bb5346.mp4)
  
   [Example 2](https://user-images.githubusercontent.com/75185852/188247039-9e68f585-80b3-4030-90c9-8cce4db12a0c.mp4)
  
   [Example 3](https://user-images.githubusercontent.com/75185852/188247570-71d7c998-c87e-41f2-b4ac-0786fa5533e7.mp4)
  
</details



>

The self-regulation model is fairly superficial and results in an implementation that is complicated and hard to control.  
**"The more factored a theory and the more emergent the observed phenomena from the theory, the more satisfying the theory."**  
*Daniel Shawcross Wilkerson, [Harmony Explained: Progress Towards A Scientific Theory of Music (2012)](https://arxiv.org/abs/1202.4212v1)*

A more appealing approach would be to consider drums as locomotive processes. [[1](#animacy)]  
By providing an agent with a *goal* in space, coupled with the use of drums as *actions that induce motion* and by carefully designing the *agent's environment*, we should derive rich and organic drum patterns.  

The main advantage is that the user would compose in a semantically rich and intuitive space(3D world) populated by intuitive objects (entities) rather than a space of buttons, knobs and MIDI files.   

However, this approach imposes the setup of a simulation environment and the refinement algorithms that recover semantically relevant physical properties from sounds.  

The former is something I'm currently working on.

For the latter, I prefer to sit on a couch like a potato [[2](#pick-problems)] and wait for the research area to be sufficiently mature.
<a id="animacy">
  
  [1][Yuri Broze. Animacy, Anthropomimesis, and Musical Line(2013)](https://etd.ohiolink.edu/apexprod/rws_etd/send_file/send?accession=osu1367425698)
  
</a>

<a id="pick-problems">
  
  [2][How to pick problems, Doug L. James (SIGGRAPH 2021)](https://youtu.be/fCE5tcnB3co?t=823)
  
</a>

<a id="diffimpact">
  
  [3][Samuel Clarke, Negin Heravi, Mark Rau, Ruohan Gao, Jiajun Wu, Doug James, Jeannette Bohg,  
DiffImpact: Differentiable Rendering and Identification of Impact Sounds(2021)](https://openreview.net/forum?id=wVIqlSqKu2D)
  
</a>
