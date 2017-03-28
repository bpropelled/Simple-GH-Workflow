# Simple Github Workflow
## Step 1 - Create a local repo and  init it
```html
git init
```

## Step 2 Got to GH and create a repo, grab link and link rep to local
```html
git remote add origin https:///XXXXXXXXXXXXXX
```

## Step 3 - Add files
#### Add All
```html
git add .
```
#### Add specific
```html
git add README.md
```

## Step 4 - Commit Changes
```html
git commit -m "make a note about the commit"
```

## Step 5 - Push to Master
```html
git push origin master
```


# Tip, stop asking me for creds with every push
```html
$ git config --global credential.helper wincred
```
Here is another example .gitignore file:

# no .a files
*.a

# but do track lib.a, even though you're ignoring .a files above
!lib.a

# only ignore the TODO file in the current directory, not subdir/TODO
/TODO

# ignore all files in the build/ directory
build/

# ignore doc/notes.txt, but not doc/server/arch.txt
doc/*.txt

# ignore all .pdf files in the doc/ directory
doc/**/*.pdf
