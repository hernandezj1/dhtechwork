### Environments

#### Building your Environment

When creating a digital project it is important to know what underlying software, platforms, libraries, code, etc. we are utilizing. By keeping track of these elements we can make sure that our future work and that of researchers that build upon our efforts can execute our codes.
But this can be a very time-consuming task especially when it is not built into the workflows that we may already use in our day-to-day practices. For this very reason, we can utilize containers which exist to help you standardize and be able to distribute your environments. 

<a href="https://coderefinery.github.io/reproducible-research/environments/">_Container Lesson_</a>

But it is not enough to just utilize already tested environments or possibly package our own. We need to also track our __dependencies__ as they get __increasingly__ complicated as this next picture illustrates perfectly. 

![dependency image](https://coderefinery.github.io/reproducible-research/_images/python_environment.png)

> Dependencies are the underlying software, libraries, platforms, etc. on which something (*can be a library, tool, code*) you are using relies upon.

For example, if you are using the package _scipy_ you need to have _python_ and _pip_ on your environment already. In this case, _python_ and _pip_ are your __dependencies__.







