### Environments

#### Building your Environment

When creating a digital project it is important to know what underlying software, platforms, libraries, code, etc. we are utilizing. By keeping track of these elements we can make sure that our future work and that of researchers that build upon our efforts can execute our codes.
But this can be a very time-consuming task especially when it is not built into the workflows that we may already use in our day-to-day practices. For this very reason, we can utilize containers that exist to help you standardize and be able to distribute your environments. 

##### Lesson - Containers
<a href="https://coderefinery.github.io/reproducible-research/environments/">_Code refinery container Lesson_</a>

But it is not enough to just utilize already tested environments or possibly package our own. We need to also track our __dependencies__ as they get __increasingly__ complicated as this next picture illustrates perfectly. 

![dependency image](https://coderefinery.github.io/reproducible-research/_images/python_environment.png)

> Dependencies are the underlying software, libraries, platforms, etc. on which something (*can be a library, tool, code*) you are using relies upon.

For example, if you are using the package _scipy_ you need to have _python_ and _pip_ on your environment already. In this case, _python_ and _pip_ are your __dependencies__. To track these dependencies we can utilize package managers which organize the environments and track the dependencies for us. 

##### Lesson - Dependencies
<a href="https://coderefinery.github.io/reproducible-research/dependencies/">_Code Refinery dependency lesson_</a>


##### Additional resources
- Common container software intro lessons and/or docs:
  - Docker
      - <a href="https://carpentries-incubator.github.io/docker-introduction/"> Carpentries lesson</a>
      - <a href="https://matthewfeickert.github.io/intro-to-docker/">Matthew Feickert Lesson</a>
      - <a href="https://docs.docker.com/get-started/">Official Intro Docs</a>
  - Singularity (very useful for High-performance Computing work)
      - <a href="https://carpentries-incubator.github.io/singularity-introduction/">Carpentries lesson</a>
      - <a href="https://docs.sylabs.io/guides/3.7/user-guide/introduction.html"> Singularity Intro Docs</a>

- Common dependency managers intro lessons and/or docs:









