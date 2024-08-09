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
#root_4\.8\.0\.1 > div > div > div > div > div.jiraDisabled__nav > div > button {background: firebrick;}
#root_4\.8\.0\.1 > div > div > div > div > div.jiraDisabled__nav > div > div {background: blue;}
#root_4\.8\.0\.1 > div > div > div > div > div.jiraDisabled__nav > div > div > div > div.css-14rjog3-Control > div {background: black;}
#root_4\.8\.0\.1 > div > div > div > div.qtm4j-nav-panel.sc-eTyWNx.Cukpe {background: firebrick;}
.qmTreeview__totalItems {background: deepskyblue !important;}
#root_4\.8\.0\.1 > div > div > div > div.module-content.sc-ekHBYt.eoLwfl > div.navbar-wrap > div.navbar.sc-imAxmJ.bcTifh {background: darkslategrey;}
#root_4\.8\.0\.1 > div > div > div > div.module-content.sc-ekHBYt.eoLwfl > div.navbar-wrap > div.navbar.sc-imAxmJ.bcTifh > div > div.project-selectBox > button{background: royalblue;}
#root_4\.8\.0\.1 > div > div > div > div.module-content.sc-ekHBYt.eoLwfl > div.navbar-wrap > div.navbar.sc-imAxmJ.bcTifh > div > div.case-tree-wrap > div > div.qmTreeviewFilter > div.qmTreeviewFilter__inner > div.qmTreeviewFilter__search > div > div.execution-search-area > form > div > div {background: dodgerblue;}
.qmTreeview__label.isActive {background: coral !important;}
.qmTreeview__label :hover {background: coral !important;}
#rendererDivForLinks {background:black;}
#root_4\.8\.0\.1 > div > div > div.create-body-tabs > div > div.detail-tab-content > div > div > div:nth-child(4) > div.\30 accordian_show__oAvKm > div > div > div:nth-child(10) > div > div > div > form > div > div > div > div > span  {background:black;}
#root_4\.8\.0\.1 > div > div > div.create-body-tabs > div > div.detail-tab-content > div > div > div:nth-child(5) > div.\30 accordian_show__oAvKm > div > div > div:nth-child(1) > div > div > div.sc-dvCyap.exixMl > form > div > div > div > div > span {background: black;}
#root_4\.8\.0\.1 > div > div > div.create-body-tabs > div > div.detail-tab-content > div > div.allowed-children > div > div > div > div  {background: black;}
.qtmTable__cell  {background: black;}
#root_4\.8\.0\.1 > div > div > div.create-body-tabs > div > div.detail-tab-content > div > div.attachment-action-panel {background: black;}
#root_4\.8\.0\.1 > div > div > div.create-body-tabs > div > div.detail-tab-content > div > div.attachment-action-panel > div.showingof-top {background: black;}
.qtmTable__cell {background: black !important;}
#root_4\.8\.0\.1 > div > div > div.create-body-tabs > div > div.detail-tab-content > div > div > div.tc-executions-table > div > div {background: cadetblue;}

```

Next, paste the code into custom CSS field and hit "Save"

![90fbfb721db0008ae03314dbd8b3b1c7](https://user-images.githubusercontent.com/37232530/166506231-28e070f3-1e26-4dc2-b097-811ae88827c2.png)
