# gmail_login
---
## INDEX

[Firebase](#firebase)

[gradle setting](#gradle-setting)

---

# Firebase


- 파이어베이스 프로젝트 생성

  - 프로젝트 생성

1. 로그인 후 우측 상단의 <콘솔로 이동> 클릭
![image](https://user-images.githubusercontent.com/67194430/173384675-f8f2b659-23d5-42c1-84b6-379444346f33.png)

2. 프로젝트 추가 클릭
![image](https://user-images.githubusercontent.com/67194430/173385038-b652a23c-8fd8-4395-9af5-680849ef80a0.png)

3. 프로젝트 이름 입력
![image](https://user-images.githubusercontent.com/67194430/173384975-56ae56a7-5db0-4127-99dd-b6f460c7adcc.png)

4. Google 애널리틱스 사용 설정
![image](https://user-images.githubusercontent.com/67194430/173385109-50697d39-95bf-40e1-b01a-055933af74e9.png)

5. 계정 선택 후 프로젝트 만들기 클릭
![image](https://user-images.githubusercontent.com/67194430/173385176-70159aa0-4430-4c16-9030-3418e107c3d3.png)

6. 안드로이드 선택
![image](https://user-images.githubusercontent.com/67194430/173385223-c1a4fb30-9ec9-4967-8cbf-5cac9fc79b57.png)

7. Android 패키지 이름과 Google 애널리틱스 이용을 위한 SHA-1 입력
![image](https://user-images.githubusercontent.com/67194430/173385280-58d4e0d1-d75e-40f4-86bc-ca261f7415f2.png)

7-1. Android 패키지 이름은 Activity code의 상단에서 확인 가능  
![image](https://user-images.githubusercontent.com/67194430/173385338-9e0e1160-876e-43fe-8afd-a98eaa4834e9.png)

7-2. SHA-1은 terminal에서 아래 command 입력
```
./gradlew signinReport
```

입력시 아래와 같은 결과 출력
```
> Task :app:signingReport
Variant: debug
Config: debug
Store: 
Alias: AndroidDebugKey
MD5: 
SHA1: 
SHA-256: 
Valid until: Sunday, December 18, 2050
```

![image](https://user-images.githubusercontent.com/67194430/173396065-4531367d-9d08-4141-b95b-329099683ffd.png)

![image](https://user-images.githubusercontent.com/67194430/173396106-9bb99f74-7722-4312-8ef1-59235aadd892.png)

![image](https://user-images.githubusercontent.com/67194430/173396147-fc63db4b-be4b-4b8d-838d-81227b9c73d4.png)

![image](https://user-images.githubusercontent.com/67194430/173396249-ec624e25-804d-46ed-919f-9f5754327343.png)

![image](https://user-images.githubusercontent.com/67194430/173396304-1cc43014-c349-4dc2-9460-e9d5cba875a1.png)



---

# gradle setting
