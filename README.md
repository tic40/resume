# Resume

- [Pages](https://tic40.github.io/resume/)
- [Markdown](https://github.com/tic40/resume/blob/main/index.md)
- [PDF](https://github.com/tic40/resume/releases/latest)

## Usage

### 文章校正
```bash
$ pnpm lint
```

### PDF出力
```bash
$ pnpm build
```

### Release

mainブランチにバージョンタグを打つとGitHub actionsでリリースを自動生成する

```bash
$ git tag {tag name}
$ git push origin {tag name}
```