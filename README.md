# programming-paradigms
Logic paradigm (prolog) and Object oriented paradigm (C# mono)

# Cloud 9
1. In c9.io: Create a new workspace: 
  * Workspace name: `programming-paradigms`
  * Description: `programming-paradigms`
  * Team: quobject1
  * Hosted workspace: `Public`
  * Clone from Git or Mercurial URL: `https://github.com/Quobject/programming-paradigms.git`
  * Choose a template: `Blank`
  * Hit 'Create workspace' button
2. Inside your workspace on the left side right click the folder name 'programming-paradigms' and select 'Open Terminal Here'
3. In your terminal type the command 

```bash
sudo chmod u+x install.sh; sudo ./install.sh
```

# Testing prolog
cd /home/ubuntu/workspace/prolog
swipl
[family1].
parent(pam, bob).
Control-C e

# Testing C#
cd /home/ubuntu/workspace/csharp
mcs program.cs
mono program.exe
