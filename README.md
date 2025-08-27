##

You need [`azure-functions-core-tools`](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=macos%2Cisolated-process%2Cnode-v4%2Cpython-v2%2Chttp-trigger%2Ccontainer-apps&pivots=programming-language-typescript#install-the-azure-functions-core-tools) to run this locally.

```
pnpm install
pnpm run start
```

```
curl -v http://localhost:7071/api/health
```
