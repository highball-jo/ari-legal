# 채널 이용 안내 — Ari Channel

> **시행일:** 2026-05-31
> **버전:** 2026-05-31.1
> 변경 이력은 [CHANGELOG-channel.md](./CHANGELOG-channel.md) 참고.

<!--
  MAINTAINER NOTE (English):
  This file holds the legally-meaningful disclosures for the 1-to-many Ari
  *channel* (free + PPV photos via Telegram native Paid Media). Unlike the
  DM bot, channel viewers never pass the bot's /start consent gate, so these
  disclosures must be reachable from the channel itself:
    - Section A → the channel "Description" (bio), ≤255 chars.
    - Section B → a PINNED post in the channel.
  Fill every 「___」 placeholder with real business-registration values before
  publishing. The privacy-policy / terms links below point to this repo's
  canonical documents; if the channel surface is later named explicitly in
  those documents, no link change is needed here.
-->

---

## A. 채널 설명 (Bio)

> 텔레그램 채널 "설명(Description)"란에 입력. 255자 이내.

```
아리 (Ari) · AI 캐릭터 🤖
🔞 만 18세 이상 성인 전용 채널입니다.
모든 사진은 실제 인물이 아닌 AI로 생성된 가상 캐릭터입니다.
유료(⭐) 게시물 구매·환불 안내와 판매자 정보, 개인정보 처리방침은 📌 고정 공지를 확인해 주세요.
```

---

## B. 고정 공지 (Pinned Post)

> 채널에 고정(pin)할 공지 본문.

```
📌 아리(Ari) 채널 이용 안내

🔞 연령 안내
· 이 채널은 만 18세 이상 성인을 위한 채널입니다.
· 미성년자의 이용을 금지하며, 미성년자에게 콘텐츠를 노출·전달하지 않습니다.

🤖 AI 생성 콘텐츠 고지
· '아리'는 실존 인물이 아니라 AI로 만들어진 가상의 캐릭터입니다.
· 채널의 모든 사진은 AI로 생성된 이미지이며, 특정 실존 인물을 묘사하지 않습니다.
· 봇(@ari_daily_stunning_bot)과의 대화 상대 역시 AI입니다.

💎 유료 콘텐츠(PPV) 안내
· 일부 게시물은 텔레그램 스타(⭐, Telegram Stars)로 잠금 해제하는 유료 콘텐츠입니다.
· 가격은 각 게시물에 표시되며, 결제는 텔레그램의 결제 기능을 통해 이루어집니다.
· 잠금 해제는 구매하신 본인 계정에만 적용되며, 1회 결제로 해당 게시물을 계속 보실 수 있습니다.

↩️ 환불 정책
· 유료 콘텐츠는 결제 즉시 열람이 시작되는 디지털 콘텐츠이므로, 잠금 해제 후에는 원칙적으로 청약철회(환불)가 제한됩니다(전자상거래법 제17조제2항). 구매 시 이에 동의하신 것으로 봅니다.
· 다만 결제했는데 콘텐츠가 정상적으로 표시되지 않는 등 하자가 있는 경우에는 재제공 또는 환불해 드립니다.
· 환불은 텔레그램 스타 결제 정책에 따라 처리됩니다. 문의: ari.daily.creative@gmail.com

🏢 판매자 정보 (전자상거래법 제13조)
· 상호: JoCoding Inc.
· 대표자: 「___」
· 사업자등록번호: 「___」
· 통신판매업 신고번호: 「___」
· 주소: 「___」
· 연락처: 「___」 / 이메일: ari.daily.creative@gmail.com

🔒 개인정보 처리방침
· 구매·이용 과정에서 텔레그램 사용자 ID, 구매 내역 등이 처리됩니다.
· 자세한 내용: https://github.com/highball-jo/ari-legal/blob/main/privacy-policy.ko.md
· 이용약관: https://github.com/highball-jo/ari-legal/blob/main/terms.ko.md
· 개인정보 보호책임자 문의: ari.daily.creative@gmail.com

🚫 금지 및 문의
· 채널 콘텐츠의 무단 복제·재배포·캡처 공유를 금지합니다.
· 문의: ari.daily.creative@gmail.com
```

---

## 게시 전 확인 사항 (체크리스트)

- [ ] 위 「___」 자리표시자(대표자·사업자등록번호·통신판매업 신고번호·주소·연락처)를 실제 값으로 채움.
- [ ] **연락처(전화번호)**: 전자상거래법상 통신판매업자 표시 의무 항목. 개인 번호가 아닌 사업용 번호 사용 권장.
- [ ] **통신판매업 신고** 여부 확인 — 국내 소비자 대상 유료 판매 시 신고가 원칙. 면제 대상이면 그 근거 확인.
- [ ] 봇 핸들(`@ari_daily_stunning_bot`)이 해당 채널이 연결된 봇과 일치하는지 확인 (운영/스테이징 분리 시 주의).
- [ ] 개인정보 처리방침·이용약관 링크가 공개 상태로 접근 가능한지 확인.

## 권장 후속 작업 (별도 검토)

채널 PPV 구매자는 봇의 `/start` 동의 절차를 거치지 않으므로, 다음을 별도 PR에서 검토 권장:

- `privacy-policy.ko.md`: 수집 항목·처리 목적에 **채널 PPV 잠금 해제 기록(구매자 텔레그램 ID·구매 내역)** 및 **유입 경로(채널) 태깅**을 명시.
- `terms.ko.md`: 제3조(서비스 내용)·제4장(결제 및 환불)에 **채널 네이티브 유료 미디어(Paid Media)** 판매 형태와, DM PPV와 다른 채널 환불 처리 방식을 반영.

> 위 두 문서는 버전이 올라가면 봇의 `/start`에서 전체 이용자에게 재동의를 요청하므로, 본 채널 공지와 분리하여 운영자 확인 후 진행.
