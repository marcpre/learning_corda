# learning_corda

## Install Corda

1. Install `Java SE Development Kit 8uXXX` 
2. Download a sample project from:

`git clone https://github.com/corda/cordapp-example`

3. Deploy Nodes `./gradlew deployNodes`(under Windows)

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

`kotlin-source/build/nodes/runnodes`

5. Open the application

[ http://localhost:10007/web/example/](http://127.0.0.1:7005/jolokia/)

**Source**
[Getting Started](https://docs.corda.net/getting-set-up.html)
