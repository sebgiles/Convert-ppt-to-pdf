Easily convert multiple files from PowerPoint to PDF.
PowerPoint is required for the script to work.
Documents are rendered by Microsoft PowerPoint and do not get scrambled (unlike what Preview or other thid party apps might do).

### App Usage:
1. Download as zip
2. Uncompress
3. Run "ppt to pdf.app"
4. Select all files to convert
5. Select and authorize PowerPoint to write to your directory
5. Wait and don't interfere. Can take a few seconds per file...
6. You will find pdf files with same name as ppt counterparts in the same folder.

本仓库提供了OS X系统下，批量转换doc/ppt文件为pdf的AppleScript脚本

This repository provides AppleScript that could convert doc/ppt to pdf using automator under OS X.

### AppleScript Usage

运行Automator，新建工作流程。

选择“获得指定的Finder项目”，添加需要转换的文件。(还可使用“过滤Finder项目”过滤出doc/docx/ppt/pptx)

选择“运行AppleScript”，复制对应的AppleScript，运行。

运行时需要提供访问权限。

Open Automator on OS X, and new a workflow.

Choosing "Get Finder items", add files. ("Filter Finder items" can help filter given file format, like doc/docx/ppt/pptx)

Choosing "Run AppleScript", and copy the script file content to the window, run it.

You need allow access permission while running.

### Thanks

[Apple Support Commnities: how do I use automator to batch convert doc to pdf?](https://discussions.apple.com/thread/3050596?start=0&tstart=0)

[StackExchange: how-do-i-get-automator-actions-for-microsoft-powerpoint-and-word](http://apple.stackexchange.com/questions/217004/how-do-i-get-automator-actions-for-microsoft-powerpoint-and-word)

[automatically-convert-powerpoints-to-pdf-in-os-x-with-automa](http://architechnic.net/architechnic/2012/11/1/automatically-convert-powerpoints-to-pdf-in-os-x-with-automa.html)

[Mac Basics: Automator](https://support.apple.com/en-us/HT2488)



2016.4
