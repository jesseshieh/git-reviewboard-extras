# Git Reviewboard Extras
Extra commands for using git with reviewboard

## Installation

1. Clone this repository somewhere
2. Add the new `git-reviewboard-extras` directory to your `PATH`.  I put the following in my ~/.bashrc

```bash
    # Add the git-reviewboard-extras to your path if you have it
    if [[ -d "$HOME/Development/git-reviewboard-extras" ]]; then
      export PATH="$HOME/Development/git-reviewboard-extras:$PATH"
    fi
```

## Usage
### `$ git reviewbranch`
Posts a new review to reviewboard for this branch compared to master.  
If you've previously posted a review for this branch already, then this updates 
that review.  




