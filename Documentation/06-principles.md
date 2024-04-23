## Principles

This section summarizes the principles that have been used to design and build the backpack. 

### Lab usage
The backpack is designed to be used in (and outside) of the lab, not as a commercially available product.

### Poka Yoke
[Poka Yoke](https://en.wikipedia.org/wiki/Poka-yoke) (Mistake Proofing) Designing systems or products in a way that prevents errors or mistakes by users. 
For example, M12 connectors have been chosen with specific pinouts such that users cannot accidentally insert a 24V connection into a 5V connection.

### Rather buy than make it yourself
Rather buy products (like ethernet cables) than making them yourself. This is because it is cheaper (and usually more reliable) to order products than spending the time to make them yourself,

### Design for Assembly
DFA (Design for Assembly): Designing products with ease of assembly in mind to reduce assembly time, complexity, and costs. For example, 
  * Only use M3 & M5 screws with the same head in order to avoid confusion between screws and number of needed tools for assembly
  * Avoid having to use nuts by using threaded inserts
  * Mount for the gas sensor is designed such that battery straps can be easily removed

### Design for new add-ons
The backpack should have no high level constraints for new parts, in other words: it should be easy to design and integrate new parts for new projects. 

### Requirements Formulation
Requirements have been written based on [EARS](https://www.researchgate.net/publication/224079416_Easy_approach_to_requirements_syntax_EARS) and have been assigned a priority according to [MoSCoW](https://en.wikipedia.org/wiki/MoSCoW_method).

### Repository Maintencance 
Maintenance of the repository itself is based on [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow).

