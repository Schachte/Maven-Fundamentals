# Ant vs Maven

### What Is Ant?

- Designed to be cross-platform
- Built on top of Java and XML
- Procedural
- Not really a build tool
  - Everything needs to be explicit
  - clean, clear, cleanup, etc
  - Ton of tribal knowledge to understand the convention
- Lots of organizations have repos that are organization specific.
- No Structure
- More of a scripting tool


### What Is Maven?

- Full fledged build Tool
- Implicit functionality
- Consistency
- Parent inheritance
- Transitive dependencies
- Built around versioning
- More of a build tool


### Pros & Cons

Maven:
- Steeper learning curve
- Convention over configuration
- Better IDE Integration
- Less overhead
- Sometimes Black box

Ant:
- Quicker to learning
- Larger project size
- Easy to trace through Ant files

# Summary

- Ant is declarative
- Mavens follows convention over configuration
  - They have standard naming conventions that will help build, clean and compile across different organizations
- Ant might be easier to learn, but it really is more or less just a scripting tool
- Maven is really centered around managing your entire projects lifecycle
