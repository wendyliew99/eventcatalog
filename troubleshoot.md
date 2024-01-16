
Run into same error reported here after scaffolding
https://github.com/boyney123/eventcatalog/issues/468

Add the following to package.json:
<code>
    "overrides": {
        "@eventcatalog/core": {
            "swagger-ui-react": "5.10.5"
        }
    }
</code>

> rm -f node_modules
> rm package lock file
> npm install
> npm run build 

It works now!!
