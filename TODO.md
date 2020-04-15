# Possible TODOs.


## Feedback

* Strengthen the sudoku frame. Explicitly call out what is happening at each level. Push forward, introduce rules, be methodical, specialise? Tell this through MY journey. Just talking about what You do at each level is unclear and impersonal
* Use the phrase "the red-green-refactor lie". Add the diagram
* Maybe add some code!
* Bake in a better answer to the "Isn't it just personal preference?" question
* Tone needs to change. Currently a little ranty. Try more positive framing.


## Research links

* framing. Ritualism? How powerful that is? Maybe use coffee as our opener. It’s not addictive but does cause dependence, and ritualistic but biochemically doesn’t do much at all. -- Maybe not.
* framing. Conversation with Plato in a pub. He's worried about TDD. He knows he can't do it perfectly. Source of shame. Talk reveals how there is no perfect for TDD. Brief divergence somewhere into platonic forms?
* Possibly mention j-curve of change. Satir curve?
* By me: "TDD is just a tool. It's one of the best I know for a lot of situations. I'd be fine with people not using it if they'd replaced it with something else. Delighted, in fact! But... most devs appear to have replaced it with maybe writing some tests after. Brittle, wasteful, poor."
* Sandi Metz & Katrina Own book 99 bottles of OOP has some great TDD stuff. Re-read
* Kent beck: simple rules of design: https://www.martinfowler.com/bliki/BeckDesignRules.html
* Brian Marick on a better style for tests (i.e. don't assert_equal) https://twitter.com/marick/status/1140021311974137857
* Brian Marick (again) on test data and randomisation being clearer https://twitter.com/marick/status/1140713459988029441
* Note that randomisation means less predicatable data. That's a good thing. Relationship/meaning is the most important thing. Randomising also means you might find more edge cases that can then be codified. If you'd prefer some predictability, you can always keep the seed constant.
* Lots of stuff in this thread (both this and the earliest part being quote tweeted by GeePaw Hill) about developer exceptionalism. An argument I put forward is that devs should be at least as interruptible as other disciplines and a tight red-green-refactor aids that: https://twitter.com/garyfleming/status/1145461742350323712
* More on Dev Exceptionalism and tight TDD loops: https://twitter.com/garyfleming/status/1144164533549838336
* Test fixtures: https://twitter.com/marick/status/1172342543490662401
* Seb Rose on unit tests rarely being written as expected: https://twitter.com/sebrose/status/1184030238931595264
* Sarah mei on TDD not working for a heterogenous team: https://twitter.com/sarahmei/status/990594488052559874, and https://twitter.com/sarahmei/status/990968833547497472 (Expanded/Easier to read version: https://retrosight.github.io/learning/why-agile-xp-so-often-fails-heterogenous-teams-sarah-mei.html)
* My initial reaction to Sarah Mei's tweets was strong disagreement, because I'd seen them work well in heterogenous groups. But I have to own my own privilege here: I'm privileged, and I need to put more time into seeing it through other lenses. Consider the issues here. -- Practices and power dynamics
* "Why are Rooie rules nice" - Brian Marick on why things that look rule-bound often need more work https://twitter.com/marick/status/1208748304311496704
* Ron Jeffries. Lots on where TDD might not work as well https://twitter.com/RonJeffries/status/1210201762705088513
* Ron Jeffries. Some overlap wiht above thread https://twitter.com/RonJeffries/status/1208748384963694592
* Michael Feathers. A set of unit testing rules https://www.artima.com/weblogs/viewpost.jsp?thread=126923
* Lots on arguments against TDD http://neopragma.com/index.php/2019/09/29/against-tdd/
* Maybe worth listing the whys? Feedback, design pressure,
* "TDD changed my life" https://twitter.com/_ericelliott/status/1222869590880985088
* GeePawHill on why writing the tests before (as opposed to after) matters https://twitter.com/GeePawHill/status/1086748964936994816
* GeePawHill and Cat Swetel on soft vs hard TDD https://twitter.com/GeePawHill/status/1057032359931973632
* Test Recycling in TDD: http://claysnow.co.uk/recycling-tests-in-tdd/
* Marco Rogers on watching your test fail: https://twitter.com/polotek/status/1211723875207114752
* Ron Jeffries on what it feels liek to do TDD: https://twitter.com/RonJeffries/status/1212025850637537281
* Thread on whether TDD is a design practice. I like Antony Marcano's answer: https://twitter.com/AntonyMarcano/status/1213421222010277888
* Allen Holub on TDD/BDD as example based design: https://twitter.com/allenholub/status/1213139013604978688
* "Test-Driven Development (TDD) is frequently misunderstood in ways that cause needless struggle, delay, and upset." https://twitter.com/qcoding/status/1215362719458779141
* "Desirable properties of tests": https://twitter.com/GeePawHill/status/1215693091887288321
* Allen Holub on why TDD isn't testing: https://twitter.com/allenholub/status/1213937824258347008
* Funny meme https://twitter.com/molly_struve/status/1216075779928395776
* Jeffries: https://twitter.com/RonJeffries/status/1215625501752090624
* https://twitter.com/RonJeffries/status/1218539682910429184    Encapsulates central premise: shame comes from being overwhelmed by TDD. By you’ll never be good enough and ashamed to do better. Imposter syndrome manifest.
* Liz Keogh on TDD as an anchor term: https://twitter.com/lunivore/status/1218866213129981954
* Geepaw Hill on underplayed reasons for TDD; https://twitter.com/GeePawHill/status/121896540211556352
* When I wouldn't use TDD: https://twitter.com/RonJeffries/status/1219399710521335809
* Jay Bazuzi on test pressure: https://twitter.com/jaybazuzi/status/1216213981213278208
* Presentation from CodeMash on TDD (need to read): https://twitter.com/paulroub/status/1216407457339232269
* Sandi metz on testing. 5.21 argues that unit tests should be Thorough, Stable, Fast, Few. 9.48 introduces a grid with 6 different testing patterns: https://www.youtube.com/watch?v=URSWYvyc42M
* Think this Sandi metz talk might also have some relevant stuff but it's been a while: https://www.youtube.com/watch?v=8bZh5LMaSmE
* Is TDD dead by Emily Bache? https://www.youtube.com/watch?v=PCEHRFHKZSk
* Something on the various schools of TDD: london, chicago, that other one by Searls? Good one here: http://coding-is-like-cooking.info/2013/04/the-london-school-of-test-driven-development/
* Why and when to Mock using libraries. Why I generally dislike mock libraries (and when to use them)
* Outside in with double loop TDD (Emily Bache): http://coding-is-like-cooking.info/2013/04/outside-in-development-with-double-loop-tdd/
* Good tests for Gilded Rose Kata (Emily Bache): http://coding-is-like-cooking.info/2013/03/writing-good-tests-for-the-gilded-rose-kata/
* Boundaries (Gary Bernhardt): https://www.youtube.com/watch?v=eOYal8elnZk
* Tdd for infra (Rosemary Wang): https://www.youtube.com/watch?v=AAcPuYfVt2c
* Lots of good bits here: https://www.obeythetestinggoat.com/pages/tdd-resources.html
* TDD that's not what we meant (Steve Freeman): https://vimeo.com/83960706
* Teaching TDD in mobs: https://twitter.com/tottinge/status/1223048720557604864
* Is TDD old news? https://twitter.com/lisacrispin/status/1222568983968276481
* Thread I started on why people don't use TDD: https://twitter.com/garyfleming/status/1216445078992039937
* Possibly worth expanding on some of the team dynamics around TDD, especially when some people don't do it.
* “show me how to do TDD on this thing that’s already way too complicated” no. Magician and their tricks.
* Alex Schladebeck: TDD makes the implicit explicit https://twitter.com/alex_schl/status/1225679473262989314
* Geepawhill on why TDD is relevant to front-end https://twitter.com/GeePawHill/status/1225513388844994561
* TDD: dead end. No future... except we've been playing with Test-Commit-Revert and Limbo.
* Rules and heuristics from Sudoku
* TDD as a core agility issue being broken by manager's who don't undestand: https://twitter.com/allenholub/status/1226573759189880832
* Learning can’t be prescriptive. “Do these things and you’ll be a TDDer”. I’ve been running katas and seeing where teams/people get stuck. Helps me see that they need to learn X and Y
* Allen Holub. Dump the T in TDD. Use example instead: https://twitter.com/allenholub/status/1227049507306778624
* sudoku bit. Easy puzzles we can do intuitively. Implicit knowledge. Minimal rules. Guesswork. Expert puzzles require more rigour. More rules. At least until we’ve done enough that the moves become more implicit. Analogies to code problems that are very familiar. Need more rigour when doing something harder. Devs often get wrong. Cynefin?
* Tale of Two TDDers thread: https://twitter.com/gdinwiddie/status/1228697497629011968
* Refactoring. What it means. Where the name comes from.
* TDD thead https://twitter.com/GeePawHill/status/1226615510151892993
* Jim weirich on testing. Good stuff on mocking https://github.com/jimweirich/presentation_testing_why_dont_we_do_it_like_this/blob/master/pdf/testing.key.pdf
* "You won't believe how old TDD is". Early references to TDD like processes going back as far as 1957. Jerry Weinbrg's first book (1961) makes it clear that's how people thought - https://arialdomartini.wordpress.com/2012/07/20/you-wont-believe-how-old-tdd-is/
* gdinwiddie: speed and tdd: https://twitter.com/gdinwiddie/status/1229411688568541190
* Geepawhill deep dives on "our branching logic": https://twitter.com/GeePawHill/status/1097261666818052097
* GeePawHill on secondary refactorings in TDD: https://twitter.com/GeePawHill/status/1239252920807415808
* Elisabeth hendrickson on why she loves TDD: https://twitter.com/testobsessed/status/1231264781299879936
* Geepawhill "[TDD] feels good right when I do it": https://twitter.com/GeePawHill/status/1242493433945755655
* gdinwiddie: the ordering of tests: https://twitter.com/gdinwiddie/status/1244649593268244480
* Code too simple to test: https://twitter.com/dtanzer/status/1249926799456374784
* Refactoring with Clare Sudbery: https://martinfowler.com/articles/class-too-large.html
