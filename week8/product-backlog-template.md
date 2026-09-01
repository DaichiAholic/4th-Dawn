# Product Backlog

**Version:** 1.0 | **Last Updated:** 2026-09-01

> รวม User Story ทั้งหมดของโปรเจกต์ — ยังไม่ได้แปลว่าต้องทำใน Sprint นี้ทั้งหมด
> โปรเจกต์นี้แบ่งงานตลอดเทอมเป็น **4 Sprint** (Sprint 1-4) — Sprint ไหนหยิบ Story ไปทำ ให้ใส่เลข Sprint นั้น (1-4) ลงคอลัมน์ `Sprint`

## Must Have (MVP)

| # | User Story                                                                                | Acceptance Criteria                                                  | Estimate (SP) | Sprint |
| - | ----------------------------------------------------------------------------------------- | -------------------------------------------------------------------- | ------------- | ------ |
| 1 | As a player, I want to explore, so that I can get supplies                                | สามารถสำรวจ area ต่างๆได้                         | 5             | 1      |
| 2 | As a player, I want to make a choice, so that I can choose my own path                    | ผู้เล่นเลือก choice เองได้                         | 3             | 1      |
| 3 | As a designer, I want have wide variation of enemies, so that player would find new enemy | ศัตรูมีหลายประเภทและหลายความสามารถ | 4             | 1      |
| 4 |                                                                                           |                                                                      |               |        |

## Should Have

| # | User Story                                                                                 | Acceptance Criteria                                                                           | Estimate (SP) | Sprint |
| - | ------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | ------------- | ------ |
| 1 | As a player, I want to see my remaining health, so that I know how close I am to game over | จำนวนชีวิตแสดงบนจอตลอดเวลา ลดลงทันทีที่โดนโจมตี | 2             | —     |
| 2 | [As a ..., I want ..., so that ...]                                                        | [เงื่อนไขที่นับว่า Story นี้ "เสร็จจริง"]                        | [SP]          | —     |

## Nice to Have

| # | User Story                                                                                                      | Acceptance Criteria                                                                                                                                      | Estimate (SP) | Sprint |
| - | --------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------ |
| 1 | As a designer, I want enemy spawn rate stored in a data file, so that I can tune difficulty without recompiling | ปรับค่า spawn rate ในไฟล์ data แล้วรันเกมใหม่ ค่าที่เปลี่ยนมีผลทันทีโดยไม่ต้อง build ใหม่ | 3             | —     |
| 2 | [As a ..., I want ..., so that ...]                                                                             | [เงื่อนไขที่นับว่า Story นี้ "เสร็จจริง"]                                                                                   | [SP]          | —     |

## MoSCoW Legend

- **Must Have** — จำเป็นต่อ core gameplay loop เกมเล่นไม่ได้ถ้าขาด (MVP)
- **Should Have** — เพิ่มคุณภาพเกม แต่เกมเล่นได้โดยไม่มีก็ได้
- **Nice to Have** — ทำถ้ามีเวลาเหลือ

## Links

- [[docs/gdd/00-concept|GDD Concept]]
- [[docs/agile/02-sprint-backlog|Sprint Backlog]]
