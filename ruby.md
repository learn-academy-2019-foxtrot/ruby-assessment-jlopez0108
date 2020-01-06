# ASSESSMENT 4: INTRO TO RUBY
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own there is always something more to learn.   

1. In what ways are JavaScript and Ruby similar? In what ways are they different?

  Your answer:

  Researched answer:JavaScript and Ruby are object-oriented, dynamic and general purpose scripting language which is interpreted rather than compile during runtime. 



2. What is a hash?

  Your answer:

  Researched answer:A Ruby hash is a collection of unique keys and their values. They are similar to arrays but array use integer as an index and hash use any object type. 



3. What is the testing framework used in Ruby? Describe the process of setting up the testing environment.

  Your answer: RSPEC is a testing framework. 

  Researched answer:To set up your environment in AWS you will need to enter a few commands into the terminal. Setting up your files and running rspec car_spec.rb in your terminal will operate the same as a local development environment.
Terminal Commands for AWS RSPEC Set Up

sudo apt install ruby-rspec-core
gem install rspec



4. Name three possible relationships between objects?

  Your answer:

  Researched answer:1. has_many 2. belong_to 3.is_a



5. What is an instance variable? How is it different from other variables in Ruby?

  Your answer: an isntance varaible is a variable that belongs to that class. It cannot be called outside of the instance whereas ruby varuiable are able to be called outside of the class

  Researched answer: An instance variable has a name beginning with @ , and its scope is confined to whatever object self refers to. ... Instance variables of ruby do not need declaration. This implies a flexible structure of objects. In fact, each instance variable is dynamically appended to an object when it is first referenced.



6. Ruby has a great community and tons of free resources to help you learn. [Here](https://www.ruby-lang.org/en/documentation/)is a list of great resources. Below are a few popular ones:
- [Interactive Ruby Tutorial](http://tryruby.org/levels/1/challenges/0)
- [Why's (poigniant) Guide to Ruby](http://poignant.guide/book/chapter-1.html): comics, anecdotes, and microscopic canaries
- [Ruby in 20 Min](https://www.ruby-lang.org/en/documentation/quickstart/)
- [Ruby Style Guide](https://rubystyle.guide/)

Choose one of these resources and look through the material for 10-15 min. List three new things you learned about Ruby:

1) comment on first line indicated to shell instructions

2) Symbols

3) Been around since 1991


7. STRETCH: What are blocks, procs, and lambdas?

  Your answer:

  Researched answer:
  block:Ruby blocks are little anonymous functions that can be passed into methods.
  procs:A Proc object is an encapsulation of a block of code, which can be stored in a local variable, passed to a method or another Proc, and can be called.
  lambdas: They're anonymous, little functional spies sneaking into the rest of your code. Lambdas in Ruby are also objects, just like everything else! The last expression of a lambda is its return value, just like regular functions.
