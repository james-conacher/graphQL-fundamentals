## GraphQL Fundamentals

This is a simple project, built to give a fundamental understanding as to how GrapQL operates. 

It uses Apollo Server to expose a minimal GraphQL API, and a web page with vanilla JavaScript as the client. In order to understand the fundamentals, this implementation makes use of a schema-first approach in its design. 
The reason for following this approach is for: 
- cleaner design with a standardised syntax
- ensuring that the interface is seperate from the implementation for a better reading experience

It is noted that a code-first approach offers an inherent avoidance of inconsistencies with implementation of resolvers, as well as an easier method to split the code into modules. 
