# hello_world
Just another repository

Hello! I'm Hiroshi!
I live in Nagano prefecture, Matsumoto city. I want to go home in Osaka.
I want to work as a system engineer in Osaka.

#Udemy はじめてのrubyonrails　（5.11記述）
rubyonrailsにgit push herokuをしたときのエラーログとGemFileをのせています。
すべてのものをのせたつもりですが、漏れがある場合恐れ入りますが、連絡をお願いします。

5.11実行時のエラー
hiroshilearning:~/environment/rails_projects/qanda (master) $ gem install bundler -v 1.17.3
Successfully installed bundler-1.17.3
Parsing documentation for bundler-1.17.3
Done installing documentation for bundler after 3 seconds
1 gem installed
hiroshilearning:~/environment/rails_projects/qanda (master) $ bundle update
The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
Fetching gem metadata from https://rubygems.org/............
Fetching gem metadata from https://rubygems.org/.
Resolving dependencies....
Using rake 13.0.1
Using concurrent-ruby 1.1.6
Using i18n 1.8.2
Using minitest 5.14.0
Using thread_safe 0.3.6
Using tzinfo 1.2.7
Using activesupport 5.2.4.2
Using builder 3.2.4
Using erubi 1.9.0
Using mini_portile2 2.4.0
Using nokogiri 1.10.9
Using rails-dom-testing 2.0.3
Using crass 1.0.6
Using loofah 2.5.0
Using rails-html-sanitizer 1.3.0
Using actionview 5.2.4.2
Using rack 2.2.2
Using rack-test 1.1.0
Using actionpack 5.2.4.2
Using nio4r 2.5.2
Using websocket-extensions 0.1.4
Using websocket-driver 0.7.1
Using actioncable 5.2.4.2
Using globalid 0.4.2
Using activejob 5.2.4.2
Using mini_mime 1.0.2
Using mail 2.7.1
Using actionmailer 5.2.4.2
Using activemodel 5.2.4.2
Using arel 9.0.0
Using activerecord 5.2.4.2
Fetching mimemagic 0.3.5 (was 0.3.4)
Installing mimemagic 0.3.5 (was 0.3.4)
Using marcel 0.3.3
Using activestorage 5.2.4.2
Fetching public_suffix 4.0.5 (was 4.0.4)
Installing public_suffix 4.0.5 (was 4.0.4)
Using addressable 2.7.0
Using io-like 0.3.1
Using archive-zip 0.12.0
Using execjs 2.7.0
Using autoprefixer-rails 9.7.6
Using bindex 0.8.1
Using msgpack 1.3.3
Using bootsnap 1.4.6
Using popper_js 1.16.0
Using rb-fsevent 0.10.4
Using ffi 1.12.2
Using rb-inotify 0.10.1
Using sass-listen 4.0.0
Using sass 3.7.4
Using bootstrap 4.1.3
Using bundler 1.17.3
Using byebug 11.1.3
Using regexp_parser 1.7.0
Using xpath 3.2.0
Using capybara 3.32.1
Using childprocess 3.0.0
Using chromedriver-helper 2.1.1
Using coffee-script-source 1.12.2
Using coffee-script 2.4.1
Using method_source 1.0.0
Using thor 1.0.1
Using railties 5.2.4.2
Using coffee-rails 4.2.2
Using jbuilder 2.10.0
Using jquery-rails 4.3.5
Using ruby_dep 1.5.0
Using listen 3.1.5
Using puma 3.12.4
Using sprockets 3.7.2
Using sprockets-rails 3.2.1
Using rails 5.2.4.2
Using rubyzip 2.3.0
Using tilt 2.0.10
Using sass-rails 5.1.0
Using selenium-webdriver 3.142.7
Using spring 2.1.0
Using spring-watcher-listen 2.0.1
Using sqlite3 1.3.13
Using turbolinks-source 5.2.0
Using turbolinks 5.2.1
Using uglifier 4.2.0
Using web-console 3.7.0
Bundle updated!
Gems in the group production were not installed.
hiroshilearning:~/environment/rails_projects/qanda (master) $ gem list bundle | grep bundle
bundler (default: 1.17.3)
bundler-unload (1.0.2)
rubygems-bundler (1.4.5)
hiroshilearning:~/environment/rails_projects/qanda (master) $ bundler(2.0.1, 1.17.3)
bash: syntax error near unexpected token `2.0.1,'
hiroshilearning:~/environment/rails_projects/qanda (master) $ bundler( 2.0.1 , 1.17.3)                                           
bash: syntax error near unexpected token `2.0.1'
hiroshilearning:~/environment/rails_projects/qanda (master) $ bundler
The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
Using rake 13.0.1
Using concurrent-ruby 1.1.6
Using i18n 1.8.2
Using minitest 5.14.0
Using thread_safe 0.3.6
Using tzinfo 1.2.7
Using activesupport 5.2.4.2
Using builder 3.2.4
Using erubi 1.9.0
Using mini_portile2 2.4.0
Using nokogiri 1.10.9
Using rails-dom-testing 2.0.3
Using crass 1.0.6
Using loofah 2.5.0
Using rails-html-sanitizer 1.3.0
Using actionview 5.2.4.2
Using rack 2.2.2
Using rack-test 1.1.0
Using actionpack 5.2.4.2
Using nio4r 2.5.2
Using websocket-extensions 0.1.4
Using websocket-driver 0.7.1
Using actioncable 5.2.4.2
Using globalid 0.4.2
Using activejob 5.2.4.2
Using mini_mime 1.0.2
Using mail 2.7.1
Using actionmailer 5.2.4.2
Using activemodel 5.2.4.2
Using arel 9.0.0
Using activerecord 5.2.4.2
Using mimemagic 0.3.5
Using marcel 0.3.3
Using activestorage 5.2.4.2
Using public_suffix 4.0.5
Using addressable 2.7.0
Using io-like 0.3.1
Using archive-zip 0.12.0
Using execjs 2.7.0
Using autoprefixer-rails 9.7.6
Using bindex 0.8.1
Using msgpack 1.3.3
Using bootsnap 1.4.6
Using popper_js 1.16.0
Using rb-fsevent 0.10.4
Using ffi 1.12.2
Using rb-inotify 0.10.1
Using sass-listen 4.0.0
Using sass 3.7.4
Using bootstrap 4.1.3
Using bundler 1.17.3
Using byebug 11.1.3
Using regexp_parser 1.7.0
Using xpath 3.2.0
Using capybara 3.32.1
Using childprocess 3.0.0
Using chromedriver-helper 2.1.1
Using coffee-script-source 1.12.2
Using coffee-script 2.4.1
Using method_source 1.0.0
Using thor 1.0.1
Using railties 5.2.4.2
Using coffee-rails 4.2.2
Using jbuilder 2.10.0
Using jquery-rails 4.3.5
Using ruby_dep 1.5.0
Using listen 3.1.5
Using puma 3.12.4
Using sprockets 3.7.2
Using sprockets-rails 3.2.1
Using rails 5.2.4.2
Using rubyzip 2.3.0
Using tilt 2.0.10
Using sass-rails 5.1.0
Using selenium-webdriver 3.142.7
Using spring 2.1.0
Using spring-watcher-listen 2.0.1
Using sqlite3 1.3.13
Using turbolinks-source 5.2.0
Using turbolinks 5.2.1
Using uglifier 4.2.0
Using web-console 3.7.0
Bundle complete! 20 Gemfile dependencies, 82 gems now installed.
Gems in the group production were not installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
hiroshilearning:~/environment/rails_projects/qanda (master) $ git push heroku master
Counting objects: 116, done.
Compressing objects: 100% (101/101), done.
Writing objects: 100% (116/116), 26.94 KiB | 1.35 MiB/s, done.
Total 116 (delta 8), reused 0 (delta 0)
remote: Compressing source files... done.
remote: Building source:
remote: 
remote: -----> Ruby app detected
remote: -----> Compiling Ruby/Rails
remote: 
remote: ###### WARNING:
remote: 
remote:        This buildpack was created as a stop-gap measure to allow running applications with Bundler 2 on Heroku.
remote:        Heroku now supports Bundler 2 directly: https://devcenter.heroku.com/changelog-items/1563
remote:        
remote:        Please discontinue use of this buildpack and instead directly use the `heroku/ruby` buildpack.
remote:        
remote:        To remove this buildpack use the `heroku buildpacks` command to list your existing buildpacks.
remote:        
remote:        If you only have one buildpack listed you can run:
remote:        
remote:        ```
remote:        heroku buildpacks:set heroku/ruby
remote:        ```
remote:        
remote:        If you have multiple buildpacks, you'll need to add the buildpack to the correct location using
remote:        `heroku buildpacks:add heroku/ruby -i <correct index>` and then remove this buildpack via:
remote:        
remote:        ```
remote:        heroku buildpacks:remove https://github.com/bundler/heroku-buildpack-bundler2
remote:        ```
remote: 
remote: -----> Using Ruby version: ruby-2.5.1
remote: -----> Installing dependencies using bundler 2.0.1
remote:        Running: bundle install --without development:test --path vendor/bundle --binstubs vendor/bundle/bin -j4 --deployment
remote:        /tmp/build_7012c27cbec7339daccb2f3d3f11c8e6/vendor/ruby-2.5.1/lib/ruby/2.5.0/rubygems.rb:284:in `find_spec_for_exe': Could not find 'bundler' (1.17.3) required by your /tmp/build_7012c27cbec7339daccb2f3d3f11c8e6/Gemfile.lock. (Gem::GemNotFoundException)
remote:        To update to the latest version installed on your system, run `bundle update --bundler`.
remote:        To install the missing version, run `gem install bundler:1.17.3`
remote:         from /tmp/build_7012c27cbec7339daccb2f3d3f11c8e6/vendor/ruby-2.5.1/lib/ruby/2.5.0/rubygems.rb:303:in `activate_bin_path'
remote:         from vendor/bundle/ruby/2.5.0/bin/bundle:23:in `<main>'
remote:        Bundler Output: /tmp/build_7012c27cbec7339daccb2f3d3f11c8e6/vendor/ruby-2.5.1/lib/ruby/2.5.0/rubygems.rb:284:in `find_spec_for_exe': Could not find 'bundler' (1.17.3) required by your /tmp/build_7012c27cbec7339daccb2f3d3f11c8e6/Gemfile.lock. (Gem::GemNotFoundException)
remote:        To update to the latest version installed on your system, run `bundle update --bundler`.
remote:        To install the missing version, run `gem install bundler:1.17.3`
remote:         from /tmp/build_7012c27cbec7339daccb2f3d3f11c8e6/vendor/ruby-2.5.1/lib/ruby/2.5.0/rubygems.rb:303:in `activate_bin_path'
remote:         from vendor/bundle/ruby/2.5.0/bin/bundle:23:in `<main>'
remote: 
remote:  !
remote:  !     Failed to install gems via Bundler.
remote:  !
remote:  !     Push rejected, failed to compile Ruby app.
remote: 
remote:  !     Push failed
remote: Verifying deploy...
remote: 
remote: !       Push rejected to qanda-67890.
remote: 
To https://git.heroku.com/qanda-67890.git
 ! [remote rejected] master -> master (pre-receive hook declined)
error: failed to push some refs to 'https://git.heroku.com/qanda-67890.git'
