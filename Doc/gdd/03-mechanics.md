---
type: gdd-mechanics
version: 0.1
date: [วันที่]
---
# Mechanic Design — [Exploration]

## State Diagram

```mermaid
stateDiagram-v2
    [*] --> Enter_room
    Enter_room --> supply_room : random_room_type
    Enter_room --> Encounter_room : random_room_type
    Enter_room --> Special_room : random_room_type
    supply_room --> resolve_outcome
    Encounter_room --> resolve_outcome
    Special_room --> resolve_outcome
    resolve_outcome --> Enter_room
  
```

## Rules

| State       | เข้าเงื่อนไข          | ออกเงื่อนไข            | Note               |
| ----------- | --------------------------------- | --------------------------------- | ------------------ |
| Enter room  | เข้าไปในห้องใหม่  | random ห้องแล้ว           |                    |
| Supply room | กดปุ่มทิศทาง          | ปล่อยปุ่ม / กระโดด | Speed = [ค่า]   |
| Jump        | กด Space ขณะอยู่พื้น | ถึงจุดสูงสุด          | Gravity = [ค่า] |
