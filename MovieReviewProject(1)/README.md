# Movie Review Project
영화 리뷰 관리 사이트 제작


## 프로젝트 소개
사용자, 영화, 시청기록, 리뷰 테이블을 생성해서 <br> 
특정 영화에 대한 시청기록이 존재하는 사용자만이 리뷰를 작성할 수 있습니다. <br>
사용자가 탈퇴한다면 모든 기록은 사라집니다.
<br>

### 맴버구성
 - 팀장  : 이태원 - REVIEWS 테이블 전담, view 제작, 깃허브 관리 
 - 팀원1 : 신하윤 - WATCH_HISTORY 테이블 전담,
 - 팀원2 : 박찬희 - USERS 테이블 전담, README 작성
 - 팀원3 : 정건일 - MOVIES 테이블 전담,

### 개발 환경
- `Java 8`
- `JDK 1.8.0`
- **Database** : Oracle DB(11xe)

##  주요 기능
#### MOVIES_GENRE_SELECT_PROCEDURE
- 장르별 영화 출력
#### WATCH_HISTORY_TOTAL_VIEW_FUNCTION
- 전체 시청시간 계산 후 출력
#### REVIEW_AVG_SCORE_FUNCTION
- 리뷰 점수 평균 계산 후 출력
