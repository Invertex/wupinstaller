This is not a branch to build upon.<br/>
I've simply merged the WUPinstaller code with the latest source of the ksploit, and removed some conditionals and error checks that aren't working correctly on 5.4 likely due to incorrect offsets. As well as a few minor things that probably aren't important.<br/>
Current master build can only install WUPs that that are very small on 5.4, because it triggers an error very quickly that halts the installation.<br/>
So this is a temporary fix to get around that until someone with better tools and knowledge like crediar can properly repair it.<br/>