# eclipse-note
Setting up eclipse environment

### Basic Plugin
* __Babel Language Pack__
    1. Get repository link in [babel](http://www.eclipse.org/babel/downloads.php)<br>
        `http://download.eclipse.org/technology/babel/update-site/R0.13.1/mars`
    2. Install:<br>
        _Babel Language Pack in Chinese (Traditional)_ <br>
        _Babel Language Pack for eclipse in Chinese (Traditional)(81.33%)_

* __Color Theme__
    <br>Link: `http://eclipse-color-theme.github.io/update/`

* __Subclipse__
    <br>Get repository link in [subclipse](http://subclipse.tigris.org/)<br>
    The version need match with subversion client<br>
    Link: `http://subclipse.tigris.org/update_1.10.x`

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
    
