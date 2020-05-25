# 데이터리안 블로그

## Ruby 설치

```bash
brew install ruby

echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.zshrc

source ~/.zshrc

gem update --system

gem install bundler
```

## 의존성 설치

```bash
bundle
```

## Jekyll server 실행

- 실행시 drafts 글 미리 확인 가능

```bash
bundle exec jekyll serve --drafts
```

<http://localhost:4000/>
