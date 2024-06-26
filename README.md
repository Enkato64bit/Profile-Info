## `*Credentials*`  
[credentials](#credentials.csv)  
[Config-Files](#config-files.json)  
___  
[Custom-Search-Engines](#custom-search-engines.csv)  

```html
google.com/searchq=%s
```
___  
### Markdown-Snippets  
#### ipsem  
[Comment](#comment)  

      ```
    <! -- your comment -->    
    ```
Renders as 

 ```
 <! -- your comment -->  
 ```
# Table-Snippet

[Table]

|-Shortcut-|-Description-|-url-|
|------|------|------|  
|-co1-|-col2-|-col3-|
|'@chrome-extension'|[temp1](1)|1|
|'@edge-extension'|[temp2](2)|2|
|'@installed-extension'|[temp3](3)|3|
|'@chrome-extension'|[temp1](1)|1|
|'@edge-extension'|[temp2](2)|2|
|'@installed-extension'|[temp3](3)|3|
|'@chrome-extension'|[temp1](1)|1|
|'@edge-extension'|[temp2](2)|2|

## Embed Images via Google Drive to Github Repository

### via <FILE_ID>  

For example, I have a.jpg on the google drive.

1. Right click the image and click Share...

2. Click Advanced and change the Who can access option to Public on the web - Anyone on the Internet

3. Copy the link to share and you will have something like
https://drive.google.com/file/d/<FILE_ID>/view?usp=sharing

4. Copy the <FILE_ID> to make a link like this:
https://drive.google.com/uc?export=view&id=<FILE_ID>

Insert image in Markdown as ususal using the link from step 4.
For example: ![image](https://drive.google.com/uc?export=view&id=<FILE_ID>)
Example: I have this octocat image in google, and its file id is 1913oZeBZPBNiUuk8gu3ZSbLBA2l_VQtG. You can try ![image](https://drive.google.com/uc?export=view&id=1913oZeBZPBNiUuk8gu3ZSbLBA2l_VQtG) in your markdown file or even in this answer.



https://drive.google.com/file/d/179O0CK_8pXQTls2iLJKr7wSOybLvqUwR/view?usp=sharing
![Map of Incident Location](https://drive.google.com/uc?export=view&id=179O0CK_8pXQTls2iLJKr7wSOybLvqUwR)  

###  Embedded Images via repo

Try this markdown:

    ![alt text](http://url/to/img.png)

I think you can link directly to the raw version of an image if it's stored in your repository. i.e.

    ![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)
