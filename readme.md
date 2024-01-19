Running on Jenkins in /var/lib/jenkins/workspace/example_setup-cicd-pipeline
[Pipeline] {
[Pipeline] stage
[Pipeline] { (Declarative: Checkout SCM)
[Pipeline] checkout
Selected Git installation does not exist. Using Default
The recommended git tool is: NONE
No credentials specified
Cloning the remote Git repository
Cloning with configured refspecs honoured and without tags
Cloning repository https://github.com/santosh/cotu
 > git init /var/lib/jenkins/workspace/example_setup-cicd-pipeline # timeout=10
Fetching upstream changes from https://github.com/santosh/cotu
 > git --version # timeout=10
 > git --version # 'git version 2.25.1'
 > git fetch --no-tags --force --progress -- https://github.com/santosh/cotu +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git config remote.origin.url https://github.com/santosh/cotu # timeout=10
 > git config --add remote.origin.fetch +refs/heads/*:refs/remotes/origin/* # timeout=10
Avoid second fetch
Checking out Revision 094a548654f1ee686b034557f2197de945c4ba22 (setup-cicd-pipeline)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 094a548654f1ee686b034557f2197de945c4ba22 # timeout=10
Commit message: "Add Cleanup stage in Jenkinsfile"
First time build. Skipping changelog.
[Pipeline] }
[Pipeline] // stage
[Pipeline] withEnv
[Pipeline] {
[Pipeline] stage
[Pipeline] { (Init)
[Pipeline] echo
Initializing..
[Pipeline] echo
Running 1 on https://ci.santoshk.dev/
[Pipeline] }
[Pipeline] // stage
[Pipeline] stage
[Pipeline] { (Test)
[Pipeline] echo
Testing..
