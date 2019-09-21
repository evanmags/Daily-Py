# An Introduction to Python

- [An Introduction to Python](#an-introduction-to-python)
  - [Why Python?](#why-python)
  - [Readability](#readability)
  - [Versitility](#versitility)
  - [Conclution](#conclution)

## Why Python?

Named for the Monty Python comedy troupe, the Python language was developed to be an english read able programming language with simple syntax allowing more people to learn to program easier and faster. For our purposes there are only   

## Readability

Take a look at these code samples of simple loops printing the numbers 1-10. Yes, even after just 2 sentences I want you to start looking at code.  

***Java:***
```java
public class Example
{
  public static void main(String[] args)
  {
    for(int i = 1; i < 11; i++)
    {
      system.out.println(i)
    }
  }
}
```

***Javascript:***
```js
for (let i = 1; i < 11; i++){
  console.log(i)
}
```

***Python:***
```python
for i in range(1, 11):
  print(i)
```

Dont be scared if you didn't understand any of those. You don't have to, yet. By the end of this section you will, at the very least understand and be able to use the very last example in your own programs.  

Each of these is significantly simpler than the previous. From class definitions with mmain functions accepting arguments and using system (whatever that means). To stripping away everything but the loop. To something that is essentially a special syntax of the english language. Lets take a deeper look at this particular example.

This example read in english would be, "For every number in the range 1 inclusive to 11 exclusive, print said number." Now looking back at each of the code examples, which ones would you have been able to distill to that phrase? I know the frist time I looked at java or javascript code I was completely lost. Python tries to eliminate that, at least to some degree. 

## Versitility

While this tutorial will look at Python in a single scope (testing), Python is used across almost every industry you can think of. And while better suited for some applications than others you would be hard pressed to find an area that python cannot be used in.  

Python comes packaged with a [laundry list of modules](https://docs.python.org/3/library/) available for import into your applications. So many so, that it is unlikely you will ever find need or use for all of them.  

However, if for some reason you are unable to find a module to do what you want, you can either design one or search the [Python Package Index (PyPi)](https://pypi.org/) for one that does. Then simply run the command `$ pip install <package name>`. Now you will be able to use that package in any project.

Take a look at this article from [FreeCodeCamp.com](https://www.freecodecamp.org/news/what-can-you-do-with-python-the-3-main-applications-518db9a68a78/). While the author does acknoledge that there are things that python is not the best choice for, they are still possibilities. And if your tool belt has at least one tool in it, thats always better than none. Aa well, the things you pick up here will only help when it comes to learnign other languages.

## Conclution

Python is an easy to use and expansive language used in almost any capacity that you could imagine. From buildin libraries come functionality that allow you to build comples applications, and when there does not exist a standard library, PyPi can almost always get you what you need.  

When there is ambiguity in what language to choose, python might be a good choice for you.