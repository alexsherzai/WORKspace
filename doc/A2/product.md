# Assignment 2 Report
Group memebers: Edward (Jong Yeon Kim) Fjura, Alex Sherzai, Songtao Bu, Owen Ramirez  
CS4540 Topics in Advanced Programming
CSULA  

## Summary
During the second phase of work, we decided that since we had a minimum viable solution estasblish, it would be in our best interest to explore the different medium of representation for the software.  
We tried looking into different forms out GUI options available in displaying the program such as sidebars or a panel that drops down from a button on the toolbar. We ultimately opted to go for trying out the sidebars functionality as we felt that the speed (based on the shortcut options) as well as an easier flexbility in size and design options.  
While we are not fully content in using the sidebars as a way to display the necessary info, that is the option we decided to stick to now. We made a quick decision as we ultimately learned that extensions are extremely flexible since we are able to use HTML and CSS to stylize as well as redo any formatting without spending any exorbitant amount of time.

## High-Level Vision
The goal for the program is to be able to create more than just 4 panel-like containers that the user has some customizablity with. With panels that act like similar to a post-it note, users will be able to save tabs and important links easily.  

``` 
"commands": {
    "_execute_sidebar_action": {
        "suggested_key": {
            "default": "Ctrl+Shift+Y"
        }
    }
}
```

## Technical Highlights
While working on this version of the project, we were able to learn new things about accessing and referring to specific parts of a code structure in CSS as well as start to learn Javascript. While not many of us are heavily into the web design topics, we found that most of our troubles came from design choices as well as the foreign syntaxing and structure of web extensions as well as the programming languages themselves. One of the things we ended up learning that was very interesting was about specificity in the CSS strucutre.  

```[id^="content_"]```  

allows CSS to specifically target elements with an id that starts with "content_". With this, we were able to, for now, create 4 distinct text boxes as well as stylize them in unison.  

Another aspect of the program we decided to include was an indicator that the user's mouse has entered the sidebar. In order to achieve this, we decided to change the color of the textbox.  

![image_1](/repo/images/mousehover_in.png)
![image_2](/repo/images/mousehover_out.png)

## Team Reflection
During this portion of the project, we learned that we as seniors had a hard time trying to find a good time to meet up and congregate regularly. Therefore, we opted to adopt a schedule where we would only meet if we had speaking points while questions regarding the project scope and technical issues were handled and addressed directly within a group messaging platform. 
