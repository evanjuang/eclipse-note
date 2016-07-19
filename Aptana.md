### Aptana
* __Installing via Eclipse__
    <br>Link: `http://download.aptana.com/studio3/plugin/install`

* __Install CI Bundle__
    <br>
    Open studio terminal<br>
    ```bash
    $ cd Aptana\ Rubles/
    
    $ git clone git://github.com/hicode/codeigniter.ruble.git
    ```
* __Format CI Coding Style__
    1. General => Workspace:
        * Text file encoding: `UTF-8`
        * New text line delimiter: `UNIX`
    2. Aptana Studio => Formatter => PHP:
        * Add new profile 'CI' 
        * Edit profile:
            * New Lines: Choose `Insert new line before 'else' statement`
            * Indentation => Tab policy: `Tab only`
            * Braces => Function delicaration: `New line`
            * Spaces => Operator:
                * `Unary Operators`: After=1
                * `Invocation Operators`: Before=After=0
    3. Apply Fomatter:
        * Source => Fomat
    
