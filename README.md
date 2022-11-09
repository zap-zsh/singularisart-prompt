# SingularisArt prompt

![main](images/1.png)

Visible here are:

- Concise left-hand prompt consisting of:
  - Last component of current directory (abbreviates $HOME to ~ if possible).
  - Prompt marker, ❯, the
    ["HEAVY RIGHT-POINTING ANGLE QUOTATION MARK ORNAMENT"](https://codepoints.net/U+276F)
    (that's `\u276f`, or `e2 9d af` in UTF-8).
- Extended right-hand size prompt which auto-hides when necessary to make room
  for long commands and contains:
  - Duration of previous command in adaptive units (seconds, minutes, hours,
    days, depending on duration).
  - Current version control branch name.
  - Current version control worktree status using colors that match those used
    in `git status`:
    - Green dot indicates staged changes.
    - Red dot indicates unstaged changes.
    - Blue dot indicates untracked files.
  - Full version of current working directory (again, abbreviating `$HOME` to
    `~`).

Nested shells are indicated with additional prompt characters. For example, one
nested shell:

<img src="https://raw.githubusercontent.com/zap-zsh/singularisart-prompt/master/images/2.png">

Two nested shells:

<img src="https://raw.githubusercontent.com/zap-zsh/singularisart-prompt/master/images/3.png">

Root shells are indicated with a different color prompt character and the word
"root":

<img src="https://raw.githubusercontent.com/zap-zsh/singularisart-prompt/master/images/4.png">

Nesting within a root shell is indicated like this:

<img src="https://raw.githubusercontent.com/zap-zsh/singularisart-prompt/master/images/5.png">

Two nested shells:

<img src="https://raw.githubusercontent.com/zap-zsh/singularisart-prompt/master/images/6.png">

Tmux shells are indicated with a different color prompt character and the word
"tmux":

<img src="https://raw.githubusercontent.com/zap-zsh/singularisart-prompt/master/images/7.png">

Nesting within a tmux shell is indicated like this:

<img src="https://raw.githubusercontent.com/zap-zsh/singularisart-prompt/master/images/8.png">

Two nested shells:

<img src="https://raw.githubusercontent.com/zap-zsh/singularisart-prompt/master/images/9.png">

If the last command exited with a non-zero status (usually indicative of an
error), a yellow exclamation is shown:

<img src="https://raw.githubusercontent.com/zap-zsh/singularisart-prompt/master/images/10.png">

If there are background processes, a yellow asterisk is shown:

<img src="https://raw.githubusercontent.com/zap-zsh/singularisart-prompt/master/images/11.png">
