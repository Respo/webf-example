
Respo Calcit on WebF
----

Based on [WebF](https://github.com/openwebf/cli). Build the web assets with:

```bash
caps --strict --ci
yarn install --immutable
caps verify --toolchain
yarn build
```

The WebF host integration has not been revalidated in this migration.

### Calcit 0.46.0

构建需要配对的 Calcit 和 `@calcit/procs` 0.46.0。PR 只检查和构建，服务器部署仅在主分支推送时执行。

### Workflow

https://github.com/calcit-lang/respo-calcit-workflow

### License

MIT
