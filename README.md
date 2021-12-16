## WELCOME TO CHOI-JIWON-38.GITHUB.IO !!!


### 깃 페이지 Build Up 과정
> 1. Repository(.github.io) 생성하기
> 2. Jekyll 설치하기
> 3. GitHub Pages에 Jekyll theme(long_haul) 적용하기
> 4. 더미 레이아웃 정리하기 (테마 및 포스트 수정)

<br>

### 깃 페이지 추가 과제 수행 과정
> 1. 페이지 favicon 변경하기
> 2. 페이지 내 댓글 기능 구현하기
> 3. Google Analytics 연동하기

<br>
<hr>

## 1. Repository(.github.io) 생성하기<br>
GitHub Page를 만들기 위해서는 GitHub 계정이 필요!<br>

1학년 1학기 때 생성하였던 GitHub 계정을 그대로 이용함.<br>

GItHub Page를 만드는 방법은 매우 간단함.<br>

Respository의 이름을 `<username.github.io>`로 생성!<br>

필자의 GitHub username은 'Choi-Jiwon-38'이므로<br>

Repository의 이름을 Choi-Jiwon-38.github.io로 생성!<br><br>

## 2. Jekyll 설치하기
Ruby 설치사이트 :: https://rubyinstaller.org/downloads/

주로 이용하는 OS가 Window기 때문에 필자는 위 사이트에서<br>

Window전용 Ruby + DevKit(개발자 키트) 설치 프로그램을 다운로드<br>

```gem install jekyll bundler``` 명령어를 통해서 지킬 번들을 설치<br> 

```jekyll -v``` 명령어로 설치가 정상적으로 완료되었는지 확인<br>

자신의 블로그 디렉토리로 이동한 뒤,<br>


```jekyll new .``` 명령어로 현재 디렉토리 내부에 블로그 파일을 새롭게 생성해줌<br>

```jekyll serve``` 명령어로 지킬을 실행<br><br>


## 3. GitHub Pages에 Jekyll theme(long_haul) 적용하기

### Jekyll Themes 사이트

1. http://jekyllthemes.org/ <br>

![image](https://user-images.githubusercontent.com/81795729/146298051-98d9ff5a-3970-4b54-8a5b-54328664682d.png) <br>

2. https://jekyllthemes.io/free <br>

![image](https://user-images.githubusercontent.com/81795729/146298168-d3419392-6fa5-4f96-96ac-7e2d335ebdc9.png) <br>

위 두 사이트에서 Jekyll 무료 Themes를 확인할 수 있음. <br>

그 중에서 나는 long haul이라는 템플릿을 사용할 예정! <br>

#### Theme :: long haul <br>
https://github.com/brianmaierjr/long-haul <br>
![image](https://user-images.githubusercontent.com/81795729/146299327-eee94fa3-325d-4a69-98e5-2b2fb45b0ed7.png) <br>

`git clone`은 원격 저장소에 있는 폴더를 로컬로 가져오는 명령어<br>

`git clone`을 통해 나의 로컬 디렉토리에 long haul의 리포지토리를 그대로 복사(클론)하여 작업 환경을 마련하였음.

<br><br>

## 4. 더미 레이아웃 정리하기 (테마 및 포스트 수정)

<br>

![image](https://user-images.githubusercontent.com/81795729/146366267-5cb83049-bdd8-43af-863e-855c4b6751f0.png)

<br>

### _config.yml

title 수정 -> 페이지 제목 변경

navigation, social 수정 -> 사용하지 않는 social 부분 삭제 및 정보 수정 <br>

### _includes/header.hmtl

기존 템플릿에 담겨있던 불필요한 header 부분 삭제 -> github와 velog로 변경 <br>

### _posts

기존에 있던 포스트를 전부 삭제한 뒤, `.markdown`으로 새로운 포스트를 만들어 업로드 <br>

<br>
<hr>
<br>

## 1. 페이지 favicon 변경하기

<br>

![image](https://user-images.githubusercontent.com/81795729/146392594-33e3277e-75a9-4241-974f-d2c0bd5467a1.png)


favicon은 무엇일까? favicon은 favorites와 icon의 합성어!

주소창 옆에 표시되는 아이콘을 의미함

구글 이미지에서 원하는 이미지를 찾아서 `.ico` 확장자로 변경한 뒤

assets/img 에 'favicon'이라는 이름으로 저장하여 변경할 수 있음.

<br>

## 2. 페이지 내 댓글 기능 구현하기

Disqus 공식 홈페이지 :: https://disqus.com

아래 옵션으로 가입해준다

1. `I want to install Disqus on my site` 선택

2. `Website Name` 선택

3. `Category` - `Tech`로 설정

4. `Create Site` 클릭

5. 버전 `Basic` 선택

6. 플랫폼 `Jekyll` 선택

7. Website Name, Website URL(깃허브 페이지) 입력

8. 정책 `Balanced` 선택

9. Universal Embed Code를 부여받고 해당 코드로 코드 수정

![image](https://user-images.githubusercontent.com/81795729/146391198-fafdbcef-5362-41d0-8215-83a0febd70cb.png)

<br>

## 3. Google Analytics 연동하기
<br><br>
![](https://images.velog.io/images/aid_choi/post/3864af10-7473-46fb-8c77-c0335ffef3e5/image.png)

깃허브 페이지에 더욱 자세하게 기술되어 있으므로 아래 링크를 통해 확인 바람!

(선택한 템플릿인 long haul에서는 UA- 형식의 추적 ID가 필요했기에 해당 부분도 같이 적어둠)

### 깃허브 페이지 주소 :: https://choi-jiwon-38.github.io/
