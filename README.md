# Estuary.KM skin for Kodi 20.x Nexus
**Repository 설치**
>##### KM레포지토리 설치
repository.km.zip를 다운받아 저장소를 설치
https://drive.google.com/file/d/1Dy_nJv599DmJDJ2UzbJjhv7LCaoPzL8b/view?usp=sharing

>##### KM레포지토리 업데이트 방법
[메뉴얼](https://drive.google.com/file/d/1V1hmknCP8XWFiqd2IVO76Usla7A4cVfK/view?usp=sharing)

##### 설치동영상
[KM레포지토리를 통한 스킨 설치](https://drive.google.com/file/d/1no66wwIiSuevcqvPGhBQo9D11kkzAVAd/view?usp=share_link)

---


>#### Plexkodiconnect 설치
##### 저장소를 통한 설치
Kodi 소스추가및 Plexkodiconnect 설치

###### Protocol: Web server directory (HTTPS)

###### Server adress: croneter.github.io

###### Remote path: pkc-source

###### Port: 443
plexkodiconnect 개발자 참고링크
https://github.com/croneter/PlexKodiConnect/wiki/Installation
##### 설치동영상
[plexkodiconnect 설치](https://drive.google.com/file/d/1-yT_qF6JsZtpuF44s-I-1f7uLAv_Yvx3/view?usp=share_link)   

---
>#### 스킨 설정
##### 보기화면 변경및 환경설정
##### 설치동영상
[스킨환경설정](https://drive.google.com/file/d/1vVl4SiADoSw7uY2nX9Iu1tQ_W85MmhBx/view?usp=sharing)
##### TMDB 메뉴 한글설정
[TMDB 메뉴 한글설정](https://drive.google.com/file/d/1BhmFJZ3d9MKUj6s36w4Gosv6wIm50ZYU/view?usp=share_link)

---

>#### 부가영상및 예고편을 보기위한 Youtube 환경설정
##### Youtube API 키 생성
키발급 참조 링크
https://www.thefastcode.com/ko-krw/article/how-to-fix-kodi-s-youtube-quota-exceeded-problem
##### 스킨설치시 설치된 plugin.video.youtube 에서 파일수정 (api_keys.json, settings.xml)

Window 기준

C:\Users\사용자이름\AppData\Roaming\Kodi\userdata\addon_data\plugin.video.youtube\

Android 기준

/storage/emulated/0/Android/data/org.xbmc.kodi/files/.kodi/userdata/addon_data/plugin.video.youtube/

api_keys.json 수정 예
``````
{
    "keys": {
        "developer": {},
        "personal": {
            "api_key": "AIzaSyDULvIsd9일부삭제cyzndlJQUz5A",
            "client_id": "23676147256-7kkl일부삭제rh5v6pdmvt",
            "client_secret": "GOCSPX-JPV일부삭제RrSiE9VMn-gqM"
        }
    }
}
``````
**settings.xml 수정 예**

```
<setting id="youtube.api.key">AIzaSyDULvIsd9일부삭제cyzndlJQUz5A</setting>    
<setting id="youtube.api.id">23676147256-7kkl일부삭제rh5v6pdmvt</setting>
<setting id="youtube.api.secret">GOCSPX-JPV일부삭제RrSiE9VMn-gqM</setting>
```
**수정된 키 복사**
##### 설치동영상
[youtube 키 복사](https://drive.google.com/file/d/142VuvJYydhl6b4MuWy-1AG9BVvUAmZ4k/view?usp=share_link)   

>#### 부가영상및 예고편을 보기위한 스킨 옵션 설정및  youtube 패치 애드온 설치
plugin.video.youtube 패치다운 (2023.5.6 기준)
[plugin.video.youtube-7.0.2.alpha7.zip](https://drive.google.com/file/d/1Ce2t7jjw8ETY37pMCsuX99f1rm1E57Rp/view?usp=share_link)   

##### 설치동영상
[youtube 부가영상 스킨설정](https://drive.google.com/file/d/1yut0vwYinQJ-NhTthmhjdJ2QH4-wUbXH/view?usp=sharing)   

---
>#### 스킨 홈메뉴 추가 수정
내 라이브러리를 홈메뉴에 추가할수 있습니다
##### 설치동영상
[홈메뉴추가](https://drive.google.com/file/d/1kzfrYSyYdzymMy-MxCHcR9veuSZlayd1/view?usp=sharing)
>#### OTT(Tiving/Watcha/Wavve 외)설정
밤보리님 애드온을 설치하면 홈메뉴에 해당 OTT가 추가됩니다.
**밤보리님 OTT 저장소파일 다운**
[repository.nightrain_v19_public.zip](https://drive.google.com/file/d/1lJz25tYcZ9ywp-Lro-vklHACIm5D18im/view?usp=sharing)

##### 설치동영상
[KOREA OTT 설정](https://drive.google.com/file/d/1Liri6hDZ1CWFgZlMu-TABfFyk8cdqMgy/view?usp=sharing)
