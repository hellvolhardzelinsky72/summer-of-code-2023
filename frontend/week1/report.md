0. Okay first, I dont have vpn access so I did all the tasks on other websites, I hope thats fine.

1. The page reddit.com is divided into nested elements. These elements form a binary tree data structure, with <html> being the root node, and all other elements being child nodes. ![tree-structure](/website/assets/tree-strcuture.png). The elements are visually indented to easily identify the parent-child relationship.

2.Editing the color property of the button, you can see how I changed the color from original![button color orange](/website/assets/button-color-before.png) to rgb(250,0,250)![button color pink](/website/assets/button-color-before.png).

3.So I used the id acceptabletest instead and the function innerText with the . operator to change the innertext from advertisement to hello world.![queryselector](/website/assets/query-selector.png)

4. We can see the java script tag for the initial request for https://www.reddit.com and the following java script.![network](/website/assets/network.png).
As for disabling cache, website reload time increased marginally as the site was forced to download resources again, even if they were the same as before.
However, throttling increased reload time significantly as the bandwidth and latency were artificially limited.
