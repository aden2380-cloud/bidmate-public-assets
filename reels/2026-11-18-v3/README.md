# BidMate 공식 릴스 시리즈 1–3편 — V3 안정화 영상

- 제작일: 2026-11-18 (Asia/Seoul)
- 공식 캐릭터: **Aden.J (아덴주니어)**
- **원본 MP4 세 편 모두 GitHub 원격 저장 완료 및 검증 완료**
- 화면: 1080 × 1920 (세로 9:16), 편당 24초, H.264 + AAC
- 이 3편은 화면 떨림을 제거한 **V3 고정화면 안정화 최종본**이다. V1/V2로 교체하지 않는다.
- **게시 상태 (2026-11-18 확인):** EP01은 Instagram @bid_mate에 릴스로 게시 완료. EP02/03은 미게시.
- **EP01 게시 근거:** Windsor.ai `create_video_post` 성공 응답의 미디어 ID `18014797709768538`; 연결된 Instagram 프로필에서 실제 [EP01 릴스](https://www.instagram.com/bid_mate/reel/Df3ACJkhDW2/) 링크와 본문 확인. Windsor.ai `get_data` 수집 목록에는 당시 아직 반영되지 않았으므로 게시 액션 응답 및 실제 프로필 조회를 근거로 한다.

## 공개 MP4 파일

| 편 | 파일 | 크기(Byte) | Git blob SHA-1 | SHA-256 |
|---|---|---:|---|---|
| 1편 우리 회사에 맞는 공사입찰 찾기 | [EP01](BidMate_EP01_Reel_V3_STABLE_1080x1920.mp4) | 2,982,471 | `b490f987b16f039878b9b8954c0b349628332a26` | `b3db84ad64b7f4bf7f672a70de9840c20bbc7a067c5739c4b1423590eb9eae46` |
| 2편 공사입찰 참가자격 확인 | [EP02](BidMate_EP02_Reel_V3_STABLE_1080x1920.mp4) | 2,874,848 | `e71be6485181172c95bd425c4fb7edd6f76c3a3d` | `e7456e6dbd95e9afd08eec7c72b5542bc9d00cb2312f36ccc501edd4a1dec571` |
| 3편 정정공고 확인 | [EP03](BidMate_EP03_Reel_V3_STABLE_1080x1920.mp4) | 3,197,543 | `2a2d6a473180d55556dbf4dea1b44524aca079eb` | `12eed4f481772ff57b33fbd6bf4e829a2b23ea25b099d081216463dace625c94` |

### 원본 무결성 검증

1·2편의 GitHub Git Blob SHA는 업로드 전 원본 `git hash-object` 값과 일치한다. 3편은 GitHub Actions 실행 `44181269733`이 원본의 조각을 합치고 SHA-256 체크를 **성공**시킨 뒤 원본 전체를 단일 MP4로 커밋했다. 이후 GitHub 원격에서 세 파일의 이름·용량·Git blob SHA 일치 확인.

### 인스타그램 게시 규칙

- 계정: [@bid_mate](https://www.instagram.com/bid_mate/)
- 게시물: EP01을 **릴스**로 게시, 기본 피드에도 공유.
- 본문: [EP01 캡션](caption_ep01.txt)
- 상세 서비스: [비드메이트 홈페이지](https://bidmate.co.kr/) 또는 프로필 홈페이지 링크. 일반 릴스의 '더보기'는 외부 버튼이 아니다.
- EP01 실제 게시 확인: https://www.instagram.com/bid_mate/reel/Df3ACJkhDW2/ (게시 미디어 ID: `18014797709768538`). 자동 게시 연결: Windsor.ai Instagram `create_video_post`.
- API 응답이 모호하거나 지연된 경우 중복 게시하지 않는다.
- EP02·EP03은 새 사용자 승인 없이 게시하지 않는다.

### 기록/이력

- GitHub 자산 공개 저장소 `aden2380-cloud/bidmate-public-assets`.
- EP03 바이너리 분할은 전송 경로의 크기 제한으로 일시 사용했으며, 조립 후 조각은 삭제했다.
- 파일 업로드 및 GitHub 원본 검증 완료. EP01은 Instagram 게시 완료·프로필 링크 확인, EP02/EP03은 미게시.

## 릴스 음악 운영 (2026-11-18 후속 결정)

- 이 V3 원본은 **H.264/AAC 음악 포함 영상**이다. 이미 Instagram에 올라간 릴스에 대해 일반적인 음악 교체 기능을 보장하지 않는다. 사용자가 EP01 업로드 뒤 음악 변경이 불가능한 상황을 보고했다.
- Windsor.ai `create_video_post`는 공개 MP4 URL·캡션·피드 공유·커버 지정은 제공하지만 **Instagram 음악 라이브러리에서 곡을 고르는 옵션은 제공하지 않는다**.
- 향후 시리즈 4~12편은 **음악 포함본(외부 API 게시용)** 과 **오디오 트랙 없는 무음본(앱 편집용)** 을 별도 버전으로 제작한다. IG 음악 선택이 중요하면 **게시 전에** 모바일 앱에서 음악을 추가·확인한다.
- 기존 EP01을 음악 교체 목적으로 무단 삭제·재게시하거나 같은 영상을 중복 게시하지 않는다. EP02·EP03 게시에도 별도 사용자 승인 필요.
