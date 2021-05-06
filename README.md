# Awesome Dependencies

## The Problem
Continuous Obsolescence is the all too common anti-pattern which emerges as a result of not properly managing your use 3rd party dependencies. The problem is simple: you depend on a 3rd party solution and they probably do to. If anything in that chain changes (or fails to change), it's your problem. Security is serious business and not taking your dependencies seriously will result in serious security issues.

There are two ways dependencies can be screwed up: 

1. Bad implementation
2. Dependency Hell

Both can be fixed but require different approaches. [Architectually speaking all 3rd party dependencies should be proxied in your code through an adaptor](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html). If you have all of your dependencies sitting behind an adaptor you shouldn't have a problem, right? 

There are two ways to find yourself in Dependency Hell:

1. There are no alternatives!
2. Your "dependency" is an entire component library and making a bazillion adaptors isn't practical. 

## The Solution - Awesome Dependencies
Awesome Dependencies is all about establishing as set of criteria for what makes a great dependency and cataloging dependencies that follow that criteria.

### Good Dependencies
- [x] Have a simple API which can be proxied/adapted
- [x] Have zero to few transient dependencies
- [x] Active support

## Frontend Dependencies
TBD

## Backend Dependencies
TBD
