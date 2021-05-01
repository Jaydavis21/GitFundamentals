# Git Remote

When wrking with git, a **remote** is any git repository not on the machine you're working on. The counterpart to this is **local**, or the machine that is being developed on. 

Take Github for example. While git is the technology that allows you to create local repositories, Github is the sitethat will host your remote repositories. Once store remotely, you can bring that repository back down or share it with others. 

**Note**: While the repositoriees (local and remote) are related and track the same project, they can have different states if changes are not shared between the two. 

## Adding a remote 

A remote can be added with the 'git remote add' command, followed by the name and location of the remote. 

The name is a loacl name, meaning it's your label and does not impact the actual remote whatsoever.

'''
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
'''

### Removing a remote 

A remote can be removed with the 'git remote remove' command, followed by the name of the remote.

'''
git remote remove origin
'''
## Resources 

- [Git Commit Documentation](https://git-scm.com/git-commit)

---

[Back to home](../README.md)

