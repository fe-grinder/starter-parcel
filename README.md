# basic starter kit

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

## 새로운 프로젝트 만들기

``` shell
# 스타터킷 클론받기
git clone https://github.com/fe-grinder/starter-parcel.git ${프로젝트이름}

# git 초기화하기
cd ${프로젝트이름}

# starter-parcel 리포지토리정보 삭제
rm -rf .git

# 신규프로젝트로 git 초기화
git init

```

## Package.json

- `starter-parcel` -> `프로젝트이름` 으로 수정

## npm scripts

``` shell
# 개발용
npm start

# js linter
npm run lint

# 프로덕션용 코드
npm run build
```

## github page 연동하기

- 빌드 아웃풋 폴더명 `docs`로 설정 (스타터킷에는 `docs`로 설정되어있습니다)
- 깃헙 리포 페이지에서 [`Settings`](https://github.com/fe-grinder/starter-parcel/settings) -> `GitHub Pages` 섹션에 드롭다운 메뉴를 `master branch/docs folder`로 변경