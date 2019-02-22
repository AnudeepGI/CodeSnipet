# Edit : 
atom ~/.bash_profile

# Custom from anudeep git
alias b='git branch'
alias c='git checkout'
alias d='git diff'
alias s='git status'
alias cm='git checkout master'
alias p='git push'
alias po='git push origin'
alias bcopy="git branch | grep '^\*' | cut -d' ' -f2 | pbcopy"

# Custom from anudeep git
alias startbkpack="nodemon -r dotenv/config app"

# Restart : 
source ~/.bash_profile
