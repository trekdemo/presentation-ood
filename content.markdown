# Software design in agile environment
![without thining][without_think]

[without_think]: http://i.imgur.com/Jp5fYlk.gif



# Why we talk about it
> We want to do out best work, and we want the work we do to have meaning.


![pain][pain]
> ...frustration occurs when it costs too muck to get things done.

[pain]: http://i.imgur.com/Iiee3.gif


## Changing requirements...
> ...are the programming equivalent of friction and gravity



# How to fight?


* Write TRUE code
* Design principles
* Design patterns
* Best practices
* ...get your brain in gear!


## TRUE
* **Transparent**

  *The consequences of change should be obvius in the code that is changing and
  in distant code relies upon it.*
* **Reasonable**

  *The cost of any change should be proportional to the benefits the change
  achives.*
* **Usable**

  *Existing code should be usable in new and unexpected contexts.*
* **Examplary**

  *The code itself should encourage those who change it to perpetuate these
  qualities.*


## Design Principles
* [SOLID][solid]
    * [Single Responsibility][srp]
    * [Open-Closed][ocp]
    * [Liskov substitution][lsp]
    * [Interface Segregation][isp]
    * [Dependency Inversion][dip]
* [DRY][dry] - Don't repeat yourself
* Many more, what's your favorite?

[solid]: http://en.wikipedia.org/wiki/SOLID_(object-oriented_design
[srp]: http://en.wikipedia.org/wiki/Single_responsibility_principle
[ocp]: http://en.wikipedia.org/wiki/Open/closed_principle
[lsp]: http://en.wikipedia.org/wiki/Liskov_substitution_principle
[isp]: http://en.wikipedia.org/wiki/Interface_segregation_principle
[dip]: http://en.wikipedia.org/wiki/Dependency_inversion_principle
[dry]: http://en.wikipedia.org/wiki/Don%27t_Repeat_Yourself


## Principles matter
[Principal Components of Orthogonal Object-Oriented Metrics][pcooom]
Victor Laing & Charles Coleman

[pcooom]: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.95.6760&rep=rep1&type=pdf


## Rocket science
![NASA][nasa]

Yeah, NASA uses Ruby, too!

For example to handle hundreds of gigs of satelite images.
[Langley Research Center][langley],
[NOAA][noaa],
[Ara T. Howard][ara]

[nasa]: http://www.basenow.net/wp-content/meatball.jpg
[noaa]: http://rubyrogues.com/094-rr-robust-ruby-with-ara-t-howard/
[ara]: http://rubyrogues.com/094-rr-robust-ruby-with-ara-t-howard/
[langley]: http://www.nasa.gov/centers/langley/home/index.html


## Design Patterns
* Knowledge of decades
* Simple identification for complex problems and solutions


### We know many from Rails

* MVC (or something like that)
* ActiveRecord (or something like that)
* Observer
* ...
* *What's your favorite?*


## Best practieses
* Convention over Configuration
* TDD - BDD as a development practice
* [Rails Best Practices][rbp]
* ...
* *What's your best practice?*

[rbp]: http://rails-bestpractices.com/



# Design object with single responsibility
*not only in class based languages*


* What are your classes?
* What behavior will they implement?
* How many should you have?
* How much of themeselves should they expose?
* How much do they know about other classes?


![god objects][god_objects]

[god_objects]: http://cdn.memegenerator.net/instances/400x/35738960.jpg


> Design is more the art of preserving changeability then it is the act of
> achieving perfection.


## Remember TRUE and the Principles?
* Change without side effects
* Small change in requirements, require small change in code
* Reuseable
* Easiest way to make change is adding new changeable code.


# Workshop



# Manage dependencies



# Interfaces



# Ducktyping



# Composition



> Program to and **interface**, not an implementation.
>
> Gang of Four, 1995



# Sources
* [Sandi Metz - Practical Object-Oriented Design in Ruby][poodr]
* [Design Patterns - Belarus RUG (Speaker Deck)][dpbrug]

[poodr]: http://www.informit.com/store/practical-object-oriented-design-in-ruby-an-agile-primer-9780321721334?w_ptgrevartcl=Practical%20Object%20Oriented%20Design%20in%20Ruby%3a%20Interfaces_1834700
[dpbrug]: https://speakerdeck.com/lest/design-patterns-belarus-ruby-on-rails-user-group-23-feb-2013



## Thanks
# Questions?

* Twitter: [@trekdemo][twitter]
* Github: [@trekdemo][github]

[twitter]: http://twitter.com/trekdemo
[github]: http://github.com/trekdemo

