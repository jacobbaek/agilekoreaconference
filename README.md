# Atlassian 으로 ITSM, CICD 흉내내기
Agile Korea Conference Hands-on 세션중 사용될 example 및 사용가이드 문서

# Chapter 별 따라하기
## Chapter 1 Hands-on 소개
[Atlassian으로 ITSM, CICD 흉내내기.pdf](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/AgileConferenceITSMCICD흉내내기.pdf)

## Chapter 2 Hands-on 준비
#### 서비스 가입
- Jira Cloud : https://id.atlassian.com<br>
[Jira Cloud Usage](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/Jira%2Bcloud%2B%EC%A4%80%EB%B9%84.pdf)

#### Project 생성
- Jira 에서 다음 project들을 생성
  - AgileConference
  - AgileConferenceServiceDesk<br>
  [Jira cloud project creation](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/Jira+cloud+project+creation.pdf)

#### 

- Bitbucket Cloud : https://bitbucket.org<br>
[Bitbucket Cloud Usage](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/Bitbucket%2Bcloud%2B%EC%A4%80%EB%B9%84.pdf)

#### Import Repository 
- Bitbucket 에서 다음 Repository를 import 수행
  - import 할 repository URL : https://bitbucket.org/oscikr/agilekoreaconf.git<br>
  [Bitbucket cloud import repository](files/Bitbucket+cloud+import+repository.pdf)

## Chapter 3 이슈 생성 및 개발 시작
- Jira Service Desk(AgileConferenceServiceDesk) Project내 Service Request 생성
- Jira (AgileConference) Project내 개발 Issue들 생성<br>
  [Jira cloud issue creation](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/Jira+cloud+issue+creation.pdf)
- Jira (AgileConference) Project내 Sprint 시작<br>
  [Jira cloud sprint](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/Jira+cloud+sprint.pdf)

## Chapter 4 Pipeline을 이용한 배포
- Bitbucket pipeline 생성 및 빌드 확인<br>
  [Bitbucket cloud pipeline](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/Bitbucket+cloud+pipeline.pdf)
- AWS codedeploy를 이용한 배포 (Demo)

## Chapter 5 이슈 종료
- Sprint 종료 및 남은 이슈 다음 Sprint로 이관<br>
  [Jira cloud sprint](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/Jira+cloud+sprint.pdf)
