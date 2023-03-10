# Part 1: Setting Up Visual Scripting

*Contents*: [Installation](#installation) | [Moving Forward](#moving-forward)

## Installation

The installation for Unity Visual Scripting depends on your version of Unity.

### Versions 2021.1 and Later

<a href="https://docs.unity3d.com/Packages/com.unity.visualscripting@1.7/manual/index.html">According to Unity</a>, versions 2021.1 and later have Unity Visual Scripting pre-installed. So, if you have any of those versions, you're already set.

### Versions 2018.4.24 to 2021.0.x

If you have an earlier version of Unity, you'll have to <a href="https://assetstore.unity.com/packages/tools/visual-scripting/bolt-163802"> download Bolt on the Unity Asset Store</a>. (Bolt is an earlier form of Unity Visual Scripting; it was named that back when it was a third-party package.)

Once you've downloaded Bolt, open Unity and go to the Package Manager (Window > Package Manager). 

A list of packages will appear--but not the list you actually want. Right now, it's only listing the packages already installed in your project.

Click "Packages: In Project" and change it to "Packages: My Assets" to include things you've downloaded off the Asset Store. Then, select Bolt in the resulting list.

<img alt="img1-1.png" height="200" src="../Images/1/img1.gif"/>

Finally, press Import on the bottom of the window.

All you need to do now is configure Bolt. Go to Tools > Install Bolt, and a setup window will appear. 

Most of the defaults should be okay. One notable choice is the one between "Programmer Naming" and "Human Naming." This tutorial series will use Programmer Naming. I recommend choosing it too since, when looking up the solution to a problem in Unity, most results will use the "programmer name" of the tools you're dealing with.

**Note:** Bolt and Unity Visual Scripting look slightly different, but function very similarly. This tutorial shows screenshots from Unity Visual Scripting.

### Versions 2018.4.23 and Older 
According to Bolt's page on the Unity Asset Store, the earliest version of Unity it will work with is 2018.4.24. So, unfortunately, you'll have to upgrade if you're using any version older than that.

## Moving Forward

Now that you've installed visual scripting, you can follow along with the rest of this tutorial series! If things aren't working as expected, you may want to check this page again to make sure the installation was done properly.

## References

https://docs.unity3d.com/Packages/com.unity.visualscripting@1.7/manual/index.html

https://assetstore.unity.com/packages/tools/visual-scripting/bolt-163802

https://www.youtube.com/watch?v=aQceChK-kC4

## Next Lesson

[Part 2: Graphs, Nodes, and Flow](2_GraphsNodesAndFlow.md)








