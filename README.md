# @youxian/scripts

Provide common scripts

# Scripts 可用命令/脚本

| Scripts                             | Alias                         |
| ----------------------------------- | ----------------------------- |
| `yx-scripts install [--npm-client]` | `<NPM_CLIENT> install`        |
| `yx-scripts clean`                  | `rm -r node_modules dist lib` |
| `yx-scripts clean:dep`              | `rm -r node_modules`          |
| `yx-scripts clean:prod`             | `rm -r dist lib`              |

## Parameters

| Name               | Description    | Default value |
| ------------------ | -------------- | ------------- |
| `-c, --npm-client` | npm 包管理工具 | `yarn`        |
| `-v, --version`    | 展示版本号     |               |
| `-V, --verbose`    | 运行时详细输出 |               |


<!-- create by @youxian/cli -->
