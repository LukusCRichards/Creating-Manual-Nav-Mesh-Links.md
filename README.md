# Creating Nav Mesh Links.md
This is a tutorial on how to create Nav Mesh links that can be used to make an AI character jump between one place to another that are separated from each other

There was a time where you might have played a game like The Simpsons Game or Mass Effect Andromeda and you have seen the AI jump between gaps in the map and you probably wanted to know why or how they manage to do that. That is what's called a Nav Mesh link which the AI is using to help them get across areas where there is no baked Nav Mesh or surface for the AI to walk on to be able to access that area of the world.

To make the Nav Mesh link, first make sure that you have a baked surface for your AI character to walk on, otherwise it will not be able to move to it. If you want it to jump onto an area above the character or across a gap, then create an empty gameobject and call "Link" while making sure it is parented to the associated platform to make it easier to remember which one it belongs to.
