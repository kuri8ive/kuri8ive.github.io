# 手順
- `git clone https://github.com/kuri8ive/hp.git`
- `cd hp`
- `git submodule update --init --recursive`
- `git submodule add -f -b main https://github.com/kuri8ive/kuri8ive.github.io.git public`
- `hugo`
- `cd public`
- `git add .`
- `git commit -m "Build website"`
- `git rebase`
- `git push origin main`
- (終盤はちょっとあやしい)

# 参考文献
- https://yohei-a.hatenablog.jp/entry/20210102/1609593616
- https://github.com/r9y9/website
- https://zenn.dev/tokiya_horikawa/articles/215637f23c8407