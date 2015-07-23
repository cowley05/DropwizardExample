# DropwizardExample
An example dropwizard application built with gradle

#Running
To run this for the first time just use `gradle run`

To generate IntelliJ Idea files use `gradle cleanIdea idea`

#Gotchas with gradle
When trying to use `gradle run` you may get some weird errors such as:
'cannot locate main class x.y.Z.class'
this will usually be down to folder structure which has to be src -> main -> java -> x.y -> Z.java
