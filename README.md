# 👩‍💻이하연 포트폴리오
항상 배우는 자세로 노력하는 백엔드 개발자 이하연입니다.

</br>

## :pushpin: Intro
- Back-end 개발자를 희망합니다.

</br>

## :pushpin: Contact
- 이메일: hayon2c@gmail.com
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

## 2. 📸 Picstory   - [자세히](https://www.notion.so/Picstory-Project-1305d1fd5ff5479395bbf9da80fc8c44?pvs=4)

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

<br/>
<br/>

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

