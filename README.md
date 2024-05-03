# 이하연 포트폴리오
성장을 추구하는 인재 이하연입니다.

</br>

## :pushpin: Intro
- Back-end 개발자를 희망합니다.

</br>

## :pushpin: Contact
- 이메일: waterlee2035@gmail.com
- 깃헙: https://github.com/ggody2

</br>

# :pushpin: Projects

## 1. 🫳 NailArt
> 이미지오버레이를 통한 디자인입히기 및 가게추천 (핵심프로젝트)
>
> - 개발기간 : 23.10.25 ~ 23.12.08
> - 핵심 역할 : 전체적인 프론트 총괄, 메인페이지 & 마이페이지 & 가게등록페이지 프론트 및 백엔드
>
>> Back-end
>> - Language : python3  
>> - Skill : Django, Django-rest-framework, PostgreSQL
>> 
>> [프로젝트 상세 설명(Back-end)](https://github.com/2023-SMHRD-IS-CLOUD-1/NailArt.git)  
>
>> Front-end
>> - Language : javascript
>> - Skill : React.js
>>
>> [프로젝트 상세 설명(Front-end)](https://github.com/2023-SMHRD-IS-CLOUD-1/NailArt.git)

<br />

## 2. 📸 Picstory

> AI 기술을 활용한 이미지 태깅 기반의 사진첩 서비스 (실전 프로젝트)
>
> - 개발기간 : 2024.2.1 ~ 2024.2.27
> - 핵심 역할 : Python Flask & AWS EC2 & 도커환경 구축 , ai모델 API생성&연결, 결제페이지&계정찾기페이지 프론트 및 백엔드,  회원가입&로그인 페이지 프론트
>> 프로젝트 설명
>> - 사용자가 사진 업로드 시 자동으로 태그를 지정하여 분류하는 서비스를 제공
>> - 사용자가 폴더 생성 시 태그를 기반으로 사진 분류의 용이성을 제공
>> - 이미지 검색을 통한 유사한 이미지 검색 기능을 제공
>> - 갈수록 늘어가는 개인의 사진을 정리하는데에 필요한 시간과 수고를 덜어주고자 제작
>
>> 프로젝트 특장점
>> - 사진 업로드 시 자동으로 태그들이 지정됨
>> - 폴더 생성 후 사진 분류 시 사진에 부여된 태그를 활용해 태그 단위로 일괄적인 옮기기 가능
>> - 사진 한장에 여러 태그를 부여함으로써 사용자가 찾고자 하는 사진의 정확성을 높임
>> - 프리미엄 결제 시 기본으로 제공하는 태그에 추가적으로 사용자가 원하는 커스텀태그 생성 가능
>
>> Back-end
>> - Language : java 
>> - Skill : Spring Boot, Naver API, I'm Port API
>> 
>> [프로젝트 상세 코드(Back-end)](https://github.com/2023-SMHRD-IS-CLOUD-1/SpringCoC.git)  
>
>> Front-end
>> - Language : javascript
>> - Skill : React.js
>>
>> [프로젝트 상세 코드(Front-end)](https://github.com/2023-SMHRD-IS-CLOUD-1/PicStoryReact.git)
>
>> Modeling 
>> - Language : python
>> - Skill : VS code, Flask, Docker, EC2
>> - Model
>>> - faiss : 벡터탐색알고리즘 이용해 이미지들의 특징벡터 추출하고 다른 이미지들의 특징벡터와 비교하여 비슷한 이미지들을 출력
>>> - Zeroshot detection(GroundingDINO) : 이미지와 태그목록을 모델에 입력하면 태그목록 중에서 이미지에서 검출한 태그들을 출력함
>>> - VQA(Blip) : 이미지와 질문(텍스트)를 모델에 입력하면 하면 질문의 결과를 'yes' or 'no'로 응답하여 'yes'에 해당하는 이미지를 출력하게함으로써 사용자에게 커스텀태그 기능을 부여함.
>
<div align="center">
	<h3>기술스택</h3>
	<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white">
	<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
	<br/>
	<img src="https://img.shields.io/badge/apachetomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black"/>
	<img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
	<br/>
	<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
	<img src="https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
	<img src="https://img.shields.io/badge/AWS EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white">
	<img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
</div>

<br />
<br />
<details>
  <summary>핵심 기능 화면</summary>
	
  #### 1. 메인 페이지
  ![메인페이지](https://github.com/ggody2/profiles/assets/117277864/beaa4306-5574-4ca3-a016-b9037d4a55bb)
  
 #### 2. 로그인 / 회원가입
 ![로그인회원가입](https://github.com/ggody2/profiles/assets/117277864/b3aef17b-bee3-45e1-a524-3483571a50d5)

[로그인 컴포넌트](https://github.com/2023-SMHRD-IS-CLOUD-1/PicStoryReact/blob/73baa2ec86e1f56c992df16dc271b1065d21b3e6/src/components/Login.jsx)

[회원가입 컴포넌트](https://github.com/2023-SMHRD-IS-CLOUD-1/PicStoryReact/blob/73baa2ec86e1f56c992df16dc271b1065d21b3e6/src/components/Join.jsx)

 #### 3. 사진업로드 및 자동태그생성 
 ![사진업로드](https://github.com/ggody2/profiles/assets/117277864/f3520e9d-b65e-427c-ad0b-a99a5b0c5f30)

[사진업로드 컴포넌트](https://github.com/2023-SMHRD-IS-CLOUD-1/PicStoryReact/blob/73baa2ec86e1f56c992df16dc271b1065d21b3e6/src/components/photoAlbum/PAMenu.jsx)

[자동태그생성 코드](https://github.com/2023-SMHRD-IS-CLOUD-1/SpringCoC/blob/f6071d78fb71de21d98be24cc1e487097b8e79fa/Picstory/src/main/java/com/picstory/service/PicstoryService.java)
 
 #### 4. 폴더생성 및 즐겨찾기 
![폴더생성](https://github.com/ggody2/profiles/assets/117277864/b8a1d6b8-16f9-42ee-ba90-5a981ed154df)

[폴더생성 컴포넌트](https://github.com/2023-SMHRD-IS-CLOUD-1/PicStoryReact/blob/73baa2ec86e1f56c992df16dc271b1065d21b3e6/src/components/photoAlbum/PALeftSide.jsx)
  
 #### 5. 유사이미지 검색 
![유사이미지](https://github.com/ggody2/profiles/assets/117277864/6f76d638-ed6a-4624-98eb-91c5f0aca13f)

[유사이미지 컴포넌트](https://github.com/2023-SMHRD-IS-CLOUD-1/PicStoryReact/blob/73baa2ec86e1f56c992df16dc271b1065d21b3e6/src/components/photoAlbum/PAMenu.jsx)

[유사이미지 코드](https://github.com/2023-SMHRD-IS-CLOUD-1/SpringCoC/blob/f6071d78fb71de21d98be24cc1e487097b8e79fa/Picstory/src/main/java/com/picstory/service/PicstoryService.java)

 #### 6. 마이페이지 및 결제페이지
 ![마이페이지](https://github.com/ggody2/profiles/assets/117277864/a81f27c8-e7a3-47a7-9383-92a89a69f4e3)

[마이페이지 컴포넌트](https://github.com/2023-SMHRD-IS-CLOUD-1/PicStoryReact/blob/73baa2ec86e1f56c992df16dc271b1065d21b3e6/src/components/MyInfo.jsx)

 [결제페이지 컴포넌트](https://github.com/2023-SMHRD-IS-CLOUD-1/PicStoryReact/blob/73baa2ec86e1f56c992df16dc271b1065d21b3e6/src/components/Payment.jsx)
 

 #### 7. 커스텀태그 생성
 ![커스텀태그](https://github.com/ggody2/profiles/assets/117277864/73443ce2-fc4a-4fe2-8bf4-07216cf7a9c8)

 [커스텀태그 코드](https://github.com/2023-SMHRD-IS-CLOUD-1/SpringCoC/blob/f6071d78fb71de21d98be24cc1e487097b8e79fa/Picstory/src/main/java/com/picstory/service/PicstoryService.java)

</details>
<br/>
<details>
<summary>트러블 슈팅</summary>
	
#### 1. 도커환경 구축
<br/>
도커이미지 빌드 시 에러
<br/>

<br/>
<img width="700" src="https://github.com/ggody2/profiles/assets/117277864/6df3b020-68ac-4fed-be58-be9c60e5435c"/> <br/>
사용자가 Docker 그룹에 속해있지 않거나 sudo를 사용하지 않고 Docker 명령을 실행하는 경우에 발생하는 에러

해결 : sudo groupadd docker(도커그룹생성) -> sudo usermod -aG docker ${USER} (도커그룹에 유저 추가) -> sudo service docker restart (도커 재시작)

<br/>
도커파일 빌드 시 에러
 - ENV TZ=Asia/Seoul  => 타임존 설정하지 않아 에러
 - RUN apt install -y python3-pip  => pip 명령어 설치 : 도커파일 빌드 시 중간에 입력할 수 없으므로 -y
<br/>


#### 2. Flask 서버
<br/>
 aws 자격증명
- s3에 저장된 이미지의 특징벡터를 추출하는 api를 서빙하는 과정에서 아래와 같이 AWS 자격증명관리 오류가 발생
 line 418, in add_auth
    raise NoCredentialsError()
 botocore.exceptions.NoCredentialsError: Unable to locate credentials
- 해결 : 구글링을 통해 인스턴스용 IAM 역할을 사용하여 권한을 원활하게 관리하는 방법을 확인하여 시도해봄
- AmazonS3FullAccess 정책을 사용해 새로운 IAM 역할을 생성한 후, AWS Management Console을 통해 EC2 인스턴스에 역할을 연결함. 에러 발생 없이 s3에 저장된 이미지에 접근할 수 있게됨.
- (참고 : https://bosungtea9416.tistory.com/entry/자격-증명-없이-EC2에서-S3-액세스)

<br/>
</details>
