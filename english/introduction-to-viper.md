**VIPER** - Architecture approach for application development(particularly iOS), based on [the Clean Architecture](https://blog.8thlight.com/uncle-bob/2012/08/13/the-clean-architecture.html) by [Robert C. Martin (Uncle Bob)](http://blog.cleancoder.com/).

![Clean Architecture](../Resources/clean-architecture.png)

**Main goals of VIPER**:

- Increasing test coverage of the Presentation level, usually built from *Massive View Controllers*.
- Conforming to the Single Responsibility Principle.

It is important to note that VIPER is not the list of rules and templates. It's the list of recommendations how to build flexible, testable and reusable architecture. We, the iOS Team of **Rambler&Co**, have adopted some canonical principles and formed our best practices for some cases.

VIPER looks difficult at first, especially for developers without the team work experiences on large projects. It might be hard to understand its benefits if independent modules and high test coverage are not your priorities. But, VIPER is helpful even for small applications.

**Pros and cons of VIPER:**

Pros:

- **Increase of testability** for the application presentation layer.
- **Modules are independent** from each other. It separates the development environment and increases the code reusability.
- **Main architecture approaches are defined**. So it's much easier to add new developer to the team or move project to another team.

Cons:

- Highly **increases number of classes** in the project, as well as the complexity of creating a new module.
- Some principles **don't work with UIKit** out of the box.
- **Lack of recommendations**, best practices and complex application examples.

We'll cover each of these concepts in detail and focus on how to solve those problems through the book.

**VIPER history timeline:**

- **08.2012** - An article [The Clean Architecture](https://blog.8thlight.com/uncle-bob/2012/08/13/the-clean-architecture.html) by Robert Martin
- **12.2013** - An article [Introduction to VIPER](http://mutualmobile.github.io/blog/2013/12/04/viper-introduction/) by [MutualMobile](http://mutualmobile.github.io/)
- **06.2014** - Issue #13. objc.io [Architecting iOS Apps with VIPER](https://www.objc.io/issues/13-architecture/viper/) by MutualMobile
- **07.2014** - [iPhreaks Show podcast](https://itunes.apple.com/ru/podcast/the-iphreaks-show/id634022060?mt=2&i=316803444) by MutualMobile. History of VIPER, goals and usage.
- **04.2015** - Rambler&Co VIPER hackatone leads to first application.
- **12.2015** - Rambler&Co has dozen of VIPER application in development and [released in AppStore](https://itunes.apple.com/ru/developer/rambler-internet-holdings/id395455934).
