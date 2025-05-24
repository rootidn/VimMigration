Vim on VsCode

====================================================

>> vscode Commands

setup profile: activity bar > settings > profile
setup commands : cmd+k+s

file
    cmd+t : function search

workspace
    cmd+p : search file
    cmd+j : terminal
    cmd+b : sidebar
    cmd+shift+e : explorer
    cmd+shift+x : extension activity bar
    cmd+alt+b : secondary sidebar (copilot)
    cmd+s cmd+b: status bar
    cmd+/ : comment line
    cmd+shift+< : switch tab (back)
    cmd+shift+> : switch tab (next)

undo
        cmd+t : go function (but nvim should have it)
        cmd+[ : switch tab
        cmd+shift+] : move tab
 
    *conflict to cmd+s (rollback: cmd+shift+p > "Preferences: Open Keyboard Shortcuts (JSON)" > delete command)

====================================================

:100 > go to line 100
:10j > down 10 line

modal editor
    - normal mode (escaped) : edit something
        navigation and search
            h/j/k/l : left/down/up/right
            w : next word
            W : next big word
            b : back one word
            B : back one big word
            ^ : first non white space in line
            0 : beginning of line
            $ : end of line
            gg : top of file
            G : bottom of file
            / : find forward
        changing
            cw : change word
            ci" : change inside "
            :x : delete char on cursor
            :dd : delete a line
            > : indent
            < : unindent
        copy-paste
            yw : copy a word
            yy : copy line
            "+y : copy to clipboard
            d : cut
            p : paste bellow
            P : paste above
            "+p : paste from clipboard bellow
        save/quit
            u : undo
            cmd+r : redo 
            :w : save
            :q : quit
            :wq : save and quit
    - insert mode
        type
            i : at cursor position
            I : at beginning of line
            a : after cursor position
            A : at end of line
            o : open new line after
            O : open new line before 
>> extension
>> resources
    - vimtutor
    - vim adventure (web)
    - smash into vim (web)