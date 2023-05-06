# Estuary.KM skin for Kodi 20.x Nexus
**Repository 설치**
>##### KM레포지토리 설치

repository.km.zip를 다운받아 저장소를 설치
[repository.km.zip](https://drive.google.com/file/d/1xMfDLi8r4Sqo8JKpfJeFc4GKjx-lvSLk/view?usp=share_link)   

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

---

>#### 부가영상및 예고편을 보기위한 Youtube 환경설정
##### Youtube API 키 생성
키발급 참조 링크
https://brunch.co.kr/@mystoryg/156
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
settings.xml 수정 예

```
<setting id="youtube.api.key">AIzaSyDULvIsd9일부삭제cyzndlJQUz5A</setting>    
<setting id="youtube.api.id">23676147256-7kkl일부삭제rh5v6pdmvt</setting>
<setting id="youtube.api.secret">GOCSPX-JPV일부삭제RrSiE9VMn-gqM</setting>
```
수정된 키 복사
##### 설치동영상
[youtube 키 복사](https://drive.google.com/file/d/142VuvJYydhl6b4MuWy-1AG9BVvUAmZ4k/view?usp=share_link)   
