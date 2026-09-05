This is my My First exercise to push the local repository github
-------------------------------------------------------------------
A Git tag is a name/label given to a specific commit.
The easiest way to understand it is:
🏷️ Git Tag = A permanent label for an important point in your Git history.
Tags are commonly used to mark releases or versions such as:
v1.0
v1.1
v2.0
Release-2026.09

Create a tag
If you are currently on the commit you want to tag:
git tag v1.0


Create a tag on a specific commit
git tag v1.0 72d3e47

See all tags
git tag


Delete a local tag
git tag -d v1.0


Annotated Tags
For releases, you'll often see annotated tags:
git tag -a v1.0 -m "Release version 1.0"
Here:
•	-a → create an annotated tag 
•	v1.0 → tag name 
•	-m → tag message

