First thing we probably want to do is to set our git environment with
our information. This is not mandatory, but if care about authoring
your work and definitely if work collaboratively you will do that:
```
$ git config --global user.name "Your Name Comes Here"
$ git config --global user.email you@yourdomain.example.com
```


When starting a _project_ from the scratch, we _init_ a repository:
```bash
$ mkdir stories
$ cd stories/
$ git init
Initialized empty Git repository
```

If the _project_ already exists somewhere out there, we _clone_ the repository:
```bash
$ git clone <project-url>
```


To add new files or modifications to files already in the repo:
```bash
$ echo '# Planmap Stories library' > README.md
$ git add README.md
```
This will stage the modifications (to filename) in the repository's _index_ area.


To permanently apply the modifications, we _commit_ the changes:
```bash
$ git commit -am "Init"
[master (root-commit) ac75d58] Init
1 file changed, 1 insertion(+)
create mode 100644 README.md
```
