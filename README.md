# itai-peleg-awesome-greeter

Steps for initialize:
1. Build local .npmrc in the root (make sure not to commit it)
2. Run nom login
3. Run ./reset.sh
4. fix the package.json
5. run npm install --registry https://secengsca.jfrog.io/artifactory/api/npm/sca-goat-npm/
6. fix the code files
7. run npm run build
8. validating you have the appropriate version in the package.json
9. make sure everything is committed
10. npm publish --registry https://secengsca.jfrog.io/artifactory/api/npm/sca-goat-npm-local/

