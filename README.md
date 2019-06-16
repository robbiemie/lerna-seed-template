# lerna-seed-template

a multi-packages manager tools


## lerna in Use

1. `Install`

```bash
$ npm i lerna -g
```

2. `create`

> 创建一个包模块

```bash
$ lerna create [loc]
```

- `name` 模块名称
- `loc` 自定义包路径，默认 `packages/` 文件夹下, 在 `lerna.json` 文件中配置。 

3. `import`

> 导入现有包模块

```bash
$ lerna import [dir]
```


4. `list`

> 查看模块列表

```bash
$ lerna list
```

5. `add`

> 为单一模块，引入外部依赖包

```bash
$ lerna add [@version/package] [--dev] <package-name>
```

6. `global`

> 为所有模块安装依赖包

```bash
$ lerna bootstrap
```

7. `clean`

> 清理所有 `node_modules`

```bash
$ lerna clean
```

8. `vesrsion`

> 版本迭代

```bash
$ lerna version [major | minor | patch | premajor | preminor | prepatch | prerelease]
```