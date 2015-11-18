# Generate.js

Generate.js is a tool to generate syntactically valid javascript based on statistics collected from existing javascript.

## To try it out

```
npm install
cat statistics.json | ./bin/generate
```

## To generate with more fun statistics

```
cat <(curl https://ajax.googleapis.com/ajax/libs/angularjs/1.3.14/angular.js) <(curl https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/react.js) | ./bin/statistics | ./bin/generate
```
