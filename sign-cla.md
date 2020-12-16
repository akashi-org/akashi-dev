Sign the CLA
============

This page is the step-by-step guide to signing our Individual Contributor License Agreement. If you have any questions, please open an issue to this repository.

----

## 1. Clone this repo

Please clone the repo as usual. If you don't have your GitHub account, please sign up and make it.

## 2. Read the CLA and check the MD5 checksum of it

First and foremost, read [the current version of the CLA](cla.md). After reading the CLA, please check the MD5 checksum of the current CLA. The checksum will be needed in a later step.

```
$ md5sum cla.md
9b2380f756bcfcc53e4e8d20b01370e4 cla.md
```

## 3. Add your sign to the appropriate place

Now, this is the signing step. For signing, you need to make a single file to the `contributors/{CURRENT_CLA_CHECKSUM}` directory of this project. **If such directory does not exist, please make it**. **It can be occurred when the CLA is updated**. And then, name the file with the same name as your GitHub username, with `.md` appended to the end. For example, for the username `peter`, the full path to the file would be `contributors/{CURRENT_CLA_CHECKSUM}/peter.md`.

The single file should look like the following:

```
[date]

I hereby agree to the terms of the Individual Contributor License Agreement, version 2.0, with MD5 checksum 9b2380f756bcfcc53e4e8d20b01370e4.

I furthermore declare that I am authorized and able to make this agreement and sign this declaration.

Signed,

[your GitHub username]
https://github.com/[your GitHub username]
```

Replace the bracketed text as follows:

* `[date]` with today's date, in the unambiguous numeric form `YYYY-MM-DD`.
* `[your GitHub username]` with your GitHub username.

## 4. Create your pull request and wait for it be merged

Create your pull request with the single file you added in step 3, and wait for us to merge it. **Please note that the CLA can be updated in the future, and every time it is updated, you have to sign the new CLA**.
