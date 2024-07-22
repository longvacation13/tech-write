source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 4.3.3"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem 'listen', '~> 3.0'

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]


# jekyll theme 적용방법
# 1. ruby 설치
# bundle install
#
# 2. jekyll 설치
# gem install jekyll
# gem install bundler
#
# 3. github repository 생성
# 그냥 껍데기만 만든다. 리포지토리 name은 tech-write.github.io 이런식으로 사이트 주소로 사용할 이름 만듦
#
# 4. 3에서 만든 github repository를 clone해서 로컬에 받아온다.
#
# 5. 설치된 로컬 폴더로 이동한다.
#
# 6. 다음 작업 수행
# $ jekyll new ./
# $ bundle install
# $ bundle update
# $ bundle install
#
# 위 과정에서 bundle할때 오류가 발생하면 다음 작업을 수행한다.
# Gemfile > gem 'wdm' ~~ 로 되어 있는거 삭제하고 gem 'listen', '~> 3.0'으로 변경
#
# 이후 위 6번 작업 다시 수행 > 정상적으로 install까지 된다.
#
# 7. 로컬에서 jekyll 서버 띄워봄
# bundle exec jekyll serve
# -> 127.0.0.1:4000 으로 했을때 서버 띄워지면 정상적으로 수행된것
#
#
# < 테마 적용 방법 >
# 1. 테마 사이트로 이동
# http://jekyllthemes.org/
#
# 2. 맘에 드는 테마 다운로드
#
# 3. _includes, _layouts, _sass, assets, styles.scss 파일만 복사해서 현재 프로젝트 폴더로 붙여넣기
#
# 4. 127.0.0.1:4000 으로 해당 페이지 다시 확인
#