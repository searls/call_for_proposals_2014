# Breaking up (with) your test suite

It's about time for the Ruby community to adopt a more mature and nuanced approach to testing.

Gone are the days when "is it tested?" was a boolean question. It no longer makes sense for a single test suite to accomplish numerous objectives, because the design of our tests are so influenced by the benefit we hope to realize from them. What's less clear to most developers is the best approach to breaking a test suite up.

This talk will introduce a testing architecture that's appropriate for the post-monolithic age of Ruby application development. We'll discuss why each test suite can provide at most one type of confidence and one type of feedback. I'll introduce a set of five narrow, focused types of test suites and explore how each of their roles can combine to provide all of the value that test automation can hope to offer. Together, we'll gain the ability to discuss the value of each test with much greater precision and subtlety.

## Justin Searls

Justin Searls has two professional passions: writing great software and sharing what he’s learned in order to help others write even greater software. He has a software studio in Columbus called Test Double, where he’s currently helping clients build well-crafted user experiences for the web.

![Profile picture](http://f.cl.ly/items/3d1e232G35100H2j0n3W/20120630-face.jpg)

- [My website](http://testdouble.com)
- [My twitter](https://twitter.com/searls)
- [Past talk slides](https://speakerdeck.com/searls)
- [Past talk video](http://blog.testdouble.com/posts/2013-08-24-office-politics.html)

## Notes

There's an annual tradition in the Ruby community to unseat the prevailing testing wisdom and replace it with new memes and practices. Over the years, the Ruby tribe has flip-flopped between xUnit and BDD semantics. We've brought nuance to TATFT by borrowing from GOOS. We've debated the merits of integration tests and DCI. Sometimes, we're even caught asking ourselves whether Rails and TDD are fundamentally at odds.

My belief is that this talk is an evolution of the following three talks:

* [Budgeting Reality](https://speakerdeck.com/searls/reality-is-expensive-a-better-way-of-thinking-about-mock-objects)
* [The Magic Tricks of Testing](http://www.youtube.com/watch?v=URSWYvyc42M)
* [467 tests, 0 failures, 0 confidence](http://vimeo.com/68730418)

And that this talk is a culmination of "how to actually put all of those ideas into practice". Its laser-focused mission will be to provide eminently actionable advice based on the observations made by the above three talks.
