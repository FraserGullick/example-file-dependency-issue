# example-file-dependency-issue
An example repo to highlight a problem we've had around file based dependencies

```
cd otherapps
npm i
npm i
```
Observe that the package_lock dependency definition changes from 'file:../node_modules/ABCDE' to 'file:githubABCDE'