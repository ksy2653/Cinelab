# Cinelab

## Cinelab APP SNS 로그인 개발
- 보안의 안정성을 위해 JWT 토큰을 이용하여 개발
- Access Token과 Refresh Token의 만료 시간을 다르게 하여 보안 안정성 강화
- 관련 코드는 회사 보안상 공개할 수 없습니다.
<br>

> **Logic**
> - 첫 로그인
>   
>  ![login](https://github.com/ksy2653/Cinelab/blob/main/jwt_login_%EC%B2%AB%EB%A1%9C%EA%B7%B8%EC%9D%B8.jpg)
>
> - access token 유효
>   
>  ![access](https://github.com/ksy2653/Cinelab/blob/main/jwt_login_%EC%95%A1%EC%84%B8%EC%8A%A4%ED%86%A0%ED%81%B0%EC%9C%A0%ED%9A%A8.jpg)
>     
> - access token 만료 & refresh token 유효
>   
>  ![access only](https://github.com/ksy2653/Cinelab/blob/main/jwt_login_%EC%95%A1%EC%84%B8%EC%8A%A4%EB%A7%8C%EB%A3%8C_%EB%A6%AC%ED%94%84%EB%A0%88%EC%8B%9C%EC%9C%A0%ED%9A%A8.jpg)
> 
> - access token 만료 & refresh token 만료
>   
>  ![refresh](https://github.com/ksy2653/Cinelab/blob/main/jwt_login_%EC%95%A1%EC%84%B8%EC%8A%A4%EB%A7%8C%EB%A3%8C_%EB%A6%AC%ED%94%84%EB%A0%88%EC%8B%9C%EB%A7%8C%EB%A3%8C.jpg)
>
<br>
<br>

