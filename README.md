# UE5MPCharCustomizer

Unreal Engine 5 data driven replicated character customizer (100% Blueprints)







\## Pre-requisites



Unreal Engine 5.7.4 or greater



\## Features



Character Customizer (Replicated)



BP\_MPCharacterCustomizer



Component-based — just add it to your Character Blueprint



Data-driven (uses Data Assets)



Each Data Asset can have it's own animation blueprint



Includes 2 modular body type examples (Quinn and Manny)



Easily extendable:



Copy existing logic in BP\_MPCharacterCustomizer (e.g. head, hair)



Add new parts in S\_CharacterPartsDA



Creating a new body type:



Duplicate, for example, DA\_BodyParts\_Quinn



OR create a new Data Asset of type DA\_CharacterCustomizer



Roadmap



Save/load character customization (client and server)



Fully replicated color selector



(currently includes a basic example for arm/leg material color changes)



Optimize replication:



Replace multiple RepNotify calls with a single consolidated update



License



Permission is granted to use, modify, and integrate this project into personal or commercial projects.



Conditions:



You must provide clear credit to the original author (this repository) in any public or distributed project.



You may not redistribute or resell this project, in whole or in part, as a standalone product.



You must include clear and visible attribution to the original author (this repository) in any use, distribution, or derivative work.



This software is provided "as is", without warranty of any kind.

