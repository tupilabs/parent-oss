# parent-oss

A parent project, with common settings for OSS projects from TupiLabs https://github.com/tupilabs/parent-oss

## What you must specify in children projects

* groupId, artifactId, version
* gpg keys
* name, description, url
* license
* developer information
* scm

How to use it with Maven.

```
<parent>
    <groupId>com.tupilabs</groupId>
    <artifactId>parent-oss</artifactId>
    <version>0.1</version>
</parent>
```
