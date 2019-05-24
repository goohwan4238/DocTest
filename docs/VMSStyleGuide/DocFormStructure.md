---
id: DocFormStructure
title: 문서 형식 및 구조
sidebar_label: Documentation Structure and Format
---

본 가이드는 사용자가 문서를 작성 시 참고하기 위한 문서 형식 및 구조에 대한 가이드입니다. 

## 제목 및 Heading 작성 가이드 ## 

본 가이드는 VMS Solutions 프로젝트 관련 Manual, Tip & Sample, 설계문서 및 Release Note 작성 시 공통으로 적용됩니다. 본 가이드는 Mark Down으로 문서 작성 시 참고하는 가이드입니다. 

### 제목 및 Heading 크기에 대한 가이드 ###
- Mark Down 기준으로 문서 제목 크기는 1단계로 합니다. 
- Mark Down 기준으로 문서 내 특정 내용에 대한 Heading은 2단계로 합니다. 
- Mark Down 기준으로 2단계 Headings에 포함된 내용에 Headings 추가가 필요한 경우 3단계를 사용합니다. 그러나 가급적 문서 작성 시 3단계까지 가지 않게 작성하는 것을 권장합니다. 

### 제목 및 Heading 정하기 ### 
- 제목은 주제와 목적을 포함해야 합니다.
- 특정 독자가 제목만 읽었을 때 어떤 내용에 대해 다루는지 알 수 있도록 '힌트'를 주어야 합니다. 
- 제목은 구체적으로 작성합니다. 

    > 안 좋은 예:   
    > 좋은 예: 

- 제목 및 Heading 이름에는 목차의 번호를 포함시키지 않습니다. 
- 제목 및 Heading에는 줄, 폰트 스타일 변경(_Italic_, 색상 변경), Highlight등의 효과를 적용하지 않습니다. 

여기서 `Batch Conversion to csv`는 MOZART Studio에 있는 기능 중 하나입니다. 해당 기능을 사용 시 열려있는 모델의 Input/Output 데이터를 일괄적으로 CSV 파일로 추출하는 기능입니다. 이러한 기능을 설명하는 내용에 대한 제목을 정해야 하는 경우 해당 기능이 어떤 용도로 사용되는지 독자가 알 수 있도록 구체적으로 작성해야 합니다. 

## 목록(List) 작성 가이드 ## 

문서를 작성함에 있어 어느 특정 내용을 구조적으로 작성이 필요한 경우 목록(List)를 사용합니다. 본 가이드에서는 목록의 종류 및 종류 별 사용 Case에 대해서 기술합니다. 

### 목록의 종류 ###

문서 작성 시 사용 가능한 목록의 종류는 다음과 같습니다. 

목록종류 | 사용 범위 | 
|---|---|
| 번호형식 목록 | 어떤 절차에 대해 순서대로 진행이 필요한 내용을 작성 시 사용합니다. |
| 영문 알파벳 (대문자) | 선택이 필요한 옵션들을 제시 하는 경우 사용합니다. |
| 글머리기호 (Bullet) | 용어에 대해 용어 + 설명/정의 작성 시 사용합니다. 그 외에는 어떤 대상이 가지고 있는 특성이나 기능에 대해 열거해야하는 경우 사용합니다. 

> 주의: 대상이 하나만 있는 경우에는 목록을 사용하지 않습니다. 예를 들어 사용자가 어떤 기능을 사용하기 위해 따라야 할 절차가 여러개 있는 경우 각 절차를 순서대로 목록으로 표현하면 되지만, 하나의 절차만 따르는 경우에는 목록을 사용하지 않습니다. 

### 목록 예제 ### 

절차에 대한 순서 예시: 

1. _C:\Program Files (x86)\VMS\Mozart\Bin_ 폴더로 이동합니다. 
2. APS_Studio.exe를 실행합니다. 
3. **[File] > [Open Project...]** 를 선택합니다. 
4. `vModel` 파일을 선택합니다. 

선택형 옵션 목록 예시: 

Data Base 제공자에 따라 `DataSource`를 설정하는 방법은 아래를 참고하십시오. 

<ol type ="A">
<li>MSSQL로 설정하는 방법</li>   
<li>Oracle로 설정하는 방법</li>   
<li>MySQL로 설정하는 방법</li>   
<li>SQLite로 설정하는 방법</li>
</ol>

글모리 기호 목록 예시:

MMC를 이용하면 다음과 같은 작업을 할 수 있습니다. 

- vModel 파일 및 DLL 파일 업로드 
- Job 및 Trigger 생성 
- Trigger 수행 주기 설정 
- Trigger 수행 이력 확인 

`FireUser` 함수의 각 파라미터는 다음과 같습니다. 

- user : Mozart Sever 접속에 사용되는 사용자 ID입니다. 
- pw : Mozart Server 접속에 사용되는 비밀번호입니다. 
- triggername : 실행 할 Trigger의 이름입니다. 


출처: Google Developer Documentation Style Guide
