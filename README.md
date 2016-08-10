# VSProjectTemplateWithWizard
The origin of this project is a sample application without a working wizard. This repo was forked to fix the wizard, so it should now be working as expected.

The original repo was created to get an answer to this question at StackOverflow: http://stackoverflow.com/questions/38791026/visual-studio-project-template-with-custom-wizard

If you clone this repository and run the project you'll have to set **Debug -> Start Action** to **Start external program** and set the path to Visual Studio, typically C:\Program Files (x86)\Microsoft Visual Studio 14.0\Common7\IDE\devenv.exe. Then add the following to **Command line arguments**: /rootsuffix Exp

## Update
The question at StackOverflow has been answered and the fix can be found in this fork:
https://github.com/karolikl/VSProjectTemplateWithWizard
