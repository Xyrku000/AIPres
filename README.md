# AIPres

I found an article by Wei Wang, Yingwei Liu, Zheng Wang, Gefei Hao, and  Baoan Song entitled "The way to AI-controlled synthesis: how far do we need to go?". I then presented this article in my AI class as a final project. These are my notes on the article. The associated PowerPoint is attached.


My article covered the use of AI in chemical synthesis. Chemical synthesis is the discovery
of new and useful molecules, such as drugs or construction materials. Throughout history, this 
synthesis has been done manually and by human intuition. However, now we have the ability to 
use artificial intelligence to automate what can be a time-consuming trial-and-error process. This
shift to automation is challenging — only in this decade are we looking to see AI chemical
synthesis adopted by labs on a large scale.

	Interest in this use for AI has spiked since 2015. Some topics in AI may not be quite in vogue 
nowadays, but it is clear how AI-driven chemical synthesis is a meaningful subject in the
scientific community. Mostly the reason for this is found in how efficient AI can be performing
routine tasks with various chemicals, all while not making as many mistakes. What might result 
from this ability? One story on The Verge by Justine Calma is titled, "AI suggested 40,000 new
possible chemical weapons in just six hours". This topic led me to find my article because I was
fascinated by this unique manner in which the human race could be destroyed. And it isn't the 
kind of disaster we've been preparing for!

	There are three major components of an AI-controlled system: hardware, software, and the automation control component (ACC). The first of these is the mechanical hardware which the AI controls to do its synthesizing. Here we have multiple modules, each for different stages of the synthesis process: the reactor, the reagent storage, the purification module, the waste storage, and the reaction analytic module. These are fairly intuitive to the reader, but it should be noted that the reactor is the hands of the system, completing all its tasks. The reaction analytic module's purpose is a little confusing because it simply collects data and does not analyze it the way one might assume — it is still primarily a hardware device. Connected to the hardware is the ACC, which is like a motherboard, taking physical data and transmitting it to the software for the AI to use, and vice versa. The ACC makes it possible for the chemists to not need to supervise the lab directly. Lastly, various software modules provide the backend to the system. Basically, the software is a regular machine learning loop structure using training data and feedback to formulate new chemical synthesis commands which the Reaction Prediction Module directs to the operational side of the system.
  
	From a business perspective, these technical features of a hypothetical AI synthesizer are all
good as long as it works well. This article examined some of the hardware and software faults of
the system, depicted as two distinct subproblems on the way to widespread adoption of the 
technology. Some of the common hardware issues are blockages in the modules by rogue
molecules which condense into an impenetrable mass, which may not be immediately
discovered. Components such as 3D printers can fail due to lack of customization for the specific
experiments done, and can fail. Software issues are present as well. Some training data is not
available from the Internet and what is available may not be intended for an AI agent to use. 
Additionally, chemists in smaller labs are not usually trained in the technical user interfaces of 
the software they are using. We cannot assume that these scientists are necessarily as computer-
savvy as the ones who developed its AI. Again, the lack of customization in the software further
hinders labs from fully embracing this new technology. Lastly, the system could in the future use
the negative feedback it receives from failed experiments to improve its syntheses. In general, 
AI-controlled synthesis is like a young teenager starting their first job: fully operational and
somewhat competent but slow and naive — not the most hireable candidate yet.

Introduction
—Can AI-driven organic synthesis create lethal bioweapons?

Hardware
Configuration
Storage Modules
—Can be adapted easily for handling by reactor.
Reactor
—Actually does not react with anything, and is not nuclear.
Reaction Analytic Module
—Performance monitor of an ongoing reaction for immediate feedback or interruption.
Purification Module
—Likely easily automated.
Device Customization Module
—The thick blue arrows in the diagram suggest that this module is very important. However, it is unclear if this customization is effected at every operation.
Applications & Flaws
—Clogging can be irreversible and expensive!

Software
Configuration
Reaction Information Module
—This is the Knowledge Base for the AI.
Reaction Prediction Module
—AI Core; quantum-based prediction (not discussed) for forward-synthetic analysis
Reaction Operation Information Module
—Collects data from the experiment
Feedback Recording Module
—Data from here is used to add to the knowledge base and also imposed directly into the ongoing experiment.
Automation Control Component
—This is basically a motherboard. However, the hardware section is expansive in comparison with a regular desktop computer.

Perspective & Outlook
Hardware
Adaptability
—This appears to be a massive undertaking for a lab using many chemicals. There are limitless chemical reactions with limitless pH, mass, temperature, presure, density, and electrochemical combinations!
Customization
—It seems like the technology should be streamlined with a UI that can easily be set to a certain lab's chemical inventory.
Automaticity
—What is the point of an AI to do these operations for us, if we are required to hold its hand through the process?
Speed
—Part of why AI-controlled synthesis is discussed is for its speed. If a reactor is slower than manual operators, then the reason for the AI is weakened.
Conveniency
—As in the last point, the idea is that the technology should make chemical synthesis easier, not harder.
Cost
—Labs will not care if the AI is supremely effective if it is unaffordable.

Software
Forward-Synthetic Analysis
—This seems to be a made-up phrase mirroring Retrosynthetic Analysis, the method of finding simpler precursers to a certain chemical.
Negative Data
—Failure in life is very useful for future situations; so too, failure of chemical experiments for better AI-directed analysis.
CASP Tools
—Critical Appraisal Skills Programme, left undefined in the article — apparently a way of validating and regulating scientific methodologies
Interactivity
—Hopefully the reactor can intervene in the disaster before its own demise and the building burns down.
Accessibility
—Nobody is going to use command-line interfaces. The extra step of making a GUI is important!

Conclusion
	—Reproducibility is essential. If humans make mistakes in this regard, the change in a chemical result will be falsely attributed to some independent variable.
