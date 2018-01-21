Hi there, I'm one of the most active OSS developers on GitHub, in order to manage 
working on a lot of popular projects I built a tool called Danger. Danger is a CI tool 
which you use to create tests for a GitHub PR.

I like to think of it as a way to enforce team expectations.  Danger is used by a lot 
of large OSS projects like React, React Native, RxJS, Styled Components and Apollo but
it's useful on any software project with more than one contributor.

Danger provides no rules. We have a recommendation or two but a 
lot of it is determined by your own project's culture. In Artsy, where I work, we've tried 
to add a danger rule every time something slipped past code review when it would be
hard to write a test for. 

Danger works by generating a bunch of useful metadata about your code. It will then evaluate 
your code which uses those 
