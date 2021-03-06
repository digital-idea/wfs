# WFS(Web File System)

![travisCI](https://secure.travis-ci.org/digital-idea/wfs.png)

주요기능: 웹을 통해서 서버의 파일을 브라우징합니다.

부가기능:
- 필요시 작업에 필요한 샷 뉴크파일 생성, 초기 셋팅

### 다운로드
- [Linux 64bit](https://github.com/digital-idea/wfs/releases/download/v1.0/wfs_linux_x86-64.tgz)
- [MacOS 64bit](https://github.com/digital-idea/wfs/releases/download/v1.0/wfs_darwin_x86-64.tgz)
- [Windows 64bit](https://github.com/digital-idea/wfs/releases/download/v1.0/wfs_windows_x86-64.tgz)

### 서버실행

```bash
$ wfs -http :8081 -rootpath /show
```

### HISTORY
- '19.6.7 : 오픈소스 전환
- '15.6.10 : 1차 개발완료. 목적 : 웹에서 스토리지의 파일 프리뷰 및 [dilink](https://github.com/digital-idea/dilink) 연동.
