# JWT Token 
이 Repository는 [SessionSecurity Repo](https://github.com/doma17/SessionSecurity)에서 추가적으로 JWT Token에 대해서 다룬 것입니다.
Fresh Token 없이 단일 Token 만 사용했습니다. 

--- 

![springSecurityJwt](https://github.com/doma17/JwtSecurity/assets/67214970/4660a7e5-2e7f-49c3-8063-deac1171e89b)

- JwtFilter (토큰 필터)
  - OncePerRequestFilter
- JwtUtil (토큰 인증 및 생성)
- LoginFilter (로그인 필터)
  - UsernamePasswordAuthenticationFilter
  
- UserDetailService
- UserDetail

- SecurityConfig
  - CorsConfigurationSource
