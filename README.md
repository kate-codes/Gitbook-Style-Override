# Gitbook-Style-Override
Gitbook Formatting in Stylebot Quality of Life Improvement
https://stylebot.dev/

1. Stickies the TOC to the left side and minimizes the title content in it
2. Stickies the Right hand panel for editing docs 
3. Enables the middle column to extend across the entire page (making it a lot easier to work with code) 

![Preview](https://gblobscdn.gitbook.com/assets%2F-MlE00DIa5ytGo6NvZAj%2F-MlE1cPni_c76_MyC8ta%2F-MlE1o_9XqUoVtjzrtKn%2Fimage.png?alt=media&token=b5f8a656-dfc8-4fad-a190-75806a974be3)

Recommended only for use with the desktop application. 


Examples: 
[This example gitbook](https://app.gitbook.com/@kcodes-gitbook/s/gitbook-style-override/)

Then copy-paste the following into the code section. 
```
.reset-3c756112--pageContainer-544d6e9c {
    flex: 1 1 auto;
    margin: 0px 16px;
    display: block;
    padding: 0px 0px 64px;
    max-width: 3000px;
    min-width: 0px;
}

.reset-3c756112--wholeContentPage-6c3f1fc5 {
    flex: 1 1 auto;
    margin: 0px;
    display: flex;
    padding: 0px;
    max-width: 100%;
    min-width: 0px;
    background: rgb(255, 255, 255);
    flex-direction: column;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
}

.reset-3c756112--contentNavigation-dd3370a4 {
    flex: 0 0 auto;
    /* max-width: calc((100% - 1448px) / 2 + 298px); */
    width: 300px;
    display: flex;
    z-index: 15;
    min-width: 298px;
    background: rgb(245, 247, 249);
    align-items: stretch;
    border-right: 1px solid rgb(230, 236, 241);
    padding-left: 0;
    /* padding-left: calc((100% - 1448px) / 2); */
    flex-direction: column;
    -webkit-box-align: stretch;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
}
```
