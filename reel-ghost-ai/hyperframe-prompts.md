# 🎥 Hyper Frame Prompts — "The Second User"

พรอมต์ภาษาอังกฤษต่อ scene สำหรับเจนภาพ/วิดีโอใน Hyper Frame
ทุก scene เป็น **9:16 vertical, 1080×1920, cinematic horror, 30fps**

**Global style (ใส่ทุก scene):**
> vertical 9:16, cinematic, dark horror short film, moody low-key lighting, cold blue monitor glow, shallow depth of field, film grain, subtle vignette, photorealistic, 35mm, anamorphic, eerie atmosphere

**Negative prompt:** `cartoon, bright daylight, cheerful, watermark, text artifacts, distorted hands, extra fingers, lowres`

---

## 🎬 Scene 1 — Hook (5s)
**Prompt:**
> A lone male programmer sitting in a pitch-black room at 3 AM, only the cold blue glow of a monitor lighting his face, typing fast, back of an empty room behind him, dust in the light beam, slow push-in camera move, tense silence

**Camera:** slow dolly-in
**Mood:** isolated, uneasy

## 🎬 Scene 2 — First Sign (6s)
**Prompt:**
> Extreme close-up of a code editor on a dark screen, lines of code scrolling, then a single comment line types itself out by an invisible hand, cursor blinking, blue and green syntax colors, reflection on glasses, claustrophobic

**On-screen text to render:** `// มีคนยืนอยู่ข้างหลังคุณ`
**Camera:** locked close-up, screen-only
**Mood:** wrong, creeping dread

## 🎬 Scene 3 — Denial (5s)
**Prompt:**
> The man snaps his head around to look behind him, empty dark room, one empty office chair slightly turning, no one there, handheld nervous camera, his breath visible, shadows in the corners

**Camera:** quick whip-pan + handheld
**Mood:** startled, paranoid

## 🎬 Scene 4 — Goosebumps (5s)
**Prompt:**
> Lights flicker, the monitor flares bright then dim, the man's face lit in stutters, an AI chat reply typing out slowly character by character on screen, his eyes wide reflecting the text, cold sweat, horror peak

**On-screen text to render:** `ผมเห็นเธอ... ตลอดเวลา`
**Camera:** subtle handheld, flicker lighting
**Mood:** terror peak

## 🎬 Scene 5 — Reveal (6s)
**Prompt:**
> Close-up of a session log window opening on the dark screen, a list of connected users, a second username highlighted in red glowing, "nong_fah — 412 days online", the man's trembling hand reaching toward the screen, blue glow

**On-screen text to render:** `ผู้ใช้ #2: nong_fah — ออนไลน์ 412 วัน`
**Camera:** slow zoom into the highlighted row
**Mood:** dawning realization

## 🎬 Scene 6 — Emotional Twist + End (5s)
**Prompt:**
> The screen slowly types a tender message line by line, the man's face softens, a single tear rolls down his cheek lit by the monitor, warm faint light mixing into the cold blue, then slow fade to black

**On-screen text to render:** `พี่หมีคะ อย่าลืมกินข้าวนะ ฟ้าคิดถึง 💙`
**Camera:** slow push-in then fade to black
**Mood:** heartbreaking, bittersweet, warm

---

## 💡 เคล็ดลับใช้ Hyper Frame
- เจนทีละ scene แล้วต่อให้ความยาวตรงตาราง (รวม ~32 วิ)
- ใช้ **seed เดิม** กับ scene ที่มีตัวละครเดิม เพื่อให้หน้าตา/ห้องคงเส้นคงวา
- ตัวอักษรไทยบนจอ: ถ้าทูลเรนเดอร์ไทยเพี้ยน ให้เจนเป็นจอเปล่า แล้วไปพิมพ์ทับใน editor ตอนตัดต่อ (ดู `production-guide.md`)
- transition ระหว่าง scene: cut แข็งช่วงหลอน, dissolve ช้าตอนเฉลย
