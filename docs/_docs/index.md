---
#title: Quickstart
title: 빠른 시작
permalink: /docs/
redirect_from:
  - /docs/home/
  - /docs/quickstart/
  - /docs/extras/
---
<!-- Jekyll is a static site generator. It takes text written in your
favorite markup language and uses layouts to create a static website. You can
tweak the site's look and feel, URLs, the data displayed on the page, and more. -->
Jekyll은 정적 사이트 생성기입니다. 당신이 즐겨쓰는 마크업 언어의 텍스트를 읽은 후, 레이아웃을 사용하여 정적 사이트를 만듭니다. 당신이 사이트의 외형, 느낌, URL, 페이지에 표시되는 데이터 등등을 커스터마이징할 수 있습니다.

<!-- ## Prerequisites

Jekyll requires the following:

* Ruby version **{{ site.data.ruby.min_version }}** or higher
* RubyGems
* GCC and Make

See [Requirements]({{ '/docs/installation/#requirements' | relative_url }}) for guides and details. -->
## 전제 조건

Jekyll은 다음을 필요로 합니다:

* 버전 **{{ site.data.ruby.min_version }} 이상의 Ruby
* RubyGems
* GCC와 Make

<!-- ## Instructions

1. Install all [prerequisites]({{ '/docs/installation/' | relative_url }}).
2. Install the jekyll and bundler [gems]({{ '/docs/ruby-101/#gems' | relative_url }}).
```sh
gem install jekyll bundler
```
3. Create a new Jekyll site at `./myblog`.
```sh
jekyll new myblog
```
4. Change into your new directory.
```sh
cd myblog
```
5. Build the site and make it available on a local server.
```sh
bundle exec jekyll serve
```
6. Browse to [http://localhost:4000](http://localhost:4000){:target="_blank"} -->
## 절차

1. 모든 [필요물]({{ '/docs/installation' | relative_url }})을 설치하세요.
2. Jekyll과 bundler [gem]({{ '/docs/ruby-101/#gems' | relative_rurl}})을 설치하세요.
```sh
gem install jekyll bundler
```
3. 새로운 Jekyll 사이트를 `./myblog`에 만드세요.
```sh
jekyll new myblog
```
4. 새로운 폴더로 들어가세요.
```sh
cd myblog
```
5. 사이트를 빌드해서, 로컬 서버에서 접속 가능하게 하세요.
```sh
bundle exec jekyll serve
```
6. [http://localhost:4000](http://localhost:4000){:target="=blank"}에 접속하세요.
<!-- {: .note .warning}
If you are using Ruby version 3.0.0 or higher, step 5 [may fail](https://github.com/github/pages-gem/issues/752). You may fix it by adding `webrick` to your dependencies: `bundle add webrick` -->
{: .note .warning}
만약 Ruby 버전 3.0.0 이상을 사용하고 계시다면, 5번이 [실패할 수도 있습니다](https://github.com/github/pages-gem/issues/752). `webrick`을 설치함으로써 이를 해결할 수 있습니다. `bundle add webrick`

<!-- {: .note .info}
Pass the `--livereload` option to `serve` to automatically refresh the page with each change you make to the source files: `bundle exec jekyll serve --livereload` -->
{: .note .info }
`serve`에 `--livereload` 옵션을 붙여서 소스파일에 변경을 만들 때마다 사이트에 반영되게 하세요. `bundle exec jekyll serve --livereload`


<!-- If you encounter any errors during this process, check that you have installed all the prerequisites in [Requirements]({{ '/docs/installation/#requirements' | relative_url }}). 
If you still have issues, see [Troubleshooting]({{ '/docs/troubleshooting/#configuration-problems' | relative_url }}). -->
만약 이 절차를 실행하는 도중 에러가 발생한다면, [준비물]({{ '/docs/installation/#requirements' | relative_url }})에 있는 모든 전제조건을 설치한 것을 확인해 주세요.
만약 그래도 문제가 생긴다면, [문제 해결]({{ '/docs/troubleshooting/#configuration-problems' | relative_url }}) 페이지를 확인해 주세요.

{: .note .info}
<!-- Installation varies based on your operating system. See our [guides]({{ '/docs/installation/#guides' | relative_url }}) for OS-specific instructions. -->
설치방법은 설치하는 운영 체제에 따라 달라집니다. OS별 가이드를 보려면 저희 [가이드]({{ '/docs/installation/#guides' | relative_url }})를 살펴봐 주세요.
