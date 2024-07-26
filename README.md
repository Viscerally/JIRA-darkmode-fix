# JIRA-darkmode-fix
This repo contains custom CSS for EA FB Jira that fixes readiblility issues with the default darkmode

The steps to enable the fix are quite easy.

NOTE: *If you are updating the CSS remember to delete the old code before pasting in the new one below*

First, open the darkmode settings by clicking on your profile and selecting "DarkTheme Settings"

Next, copy the code below into your clipboard:

```
#filter-wrapper > div > div > div > button {background-color: cornflowerblue;}
#block-add-root-comment > button {background-color: #6b778c !important;}
#customfield_43800 > div.o-checklist-subcontainer.o-checklist-limited-width > div.add-item-section > div.add-item-actions > div > button.add-checklist-item > span {color: black !important;}
#customfield_43800 > div.o-checklist-subcontainer.o-checklist-limited-width > div.add-item-section > div.add-item-actions > div > button.add-checklist-header-item > span {color: black !important;}

```

Next, paste the code into custom CSS field and hit "Save"

![90fbfb721db0008ae03314dbd8b3b1c7](https://user-images.githubusercontent.com/37232530/166506231-28e070f3-1e26-4dc2-b097-811ae88827c2.png)
