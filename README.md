<div style="border: 2px solid #aaa; border-radius: 12px; overflow: hidden;">
    <img src="https://cdn.akamai.steamstatic.com/steam/apps/1296610/header.jpg?t=1700092609" alt="Peglin" style="width: 10% align="center"; height: auto;">
</div>

# Peglin 한글 패치

이 프로젝트는 Peglin 의 한글 패치를 제공합니다.<br>
기존 한글패치의 번역 미적용 문제를 해결했습니다.<br>
번역 문장이 많고, 직접 번역하여 오역이 있을 수 있습니다!

## 패치 적용 방법

1. 게임을 최신 버전으로 업데이트하세요.
2. [[구글 드라이브로 이동]](https://drive.google.com/file/d/1P-O7EVREUmGHdbYlVsQLr67L3Hw0l9My/view?usp=sharing) 좌측 링크를 클릭하여, 한글 패치 파일을 다운받으세요.
3. 'Peglin_Data.zip' 파일을 압축 해제 하세요.
4. Steam 라이브러리에서 Peglin을 우클릭하여 '관리 -> 로컬 파일 보기' 를 클릭하세요.
5. SteamLibrary\steamapps\common\Peglin 폴더가 열리는데,<br>
다운받은 'Peglin_Data' 폴더를 붙여넣기 하여 '덮어쓰기'를 하세요.
6. 게임을 실행하고 환경설정에서 '언어 - 한국어' 을 선택하고, 변경된 내용을 확인하세요.

## 주의 사항

- 패치를 적용하고 문제가 생긴다면<br>
Steam 라이브러리에서 Peglin을 우클릭하여 '속성 -> 설치된 파일 -> 무결성 검사' 를 클릭하세요.
- 이 패치는 게임 버전 v0.9.32 에 대해 테스트되었습니다.
- 문제가 발생할 경우 이슈를 생성해주세요.

## 기여

기여는 언제나 환영합니다! 버그를 발견하거나 기능을 추가하고 싶다면 풀 리퀘스트를 보내주세요.

## 번역 방법
1. '<> Code -> Download ZIP' 을 클릭하여, 번역 파일을 다운받으세요.
2. 압축을 해제하여 I2Languages-resources.assets-11108.json를 여세요.
3. 아래와 같은 형식으로 번역한다. <br>
```
{
    "0 MonoBehaviour Base": 
    {
            "1 string m_Name": "I2Languages",
        "0 LanguageSourceData mSource": 
        {
            "1 UInt8 UserAgreesToHaveItOnTheScene": 0,
            "1 UInt8 UserAgreesToHaveItInsideThePluginsFolder": 0,
            "1 UInt8 GoogleLiveSyncIsUptoDate": 1,
            "0 TermData mTerms":  {
                "0 Array Array": [
                    {"0 TermData data": 
                    {
                        "1 string Term": "Bomb",
                        "0 int TermType": 0,
                        "0 vector Languages":  {
                            "0 Array Array": [
                                {"1 string data": "Bomb"},
                                {"1 string data": ""},
                                {"1 string data": "Bombe"},
                                {"1 string data": "Bomba"},
                                {"1 string data": "Bombe"},
                                {"1 string data": "Bom"},
                                {"1 string data": "Bomba"},
                                {"1 string data": "Bomba"},
                                {"1 string data": "Бомба"},
                                {"1 string data": "炸弹"},
                                {"1 string data": "炸彈"},
                                {"1 string data": "ボム"},
                                {"1 string data": "폭탄"}, <- 아래에서 6번째줄인 이곳을 수정하면 됩니다.
                                {"1 string data": "Bomb"},
                                {"1 string data": "Bomba"},
                                {"1 string data": "Bomba"},
                                {"1 string data": "Bomba"},
                                {"1 string data": "Бомба"}
                            ]
                        },
```
4. 이슈를 통해 업로드 또는 이슈를 통해 오역을 지적해준다.
