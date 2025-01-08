Considering you're new to the amazing world of engineering

- DYOR-> always read the documentation and do a lot of googling. this is a way of learning how to learn. needn't reinvent the wheel. 
- For every game you have an instruction manual. Everything is a composition of multiple instructions, you just have to figure out the instruction 
- You need to know the key arhcitectural components behind everything. Take for example an airplane, it has wings, a tail, a body, a nose, and two tailwings. 
- Reverse engineer and use your intuition and common sense as to what came first amongst these components and why. This usually aligns with the initial goals and strategy adopted to create the system. If possible, check the history of the system. This could be a list of github commits, technical documentation of 
past architectures, etc. Question the assumptions that were made per component, who made the assumption, wny they made that paricular assumption and what the assumption derives from (as elon and tpot calls it, first principles thinking)
- Learn to look at the whole system, blacbox some components and then come to them later, in case they are leaf nodes, i.e. if there is no connection between one component and the other. 
- Check the requirements of the environment to which you are deploying it. For software this is enterpises, consumers, etc. If you were talking about system software it'd be something like your hardware and your user (frontend/backend). Anything and evberythijng you develop
has anthropic, financial and technical constraints. Find them first. 

Ok, once you did your figuring out, find the points of first input/entry in your environment. For an airplane, the point of first input is wheels and then it is the airframe. The driving forces are the force of momentum, going against the force of air resistance and gravity. 
Similarly for software it is APIs, etc. 
Folow the execution path of the basic operations that you have surveyed 
map out the flow of control for the core operations 
identify the key interactions betweeen components. Eg. 

# Entry point analysis
def main():
    config = load_config()  # Configuration loading
    app = create_app()      # App initialization
    server = setup_server() # Server setup
    server.start(app)       # Execution start

Analyze Dependencies (External and Internal). For an airplane this means the internal weight and forces, the surface curvature, thrust, etc. and externally environmental forces. 

Review dependency management files (package.json, requirements.txt, etc.)
Map out internal module dependencies
Identify external service dependencies
Understand database schemas and relationships
Check configuration requirements

Deep Dive into Key Components

Study core modules and their responsibilities
Understand data models and structures
Review business logic implementation
Analyze error handling patterns
Look at testing strategies


Study the Data Flow (data could be anything here, basically it is anything that remains the key of an environment that you're working with) 

Track how data moves through the system
Identify data transformations
Understand storage patterns
Review caching mechanisms
Map out integration points


Examine Cross-Cutting Concerns

Security mechanisms
Logging and monitoring
Performance optimization
Error handling
Configuration management

Review Non-Functional Requirements

Performance expectations
Scalability requirements
Security requirements
Reliability needs
Compliance requirements


Practical Investigation


Set up a local development environment
Run the system locally
Use debugging tools
Experiment with code changes
Review logs and metrics


Study Operational Aspects


Deployment processes
Monitoring setup
Backup procedures
Disaster recovery plans
Maintenance requirements


Understand Development Workflow


Version control practices
CI/CD pipelines
Code review processes
Testing strategies
Release procedures
