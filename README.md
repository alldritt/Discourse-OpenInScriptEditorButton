# Open in Script Editor Button

This Discourse Theme Component adds an Open in Script Editor button below AppleScript code blocks.

## Discourse Configuration

1. Add `applescript` to the `highlighted languages` Discourse setting.

2. _Optional_ - You can make AppleScript the default language for code blocks by setting the `default code lang` Discoursse setting to `applescript`.

    If you do not make AppleScript the default language, your forum users must explicitly indicate their code is AppelScript code:
  

        ```applescript
        your code goes here...
        ```


3. The **Open in Script Editor Button** theme component has two settings of its own:

   - Button Title: the title of the button appearing below AppleScript code blocks.

   - Editor Schema: the URL scheme used to open scripts.  99% of the time this should be `applescript` which opens code in the user's default AppleScript Editor.  The `sdapplescript` schema forces scripts to be opened in [Late Night Software's Script Debugger](http://latenightsw.com) which the user may not have installed.

