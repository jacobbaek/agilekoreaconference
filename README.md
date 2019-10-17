# Atlassian 으로 ITSM, CICD 흉내내기
Agile Korea Conference Hands-on 세션중 사용될 example 및 사용가이드 문서

# Chapter 별 따라하기
## Chapter 1 Hands-on 소개
[Atlassian으로 ITSM, CICD 흉내내기.pdf](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/AgileConferenceITSMCICD흉내내기.pdf)
## Chapter 2 Hands-on 준비
#### Jira 서비스 가입
> 사용되지 않았던 Atlassian 계정의 사용을 권장드립니다.
- Jira Cloud : https://id.atlassian.com<br>
[01. Jira Cloud Usage](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/01.%2BJira%2Bcloud%2Bprepare.pdf)

#### Project 생성
- Jira 에서 다음 project들을 생성
  - 지라
  - 서비스데스크<br>
  [02. Jira cloud project creation](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/02.%2BJira%2Bcloud%2Bproject%2Bcreation.pdf)

#### Bitbucket 서비스 가입
- Bitbucket Cloud : https://bitbucket.org<br>
[03. Bitbucket Cloud Usage](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/03.%2BBitbucket%2Bcloud%2B%EC%A4%80%EB%B9%84.pdf)

#### Import Repository 
- Bitbucket 에서 다음 Repository를 import 수행
  - import 할 repository URL : https://bitbucket.org/oscikr/agilekoreaconf.git<br>
  [04. Bitbucket cloud import repository](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/04.%2BBitbucket%2Bcloud%2Bimport%2Brepository.pdf)

## Chapter 3 이슈 생성 및 개발 시작
- Jira Service Desk(서비스데스크) Project내 Service Request 생성
- Jira (지라) Project내 개발 Issue들 생성<br>
  [05. Jira cloud issue creation](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/05.%2BJira%2Bcloud%2Bissue%2Bcreation.pdf)
- Jira (지라) Project내 Sprint 시작<br>
  [06. Jira cloud sprint](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/06.%2BJira%2Bcloud%2Bsprint.pdf)

## Chapter 4 Pipeline을 이용한 배포
- Bitbucket pipeline 생성 및 빌드 확인<br>
  [07. Bitbucket cloud pipeline](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/07.%2BBitbucket%2Bcloud%2Bpipeline.pdf)
- AWS codedeploy를 이용한 배포 (Demo)

## Chapter 5 이슈 종료
- Sprint 종료 및 남은 이슈 다음 Sprint로 이관<br>
  [08. Jira cloud sprint 종료](https://github.com/jacobbaek/agilekoreaconference/blob/master/files/08.%2BJira%2Bcloud%2Bsprint%2Bfinish.pdf)
