---
description: Setup Apostrophe Essentials
---

# Setup Apostrophe Essentials from scratch


Ask a new {project_name} in the instructions below we will use it.


Clone repository:

```
cd {project_name}
git clone git@github.com:apostrophecms/starter-kit-essentials.git .
```

Delete .git to unbind the code from the repository:

```
rm -R .git
```

Install the ApostropheCMS:

```
cd starter-kit-essentials
npm i
```

Create admin user:

```
node app @apostrophecms/user:add admin admin
```

Run the ApostropheCMS:

```
node app start
```
