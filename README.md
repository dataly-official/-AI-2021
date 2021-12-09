![poster](https://user-images.githubusercontent.com/93746948/141390138-95203535-9597-4983-81a6-c3be58595f9e.png)
![05 한국판뉴딜_서브 브랜드 로고_디지털뉴딜](https://user-images.githubusercontent.com/93746948/142318440-ef042a4d-a070-4d5c-8df7-1426c30ace8c.png)

# 민원 데이터 활용 AI 해커톤 2021
민원 데이터의 부서 정보를 활용하여 부서 분류 모델을 개발하는 해커톤입니다. 많은 참여부탁드립니다.

## 소개
과학기술정보통신부가 주관하고 한국지능정보사회진흥원(NIA)이 지원하는 2021년 인공지능 학습용 데이터 구축 사업의 일환으로 민원 데이터 업무 자동화를 위한 언어 인공지능 학습데이터 정제와 구축을 통한 인공지능 국가 기술력 제고와 인공지능 학습용 데이터에 대한 관심 제고로 4차 산업 혁명의 선도인력 양성에 기여하기 위하여 해커톤을 진행하오니 많은 관심과 적극적인 참여 부탁드립니다.

저희 Data.ly는 인공지능 분야 딥러닝 학습에 필요한 데이터를 생성, 관리, 가공, 보급하는 전문기업으로 자연어 처리 분야에 강점을 두고 있는 기업입니다. 자사의 WISEDOME(와이즈돔) 플랫폼을 이용해 고품질 데이터 가공 서비스를 전문적으로 제공하고 있습니다.

이번 해커톤에 관심이 있는 참가자분들이 파이썬을 이용하여 민원 데이터를 활용한 AI 모델을 직접 개발할 수 있는 기회가 되길 바랍니다.

## 개요
+ 주제: 민원 데이터의 부서 정보를 활용하여 부서 분류 모델 개발
+ 참가 대상: 전국대학에 재학 중인 대학생 이상 개인 또는 팀(3인 이하)
+ 참가 신청: 참가신청서 양식 다운로드 및 작성 (접수처 email로 제출)
  - 접수처 email: data.ly.official@gmail.com
  
## 대회 주요 일정
+ 참가팀 모집 및 안내 : 11.10. ~ 11.17.
+ 대회 진행 : 11.18. 11:00 ~ 12.10. 14:00
+ 평가 : 12.11. ~ 12.14.
+ 결과 발표 및 시상 : 12.15.

## 해커톤 안내
+ 개발 언어: python
+ 주어진 데이터셋으로 부서 분류 모델을 개발하여 가장 높은 정확도 성능 순으로 순위 선정 (데이터셋은 대회 시작 시 참가팀에게만 공개)
+ 팀 구성
  + 개인 또는 3인 이하로 팀 구성 가능합니다.
  + 중복의 팀에 참가 불가능합니다.
+ 답안 제출
  + 결과물 **포맷**(json, https://github.com/dataly-official/AI-Hackathon-2021-Using-Civil-Service-Data/issues/2#issue-1054353844
  )에 **맞추고** **dep 정보를 채워서 접수처 이메일로 제출**합니다.
  + 포맷 불일치시 해당 파일은 평가되지 않으며, 한팀은 하루에 한번 답안을 제출 가능합니다.
+ 모델 제출
  + 대회 진행이 마감되면, 리더보드 상위권 참가자 대상으로 모델 제출을 요청(필수)합니다.
  + 리더보드에 제출한 모델 결과가 재현되는지 여부를 확인하기 위한 절차로
    데이터를 제외한 나머지 소스코드가 github에 업로드 되어야합니다.
    또한 실행에 관한 설명문(또는 스크립트)이 포함되어야합니다.
  + 딥러닝 모델을 사용하는 것이 목표이고, 사전 학습 모델(예: BERT) 사용 가능합니다. 
    학습 중에 다른 제한 조건은 없습니다.
+ 데이터 
  + 학습/개발(검증)/평가 데이터 : json 포맷이고 각 40,000건/5,000건/5,000건 데이터가 참가 대상에게 이메일로 전달됩니다.
    참가자는 학습과 개발 데이터로 모델을 학습하고, 평가데이터 포맷에 맞춰 결과를 제출해주세요.
  + 데이터 json 속성: id, Q(민원), dep(담당부서)  
+ 평가
  + 참가자가 제출한 dep와 정답을 비교하여 Accuracy를 계산합니다.
  + Accuracy가 높은 순으로 순위를 정의합니다. 

## 리더보드(모델 평가 순위) [UPDATE 12.09, 3:30pm]
 + 결과물 파일 생성하실 때 utf-8로 인코딩하여 제출바랍니다.
 + 가장 최근 제출하신 답안 기준으로 순위 및 정확도가 업데이트됩니다.
 + 순위에 없는 팀은 리더보드 하단 팀명/점수로 표기
 + 12월10일 까지 제출해주신 결과물로 12월13일 순위 업데이트 
<table>
    <thead>
        <tr>
            <th>순위</th>
            <th>팀명</th>
            <th>Accuracy</th>
        </tr>
    </thead>
    <tbody>        
        <tr>
            <td> 1위 </td>
            <td> 데이터베이 </td>
            <td> 82.22% </td>
        </tr>
        <tr>
            <td> 2위 </td>
            <td> 민원해결 </td>
            <td> 82.02% </td>
        </tr>
        <tr>
            <td rowspan=2> 3위 </td>
            <td> 빅터널스 </td>
            <td> 81.36% </td>
        </tr>
        <tr>
            <td> SuperAwsome </td>
            <td> 80.88% </td>            
        </tr>
    </tbody>
</table>
+ 리벤지/80.3%, Air너구리/80.3%

# 주관/주최 : 한국지능정보사회진흥원(NIA)/데이터리(Data.ly)

+ Project Name : AI language training data for automation of civil affair work (민원 업무 자동화 인공지능 언어 데이터)

+ Participated Affiliation : Data.ly, 창원시청, NHN다이퀘스트, 에프아이솔루션, 케이웨어  

+ Website : <http://wisedome.kr>
