## Linking to another web page in the same project

Web projects can be made up of lots of HTML files linked together.

+ Trinketをひらく: <a href="http://jumpto.cc/web-rooms" target="_blank">jumpto.cc/web-rooms</a>.
    
    プロジェクトはこのようになります。
    
    ![スクリーンショット](images/rooms-starter.png)

+ The trinket should autorun and you will find yourself in the Hall:
    
    ![スクリーンショット](images/rooms-hall-start.png)

+ Look at the list of file tabs for this trinket. Can you see `tvroom.html`? Click on it.
    
    ![スクリーンショット](images/rooms-tvroom-html.png)
    
    This is another html file in the same project.

+ To get to `tvroom.html` you need to add a link in `index.html`.
    
    Add the highlighted code inside the `<div>` with the class `room`:
    
    ![スクリーンショット](images/rooms-link-tvroom.png)

+ Test your trinket by clicking on the **TV Room** link to see the `tvroom.html` webpage.
    
    Note that `tvroom.html` also has its own `tvroom.css` style file which defines the layout for this page.
    
    ![スクリーンショット](images/rooms-tvroom-unstyled.png)