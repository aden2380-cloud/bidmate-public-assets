# BidMate 공사입찰 릴스 1–3편 (V3 안정화) — 업로드 인계

**상태:** 영상 원본 3개는 검증되었지만 **이 GitHub 저장소에는 아직 MP4 바이너리 업로드되지 않음**. 파일 URL을 발행 완료라고 안내하거나 Instagram에 게시하지 않는다.

작업 브랜치: `media/reels-v3-ep01-03-20261118`. 사용자 요청: 본 공개 저장소에 V3 영상 1~3편을 저장하고 **1편만 `@bid_mate`에 게시**, 나머지 2·3편은 미게시 보관.

## 저장할 영상 원본

| 편 | 목적 경로 | 크기 | SHA-256 |
|---|---|---:|---|
| EP01 공사입찰 찾기 | `reels/2026-11-18-v3/BidMate_EP01_Reel_V3_STABLE_1080x1920.mp4` | 2,982,471 B | `b3db84ad64b7f4bf7f672a70de9840c20bbc7a067c5739c4b1423590eb9eae46` |
| EP02 참가자격 확인 | `reels/2026-11-18-v3/BidMate_EP02_Reel_V3_STABLE_1080x1920.mp4` | 2,874,848 B | `e7456e6dbd95e9afd08eec7c72b5542bc9d00cb2312f36ccc501edd4a1dec571` |
| EP03 정정공고 확인 | `reels/2026-11-18-v3/BidMate_EP03_Reel_V3_STABLE_1080x1920.mp4` | 3,197,543 B | `12eed4f481772ff57b33fbd6bf4e829a2b23ea25b099d081216463dace625c94` |

모두 MP4(H.264/AAC), 1080×1920, 24.0초. **V2가 아니라 사용자가 떨림 문제를 지적한 뒤 제작한 V3 안정화본**을 사용한다.

## 게시 기준

1. 세 원본을 실제 GitHub 저장소에 올리고 GitHub 원격 파일 크기 및 가능하면 SHA-256을 확인.
2. GitHub `raw.githubusercontent.com` 공개 MP4 파일 URL의 다운로드 접근 및 `Content-Type` 확인. GitHub 원시 파일 URL이 Instagram 서버에 호환되지 않으면 승인된 별도 정적 호스팅을 이용해야 하며, 미검증 URL을 사용하지 않는다.
3. `@bid_mate` Windsor.ai Instagram 연결 ID `17841412586284614` 확인 후 `create_video_post`로 EP01 **1회만** 게시. Instagram 게시 성공/미확인 결과에서 중복 발행 금지.
4. EP02·EP03은 사용자 추가 승인 전 게시하지 않음.
5. 본문은 [EP01 캡션](caption_ep01.txt)과 비드메이트 공식 설명을 사용하며 홈페이지 URL은 클릭 가능한 광고 버튼이 아니라 프로필 링크로 유도한다.

이 문서는 **원본 파일의 GitHub 업로드 완료 증빙이 아니다**. API 연결은 text/Base64 문자열만 받아 현재 로컬 MP4 파일 바이트를 직접 송신하지 못하므로 바이너리 작업이 남아 있다.
