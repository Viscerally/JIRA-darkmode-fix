# JIRA-darkmode-fix
This repo contains custom CSS for EA NHL Jira that fixes readiblility issues with the default darkmode

The steps to enable the fix are quite easy.

First, open the darkmode settings by clicking on your profile and selecting "DarkTheme Settings"

Next, copy the code below into your clipboard:

```
.qrf-rich-view-label {
background-color: #344563;
}
.qrf-rich-views {
background-color: #3e147a3b !important;
}
#ktm-application-110538 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {background: #bdb76b36;
}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control > div > button.aui-button.aui-button-split-main.ktm-test-results-more {
background: darkslategrey;}

div.issue-data-block.activity-comment.twixi-block.expanded:hover {
background-color: #0a3a32 !important;
}

#main > table > thead:nth-child(n) > tr:nth-child(n) > th:nth-child(n) {
background-color: black !important;
}

#main > table > tbody:nth-child(n) > tr:nth-child(n) > td:nth-child(n) {
background-color: black !important;
}

div.issue-data-block:hover  {
background-color: #0a3a32 !important;
}

input#issue-workflow-transition-submit:hover {
color: #1e88e5 !important;
}

.issue-data-block:hover, .issue-data-block.focused {
background-color: #0a3a32 !important;
}

#content > div > div > div > floating-header > div > ng-transclude > header-content > aui-navigation > nav > div > div {
background-color: #1e28e5;
}

#content > div > div > div > floating-header > div > div {
background-color: black
}

#content > div > div > div > div.aui-page-panel > div > form.aui.ng-pristine.ng-valid.ng-valid-required.ng-valid-time.ng-valid-number.ng-valid-max-tags.ng-valid-min-tags.ng-valid-leftover-text > ng-include > div > div:nth-child(2) > div.ktm-collapsable-section-header > div > form > h3 {
background-color:#46721b;
}

h3.ng-binding {
background-color:#46721b !important;
}

#content > div > div > div > floating-header > div > ng-transclude > header-content > aui-navigation > nav > div > div > ul > li.ng-scope.ng-isolate-scope.aui-nav-selected > a {background-color: #1e28e5;
}

#content > div > div > div > floating-header > div > ng-transclude > header-content > aui-navigation > nav > div {
background-color: darkslategrey;
}

#content > div > div > div > div.aui-page-panel > div > form.aui.ng-valid.ng-valid-required.ng-valid-time.ng-valid-number.ng-valid-max-tags.ng-valid-min-tags.ng-valid-leftover-text.ng-dirty.ng-valid-parse > ng-include > div > div:nth-child(4) > div.ktm-collapsable-section-content.ng-scope > div:nth-child(3) > tags-input > div > div {background-color: #252526 !important;
}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div:nth-child(2) > div > div.ktm-test-player-run-data-body.ng-scope {background: darkslategrey;
}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div {background: darkslategrey;
}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div {background: darkslategrey;
}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control {background: #2f4f4f;}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control > div > button.aui-button.aui-button-split-more.ktm-test-results-more.aui-dropdown2-trigger {    background: darkslategrey !important;}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(6) > div.ktm-collapsable-section-header > div > form > ul {background: darkslategrey !important;}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-header > div > form > ul {background: darkslategrey !important;}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-index.ktm-testscript-transparent.ng-scope {    background: darkslategrey !important;}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-data.ktm-testscript-transparent {background: darkslategrey;}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-data.ktm-testscript-transparent > step-info > div {background: darkslategrey;
}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-step-action-bar-container > step-action-bar > div > ul {background: darkslategrey;}

#ktm-test-player-scope > div.ktm-test-player-scope-single-view.ng-scope > div.ktm-header {
background: black;
}

#ktm-test-player-scope > div.ktm-test-player-scope-single-view.ng-scope > div.ktm-groups-list.ng-scope > ol > li > ol > li.ng-scope.ktm-testplayer-selected > div > div.aui-item.ktm-testplayer-testresults-data {
background: green;}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control > div > button.aui-button.aui-button-split-main.ktm-test-results-more > span.ng-binding {color: black !important;}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control > span > span.aui-lozenge.ng-binding.ng-scope.ng-isolate-scope {background: black;}
body[data-aui-version^="9"] .aui-navgroup-horizontal:before, body[data-aui-version^="9"] .aui-tabs.horizontal-tabs>.tabs-menu:before, body[data-aui-version^="9"] .aui-navgroup-horizontal .aui-nav>.aui-nav-selected a:before, body[data-aui-version^="9"] .aui-tabs.horizontal-tabs>.tabs-menu>.menu-item.active-tab a:before {background: #1e2ae5;
}

#ktm-library-folder-tree > react-folder-tree > div > div:nth-child(3) > div.ktm-folder-tree-item.isSelected.css-hlzk95-DraggableFolder.ejddkck0.ui-droppable {
background: crimson;}
div.ktm-folder-tree-item:hover {
background: crimson;}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control > span > span.aui-lozenge.ng-binding.ng-scope.ng-isolate-scope {
color: black !important;}

#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-data.ktm-testscript-transparent > step-info > div > span.aui-lozenge.ng-binding.ng-scope.ng-isolate-scope {
color: black !important;}

#content > div > div > div > div.aui-page-panel > div > form.aui.ng-pristine.ng-valid.ng-valid-required.ng-valid-time.ng-valid-number.ng-valid-max-tags.ng-valid-min-tags.ng-valid-leftover-text > ng-include > div > div:nth-child(4) > div.ktm-collapsable-section-content.ng-scope > div:nth-child(3) > tags-input > div > div {background: slategray}
#rte-plain-testscript > div > div {background: #000000d1;}

#ktm-testplan-list > react-folder-tree > div > div:nth-child(3) > div {background: crimson;}

#content > div > div > div > div.ktm-inner-content-panel > div > div.ktm-testplan-panel > div.ktm-grid-wrapper > refresher > grid > span > table > thead > tr > th:nth-child(3) {background: #1475ed;}
.css-hlzk95-DraggableFolder:active {
background: crimson !important;
}
.css-hlzk95-DraggableFolder.isSelected {
background: crimson !important;
}

#main > div > div.navigator-group > div > div > div > div.aui-group.aui-group-split.count-pagination {
background: black;
}
.ktm-test-player-scope-single-view .ktm-groups-list .ktm-groups .ktm-testplayer-testresults li:hover { background-color: green !important;
}

#ktm-application-110538 > gadget-view > div > div.ktm-gadgets-view {
background: #1e88e5;}

#ktm-reports-chart-37 > svg {
background: #1e88e5; }
#ktm-reports-chart-13 > svg {
background: #1e88e5; }
#ktm-application-111226 > gadget-view > div > div.ktm-gadgets-view{
background: #1e88e5;}
#ktm-reports-chart-21 > svg {
background: #1e88e5;}
#ktm-reports-chart-53 > svg {
background: #1e88e5;}
#ktm-application-110503 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background: #bdb76b36;}
#ktm-application-110506 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background: #bdb76b36;}
#ktm-application-111226 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background: #bdb76b36;}
#ktm-application-111228 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background: #bdb76b36;}
#ktm-application-110535 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background: #bdb76b36;}
#ktm-application-126166 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background:black;}
.ktm-gadgets-view-wrapper .ktm-gadgets-view-header
{background: black !important;}
.qrf-rich-view-label {
    background-color: #344563;
    }
     .qrf-rich-views {
    background-color: #3e147a3b !important;
 }
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view > div.ktm-test-player-run-data-wrapper > div > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-header > div > form > ul {background: darkgrey;}


#ktm-application-110538 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {background: #bdb76b36;
}
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control > div > button.aui-button.aui-button-split-main.ktm-test-results-more {
    background: darkslategrey;}
    div.issue-data-block.activity-comment.twixi-block.expanded:hover {
    background-color: #0a3a32 !important;
    }
    
    #main > table > thead:nth-child(n) > tr:nth-child(n) > th:nth-child(n) {
    background-color: black !important;
    }
    
    #main > table > tbody:nth-child(n) > tr:nth-child(n) > td:nth-child(n) {
    background-color: black !important;
    }
    
    div.issue-data-block:hover  {
    background-color: #0a3a32 !important;
    }
    input#issue-workflow-transition-submit:hover {
    color: #1e88e5 !important;
    }
    
    .issue-data-block:hover, .issue-data-block.focused {
    background-color: #0a3a32 !important;
    }
    #content > div > div > div > floating-header > div > ng-transclude > header-content > aui-navigation > nav > div > div {
    background-color: #1e28e5;
    }
    #content > div > div > div > floating-header > div > div {
    background-color: black
    }
    #content > div > div > div > div.aui-page-panel > div > form.aui.ng-pristine.ng-valid.ng-valid-required.ng-valid-time.ng-valid-number.ng-valid-max-tags.ng-valid-min-tags.ng-valid-leftover-text > ng-include > div > div:nth-child(2) > div.ktm-collapsable-section-header > div > form > h3 {
    background-color:#46721b;
    }
    h3.ng-binding {
    background-color:#46721b !important;
    }
    #content > div > div > div > floating-header > div > ng-transclude > header-content > aui-navigation > nav > div > div > ul > li.ng-scope.ng-isolate-scope.aui-nav-selected > a {background-color: #1e28e5;
    }
    #content > div > div > div > floating-header > div > ng-transclude > header-content > aui-navigation > nav > div {
    background-color: darkslategrey;
    }
    #content > div > div > div > div.aui-page-panel > div > form.aui.ng-valid.ng-valid-required.ng-valid-time.ng-valid-number.ng-valid-max-tags.ng-valid-min-tags.ng-valid-leftover-text.ng-dirty.ng-valid-parse > ng-include > div > div:nth-child(4) > div.ktm-collapsable-section-content.ng-scope > div:nth-child(3) > tags-input > div > div {background-color: #252526 !important;
    }
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div:nth-child(2) > div > div.ktm-test-player-run-data-body.ng-scope {background: darkslategrey;
    }
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div {background: darkslategrey;
    }
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div {background: darkslategrey;
    }
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control {background: #2f4f4f;}
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control > div > button.aui-button.aui-button-split-more.ktm-test-results-more.aui-dropdown2-trigger {    background: darkslategrey !important;}
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(6) > div.ktm-collapsable-section-header > div > form > ul {background: darkslategrey !important;}
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-header > div > form > ul {background: darkslategrey !important;}
    
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-index.ktm-testscript-transparent.ng-scope {    background: darkslategrey !important;}
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-data.ktm-testscript-transparent {background: darkslategrey;}
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-data.ktm-testscript-transparent > step-info > div {background: darkslategrey;
    }
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-step-action-bar-container > step-action-bar > div > ul {background: darkslategrey;}
    #ktm-test-player-scope > div.ktm-test-player-scope-single-view.ng-scope > div.ktm-header {
    background: black;
    }
    #ktm-test-player-scope > div.ktm-test-player-scope-single-view.ng-scope > div.ktm-groups-list.ng-scope > ol > li > ol > li.ng-scope.ktm-testplayer-selected > div > div.aui-item.ktm-testplayer-testresults-data {
    background: green;}
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control > div > button.aui-button.aui-button-split-main.ktm-test-results-more > span.ng-binding {color: black !important;}
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control > span > span.aui-lozenge.ng-binding.ng-scope.ng-isolate-scope {background: black;}
    body[data-aui-version^="9"] .aui-navgroup-horizontal:before, body[data-aui-version^="9"] .aui-tabs.horizontal-tabs>.tabs-menu:before, body[data-aui-version^="9"] .aui-navgroup-horizontal .aui-nav>.aui-nav-selected a:before, body[data-aui-version^="9"] .aui-tabs.horizontal-tabs>.tabs-menu>.menu-item.active-tab a:before {background: #1e2ae5;
    }
    #ktm-library-folder-tree > react-folder-tree > div > div:nth-child(3) > div.ktm-folder-tree-item.isSelected.css-hlzk95-DraggableFolder.ejddkck0.ui-droppable {
    background: crimson;}
    div.ktm-folder-tree-item:hover {
    background: crimson;}
    
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div:nth-child(1) > div > div.ktm-test-player-time-control > span > span.aui-lozenge.ng-binding.ng-scope.ng-isolate-scope {
    color: black !important;}
    
    #content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-test-player-run-data-wrapper.ng-scope > div > div.ktm-test-player-run-data.ng-scope > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-data.ktm-testscript-transparent > step-info > div > span.aui-lozenge.ng-binding.ng-scope.ng-isolate-scope {
    color: black !important;}
    #content > div > div > div > div.aui-page-panel > div > form.aui.ng-pristine.ng-valid.ng-valid-required.ng-valid-time.ng-valid-number.ng-valid-max-tags.ng-valid-min-tags.ng-valid-leftover-text > ng-include > div > div:nth-child(4) > div.ktm-collapsable-section-content.ng-scope > div:nth-child(3) > tags-input > div > div {background: slategray}
    #rte-plain-testscript > div > div {background: #000000d1;}
    #ktm-testplan-list > react-folder-tree > div > div:nth-child(3) > div {background: crimson;}
    #content > div > div > div > div.ktm-inner-content-panel > div > div.ktm-testplan-panel > div.ktm-grid-wrapper > refresher > grid > span > table > thead > tr > th:nth-child(3) {background: #1475ed;}
    .css-hlzk95-DraggableFolder:active {
    background: crimson !important;
    }
    .css-hlzk95-DraggableFolder.isSelected {
    background: crimson !important;
    }
    #main > div > div.navigator-group > div > div > div > div.aui-group.aui-group-split.count-pagination {
    background: black;
    }
    .ktm-test-player-scope-single-view .ktm-groups-list .ktm-groups .ktm-testplayer-testresults li:hover { background-color: green !important;
    }
#ktm-application-110538 > gadget-view > div > div.ktm-gadgets-view {
background: #1e88e5;}
#ktm-reports-chart-37 > svg {
background: #1e88e5; }
#ktm-reports-chart-13 > svg {
background: #1e88e5; }
#ktm-application-111226 > gadget-view > div > div.ktm-gadgets-view{
background: #1e88e5;}
#ktm-reports-chart-21 > svg {
background: #1e88e5;}
#ktm-reports-chart-53 > svg {
background: #1e88e5;}
#ktm-application-110503 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background: #bdb76b36;}
#ktm-application-110506 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background: #bdb76b36;}
#ktm-application-111226 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background: #bdb76b36;}
#ktm-application-111228 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background: #bdb76b36;}
#ktm-application-110535 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background: #bdb76b36;}
#ktm-application-126166 > gadget-view > div > div.ktm-gadgets-view-header.ng-binding.ng-scope {
background:black;}
.ktm-gadgets-view-wrapper .ktm-gadgets-view-header
{background: black !important;}
#ktm-reports-chart-61 > svg {
background: antiquewhite;
}
#ktm-application-128109 > gadget-view > div > div.ktm-gadgets-view > reports-viewer-overall-progress > div > div > span {
background: darkcyan;
}
#ktm-application-128109 > gadget-view > div > div.ktm-gadgets-view {
background: burlywood;
}
#ktm-application-128111 > gadget-view > div > div.ktm-gadgets-view {
background: steelblue;
}
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view > div.ktm-test-player-run-data-wrapper > div > div > div.ktm-test-player-run-data-body.ng-scope {
background: darkslategrey
}
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view > div.ktm-test-player-run-data-wrapper > div > div > div:nth-child(1) > div {
background: darkslategray;
}
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view > div.ktm-test-player-run-data-wrapper > div > div > div:nth-child(1) > div > div.ktm-test-player-time-control {
background: darkslategray;
}
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view > div.ktm-test-player-run-data-wrapper > div > div > div:nth-child(1) > div > div.ktm-test-player-time-control > div > button.aui-button.aui-button-split-more.ktm-test-results-more.aui-dropdown2-trigger {
background: darkslategrey !important;}
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view {
background: darkslategrey;
}
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view > div.ktm-test-player-run-data-wrapper > div > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-data.ktm-testscript-transparent {
background: darkslategrey;
}
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view > div.ktm-test-player-run-data-wrapper > div > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-index.ktm-testscript-transparent.ng-scope {
background: darkslategrey;}
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view > div.ktm-test-player-run-data-wrapper > div > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(6) > div.ktm-collapsable-section-header > div > form > ul {background: darkgrey;}
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view > div.ktm-test-player-run-data-wrapper > div > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-testscript-step-data.ktm-testscript-transparent > step-info > div {
background: darkslategrey;}
#content > div > div > div > div.aui-page-panel.ng-scope > div.ktm-test-player-content > div.ktm-result-details-single-view > div.ktm-test-player-run-data-wrapper > div > div > div.ktm-test-player-run-data-body.ng-scope > div:nth-child(9) > div > div.ktm-collapsable-section-content.ng-scope > ng-include > div > div > div > div > div.ktm-step-action-bar-container > step-action-bar > div > ul {
background: darkslateblue;}
```

Next, paste the code into custom CSS field and hit "Save"

![90fbfb721db0008ae03314dbd8b3b1c7](https://user-images.githubusercontent.com/37232530/166506231-28e070f3-1e26-4dc2-b097-811ae88827c2.png)
