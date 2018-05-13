# learning_corda

## Install Corda (Windows)

1. Install `Java SE Development Kit 8uXXX` 
2. Download a sample project from:

`git clone https://github.com/corda/cordapp-example`

3. Deploy Nodes `./gradlew.bat deployNodes`(under Windows)

After deployment finished:

```
Gathering notary identities
Notary identities to be used in network parameters: O=Notary, L=London, C=GB (non-validating)
No existing whitelist file found.
Calculating whitelist for current installed CorDapps..
CorDapp whitelist generated in C:\Users\marcus\Desktop\Coding Projects\learning_corda\kotlin-source\build\nodes\whitelist.txt
Updating whitelist
Bootstrapping complete!

BUILD SUCCESSFUL in 7m 11s
10 actionable tasks: 10 executed

``` 

4. Run Nodes

Put the following in the git-command prompt:

`kotlin-source/build/nodes/runnodes`

Wait until terminal has been fully started:

```
Welcome to the Corda interactive shell.
Useful commands include 'help' to see what is available, and 'bye' to shut down
the node.

Sun May 13 09:07:26 CEST 2018>>>
```

5. Open the application

[http://localhost:10007/web/example/](http://localhost:10007/web/example/)

**Source**
[Getting Started](https://docs.corda.net/getting-set-up.html)
[Example Corda App](https://docs.corda.net/tutorial-cordapp.html#the-example-cordapp)
