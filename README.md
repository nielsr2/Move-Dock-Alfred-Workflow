# Move Dock - Alfred Workflow
A simple Alfred workflow for moving your dock's position to the left, right, or bottom.

![](https://i.imgur.com/MRImweF.png)
![](https://i.imgur.com/vG8gYxf.png)


It calls the follow bash command(s):

````bash
defaults write com.apple.dock orientation -string $query;

killall Dock;
```
````
