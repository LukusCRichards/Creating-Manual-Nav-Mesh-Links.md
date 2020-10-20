# Creating an AI Nav Mesh in Unity.md
This is a tutorial on how to create a Nav Mesh for the AI so it can move around the space you allow it to

After starting up Unity, 

Next, create a C# script and give it an applicable name, such as **AI Controller**.

To make the Nav Mesh link, first make sure that you have a baked surface for your AI character to walk on, otherwise it will not be able to move to it. If you want it to jump onto an area above the character or across a gap, then create an empty gameobject and call it **"Link"** while making sure it is parented to the associated platform to make it easier to remember which one it belongs to.

Next, add the **Nav Mesh Link** component to the Link gameobject
