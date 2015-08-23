LanguageTool
============

This is an image of the original source, which is: http://www.vim.org/scripts/script.php?script_id=3223

To Install, for Windows users, 

1. You can use Vundle to install the Vim-plugin from this repo, using: 

 Plugin 'llinfeng/LanguageTool'

  
2. To insall the LanguageTool Java distribution, download the `Stand-alone` version of LanguageTool from this address: 
  
  https://www.languagetool.org/

  Alternatively, one can: 
  
  * Find obsolete builds of langaugeTool at: https://www.languagetool.org/download/
  * Find nightly built (yet may be unstable) at: http://www.languagetool.org/download/snapshots/

3. Put the following line in your _vimrc

  let g:languagetool_jar='~SomethingHere\LanguageTool-X.X\languagetool-commandline.jar'

4. Install `Java JDK` from Oricale, and **restart the machine**. This will enable `java` as a command from CMD (command line) of Windows.

This would be good enough to have languagetool run for Windows users. (I have tested it on my Windows 8.1 machine and my screenshoot recording the successful run could be found here: https://onedrive.live.com/redir?resid=BC086804FCAEF04F%2117513).
