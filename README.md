# Frida Android Scripts
Frida is a dynamic instumentation framework and has very easy to use scripting front ends in javascript and python (probably others too). The repository here serves as collection of scripts I've written and happen to find useful during some actual research and pentest activities.

## BlueCrawl
A bluetooth metadata collector for Android applicaitons. This tool essentialy dumps as much cool bluetooth information within view of a target app according to the Java class loader (since frida essentially swipes a copy of the apps instances for us)

