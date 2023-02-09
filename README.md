# itai-peleg-awesome-greeter

Steps for initialize:
1. Build local .npmrc in the root (make sure not to commit it)
2. Run nom login
3. Run ./reset.sh
4. fix the package.json (including the new version)
5. run npm install --registry https://secengsca.jfrog.io/artifactory/api/npm/sca-goat-npm/
6. fix the code files
7. run npm run build
8. make sure everything is committed
9. npm publish --registry https://secengsca.jfrog.io/artifactory/api/npm/sca-goat-npm-local/

