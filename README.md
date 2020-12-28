"# start-new-project"
# Create a new project folder and setup git using a python script

This litte project was inspired by a youtube video I watched the other day about automating everyday things with python

## Assumptions or requirements

> You are running Windows 10 (at least)
> You have python 3 installed on your system
>You have git installed
> You have the new [GitHub CLI](https://github.com/cli/cli) tool (gh) installed as well.
> You have gone through the gh login process and are able to create repositories using gh
> You have VS code installed. We use it at the end, but it is not needed


## How to use the script

- Using for favorite editor (vscode) Edit the line below to match your file structure.

```py
chgDir = os.chdir('C:\\Users\\phil4\\Documents\\development')
```

- Open a Powershell terminal and run: (change folder name to match whatever name you want)
```py
python .\create_project.py <folder name>
```
