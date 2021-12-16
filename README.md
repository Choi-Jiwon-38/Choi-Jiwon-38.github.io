## WELCOME TO CHOI-JIWON-38.GITHUB.IO !!!


### 깃 페이지 Build Up 과정
> 1. Repository(.github.io) 생성하기
> 2. Jekyll 설치하기
> 3. GitHub Pages에 Jekyll theme(long_haul) 적용하기
> 4. 더미 레이아웃 정리하기 (테마 및 포스트 수정)

### 깃 페이지 추가 과제 수행 과정
> 1. 페이지 favicon 변경하기
> 2. 페이지 내 댓글 기능 구현하기
> 3. Google Analytics 연동하기
<hr>

## 1. Repository(.github.io) 생성하기<br>
GitHub Page를 만들기 위해서는 GitHub 계정이 필요!<br>
1학년 1학기 때 생성하였던 GitHub 계정을 그대로 이용함.

GItHub Page를 만드는 방법은 매우 간단함.<br>
Respository의 이름을 `<username.github.io>`로 생성!<br>
필자의 GitHub username은 'Choi-Jiwon-38'이므로<br>
Repository의 이름을 Choi-Jiwon-38.github.io로 생성!
<hr>

## 2. Jekyll 설치하기
Ruby 설치사이트 :: https://rubyinstaller.org/downloads/
주로 이용하는 OS가 Window기 때문에 필자는 위 사이트에서<br>
Window전용 Ruby + DevKit(개발자 키트) 설치 프로그램을 다운로드<br>

```gem install jekyll bundler``` 명령어를 통해서 지킬 번들을 설치<br> 
```jekyll -v``` 명령어로 설치가 정상적으로 완료되었는지 확인<br>

자신의 블로그 디렉토리로 이동한 뒤,<br>

```jekyll new .``` 명령어로 현재 디렉토리 내부에 블로그 파일을 새롭게 생성해줌<br>
```jekyll serve``` 명령어로 지킬을 실행<br>

## 3. GitHub Pages에 Jekyll theme(long_haul) 적용하기

### Jekyll Themes 사이트

1. http://jekyllthemes.org/
![image](https://user-images.githubusercontent.com/81795729/146298051-98d9ff5a-3970-4b54-8a5b-54328664682d.png) <br>

2. https://jekyllthemes.io/free
![image](https://user-images.githubusercontent.com/81795729/146298168-d3419392-6fa5-4f96-96ac-7e2d335ebdc9.png) <br>

위 두 사이트에서 Jekyll 무료 Themes를 확인할 수 있음. <br>

그 중에서 나는 long haul이라는 템플릿을 사용할 예정! <br>

#### Theme :: long haul <br>
https://github.com/brianmaierjr/long-haul <br>

`git clone`은 원격 저장소에 있는 폴더를 로컬로 가져오는 명령어<br>
`git clone`을 통해 나의 로컬 디렉토리에 long haul의 리포지토리를 그대로 복사(클론)하여 작업 환경을 마련하였음.
<br>

## 4. 더미 레이아웃 정리하기 (테마 및 포스트 수정)
