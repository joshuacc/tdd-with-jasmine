# Outline

Note: Make sure that I have an empty Sublime window open in case someone asks a question that requires code to answer.

* Title Slide
* Intro Slide
    * Name, Job, what I do, etc.
    * Feel free to ask questions during the presentation
* Questions for the room
    * How many of you are primarily JS developers?
    * How many of you know what unit testing is?
    * How many of you write unit tests for your JS?
    * How many of you know what Test Driven Development is?
    * How many of you do TDD for your JS?
    * How many of you have heard of Jasmine before this talk?
    * How many of you actually use Jasmine?
* Answers
    * Unit testing is...
    * TDD is...
        * Red. Green. Refactor.
    * Jasmine is...
    * Tests vs. Specs
* The pieces of a Jasmine test suite
    * A short suite
    * The describe block
        * Can be nested
    * The it block
    * Expectations
    * Matchers
        * Some examples
    * The result of running it
    * The Spec Runner HTML
* Using Jasmine the TDD Way
    * The plan
    * Write the spec first
    * Make sure that the spec fails (Red)
    * Failure first === success
    * Write the code
    * Green
    * Refactor
    * Successful refactoring
* Why TDD? (Instead of writing tests afterward?)
    * Writing tests beforehand forces you to think through how you want your code to behave before you start writing it.
    * Leads to better code design by encouraging smaller pieces of code which you can combine to achieve your larger goals.
    * Means that you know you wrote the tests correctly. If you didn't see the tests fail, you're not actually sure that they *will* fail.
    * Your tests will be more complete, because you at each step you only write the code necessary to pass the newly added spec. You just keep adding specs until your code is feature complete.
* More handy features
    * Some matchers
    * Spies
* Jasmine Documentation
    * It's good.
    * Self describing example.
* Jasmine & CoffeeScript
    * It's much cleaner
* Jasmine in Terminal
    * Example results
    * Benefits to TDD
    * How it works
        * Node
        * Grunt build tool
        * Jasmine plugin for Grunt
        * Watch plugin
        * PhantomJS (headless webkit)
    * Example Gruntfile
* Promos
    * Twitter & Blog
    * A Drip of JavaScript
    * Jasmine Testing: A Cloak and Dagger Guide
        * 50% off coupon
        * Work in progress
* Slides
    * Creative Commons attribution license
    * Hosted on Github
    * Feel free to use them to present at your company, just link back to the original slices.