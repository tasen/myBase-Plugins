# Overview

This folder contains the plugins for myBase 7.x.

> **Note:** These plugins are tested in win7 64bit system, and myBase 7.0 beta 19 only. If you want to use in MacOS or Linux environment, please fully test.
 
**Usage:**  
1. Closed the software  
2. Copy the plugin .js file to \plugins folder.  
3. Run the software again.  
4. Based on the setting of the plugins, you can find the new functions from different menus.  
5. More details can be found in myBase website: [http://www.wjjsoft.com/mybase_jsapi.html#install](http://www.wjjsoft.com/mybase_jsapi.html#install)

# Plugins Lists
## 1. Syntax highlight.js ##
The main contributor of this plugin is WJJ. This plugin supports Syntax highlight for C/C++, C/C++ with STL, Java, C#, Javascript, T-SQL, PHP, Google GO, GNU/R Language and Visual Basic and still **under development**.  
This function can be accessed by selecting the content and right click menu "Syntax highlight...".

## 2. SetFontSize.js (**Unofficial Plugin**)
This plugin can be used to set the font size of current info item.  
Please note, this plugin will change all the font size of the current info item and **do not have a reverse function**, meaning you **can not use** `crtl+z` to reverse back. Currently, the font size can be set between 5-40pt. You can find this function (**Set Font Size**) by right click in the input area.

## 3. Markdown related plugins (**Unofficial Plugin**)
> **Dependency:** The below two markdown related plugins use the interface provided by **marked.js**. To run these two plugins, you need first to download the **marked.js** from the project page: [https://github.com/chjj/marked](https://github.com/chjj/marked) and put to myBase \plugins folder.

### 3.1 Markdown2html.js (**Unofficial Plugin**)
This Plugin can change the markdown syntax contents in info item to HTML. You can access to this function by selecting the contents and by right click menu -> Text Utilities -> mdText2html

### 3.2 Markdownattach.js (**Unofficial Plugin**)
This Plugin can change the .md attachment to HTML info item. You can access to this function by right click the .md attachment menu -> .mdatt2InfoItem. Please note running this plugin **will replace all the original content** of the current info item and it **do not have** `crtl+z` function to reverse back.

## 4. WordCount.js (**Unofficial Plugin**)
This plugin can be used to calculate the word count of the selected contents of the info item. You can access to this function by selecting the content and via right click menu -> Text Utilities -> Word Count.

## 5. Calculate.js (**Unofficial Plugin**)
> **Dependency:** This plugin uses the interface provided by **math.js**. To run this plugin, you need first to download the **math.js** from the project page: [https://github.com/josdejong/mathjs](https://github.com/josdejong/mathjs) and put to myBase \plugins folder together with Calculate.js.
 
To access this function, you can highlight any math expression from the info item area and right click menu -> Text Utilities -> Calculate.  

**Example math expression:** `cos(20.9 deg) * 0.9342 / (3+9) * (2.3+5.87) / 11`  


