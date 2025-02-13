> Checklist made by the teacher for the student(s), to provodie a feedback. __DO NOT__ edit. Do not consider it as "definitive" until "WIP" is removed from the title

### DVCS
    
- [ ] Adoption of Git and GitHub for the report and the code
    
- [ ] Consistently following some committing convention (e.g. [Conventional Commits](https://www.conventionalcommits.org/))
    
- [ ] Consistently following some branching convention (e.g. [GitFlow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow))
    
- [ ] Commits are consistent and coherent  
    + i.e. only what should be committed together has been committed together

### Versioning
    
- [ ] Web API specifications (e.g. OpenAPI, [Swagger](https://swagger.io/)), if any, are versioned
    
- [ ] Web servers routes (if any) are versioned
    
- [ ] Releases are versioned
    
- [ ] Version number variations are [SemVer](https://semver.org) compliant

### Project structure	
    
- [ ] The organization of files in the directory project is canonical w.r.t. the programming language/platform of choice
    
- [ ] The project directory contains a formal specification of **_dev_ dependencies**
    
- [ ] The project directory contains a formal specification of **dependencies**
    
- [ ] The project directory includes **build automation** facilities for restoring the development environment
    
- [ ] The project directory includes **build automation** facilities for releasing the software
    
- [ ] The project structure includes a **directory** for _main_ code
    
- [ ] The project structure includes a **directory** for _test_ code (separated from the above)
    
- [ ] The organization of source code into **packages** and/or **modules** is _meaningful_
    
- [ ] The organization of **modules** reflects the **architectural** design (e.g. [hexagonal architecture](https://en.wikipedia.org/wiki/Hexagonal_architecture_(software)))

- [ ] All repositories have a clear `README.md` file describing their purpose and content

### Licensing
    
- [ ] The project directory includes a license file
    
- [ ] The choice of the licence is adequately motivated in the report

### API	

- [ ] Interfaces and implementations are clearly separated in the code

- [ ] The Web API of any Web-service developed or used is clearly formalised and documented in the report

### Testing (only if code is realised)
    
- [ ] The code includes automatic tests
    
- [ ] A procedure for the computation of test coverage is in place, and the final coverage is reported
    
- [ ] Global test coverage is above 50%
    
- [ ] Test coverage is non-negligible for all interfaces / Web-API
    
- [ ] Global test coverage is above 70%
    
- [ ] A procedure for acceptance testing of EACH requirement is in place, and its final results are reported

### Build	(only if code is realised)	
    
- [ ] An automatic procedure for building (or syntactical check of) the code is in place, and its final results are reported

### Deploy (only if code is realised)	
    
- [ ] Code is realised on the most adequate software repository for the programming language/platform of choice
    + e.g. PyPI for Python, npm for Node.js, Maven for Java, etc.

- [ ] An automatic procedure for generating and releasing software artifacts on software repositories is in place
    
- [ ] Instruction for deploy are reported 

### DevOps	
    
- [ ] CI/CD pipelines have been defined to automate build checks
    
- [ ] CI/CD pipelines have been defined to automate testing
    
- [ ] CI/CD pipelines have been defined to automate deployment

### Domain-driven Design (DDD)	
    
- [ ] __Domain__ and __bounded contexts__ have been clearly identified
    
- [ ] __Entities__, __value-objects,__ and __aggregate roots__ have been adequately modelled according to DDD
    
- [ ] __Repositories__ have been adequately modelled according to DDD
    
- [ ] __Services__ have been adequately modelled according to DDD
    
- [ ] __Factories__ have been adequately modelled according to DDD
    
- [ ] Exploitation of __model-integrity__ patterns is adequately motivated
    
- [ ] The overall design of the system reflects the [hexagonal architecture](https://en.wikipedia.org/wiki/Hexagonal_architecture_(software))

### Implementation (only if code is realised)	
    
- [ ] The code actually implement domain entities
    
- [ ] The code actually implements web services (e.g. microservices)
    
- [ ] The code actually implements clients (e.g. front-ends)

### Modelling	
    
- [ ] __Class diagrams__ are provided for domain entities
    
- [ ] __State diagrams__ are provided for domain entities
    
- [ ] __Sequence diagrams__ are provided for domain entities
    
- [ ] __Data-flow diagrams__ are provided for domain entities
    
- [ ] __Flow charts__ are provided for domain entities

### Requirements	
    
- [ ] _Requirements_ are clearly captured, and categories (e.g. functional vs. non-functional)
    
- [ ] _Scenarios_ are clearly described via __user stories__
    
- [ ] Definition of 'done' for each requirement

### Time
    
- [ ] Project submission within the first useful session after the course is over
    
- [ ] Project submission within 1 year since the end of the course

### Presentation	
    
- [ ] Clarity of the report

- [ ] Clarity of the code (if any)
    
- [ ] Clarity of oral exposition (to be checked when the project work is finally discussed with the teacher)
