#### psjsbestprac
#####Production code
######NPM settings
package.json
```
license->
"engines":{
  "node":"4.2.1"
}
```
If do not want to type `npm install xx --save` every time, use
```
npm config set save=true
```
If download specific version, use
```
npm config set save-exact=true
```

######Environmental variables
```
npm install foreman -g
nf start
touch .env
```
edit .env
```
{
  "port":"9000",
  "connection":{
    "sql":"",
    "mongo":""
  }
}
```
######Cross platform concerns
using all losercase file name(js)
