# GotYA · 콘텐츠 추천 구현

GotYA는 취향 테스트 결과를 바탕으로 영화, 책, 문화행사를 추천하는 팀 프로젝트입니다. 이 저장소에는 포트폴리오에서 설명한 추천 처리와 Django 데이터 모델을 살펴볼 수 있는 원본 소스 네 파일이 들어 있습니다.

| 살펴볼 내용 | 코드 |
| --- | --- |
| AI가 돌려준 추천에서 후보에 없는 ID와 중복을 걸러내고 부족한 결과를 채우는 과정 | [추천 처리](backend/tastes/services/recommendation_service.py#L75-L99) |
| 추천 모델 요청과 응답 처리 | [GMS 클라이언트](backend/tastes/services/gms_client.py) |
| 콘텐츠의 공통 정보와 사용자 상호작용 모델 | [콘텐츠 모델](backend/tastes/models.py#L98-L238) |
| 공통 콘텐츠와 영화 상세 정보의 관계 | [영화 모델](backend/movies/models.py#L6) |

전체 서비스의 화면과 프로젝트 설명은 [정유림의 포트폴리오](https://jj-yurim.github.io/Portfolio/)에서 볼 수 있습니다.
