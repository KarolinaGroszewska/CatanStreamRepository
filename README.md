## Links for GHW:Games Catan Stream

### Research Documents
- [University of Edinburgh Research Paper](https://homepages.inf.ed.ac.uk/alex/papers/cig2014_gs.pdf) is the first paper we looked at during Part 1 of the Stream: it discusses a lot of important research in developing a Catan AI.
- [QSettlers](https://akrishna77.github.io/QSettlers/) describes a student-led masters' project in which a team of 4 looked at developing a DQN network to improve on JSettlers' results.
- [Evolvers of Catan Technical Report](https://cs.carleton.edu/cs_comps/2021/game-ai/Final-Results/Evolvers-of-Catan-Website/files/Evolvers-of-Catan-Technical-Documentation.pdf) is another student-led project in which a team of 4 looked at running and improving on JSettlers

### Websites
- [Colonist.io](https://colonist.io/) is an online free-to-play Catan alternative emulator, that functions similarly to Chess.com
- The [JSettlers Developer Page](https://nand.net/jsettlers/devel/) contains more information about the JSettlers project, as well as updated download links, screenshots, and important information. 

### Repositories
- [JSettlers](https://github.com/jdmonin/JSettlers2) is a Java local version and server + client for playing + training Catan. It also has the "world standard" of Catan AIs.
- [QSettlers](https://github.com/akrishna77/CS7641-QSettlers) also has a publicly available Github Repository. 

### Tips and Tricks for JSettlers
**Running JSettlers**
- Requires downloading [JDK](https://jdk.java.net/) or [JRE](https://www.java.com/en/download/), then downloading the JAR from the JSettlers repository or Developer Page.
**Closing out of the Server (on Mac)**
- `ps -ef | grep java`
- Find the pid of the process (second one from the left)
- `sudo kill -9 <pid>`
**Setting Up a Bots-Only Server**
