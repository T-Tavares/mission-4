# Mission Ready - Mission 4

## Mission tasks

This mission is where we started to put it all together. Here we had to do:

-   Command Line Interface (CLI) Tool to manage our MongoDB Cars Database.
-   Tweak the Backend to have the AI interacting with our DB and compare our stock with the image analisys results.
-   Adjust the Frontend to read that response.

# About

The CLI tool is where I did most of the work.
It was thought to have shared functions with the backend. For that reason functions got a bit more complex.
I'm still unsure if this was a practical solution due to a dilemma between reusability and maintainability
It takes longer to code and set up. But once is done all the functions can be used across CLI and Backend.

Pros

-   Consistency
-   Reusability is King
-   Maintenance across platforms would be easier

Cons

-   Takes longer to code and setup
-   Harder to read code
-   Harder to maintain when multiple devs work on it, because one function holds 2 branchs of logic

# Notes

I haven't really tried out the functions on a Backend environment a part from small tests.
So is safe to say that they are stable for the CLI environment but not for a Backend environment.

# Links

[CLI NPM package](https://www.npmjs.com/package/turners-cli-tavares)
