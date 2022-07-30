# hyperstep

Process and Agent Based Music.
## [Agent Self Regulation](https://github.com/a-sumo/hyperstep/blob/main/agent_self_regulation.ipynb)
  In this notebook, I attempt to recreate organic temporal patterns and syncopation by modeling composition as an agent regulating internal properties through a set of sound-associated actions. The key insight is to assign opposite effects to kicks and snare/claps. The direction of these effects has been determined arbitrarily, although I believe there is a *algebra of processes* that can be derived from real-world observations.  
  I have done my best to derive the magnitude of the actions' effects through the analysis of audio features. 
  The direction and magnitude of the actions' effects can be greatly improved by integrating algorithms that estimate impact forces from sound such as [DiffImpact](https://openreview.net/forum?id=wVIqlSqKu2D)
  
Here is one of the model's outputs:
<details>
  <summary>Agent Self Regulation Example </summary>
  
   [Agent Self Regulation Example 1](https://user-images.githubusercontent.com/75185852/174502800-3452d939-b6da-4998-90c9-3c02c7bb5346.mp4)
</details>

UPDATE(July 2022): 
The self-regulation model is superficial and results in an overcomplicated implementation.  
**"The more factored a theory and the more emergent the observed phenomena from the theory, the more satisfying the theory."**  
*Daniel Shawcross Wilkerson, [Harmony Explained: Progress Towards A Scientific Theory of Music (2012)](https://arxiv.org/abs/1202.4212v1)*

A more appealing approach would be to consider drums as locomotive processes.[1]
By:
-providing an agent with a goal in space and by using drums as actions that induce motion
-carefully designing the agents' environment, 
we should derive rich and organic drum patterns.  

The main advantage is that the user would compose in a semantically rich and intuitive space(3D world) populated by intuitive objects (entities) rather than a space of buttons, knobs and MIDI files.   

I think this approach shows promise to be more satisfactory but it imposes the setup of a simulation environment and the refinement algorithms that recover semantically relevant physical properties from sounds.  

The former is something I'm working on using Bevy and its ECS framework. In fact, I believe an agent-oriented approach to 3D content-creation is required to tackle the complex and diverse multi-scale processes at the origin of musical patterns and popular styles.  

For the latter, I prefer to couch potato sit and wait for the algorithms to improve.[2]

[1][Yuri Broze. Animacy, Anthropomimesis, and Musical Line(2013)](https://etd.ohiolink.edu/apexprod/rws_etd/send_file/send?accession=osu1367425698)

[2][How to pick problems, Doug L. James (SIGGRAPH 2021)](https://youtu.be/fCE5tcnB3co?t=823)
