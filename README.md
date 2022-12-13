![로고](https://raw.githubusercontent.com/choi1five/project-watermelon/8e0331562a7acdb1800702e2232fbe1518b92718/assets/images/melon-01.svg)

<br />

---

<div id="1"></div>
<br />

## 📢 프로젝트 소개

멜론 클론 프로젝트로 반응형 구현, 웹접근성 개선, 플레이어 설치 없이 웹에서 음악 청음 구현을 목표

<img width="1423" alt="스크린샷 2022-12-13 오후 9 54 50" src="https://user-images.githubusercontent.com/99406837/207323880-dbc8609c-3a92-4792-ba05-49279af03dca.png">

<br />

## 💻 실행방법

</br>

```
npm install
npm start
```

</br>

## 🛠️ 담당 업무

- 차트 페이지 반응형 구현
  <img width="991" alt="스크린샷 2022-12-13 오후 9 49 31" src="https://user-images.githubusercontent.com/99406837/207324123-b1ececfd-14dd-4b65-b9a8-fc97aa159723.png">

- 접근성을 위해 이미지로 구현된 기존 네비게이션을 텍스트로 구현
  <img width="1177" alt="image" src="https://user-images.githubusercontent.com/99406837/207324879-83768446-4728-4410-85aa-40a8feaba1b8.png">

- 로그인 버튼으로 바로 이동 가능하도록 스킵 네비게이션 개선
  <img width="1174" alt="image" src="https://user-images.githubusercontent.com/99406837/207325224-56213272-ebc1-493c-8146-7922404a68a9.png">

- 비디오 재생시간 스크린리더 환경에서 올바르게 읽어주도록 개선
  <img width="1286" alt="image" src="https://user-images.githubusercontent.com/99406837/207325447-8bc72a9e-b5f9-4c1a-b180-1505f6183809.png">

<br />

## 💼 회고

### 웹 접근성

음악은 누구나 즐길 수 있는 컨텐츠 임에도 스크린 리더 사용자를 위한 웹 접근성이 많이 아쉬웠다.
<img width="1268" alt="스크린샷 2022-12-13 오후 10 10 08" src="https://user-images.githubusercontent.com/99406837/207326796-34c723bf-ece3-45d1-9aed-0e11ad6f148f.png">
오타로 인해 따옴표라고 읽어 혼란을 야기하는 부분도 있었고 위의 개선 사례에 나왔던 비디오 재생시간이 분과 초로 제공되는 컨텐츠를 몇 대 몇으로 읽기도 하고 시와 분으로 읽기도 하여 완전 잘못된 정보를 제공하는 경우도 있었다.
<br />

### 시멘틱 마크업

<img width="1290" alt="image" src="https://user-images.githubusercontent.com/99406837/207327534-af9939e1-a9c4-4171-bd05-b3e2a1a67cd6.png">
div 위주의 마크업에서 시멘틱한 마크업에 대한 많은 고민을 하며 학습할 수 있었다.
<br />
스크린 리더 사용자들에게 보다 나은 접근성을 제공하고 SEO 측면에서 시멘틱 태그를 중요 키워드로 크롤링함을 알게 되었다.
<br />
또한 유지보수 및 가독성의 측면에서 보더라도 훨씬 직관적으로 유리함이 있음을 느꼈다.
