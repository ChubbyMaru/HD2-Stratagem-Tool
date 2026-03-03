<img width="1452" height="825" alt="1" src="https://github.com/user-attachments/assets/f529fa1b-ffbf-454f-b73d-fa99d7e3af25" />
<img width="850" height="478" alt="2" src="https://github.com/user-attachments/assets/554314f3-799b-404c-aa9d-5b4e1b6e6bae" />

### 주요 기능
* **스트라타젬 설정 자동 인식 :** 프로그램 실행 시 인게임 스트라타젬 설정을 자동으로 로드합니다.
* **사후 데이터 관리 :** 업데이트가 중단되어도 `stratagems.json` 수정을 통해 새로운 스트라타젬을 추가할 수 있습니다.
* **단축키 지원 :** 할당된 단축키의 스트라타젬을 바로 사용할 수 있습니다.
* **오버레이 지원 :** 마우스 중심 오버레이(라디얼 메뉴)로 직관적인 선택이 가능합니다.
* **사용자 친화적 UI :** 인게임과 동일한 배열 및 마우스 오버 시 이름 표시 기능을 지원합니다.

---

### 사용 방법
* **오버레이 단축키 :** `MButton` (마우스 휠 클릭)
* **증원 단축키 :** `XButton1` (마우스 뒤로가기)
* **슬롯 단축키 :** `F6` ~ `F9`

---

### 설정 변경 (`settings.ini`)
단축키를 변경하고 싶다면 파일을 열어 수정하면 됩니다.

```ini
[Hotkeys]
overlayKey=MButton
reinforceKey=XButton1
slot0=F6
slot1=F7
slot2=F8
slot3=F9
```
단축키를 해제하고 싶다면 값을 비워두면 됩니다.
```ini
overlayKey=
```
---

### 단축키 목록

| 구분 | 키 명칭 (Value) | 설명 |
| --- | --- | --- |
| **MButton** | `MButton` | 마우스 휠 클릭 |
| **XButton1** | `XButton1` | 마우스 뒤로가기 |
| **XButton2** | `XButton2` | 마우스 앞으로가기 |
| **A – Z** | `A` – `Z` | 알파벳 |
| **0 – 9** | `D0` – `D9` | 상단 숫자 키 |
| **Numpad 0 – 9** | `NumPad0` – `NumPad9` | 넘버패드 숫자 |
| **~** | `Oem3` | 틸드 / 백틱 |
| **-** | `OemMinus` | 마이너스 |
| **=** | `Oemplus` | 등호 |
| **[** | `Oem4` | 왼쪽 대괄호 |
| **]** | `Oem6` | 오른쪽 대괄호 |
| **\** | `Oem5` | 역슬래시 |
| **;** | `Oem1` | 세미콜론 |
| **'** | `Oem7` | 작은따옴표 |
| **,** | `OemComma` | 쉼표 |
| **.** | `OemPeriod` | 점 |
| **/** | `Oem2` | 슬래시 |
| **Space** | `Space` | 스페이스바 |
| **Enter** | `Return` | 엔터 |
| **Backspace** | `Back` | 백스페이스 |
| **Tab** | `Tab` | 탭 |
| **Escape** | `Escape` | ESC |
| **CapsLock** | `CapsLock` | 캡스락 |
| **Left Shift** | `LShiftKey` | 왼쪽 시프트 |
| **Right Shift** | `RShiftKey` | 오른쪽 시프트 |
| **Left Ctrl** | `LControlKey` | 왼쪽 컨트롤 |
| **Right Ctrl** | `RControlKey` | 오른쪽 컨트롤 |
| **Left Alt** | `LMenu` | 왼쪽 알트 |
| **Right Alt** | `RMenu` | 오른쪽 알트 |
| **F1 – F24** | `F1` – `F24` | 기능 키 |
| **Insert** | `Insert` | 인서트 |
| **Delete** | `Delete` | 딜리트 |
| **Home** | `Home` | 홈 |
| **End** | `End` | 엔드 |
| **PageUp** | `PageUp` | 페이지 업 |
| **PageDown** | `PageDown` | 페이지 다운 |
| **↑** | `Up` | 화살표 상 |
| **↓** | `Down` | 화살표 하 |
| **←** | `Left` | 화살표 좌 |
| **→** | `Right` | 화살표 우 |
| **NumLock** | `NumLock` | 넘버패드 잠금 |
| **Divide** | `Divide` | 넘버패드 / |
| **Multiply** | `Multiply` | 넘버패드 * |
| **Subtract** | `Subtract` | 넘버패드 - |
| **Add** | `Add` | 넘버패드 + |
| **Decimal** | `Decimal` | 넘버패드 . |
