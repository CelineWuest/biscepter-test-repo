# Biscepter Test Repo

This repository is used to test and demonstrate [biscepter](https://github.com/CelineWuest/biscepter), the efficient git bisecter.

There is a single file `main.go` which is a simple Go webserver.
It contains several endpoints, accessible under `/i`, where `i` is an integer that ranges from 0 to 5.
The endpoint `/i` is considered functional if it returns `i`, otherwise it is considered buggy.

This repository's git history looks as follows:

```
* 6ed0198 - Update README
* aefa73a - Fix build
* c1a9aa3 - Break build
* ef26456 - Empty Commit 3
* 513b03c - Add README
*   41b75b6 - Merge branch 'make-endpoints-buggy'
|\
| *   89edcdd - Merge branch 'make-endpoint-5-buggy' into make-endpoints-buggy
| |\
| | * 7bec714 - Empty Commit 1
| | *   402566c - Merge branch 'make-endpoint-5-buggy-nested-branch' into make-endpoint-5-buggy
| | |\
| | | * c8f90f6 - Add bug to /5
| | |/
| | * 91edb18 - Empty Commit 0
| |/
| *   0a1824b - Merge pull request #1 from CelineWuest/make-endpoint-4-buggy
| |\
| | * 97db214 - Empty Commit 1
| | * 8ea445c - Add bug to /4
| | * cf020b0 - Empty Commit 0
| |/
| *   1e17b73 - Merge branch 'make-endpoint-3-buggy' into make-endpoints-buggy
| |\
| | * bd7c3fd - Add bug to /3
| |/
| * 4518c1b - Empty Commit 0
|/
* 0fe06fb - Add /3, /4 and /5 testing endpoints
* 3219afd - Empty Commit 2
* 360cee2 - Empty Commit 1
* 266cef4 - Empty Commit 0
* 130f227 - Add bug to /2
* d7b2ed8 - Add bug to /1
* fc948ed - Add bug to /0
* 6993161 - Make simple project
```
