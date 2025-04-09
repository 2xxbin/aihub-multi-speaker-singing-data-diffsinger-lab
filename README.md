# NOTE : This data is only available to Koreans.

해당 데이터는 `한국지능정보사회진흥원` 의 사업결과 이며, [Aihub 데이터 이용정책](https://www.aihub.or.kr/intrcn/guid/usagepolicy.do?currMenu=151&topMenu=105)을 확인해보면 "본 AI데이터 등의 국외 반출을 위해서는 수행기관 등 및 한국지능정보사회진흥원과 별도로 합의가 필요합니다." 라고 적혀있습니다.

따라서 제작자, CV (목소리 제공자), 관리자가 모두 한국인이 아닐 경우, 해당 데이터 사용을 삼가해 주시면 감사하겠습니다.

<br/>

This data is the result of a project by the `National Information Society Agency of Korea (NIA)`. According to the [AIHub Data Usage Policy](https://www.aihub.or.kr/intrcn/guid/usagepolicy.do?currMenu=151&topMenu=105), “Exporting this AI data abroad requires a separate agreement with the implementing organization and the NIA.”

Therefore, if the creator, voice provider, or manager is not Korean, please refrain from using this data.

# 다화자 가창 데이터 라빌링 (Diffsinger 전용)

`한국지능정보사회진흥원`의 사업 결과인 Aihub [다화자 가창 데이터](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=465)의 일부를 [Diffsinger](https://github.com/openvpi/DiffSinger)용으로 재 라벨링 한 파일입니다.

해당 레포지토리에서는 라벨링 파일 (`.lab`)만 제공하며, 오디오 파일 (`.wav`)은 Aihub 공식 사이트에서 다운로드 받아 주세요.

WAV 파일 다운로드 : https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=465

라벨링 파일의 오디오 파일은 라벨링 파일과 동일한 이름의 파일로 찾을 수 있습니다.

## 사용된 화자 목록 (`화자명`: `파일 경로`)

- `s02` : `학습/02.록팝/A. 남성/01. 20대/가창자_s02`
- `s06` : `학습/02.록팝/B. 여성/01. 20대/가창자_s06`

<br/>

[Coda SVS](https://x.com/codasvs) 팀의 [디프싱어 한국어 표기법](https://github.com/Coda-SVS/diffsinger-korean-support/blob/main/PHONEMES.md) 표기로 제작되었습니다.

해당 음소 표기법에 추가로, 어미숨을 위한 `exh` 음소, 잡음 및 사용 불가능 발음을 포함하는 `trash`가 추가되어 있습니다.

영어 가사의 경우에는 최대한 한국어로 라벨링을 한 후, `f` 등의 한국어에서 존재하지 않는 발음은 그 부분만 `trash` 음소 처리 했습니다.

<br/>

해당 라벨링 파일을 사용 한 경우, 제작한 모델에 대해 아래와 같이 크레딧 표기를 남겨주세요.

```
본 모델에는 한국지능정보사회진흥원(NIA)의 사업 결과인 "AIHub 다화자 가창 데이터"의 일부가 사용되었습니다.
데이터 라벨링: 빈빈 (X: @2xxbin)
```
