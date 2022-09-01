# Learning about Git

Research the topics listed below and add a short definition of them **in your words** to the README 
  - Surface level research for now, we are not making a PHD here...
  - Commit after each one!

# Topics:
1.  - "What makes a good commit message"
2.  - "What is staging in git"
3.  - "How to check which version of git you have installed"
4.  - "What is Semantic Versioning (SemVer)"
5.  - "How to see previous commands I have done in Linux"
6. - "VS Code tips and tricks"
7. - "How to practice typing fast"
8. - "What is DNS"
9. - "Binary number system"
10. - "Hexadecimal number system"
11. - "What is ROT-13"



# Replies:

1. - A good commit message should have some rules, e.g.:    - programmers should only commit working code
                                                            - programmers should only commit logical set of changes
                                                            - Commit's lenght should be defined by the individual private companies (or max 50 charachters long, usually)
                                                            - programmers should use complete sentences
                                                            - programmers should start with an issue ID (e.g coming from a Ticketing System)
                                                            - Commit messaged should be written in 'Imperative Tense'

2. - "Staging" is the second Git Environment [the others being (1.) Working and (3.) Commit Envos]. 
     'Staging' environment gives you a way to queue up changes until you are ready to commit. 
   - You can 'Staging' working files within the current directory, after saving them (Cntr+S), via the command <git add .>
   - If you only want to stage one file, then type: <git add 'nameofthefilehere.fileextension'>


3. - In Terminal, type: <git --version> command to see which version of git you have installed on your computer.

4. - 'Semantic Versioning (SemVer)' is the most popular system of versioning unique states of the project. 
    To have a universal way of versioning helps to keep things clean and simple and to keep track of the software changes.
    Given a version number (e.g.: version 4.0.1) meaning: MAJOR.MINOR.PATCH, increment the:

    - MAJOR version when you make incompatible API changes
    - MINOR version when you add functionality in a backwards compatible manner
    - PATCH version when you make backwards compatible bug fixes

    - Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

5. - In Linux terminal, to see previous commands an user have done: simply hit 'arrow up', on the keyboard.
   - Alternatively, within the Terminal, a very useful command is to simply type: <history>
