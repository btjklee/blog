---
layout: post
read_time: true
show_date: true
title: Github commands study
date: 2021-07-09 17:24:00
img: posts/20210402/post7-header.webp
tags: [neural networks, machine learning, artificial intelligence]
category: theory
author: Ju Lee
description: "This is for Github study."
---


## Using Github on command prompt.
-----------

Github is Repository storage.  
Repository is a remote directory that can be shared by others.  
You can push or pull repository files from the github storage.  

- Git push
----------------

To push current directory's files onto the github repository, one has to add and commit beforehand.
- Git add
Git add specifies which files to upload.
-Git commit
git commit allows the user to add comments to the push.

```
Usage

git add <directory-path>
git commit -m "<message>"
git push

Example

gid add .
gid commit -m "Hello World"
git push

```

- Git clone
------------------

To clone the github repository to a local directory, one has to clone the repository's https address.

```
Usage

git clone <https-address>

Example

git clone https://github.com/btjklee/blog.git
```

- Git pull
-----------------------

Unlike Git Push, in which the github repository is updated FROM my directory's changes, Git Pull updates my local directory using the repository's changes.

However, git pull is useful when multiple people are updating one repository, so I will not write down how to use it just yet.

--------------------------------------------------

### If I want to make a new repository?

1. Go to github.com and create new repository
2. Get the https address from the new repository
3. Go to CMD and git clone the https address to the desired local directory
4. Once the local directory and the github repository are connected, start coding.
5. After changes have been made, go to the command prompt, 
```
git add.
git commit -m "example"
git push
```

