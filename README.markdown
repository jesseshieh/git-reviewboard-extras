# Git Reviewboard Extras
Extra commands for using git with reviewboard.
This was tested on
- Mac OS X 10.7.3
- Reviewboard 1.6.6
- RBTools 0.4.1
- Git 1.7.10
- Bash 3.2.48(1)-release (x86_64-apple-darwin11)

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






