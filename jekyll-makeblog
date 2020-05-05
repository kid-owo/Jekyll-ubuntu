1. git 설치
```bash
$ sudo apt-get install git
$ sudo apt install git
```

2. Ruby, Jekyll 설치
```bash

$ sudo apt install ruby 
$ gem install jekyll
```
> Fetching: public_suffix-4.0.4.gem (100%)
ERROR:  While executing gem ... (Gem::FilePermissionError)
    You don't have write permissions for the /var/lib/gems/2.5.0 directory.
- permission error

```bash

$ sudo gem install jekyll

```
 
 
> Fetching: public_suffix-4.0.4.gem (100%)  
Successfully installed public_suffix-4.0.4  
Fetching: addressable-2.7.0.gem (100%)  
Successfully installed addressable-2.7.0  
Fetching: colorator-1.1.0.gem (100%)  
Successfully installed colorator-1.1.0  
Fetching: http_parser.rb-0.6.0.gem (100%)  
Building native extensions. This could take a while...  
ERROR:  Error installing jekyll:  
	ERROR: Failed to build gem native extension.  

>  current directory: /var/lib/gems/2.5.0/gems/http_parser.rb-0.6.0/ext/ruby_http_parser   
/usr/bin/ruby2.5 -r ./siteconf20200506-21643-71qx2y.rb extconf.rb  
mkmf.rb can't find header files for ruby at /usr/lib/ruby/include/ruby.h  
  
> extconf failed, exit code 1  

> Gem files will remain installed in /var/lib/gems/2.5.0/gems/http_parser.rb-0.6.0 for inspection.  
Results logged to /var/lib/gems/2.5.0/extensions/x86_64-linux/2.5.0/http_parser.rb-0.6.0/gem_make.out  

- 헤더파일을 못찾는거 같아 검색해보니까 다른버전으로 설치 해보라함.

```bash
sudo apt-get install ruby-dev
$ sudo gem install jekyll bundler

``` 

3. 블로그 만들기
```bash
git clone https://github.com/[username]/[username].github.io

```
```bash
git add
git commit
git push
```
4. 테마
```bash
$ git clone https://github.com/mmistakes/minimal-mistakes.git
$ bundle
$ mv minimal-mistakes/ kid-owo.github.io
$ cd kid-owo.github.io/
$ git remote remove origin
$ git remote add origin https://github.com/kid-owo/kid-owo.github.io.git
$ git push -u origin master


```
- 주의 할 점 repository 생성시 초기화금지....
