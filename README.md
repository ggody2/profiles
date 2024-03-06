# 이하연 포트폴리오
성장을 추구하는 인재 이하연입니다.

</br>

## :pushpin: Intro
- Back-end 개발자를 희망합니다

</br>

## :pushpin: Contact
- 이메일: waterlee2035@gmail.com
- 깃헙: https://github.com/ggody2

</br>

# 📝Projects
5개월간 진행했던 프로젝트들 입니다!  
팀장으로서는 운영적인 면과 ***팀원들 학습 관리***, 프로젝트 일정 관리 등 많은 경험을 할 수마

## 1. 🫳 NailArt
> 이미지오버레이를 통한 디자인입히기 및 가게추천 (핵심프로젝트)
>
> - 개발기간 : 23.10.25 ~ 23.12.08
> - 핵심 역할 : 전체적인 프론트 총괄, 메인페이지 & 마이페이지 & 가게등록페이지 화면구성 및 기능
>
>> Back-end
>> - Language : python3  
>> - Skill : Django, Django-rest-framework, PostgreSQL
>> 
>> [프로젝트 상세 설명(Back-end)](https://github.com/2023-SMHRD-IS-CLOUD-1/SpringCoC.git)  
>
>> Front-end
>> - Language : javascript
>> - Skill : React.js
>>
>> [프로젝트 상세 설명(Front-end)](https://github.com/2023-SMHRD-IS-CLOUD-1/PicStoryReact.git)

<br />

## 2. 📸 Picstory

> AI 기술을 활용한 이미지 태깅 기반의 사진첩 서비스 (실전 프로젝트)
>
> - 개발기간 : 2024.2.1 ~ 2024.2.27
> - 핵심 역할 : python Flask & EC2 & 도커환경 구축 , ai모델들 API생성 & 서빙 , faiss모델 Spring Boot,React와 연결, 결제페이지(I'm port API) & 아이디,비밀번호 찾기페이지 화면구성 및 기능,  회원가입,로그인 페이지 화면구성
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
	<P>기술스택</P>
	<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white">
	<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
	<img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
	<img src="https://img.shields.io/badge/apachetomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black"/>
	<img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
	<img src="https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
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
> - 도커이미지 빌드 시 에러
<br/>
![image]()

<br/>
> Docker를 실행하는 사용자가 Docker 데몬에 액세스할 수 있는 권한이 없기 때문에 사용자가 Docker 그룹에 속해있지 않거나 sudo를 사용하지 않고 Docker 명령을 실행하는 경우에 발생하는 에러

> 해결 : sudo groupadd docker(도커그룹생성) -> sudo usermod -aG docker ${USER} (도커그룹에 유저 추가) -> sudo service docker restart (도커 재시작)

<br/>
> - 도커파일 빌드 시 에러
>> - ENV TZ=Asia/Seoul  => 타임존 설정하지 않아 에러
>> - RUN apt install -y python3-pip  => pip 명령어 설치 : 도커파일 빌드 시 중간에 입력할 수 없으므로 -y
<br/>


#### 2. Flask 서버
모바일 환경에 최적화를 위해 게시판 형식의 기본 페이징이 아닌, 무한 스크롤 방식을 사용함.
기존의 페이징은 offset과 limit을 사용해서 페이징할 범위를 정하지만, 이 방식은 초반에는 효율이 나쁘지 않지만 뒤로 갈수록 효율이 급격히 떨어진다는 단점이 있어 사용하지 않고, JPA의 pageable 기능을 사용해 구현했습니다.
<br/>
 spring Boot 
 <br/>
 @post controller
 <br/>
 
 ![image](https://github.com/yusuyeon1111/portfolio/assets/142488306/65c1da60-66a0-452a-9d12-e09afb0673b0)
 
 <br/>
 
 ![image](https://github.com/yusuyeon1111/portfolio/assets/142488306/e83e393c-8f3c-45c5-ba89-ef1f814407f9)
 
<br/>

React 

<br/>
useInview를 활용하여 페이지 끝에 도달할 시 페이지 넘버를 증가시켜 로드 했습니다.

<br/>

![image](https://github.com/yusuyeon1111/portfolio/assets/142488306/f97031a6-9097-4960-a890-b45568d24586)

<br/>

페이지넘버를 get방식으로 요청해 이미지를 로드 하였습니다.

<br/>

![image](https://github.com/yusuyeon1111/portfolio/assets/142488306/acf1d653-b0b1-471f-ae06-410840c1216f)

<br/>

[코드보러가기](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front/blob/05e84843bfaef66c4b6417432049e14dc2a611a1/src/components/CommunityMasonry.jsx#L76)

<br/>
 [느낀점]
 <br/>
 JPA를 처음 사용하다 보니 어려움을 겪었으나 수많은 시행착오와 구글링을 통해 구현할 수 있었으며, JPA에 대한 이해도를 올릴 수 있었습니다.
</details>


## :pushpin: Projects

---

### 1. [실전 프로젝트](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front)
#### [백엔드](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein.git)

> Letmein (팀 프로젝트) 
>개발 기간: 2024.2.1 ~ 2024.2.27 
> 
> Front-end + Back-end
> 
> 프로젝트 기여도 50%
> 
> 팀원 3명 (PM, 모델링, Front-end+Back-end)
> 
> 프로젝트 설명
> 
> - YOLO기반 체형확인 및 패션 스타일러 입니다
> - 커뮤니티에 코디 사진을 업로드 할 수 있습니다!
> - 체형 사진을 업로드해 체형 기반 아바타를 생성해 코디를 해볼 수 있습니다!
> - 사진대신 사이즈를 입력한 아바타 생성도 가능합니다!
>
>   구현내용
>  - aws s3 이미지 업로드 기능
>  - spring boot security를 활용한 비밀번호 암호화 구현
>  - 메인페이지 제작
>  - 커뮤티니 페이지 제작 & 모든 기능 구현
>  - 체형 분석 페이지 제작 & 모든 기능 구현
>  - 고객 센터 페이지 제작 & 모든 기능 구현
>  - 마이페이지 제작 & 기능 구현
>  - 관리자 페이지 제작 & 모든 기능 구현
>  - EC2 활용한 Spring Boot, react 배포
> 
<div align="center">
	<P>기술스택</P>
	<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white">
	<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
	<img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
	<img src="https://img.shields.io/badge/apachetomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black"/>
	<img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
	<img src="https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
</div>
 <br/>
 <br/>
<details>
  <summary>핵심 기능 화면</summary>
	
  #### 1. 메인 페이지
![제목 없는 동영상 - Clipchamp로 제작](https://github.com/yusuyeon1111/portfolio/assets/142488306/e94a754c-fa5c-4b7a-b925-be1531f704f0)
 #### 2. 로그인 / 회원가입
![-Clipchamp2-ezgif com-video-to-gif-converter](https://github.com/yusuyeon1111/portfolio/assets/142488306/e8c78fed-0cff-4399-a472-f6997ebfd03c)

[로그인 코드 보러가기](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front/blob/2166e393216249129134d9dae6d1bd3a46d2a41e/src/components/Login.jsx#L9)

[회원가입 코드 보러가기](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front/blob/2166e393216249129134d9dae6d1bd3a46d2a41e/src/components/Join.jsx#L11)

 #### 3. 커뮤니티
 ![-Clipchamp3-ezgif com-video-to-gif-converter](https://github.com/yusuyeon1111/portfolio/assets/142488306/b5dfbf08-3f8d-4344-bc32-18f00510663f)

[커뮤니티 코드 보러가기](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front/blob/2166e393216249129134d9dae6d1bd3a46d2a41e/src/components/Community.jsx#L21)

[커뮤니티 최신글 컴포넌트](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front/blob/2166e393216249129134d9dae6d1bd3a46d2a41e/src/components/CommunityMasonry.jsx#L12)

[커뮤니티 인기글 컴포넌트](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front/blob/2166e393216249129134d9dae6d1bd3a46d2a41e/src/components/ComSortMansory.jsx#L12)

[커뮤니티 글 상세보기 컴포넌트](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front/blob/2166e393216249129134d9dae6d1bd3a46d2a41e/src/components/CommunityDetail.jsx#L24)
 
 #### 4. 마이페이지
  ![-Clipchamp5-ezgif com-video-to-gif-converter](https://github.com/yusuyeon1111/portfolio/assets/142488306/3d90494b-3cd9-4401-8763-cca21fa97364)
  
[마이페이지 코드 보러가기](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front/blob/2166e393216249129134d9dae6d1bd3a46d2a41e/src/components/Mypage.jsx#L13)
  
 #### 5. 이미지 업로드 체형 분석 페이지
![-Clipchamp6-ezgif com-video-to-gif-converter](https://github.com/yusuyeon1111/portfolio/assets/142488306/275a7a94-302d-44cf-bf7c-bb4875c91fef)

 #### 6. 결과페이지 및 아바타 페이지
![제목 없는 동영상 - Clipchamp로 제작 (2)](https://github.com/yusuyeon1111/portfolio/assets/142488306/48d39fef-468b-41a8-bf2a-b8538254e20b)

 #### 7. 사이즈 입력 체형 분석 페이지
![제목 없는 동영상 - Clipchamp로 제작 (1)](https://github.com/yusuyeon1111/portfolio/assets/142488306/f2eb06b4-19fb-4061-9660-477c28c7c9d0)

 #### 8. 관리자 페이지
 ![image](https://github.com/yusuyeon1111/portfolio/assets/142488306/919ebf59-9f54-4013-976c-cf189de56682)

</details>

	
#### 1. 이메일 API 사용
<br/>
이메일 인증을 위해 이메일 API인 email.js를 사용했습니다.
<br/>

![image](https://github.com/yusuyeon1111/portfolio/assets/142488306/deb5ca66-6f01-4579-b827-d50302f7055c)

<br/>

[코드 보러 가기](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front/blob/05e84843bfaef66c4b6417432049e14dc2a611a1/src/components/Join.jsx#L23)

<br/>


#### 2. 무한 스크롤 기능 구현
모바일 환경에 최적화를 위해 게시판 형식의 기본 페이징이 아닌, 무한 스크롤 방식을 사용함.
기존의 페이징은 offset과 limit을 사용해서 페이징할 범위를 정하지만, 이 방식은 초반에는 효율이 나쁘지 않지만 뒤로 갈수록 효율이 급격히 떨어진다는 단점이 있어 사용하지 않고, JPA의 pageable 기능을 사용해 구현했습니다.
<br/>
 spring Boot 
 <br/>
 @post controller
 <br/>
 
 ![image](https://github.com/yusuyeon1111/portfolio/assets/142488306/65c1da60-66a0-452a-9d12-e09afb0673b0)
 
 <br/>
 
 ![image](https://github.com/yusuyeon1111/portfolio/assets/142488306/e83e393c-8f3c-45c5-ba89-ef1f814407f9)
 
<br/>

React 

<br/>
useInview를 활용하여 페이지 끝에 도달할 시 페이지 넘버를 증가시켜 로드 했습니다.

<br/>

![image](https://github.com/yusuyeon1111/portfolio/assets/142488306/f97031a6-9097-4960-a890-b45568d24586)

<br/>

페이지넘버를 get방식으로 요청해 이미지를 로드 하였습니다.

<br/>

![image](https://github.com/yusuyeon1111/portfolio/assets/142488306/acf1d653-b0b1-471f-ae06-410840c1216f)

<br/>

[코드보러가기](https://github.com/2023-SMHRD-IS-CLOUD-1/Letmein-front/blob/05e84843bfaef66c4b6417432049e14dc2a611a1/src/components/CommunityMasonry.jsx#L76)

<br/>
 [느낀점]
 <br/>
 JPA를 처음 사용하다 보니 어려움을 겪었으나 수많은 시행착오와 구글링을 통해 구현할 수 있었으며, JPA에 대한 이해도를 올릴 수 있었습니다.
</details>

---

### 2. [핵심 프로젝트](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject.git)
>HEF  (팀 프로젝트)  
>개발 기간: 2023.11.22 ~ 2023.12.8
>
> Front-end + Back-end
>
>프로젝트 설명
> - 게시판 기반 심부름 매칭 서비스 입니다!<br/>
> - OCR로 신분증 인증이 가능합니다!<br/>
> - 커뮤니티로 소통할 수 있습니다!<br/>
<div align="center">
	<P>기술스택 </P>
	<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white" />
	<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white" />
	<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white" />
	<img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"/>
	<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"/>
</div>


<details>
<summary><b>핵심 기능 설명 펼치기</b></summary>

 #### 1. 전체 흐름
![image](https://github.com/yusuyeon1111/sample/assets/142488306/fb8c738f-39f2-4bde-8ffb-b62c8f893d55)
1. 의뢰인이 심부름 의뢰글을 작성합니다
2. 의뢰글을 수행인이 심부름 페이지에서 검색해서 조회할 수 있습니다.
3. 수행인이 의뢰글에 수행 신청을 하게되면
4. 의뢰인의 수행인 신청 목록 확인 서비스에서 수행인의 프로필을 확인할 수 있습니다
5. 의뢰인은 수행인의 신청 목록을 확인해 신청을 수락할 수 있고 거절할 수 있습니다.
6. 신청을 수락하게 되면 심부름은 매칭되고 매칭 여부가 데이터베이스 상에서 변화됩니다.

#### 2. 심부름 페이지

![image](https://github.com/yusuyeon1111/sample/assets/142488306/e5cb9e68-77ad-4374-ba8d-b40cda984f70)

<br/>
 1. 카테고리 : 카테고리 필터링 시스템을 구현해 카테고리에 따라 확인 가능
   
[🔍](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject/blob/c01013df001193fbb4c00e65eb206ceccf58d18b/FirstProject_Whip/src/main/java/com/smhrd/controller/Err_readService.java#L18)
<br/>
 2. 검색창 : 검색 기능을 통해 사용자가 원하는 심부름 신청글을 제목과 작성자를 기준으로 검색 가능<br/>
   
[🔍](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject/blob/c01013df001193fbb4c00e65eb206ceccf58d18b/FirstProject_Whip/src/main/java/com/smhrd/controller/Err_searchService.java#L18)
   <br/>

3. 심부름 요청 글 작성 페이지로 이동


4. 심부름 글의 상세 내용을 확인할 수 있는 기능, 다른 사용자가 열람 가능.

[🔍글 상세보기](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject/blob/c01013df001193fbb4c00e65eb206ceccf58d18b/FirstProject_Whip/src/main/java/com/smhrd/controller/Err_detailService.java#L18)<br/>
[🔍글 수정](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject/blob/c01013df001193fbb4c00e65eb206ceccf58d18b/FirstProject_Whip/src/main/java/com/smhrd/controller/ErrmodifyService.java#L15)
<br/>
[🔍글 삭제](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject/blob/c01013df001193fbb4c00e65eb206ceccf58d18b/FirstProject_Whip/src/main/java/com/smhrd/controller/ErrdeleteService.java#L15)
<br/>
 5. 신청 버튼 클릭시 신청되며 신청인의 수행인 신청 목록 확인 서비스에서 확인 가능
   
[🔍](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject/blob/c01013df001193fbb4c00e65eb206ceccf58d18b/FirstProject_Whip/src/main/java/com/smhrd/controller/Err_matchService.java#L20)
<br/>
#### 3. 고객센터 페이지

![image](https://github.com/yusuyeon1111/sample/assets/142488306/3e7a3b69-9e93-411c-904e-1df81ba40895)

1)  검색창 : 검색 기능을 통해 사용자가 원하는 문의글을 제목과 작성자를 기준으로 검색 가능
    <br/>
[🔍](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject/blob/c01013df001193fbb4c00e65eb206ceccf58d18b/FirstProject_Whip/src/main/java/com/smhrd/controller/Man_searchService.java#L21)
<br/>   

2) 문의글 작성 페이지로 이동

[🔍](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject/blob/c01013df001193fbb4c00e65eb206ceccf58d18b/FirstProject_Whip/src/main/java/com/smhrd/controller/ManagePostService.java#L15)
 
3) 문의글 상세 내용을 확인할 수 있는 기능

[🔍](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject/blob/c01013df001193fbb4c00e65eb206ceccf58d18b/FirstProject_Whip/src/main/java/com/smhrd/controller/Manage_detailService.java#L21)
   <br/>
   
4) 관리자 답변여부 확인 가능<br/>

5) 관리자 계정을 생성해, 관리자 계정으로 로그인 시, 고객센터 문의글에 답변할 수 있는 기능

[🔍](https://github.com/2023-SMHRD-IS-CLOUD-1/1stProject/blob/c01013df001193fbb4c00e65eb206ceccf58d18b/FirstProject_Whip/src/main/java/com/smhrd/controller/Manage_answerService.java#L16)    
---
  </details>
