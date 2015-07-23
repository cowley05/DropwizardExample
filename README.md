# DropwizardExample
An example dropwizard application built with gradle

#Running
Open your terminal

If you dont have gradle installed *and your on a mac* first run `brew install gradle`

To run the application just use `gradle run`

Your server will start and be accessible via http://localhost:8080/hello-world

To view your name on the screen got to http://localhost:8080/hello-world?name=YOUR_NAME

To generate IntelliJ Idea files for this application use `gradle cleanIdea idea`

#Gotchas with gradle
When trying to use `gradle run` you may get some weird errors such as:

'cannot locate main class x.y.Z.class'

this will usually be down to folder structure which has to be:

src -> main -> java -> x.y -> Z.java
