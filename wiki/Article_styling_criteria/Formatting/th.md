---
outdated_translation: true
outdated_since: 342b4e51378689a89b13feb101c2a657f5f1ac3c
---

# การจัดรูปแบบ

*สำหรับมาตรฐานการเขียน, ดู: [เกณฑ์รูปแบบบทความ/การเขียน](../Writing)*

*ข้อสังเกต: บทความนี้ใช้ [RFC 2119](https://tools.ietf.org/html/rfc2119 "IETF Tools") เพื่ออธิบายระดับความต้องการ*

## ภาษา

นี่คือ locale ที่สามารถการแปลบทความบนวิกิได้:

| ชื่อไฟล์ | ชื่อภาษา | ภาษาพื่นเมือง |
| :-- | :-- | :-- |
| `en.md` | อังกฤษ | English |
| `ar.md` | อารบิก | اَلْعَرَبِيَّةُ |
| `be.md` | เบลารุส | Беларуская мова |
| `bg.md` | บัลแกเรีย | Български |
| `cs.md` | เช็ก | Česky |
| `da.md` | เดนมาร์ก | Dansk |
| `de.md` | เยอรมัน | Deutsch |
| `el.md` | กรีก | Ελληνικά |
| `es.md` | สเปน | Español |
| `fi.md` | ฟินแลนด์ | Suomi |
| `fr.md` | ฝรั่งเศส | Français |
| `hu.md` | ฮังการี | Magyar |
| `id.md` | อินโดนีเซีย | Bahasa Indonesia |
| `it.md` | อิตาลี | Italiano |
| `ja.md` | ญี่ปุ่น | 日本語 |
| `ko.md` | เกาหลี | 한국어 |
| `nl.md` | ดัตช์ | Nederlands |
| `no.md` | นอร์เวย์ | Norsk |
| `pl.md` | โปแลนด์ | Polski |
| `pt.md` | โปรตุเกส | Português |
| `pt-br.md` | โปรตุเกส บราซิล | Português (Brasil) |
| `ro.md` | โรมาเนีย | Română |
| `ru.md` | รัสเซีย | Русский |
| `sk.md` | สโลวัก | Slovenčina |
| `sv.md` | สวีเดน | Svenska |
| `th.md` | ไทย | ไทย |
| `tr.md` | ตุรกี | Türkçe |
| `uk.md` | ยูเครน | Українська мова |
| `vi.md` | เวียดนาม | Tiếng Việt |
| `zh.md` | จีน (ตัวย่อ) | 简体中文 |
| `zh-tw.md` | จีนดั้งเดิม (ไต้หวัน) | 繁體中文（台灣） |

*หมายเหตุ: เว็บไซต์จะให้ผู้อ่านได้บทความที่มีเป็นภาษาตามที่ผู้อ่านได้ตั้งภาษา ถ้าไม่มีภาษานั้น เว็บไซต์จะให้ภาษาอังกฤษแทน*

### ความเท่าเทียมกันของเนื้อหา

การแปลขึ้นอยู่กับความเท่าเทียมกันของเนื้อหากับบทความภาษาอังกฤษอย่างเข้มงวด ในแง่ที่ว่าพวกเขาต้องมีข้อความเดียวกัน โดยไม่คำนึงถึงไวยากรณ์และการเขียน การเปลี่ยนแปลงความหมายของการแปลจะต้องมาพร้อมกับการเปลี่ยนแปลงที่เทียบเท่ากับบทความภาษาอังกฤษ

มีบางกรณีที่เนื้อหาสามารถแตกต่างกันได้:

- บทความที่เขียนเป็นภาษาอื่นที่ไม่ใช่ภาษาอังกฤษ (ในกรณีนี้ ภาษาอังกฤษควรทำหน้าที่เป็นคำแปล)
- คำอธิบายของคำภาษาอังกฤษที่เป็นคำทั่วไปในชุมชน osu!
- ลิงค์เว็บไซต์อื่น
- แท็ก
- คำอธิบายเฉพาะชุมชนเกมใด เกมหนึ่ง

## เรื่องหน้า

ต้องวางวัตถุด้านหน้าไว้ที่ด้านบนสุดของไฟล์ เขียนใน [YAML](https://en.wikipedia.org/wiki/YAML#Example "บทความ YAML บนวิกิพีเดีย") และอธิบายข้อมูลเพิ่มเติมเกี่ยวกับบทความ โดยต้องล้อมรอบด้วยขีดกลางสามตัว (`---`) ในบรรทัดด้านบนและด้านล่าง และบรรทัดว่างจะต้องอยู่ตามหลังก่อนส่วนหัวของชื่อ

### บทความที่ต้องการความช่วยเหลือ

*หมายเหตุ: หลีกเลี่ยงการแปลบทความภาษาอังกฤษที่มีแท็กนี้ นอกจากนี้ ควรเพิ่มแท็กนี้เมื่อการแปลจำเป็นต้องถูกแก้เยอะ*

แท็ก `needs_cleanup` อาจถูกเพิ่มลงในบทความที่ต้องการความช่วยเหลือในการเขียนใหม่หรือการจัดรูปแบบ นอกจากนี้ยังเป็นที่ยอมรับในการเปิดปัญหาบน GitHub เพื่อจุดประสงค์นี้ แท็กนี้จะต้องเขียนตามที่แสดงด้านล่าง:

``` yaml
need_cleanup: true
```

เมื่อเพิ่มแท็กนี้ในบทความ ควรเพิ่ม [ความคิดเห็น](#ความคิดเห็น) เพื่ออธิบายสิ่งที่ต้องทำเพื่อนำแท็กออก

### บทความที่เก่ามาก ๆ

*หมายเหตุ: หลีกเลี่ยงการแปลบทความภาษาอังกฤษที่มีแท็กนี้ หากบทความภาษาอังกฤษมีแท็กนี้ คำแปลต้องมีแท็กนี้ด้วย*

บทความที่แปลแล้วล้าสมัยต้องใช้แท็ก `outdated` เมื่อมีการอัปเดตตัวแปลภาษาอังกฤษ บทความภาษาอังกฤษอาจล้าสมัยเมื่อเนื้อหาที่มีอยู่ทำให้เข้าใจผิดหรือไม่เกี่ยวข้องอีกต่อไป แท็กนี้จะต้องเขียนตามที่แสดงด้านล่าง:

```yaml
outdated: true
```

เมื่อเพิ่มแท็กนี้ในบทความ ควรเพิ่ม [ความคิดเห็น](#ความคิดเห็น) เพื่ออธิบายสิ่งที่จำเป็นต้องอัปเดตเพื่อนำแท็กออก

### บทความติดแท็ก

แท็กช่วยให้บทความค้นหาของเครื่องมือค้นหาของเว็บไซต์ดีขึ้น แท็กควรเขียนในภาษาเดียวกับบทความและรวมรายการแท็กต้นฉบับด้วย แท็กควรใช้อักษรตัวพิมพ์เล็กหากมี

ตัวอย่างเช่น บทความชื่อ "การสนทนาของ Beatmap" อาจมีแท็กต่อไปนี้:

```yaml
tags:
  - การสนทนาบีทแมพ
  - การวิจารณ์บีทแมพ เวอร์ชั้น 2
  - MV2
```

### การแปลโดยไม่มีบทวิจารณ์

*หมายเหตุ: ผู้ดูแลวิกิจะกำหนดและใช้เครื่องหมายนี้ก่อนที่จะ merge*

บางครั้ง การแปลจะถูกเพิ่มลงในวิกิโดยไม่ได้รับการตรวจสอบจากเจ้าของภาษาคนอื่น ๆ ในกรณีนี้ เครื่องหมาย `no_native_review` จะถูกเพิ่มเพื่อให้นักแปลในอนาคตทราบว่าอาจต้องตรวจสอบอีกครั้ง แท็กนี้จะต้องเขียนตามที่แสดงด้านล่าง:

```yaml
no_native_review: true
```

## การตั้งชื่อบทความ

*ดูเพิ่มเติมที่: [ชื่อโฟลเดอร์](#ชื่อโฟลเดอร์) และ [ชื่อเรื่อง](#ชื่อเรื่อง)*

ชื่อบทความควรเป็นเอกพจน์และใช้ตัวพิมพ์ประโยค ดู[บทความอนุสัญญาการตั้งชื่อวิกิพีเดีย](https://en.wikipedia.org/wiki/Wikipedia:Naming_conventions_(plurals) "วิกิพีเดีย") สำหรับรายละเอียดเพิ่มเติม

ชื่อบทความควรตรงกับชื่อโฟลเดอร์ที่มีอยู่ (ช่องว่างอาจแทนที่เครื่องหมายขีดล่าง (`_`) ตามความเหมาะสม) หากชื่อโฟลเดอร์เปลี่ยน ควรเปลี่ยนชื่อบทความให้ตรงกันและในทางกลับกัน

---

บทความการแข่งขันและการแข่งขันเป็นข้อยกเว้น ชื่อโฟลเดอร์ต้องใช้ตัวย่อ ตัวย่อ หรือชื่อย่อ ชื่อบทความต้องเป็นชื่อเต็มของการแข่งขันหรือการแข่งขัน

## โครงสร้างโฟลเดอร์และไฟล์

### ชื่อโฟลเดอร์

*ดูสิ่งนี้ด้วย: [การตั้งชื่อบทความ](#การตั้งชื่อบทความ)*

ชื่อโฟลเดอร์ต้องเป็นภาษาอังกฤษและใช้ตัวพิมพ์ประโยค

ชื่อโฟลเดอร์ต้องใช้อักขระเหล่านี้เท่านั้น:

- ตัวพิมพ์ใหญ่และตัวพิมพ์เล็ก
- ตัวเลข
- ขีดล่าง (`_`)
- ยัติภังค์ (`-`)
- เครื่องหมายอัศเจรีย์ (`!`)

### ชื่อไฟล์บทความ

ชื่อไฟล์ของบทความอยู่ในคอลัมน์ "ชื่อไฟล์" ของ [ส่วนภาษา](#ภาษา) ตำแหน่งของบทความที่แปลต้องอยู่ในโฟลเดอร์เดียวกับบทความภาษาอังกฤษ

### บทความดัชนี

ต้องสร้างบทความดัชนีหากโฟลเดอร์นั้นมีไว้สำหรับเก็บบทความอื่นเท่านั้น บทความดัชนีต้องมีรายชื่อบทความที่อยู่ภายในโฟลเดอร์ของตัวเอง พวกเขาอาจมีข้อมูลอื่น ๆ เช่นย่อหน้านำหรือคำอธิบายของบทความที่เชื่อมโยง

### บทความแก้ความกำกวม

บทความ [แก้ความกำกวม](/wiki/Disambiguation) ต้องอยู่ในโฟลเดอร์ `/wiki/Disambiguation` ต้องอัปเดตหน้าหลักเพื่อรวมบทความแก้ความกำกวม อ้างถึง [Disambiguation/Mod](/wiki/Disambiguation/Mod) เพื่อเป็นตัวอย่าง

ต้องอัปเดตการเปลี่ยนเส้นทางเพื่อให้คำหลักที่คลุมเครือเปลี่ยนเส้นทางไปยังบทความแก้ความกำกวม

บทความที่เชื่อมโยงจากบทความแก้ความกำกวมต้องมีหมวก [สำหรับการใช้งานอื่น](#for-other-uses)

## HTML

ห้ามใช้ HTML ยกเว้น [ความคิดเห็น](#ความคิดเห็น) โครงสร้างของบทความจะต้องทำใหม่หากใช้ HTML

### ความคิดเห็น

ควรใช้ความคิดเห็น HTML เพื่อทำเครื่องหมายสิ่งที่ต้องทำ แต่อาจใช้เพื่อใส่คำอธิบายประกอบข้อความ ควรอยู่ในบรรทัดของตนเอง แต่สามารถวางแบบอินไลน์ในย่อหน้าได้ หากวางไว้ในบรรทัด จุดเริ่มต้นของความคิดเห็นจะต้องไม่มีช่องว่าง

ตัวอย่างที่ไม่ดี:

```markdown
ความคิดเห็น HTML <!-- TODO อธิบายความคิดเห็น HTML --> ควรใช้เพื่อทำเครื่องหมายสิ่งที่ต้องทำหรือใส่คำอธิบายประกอบ
```

ตัวอย่างที่ดี:

```markdown
ความคิดเห็น HTML<!-- TODO อธิบายความคิดเห็น HTML --> ควรใช้เพื่อทำเครื่องหมายสิ่งที่ต้องทำหรือใส่คำอธิบายประกอบ
```

## การแก้ไข

### ลำดับสิ้นสุดบรรทัด

*ข้อควรระวัง: การอัปโหลดไฟล์ Markdown โดยใช้ `CRLF` (การขึ้นบรรทัดใหม่และการป้อนบรรทัด) ผ่าน GitHub จะส่งผลให้ไฟล์เหล่านั้นใช้ `CRLF` เพื่อป้องกันสิ่งนี้ ให้ตั้งค่าบรรทัดที่ลงท้ายด้วย `LF` (การฟีดบรรทัด) ก่อนอัปโหลด*

ต้องเช็คอินไฟล์ Markdown โดยใช้ลำดับท้ายบรรทัด `LF`

### การ Escape

ไวยากรณ์ Markdown ควร Escape ตามต้องการ อย่างไรก็ตาม ชื่อบทความจะถูกแยกวิเคราะห์เป็นข้อความธรรมดา ดังนั้นต้องไม่ Escape

### ย่อหน้า

แต่ละย่อหน้าต้องตามด้วยบรรทัดว่างหนึ่งบรรทัด

### ตัวแบ่งบรรทัด

ตัวแบ่งบรรทัดต้องใช้แบ็กสแลช (`\`)

ต้องใช้ตัวแบ่งบรรทัดเท่าที่จำเป็น

## บันทึกย่อ

*อย่าสับสนกับ [หมายเหตุ](#notice)*

บันทึกย่อ เป็นบันทึกย่อที่วางไว้ที่ด้านบนของบทความหรือส่วนเพื่อช่วยให้ผู้อ่านนำทางไปยังบทความที่เกี่ยวข้องหรือแจ้งให้พวกเขาทราบเกี่ยวกับหัวข้อที่เกี่ยวข้อง

บันทึกย่อ ต้องเป็นตัวเอียงและวางทันทีหลังจากหัวข้อ หากมีการใช้บันทึกย่อหลายอัน ต้องอยู่ในย่อหน้าเดียวกันโดยคั่นด้วยการขึ้นบรรทัดใหม่

### หน้าหลัก

บันทึกย่อ *หน้าหลัก* นำผู้อ่านไปยังบทความหลักของหัวข้อ เมื่อใช้บันทึกย่อนี้ แสดงว่าส่วนที่อยู่บนนั้นเป็นบทสรุปของหน้าที่เชื่อมโยงนั้นเกี่ยวกับอะไร บันทึกย่อนี้ควรมีลิงก์เดียวเท่านั้น ต้องจัดรูปแบบดังนี้:

```markdown
*หน้าหลัก: {บทความ}*

*หน้าหลัก: {บทความ} และ {บทความ}*
```

### ดูสิ่งนี้ด้วย

บันทึกย่อ *ดูสิ่งนี้ด้วย* แนะนำให้ผู้อ่านจุดที่น่าสนใจอื่น ๆ จากบทความหรือส่วนที่กำหนด ต้องจัดรูปแบบดังนี้:

```markdown
*ดูเพิ่มเติมที่: {บทความ}*

*ดูเพิ่มเติมที่: {บทความ} และ {บทความ}*
```

### สำหรับดู

บันทึกย่อ *สำหรับดู* คล้ายกับหมายเหตุหมวก *ดูสิ่งนี้ด้วย* แต่โดยทั่วไปมีคำอธิบายและตรงไปตรงมามากกว่า บันทึกย่อ นี้อาจใช้มากกว่าหนึ่งลิงก์หากจำเป็น ต้องจัดรูปแบบดังนี้:

```markdown
*สำหรับ {คำอธิบาย} โปรดดูที่: {บทความ}*

*สำหรับ {คำอธิบาย} ดู: {บทความ} และ {บทความ}*
```

### เพื่อไม่ให้สับสนกับ

บันทึกย่อ *เพื่อไม่ให้สับสนกับ* ช่วยแยกแยะชื่อหรือหัวข้อบทความที่คลุมเครือหรือเข้าใจผิด บันทึกย่อ นี้อาจใช้มากกว่าหนึ่งลิงก์หากจำเป็น ต้องจัดรูปแบบดังนี้:

```markdown
*อย่าสับสนกับ {บทความ}.*

*อย่าสับสนกับ {บทความ} หรือ {บทความ}.*
```

### สำหรับการใช้งานอื่นๆ

บันทึกย่อ *สำหรับการใช้งานอื่นๆ* จะคล้ายกับ *เพื่อไม่ให้สับสนกับ* บันทึกย่อ แต่มีการเชื่อมโยงโดยตรงไปยัง[บทความแก้ความกำกวม](#disambiguation-articles) หมวกใบนี้ต้องลิงก์ไปยังบทความแก้ความกำกวมเท่านั้น ต้องจัดรูปแบบดังนี้:

```markdown
*สำหรับความหมายอื่น ดูที่ {บทความแก้ความกำกวม}*
```

## หมายเหตุ

*เพื่อไม่ให้สับสนกับ [บันทึกย่อ](#บันทึกย่อ)*

ควรมีการแจ้งเตือนในส่วนที่เหมาะสม แต่ต้องเริ่มจากย่อหน้าและใช้ตัวเอียง ประกาศอาจมีตัวหนาตามความเหมาะสม แต่ควรเก็บไว้ให้น้อยที่สุด คำบอกกล่าวจะต้องเขียนเป็นประโยคที่สมบูรณ์ ดังนั้น จึงไม่เหมือนกับ [บันทึกย่อย่อ](#บันทึกย่อ) ส่วนใหญ่ ต้องใช้จุดเต็ม (`.`) หรือเครื่องหมายอัศเจรีย์ (`!`) หากเหมาะสม สิ่งใดก็ตามที่อยู่ในวรรคเดียวกันของประกาศจะต้องเป็นตัวเอียงด้วย ต้องจัดรูปแบบดังนี้:

```markdown
*หมายเหตุ: {หมายเหตุ}.*

*ประกาศ: {ประกาศ}.*

*ข้อควรระวัง: {ข้อควรระวัง}.*

*คำเตือน: {คำเตือน}.*
```

- ควรใช้ `หมายเหตุ` สำหรับรายละเอียดที่เป็นข้อเท็จจริงหรือเล็กน้อย
- ควรใช้ `ประกาศ` เพื่อเตือนความจำหรือดึงความสนใจไปยังสิ่งที่ผู้อ่านควรทราบ
- ควรใช้ `ข้อควรระวัง` เพื่อเตือนผู้อ่านเพื่อหลีกเลี่ยงผลกระทบที่ไม่ได้ตั้งใจ
- ควรใช้ `คำเตือน` เพื่อเตือนผู้อ่านว่าอาจมีการดำเนินการกับพวกเขา

## การเน้น

### ตัวหนา

ตัวหนาต้องใช้เครื่องหมายดอกจันคู่ (`**`)

ย่อหน้านำอาจทำให้ชื่อบทความปรากฏขึ้นครั้งแรกเป็นตัวหนา

### ตัวเอียง

ตัวเอียงต้องใช้ดอกจันเดี่ยว (`*`)

ชื่องานหรือวิดีโอเกมควรเป็นตัวเอียง osu!—ตัวเกม—ได้รับการยกเว้นจากสิ่งนี้

การเกิดขึ้นครั้งแรกของตัวย่อ ตัวย่อ หรืออักษรย่ออาจเป็นตัวเอียง

อาจใช้ตัวเอียงเพื่อเน้นหรือช่วยในการอ่านได้

## หัวเรื่อง

หัวเรื่องทั้งหมดต้องใช้ตัวพิมพ์ประโยค

ส่วนหัวต้องใช้รูปแบบ [ATX (hash)](https://github.github.com/gfm/#atx-headings "GitHub") และต้องมีบรรทัดว่างก่อนและหลังส่วนหัว หัวเรื่องเป็นข้อยกเว้นเมื่ออยู่ในบรรทัดแรก หากเป็นกรณีนี้ จะต้องเว้นบรรทัดว่างไว้หลังหัวเรื่องเท่านั้น

หัวเรื่องต้องไม่เกินระดับหัวเรื่อง 5 และห้ามใช้เพื่อจัดรูปแบบหรือจัดรูปแบบข้อความ

### ชื่อเรื่อง

*ดูสิ่งนี้ด้วย: [การตั้งชื่อบทความ](#การตั้งชื่อบทความ)*\
*ข้อควรระวัง: ชื่อจะถูกแยกวิเคราะห์เป็นข้อความธรรมดา พวกเขาจะต้องไม่ escape*

หัวเรื่องแรกในบทความทั้งหมดต้องเป็นหัวเรื่องระดับ 1 ซึ่งเป็นหัวเรื่องของบทความ หัวข้อทั้งหมดหลังจากนั้นต้องเป็น[หัวข้อส่วน](#ส่วน) ชื่อเรื่องต้องไม่มีการจัดรูปแบบ ลิงก์ หรือรูปภาพ

หัวเรื่องต้องอยู่ในบรรทัดแรก ยกเว้นกรณีที่มีการใช้[เรื่องหน้า](#เรื่องหน้า) หากเป็นกรณีนี้ หัวเรื่องจะต้องอยู่ข้างหลังและมีบรรทัดว่างก่อนหัวเรื่อง

### ส่วนย่อย

ส่วนหัวของส่วนย่อยต้องใช้หัวเรื่องระดับ 2 ถึง 5 และส่วนหัวของส่วนย่อยที่มาตามหลัง [ส่วนหัวของชื่อเรื่อง](#ชื่อเรื่อง) ต้องใช้หัวเรื่องระดับ 2 โดยที่ส่วนหัวของส่วนย่อยสามารถมีรูปภาพไอคอนขนาดเล็กประกอบได้

ส่วนหัวของส่วนต้องไม่ข้ามระดับหัวเรื่อง (เช่น อย่าเปลี่ยนจากส่วนหัวระดับ 2 ไปเป็นส่วนหัวระดับ 4) และต้องไม่มีการจัดรูปแบบหรือลิงก์

*หมายเหตุ: บนเว็บไซต์ หัวเรื่องระดับ 4 และ 5 จะไม่ปรากฏในสารบัญ*

### ตัวระบุที่กำหนดเอง

เป็นไปได้ที่จะกำหนดตัวระบุของส่วนใหม่ ซึ่งใช้สำหรับเชื่อมโยงไปยังส่วนนั้นโดยตรง ตัวระบุที่กำหนดเองควรใช้ในกรณีที่ตัวระบุที่สร้างขึ้นโดยอัตโนมัติยาวเกินไปหรือมีเครื่องหมายวรรคตอนหรือรูปภาพที่ยุ่งยาก:

```markdown
## My cooldown has passed. How do I appeal? {id=appeal}

## Various examples of osu! gameplay {id=osu!-gameplay}
```

คุณลักษณะนี้ยังสามารถใช้สำหรับแท็กเฉพาะส่วนของบทความที่ไม่มีหัวเรื่อง ใช้เท่าที่จำเป็น:

```markdown
> แค่นั้นแหละ! คุณพร้อมที่จะเป็น osu! แชมป์!
{id=ข้อความ-การสอน}
```

## รายการ

รายการไม่ควรเกิน 4 ระดับการเยื้องและไม่ควรมีบรรทัดว่างระหว่างแต่ละรายการ

สำหรับรายการที่ซ้อนกัน สัญลักษณ์แสดงหัวข้อย่อยหรือตัวเลขต้องสอดคล้องกับเนื้อหารายการของรายการหลัก

ตัวอย่างต่อไปนี้ทำไม่ถูกต้อง (สังเกตการเว้นวรรคก่อนสัญลักษณ์แสดงหัวข้อย่อย):

```markdown
1. เล่นว่าว
  - อย่าเล่นว่าวถ้าฝนตก
```

ตัวอย่างต่อไปนี้ทำอย่างถูกต้อง:

```markdown
1. เล่นว่าว
   - อย่าเล่นว่าวถ้าฝนตก
```

### สัญลักษณ์แสดงหัวข้อย่อย

รายการสัญลักษณ์แสดงหัวข้อย่อยต้องใช้ยัติภังค์ (`-`) สิ่งเหล่านี้จะต้องตามด้วยช่องว่างเดียว (ตัวอย่างที่แสดงด้านล่าง)

```markdown
- osu!
  - วงกลม
    - หมายเลขวงกลม
    - เส้นเข้าหาวงกลม
  - สไลเดอร์
    - วงกลม
    - ตัวเลื่อน
    - Tick สไลเดอร์
  - ตัวหมุน
- กลอง
```

### หมายเลข

ตัวเลขในรายการลำดับเลขจะต้องเพิ่มขึ้นเพื่อแสดงลำดับขั้นตอน

```markdown
1. ดาวน์โหลด osu! ตัวติดตั้ง
2. เรียกใช้โปรแกรมติดตั้ง
   1. หากต้องการเปลี่ยนตำแหน่งการติดตั้ง ให้คลิกข้อความใต้แถบความคืบหน้า
   2. โปรแกรมติดตั้งจะถามหาตำแหน่งใหม่ เลือกโฟลเดอร์การติดตั้ง
3. osu! จะเริ่มทำงานเมื่อการติดตั้งเสร็จสิ้น
4. ลงชื่อเข้าใช้
```

### ผสม

การรวมรายการสัญลักษณ์แสดงหัวข้อย่อยและลำดับเลขเข้าด้วยกันควรทำเท่าที่จำเป็น

```markdown
1. ดาวน์โหลดสกินจากฟอรัม
2. โหลดไฟล์สกินเข้า osu!.
   - หากไฟล์เป็น `.zip` ให้เปิดเครื่องรูดและย้ายเนื้อหาไปยังโฟลเดอร์ `Skins/` (พบได้ในโฟลเดอร์การติดตั้ง osu!)
   - หากไฟล์เป็น `.osk` ให้เปิดไฟล์บนเดสก์ท็อปหรือลากและวางลงในไคลเอนต์เกม
3. เปิด osu! ถ้ายังไม่เปิด ให้เลือกสกินในตัวเลือก
   - การดำเนินการนี้อาจเสร็จสิ้นหากคุณเปิดไฟล์ `.osk` หรือลากและวางลงในไคลเอนต์เกม
```

## โค้ด

มาร์กอัปสำหรับโค้ดคือเครื่องหมาย grave mark (`` ` ``) ในการใส่เครื่องหมาย grave mark ในโค้ด ให้ใช้เครื่องหมาย grave mark คู่แทน ถ้าเครื่องหมาย grave mark อยู่ที่จุดเริ่มต้นหรือจุดสิ้นสุด ให้เว้นช่องว่างหนึ่งช่อง (ตามตัวอย่างที่แสดงด้านล่าง)

```markdown
`` ` ``
`` `ช่องว่าง` ``
```

### แป้นคีย์บอร์ด

*หมายเหตุ: เมื่อแสดงถึงตัวอักษรนั้นเองที่ไม่ใช่แป้นคีย์บอร์ด ให้ใช้เครื่องหมายคำพูดแทน*

เมื่อต้องการที่จะแสดงถึงแป้นบนคีย์บอร์ด ให้ใช้อักษรตัวพิมพ์ใหญ่สำหรับอักขระตัวเดียวและตัวพิมพ์แบบลักษณะชื่อเรื่องสำหรับตัวปรับแต่ง และใช้สัญลักษณ์บวก (`+`) (ไม่อยู่ในรูปแบบโค้ด) เพื่อแสดงถึงการผสมคีย์ (ตามตัวอย่างที่แสดงด้านล่าง)

```markdown
pippi สะกดด้วยตัว "p" ตัวพิมพ์เล็กเช่น peppy

กด `Ctrl` + `O` เพื่อเปิดกล่องโต้ตอบที่เปิดอยู่
```

เมื่อแทนช่องว่างหรือสเปซบาร์ ให้ใช้ `` `ช่องว่าง` ``.

### ข้อความปุ่มและเมนู

เมื่อคัดลอกข้อความจากเมนูหรือปุ่ม ควรคัดลอกตัวพิมพ์ใหญ่เล็กตามที่ปรากฏ (ตัวอย่างที่แสดงด้านล่าง)

```markdown
ปุ่ม `osu!direct` จะปรากฏในเมนูหลักทางด้านขวา ถ้าคุณมีแท็ก osu!supporter ที่ใช้งานอยู่
```

### ชื่อโฟลเดอร์และไดเรกทอรี

เมื่อคัดลอกชื่อโฟลเดอร์หรือไดเร็กทอรี ควรคัดลอกตัวพิมพ์ใหญ่เล็กตามที่ปรากฏ แต่ควรใช้เส้นทางตัวพิมพ์เล็กหากเป็นไปได้ เส้นทางไดเรกทอรีต้องไม่แน่นอน (เช่น อย่าเริ่มชื่อไดเรกทอรีจากอักษรระบุไดรฟ์หรือจากโฟลเดอร์ราก) (ตัวอย่างที่แสดงด้านล่าง)

```markdown
osu! ได้รับการติดตั้งในโฟลเดอร์ `AppData/Local` โดยค่าเริ่มต้น เว้นแต่จะระบุไว้เป็นอย่างอื่นระหว่างการติดตั้ง
```

### คำสำคัญและคำสั่ง

เมื่อคัดลอกคีย์เวิร์ดหรือคำสั่ง ควรคัดลอกตัวพิมพ์ใหญ่เล็กตามที่ปรากฏหรือวิธีที่ผู้อื่นพิมพ์ตามปกติ หากเป็นไปได้ ให้เลือกอักษรตัวพิมพ์เล็ก (ตามตัวอย่างที่แสดงด้านล่าง)

```markdown
ณ ตอนนี้ คำสั่ง `ชื่อ` และ `ผู้แต่ง` ในไฟล์การกำหนดค่าสกิน (`skin.ini`) ไม่ทำอะไรเลย
```

### ชื่อไฟล์

เมื่อทำการคัดลอกชื่อไฟล์ ตัวพิมพ์ควรถูกคัดลอกตามที่ปรากฏ หากเป็นไปได้ ให้เลือกอักษรตัวพิมพ์เล็ก (ตัวอย่างที่แสดงด้านล่าง)

```markdown
ในการเล่น osu! ให้ดับเบิลคลิกที่ไอคอน `osu!.exe`
```

### นามสกุลไฟล์

*หมายเหตุ: รูปแบบไฟล์ (เพื่อไม่ให้สับสนกับนามสกุลไฟล์) ต้องเขียนด้วยอักษรตัวพิมพ์ใหญ่โดยไม่มี fullstop นำหน้า (`.`)*

นามสกุลไฟล์ต้องขึ้นต้นด้วย fullstop (`.`) และตามด้วยนามสกุลไฟล์ด้วยอักษรตัวพิมพ์เล็ก (ตัวอย่างที่แสดงด้านล่าง)

```markdown
รูปแบบไฟล์ JPG (หรือ JPEG) มีนามสกุล `.jpg` (หรือ `.jpeg`)
```

### ช่องแชท

เมื่อคัดลอกชื่อช่องแชท ให้เริ่มต้นด้วยแฮช (`#`) ตามด้วยชื่อช่องที่เป็นตัวพิมพ์เล็ก (ตัวอย่างที่แสดงด้านล่าง)

```markdown
`#lobby` คือที่ที่คุณสามารถโฆษณาห้องโหมดผู้เล่นหลายคนของคุณได้
```

## ข้อความที่จัดรูปแบบไว้ล่วงหน้า (บล็อกโค้ด)

*ประกาศ: การเน้นไวยากรณ์สำหรับข้อความที่จัดรูปแบบไว้ล่วงหน้ายังใช้งานบนเว็บไซต์ไม่ได้*

ข้อความที่จัดรูปแบบไว้ล่วงหน้า (หรือที่เรียกว่าบล็อคโค้ด) จะต้องล้อมรั้วโดยใช้เครื่องหมาย grave mark สามอัน และควรที่จะตั้งค่าตัวระบุภาษาสำหรับการเน้นไวยากรณ์

## ลิงค์

ลิงค์มีสองประเภท: อินไลน์และการอ้างอิง อินไลน์มีสองรูปแบบ

ต่อไปนี้คือตัวอย่างของรูปแบบอินไลน์ทั้งสองแบบ:

```markdown
[ตัวดัดแปลงเกม](/wiki/Gameplay/Game_modifier)

<https://osu.ppy.sh/home>
```

ต่อไปนี้เป็นตัวอย่างของรูปแบบการอ้างอิง:

```markdown
[ตัวดัดแปลงเกม][ลิงค์ตัวดัดแปลงเกม]

[ลิงค์ตัวดัดแปลงเกม]: /wiki/Game_Modifiers
```

---

ลิงก์ต้องใช้รูปแบบอินไลน์หากมีการอ้างอิงเพียงครั้งเดียว ควรหลีกเลี่ยงรูปแบบวงเล็บมุมอินไลน์ การอ้างอิงไปยังลิงก์อ้างอิงจะต้องอยู่ที่ด้านล่างของบทความ

### ลิงค์ภายใน

*หมายเหตุ: ลิงก์ภายในหมายถึงลิงก์ที่อยู่ภายในโดเมน `https://osu.ppy.sh/`*

#### ลิงก์ Wiki

ลิงก์ทั้งหมดที่ชี้ไปยังบทความ wiki ควรเริ่มต้นด้วย `/wiki/` ตามด้วยเส้นทางเพื่อไปยังบทความที่คุณกำหนดเป้าหมาย อาจใช้ลิงก์สัมพัทธ์ ตัวอย่างบางส่วนมีดังต่อไปนี้:

```markdown
[คำถามที่พบบ่อย](/wiki/FAQ)
[pippi](/wiki/Mascots#-pippi)
[บีทแมป](../)
[แพทเทิร์น](./pattern)
```

ลิงก์ Wiki ต้องไม่ใช้การเปลี่ยนเส้นทางและต้องไม่มีเครื่องหมายทับปิดท้าย (`/`)

ตัวอย่างที่ไม่ดี ได้แก่:

```markdown
[เกณฑ์การจัดรูปแบบบทความ](/wiki/ASC)
[ผู้พัฒนา](/wiki/Developers/)
[ผู้พัฒนา](/wiki/Developers/#game-client-developers)
```

ตัวอย่างที่ดีได้แก่:

```markdown
[เกณฑ์การจัดรูปแบบบทความ](/wiki/Article_styling_criteria)
[ผู้พัฒนา](/wiki/Developers)
[ผู้พัฒนา](/wiki/Developers#game-client-developers)
```

##### ลิงค์บทความย่อย

ลิงก์ Wiki ที่ชี้ไปยังบทความย่อยควรมีชื่อโฟลเดอร์ของบทความหลักในข้อความลิงก์ ดูตัวอย่างต่อไปนี้:

```markdown
*ดูเพิ่มเติมที่: [ตัวแก้ไขบีทแมพ/การออกแบบ](/wiki/Client/Beatmap_editor/Design)*
```

##### ลิงค์ส่วนย่อย

*หมายเหตุ: บนเว็บไซต์ หัวเรื่องระดับ 4 และ 5 ไม่ได้รับแอตทริบิวต์ id ซึ่งหมายความว่าไม่สามารถเชื่อมโยงโดยตรงได้*

ลิงก์ Wiki ที่ชี้ไปยังส่วนของบทความอาจใช้สัญลักษณ์เครื่องหมายส่วน (`§`) ดูตัวอย่างต่อไปนี้:

```markdown
*สำหรับกฎการจับเวลา โปรดดู: [เกณฑ์การจัดอันดับ § เวลา](/wiki/Ranking_criteria#timing)*
```

#### ลิงค์ osu! อื่น ๆ

ควรคัดลอก URL จากแถบที่อยู่ของเว็บเบราว์เซอร์ของคุณตามที่ปรากฏ เมื่อลิงก์ไปยังหน้าอื่นภายในเว็บ osu!  และเว็บต้องมีส่วน `https://osu.ppy.sh` ของ URL เสมอ

##### โปรไฟล์ผู้ใช้

ชื่อผู้ใช้ทั้งหมดจะต้องเชื่อมโยงในครั้งแรก เหตุการณ์อื่น ๆ เป็นทางเลือก แต่จะต้องสอดคล้องตลอดทั้งบทความสำหรับชื่อผู้ใช้ทั้งหมด หากระบุ ID ผู้ใช้ได้ยาก อาจถูกข้ามไป

เมื่อเชื่อมโยงไปยังโปรไฟล์ผู้ใช้ ต้องใช้หมายเลขประจำตัวผู้ใช้ ใช้เว็บไซต์ใหม่ (`https://osu.ppy.sh/users/{ชื่อผู้ใช้}`) เพื่อรับ ID ของผู้ใช้

ข้อความลิงก์ของลิงก์ผู้ใช้ควรเป็นชื่อปัจจุบันของผู้ใช้

##### ระดับความยาก

เมื่อใดก็ตามที่เชื่อมโยงไปยังระดับความยากเดียว ให้ใช้รูปแบบนี้เป็นข้อความลิงก์:

```
{ศิลปิน} - {ชื่อ} ({ผู้สร้าง}) [{ชื่อระดับความยาก}]
```

ลิงค์จะต้องเชื่อมโยงไปยังระดับความยากเดียวนั้นจริง ๆ และ URL ของระดับความยากของ Beatmap ต้องจัดรูปแบบดังนี้:

```
https://osu.ppy.sh/beatmapsets/{รหัสบีทแมพเซ็ต}#{mode}/{รหัสบีทแมพ}
```

ชื่อระดับความยากอาจอยู่นอกข้อความลิงก์ แต่ต้องสอดคล้องกันตลอดทั้งบทความ

##### บีทแมป

เมื่อใดก็ตามที่เชื่อมโยงไปยังบีทแมป ให้ใช้รูปแบบนี้เป็นข้อความลิงก์:

```
{ศิลปิน} - {ชื่อ} ({ผู้สร้าง})
```

URL ของบีตแมปทั้งหมดต้องอยู่ในรูปแบบดังนี้:

```
https://osu.ppy.sh/beatmapsets/{ID ของ บีทแมพ}
```

### ลิงค์ภายนอก

*หมายเหตุ: ลิงก์ภายนอกหมายถึงลิงก์ที่อยู่นอกโดเมน `https://osu.ppy.sh/`*

ต้องใช้โปรโตคอล "https" เว้นแต่ไซต์จะไม่รองรับ ลิงก์ภายนอกต้องเป็นลิงก์ที่ตรงไปยังแหล่งที่เชื่อถือได้ ควรคัดลอก URL จากแถบที่อยู่ของเว็บเบราว์เซอร์ตามที่ปรากฎ เมื่อลิงก์ไปยังหน้าภายนอกอื่น ๆ

ไม่มีความแตกต่างเรื่องการเขียนระหว่างลิงค์เว็บภายนอกและ ลิงค์เว็บ osu! ด้วยเหตุนี้ ชื่อเว็บไซต์จึงควรรวมอยู่ในข้อความชื่อ ตามตัวอย่างต่อไปนี้:

```markdown
*ดูข้อมูลเพิ่มเติมเกี่ยวกับทฤษฎีดนตรีได้ที่ [ทฤษฎีดนตรี](https://en.wikipedia.org/wiki/Music_theory "วิกิพีเดีย")*
```

## รูปภาพ

การลิงก์รูปภาพมีสองประเภทคือ แบบอินไลน์และการใช้การอ้างอิง ตัวอย่าง:

**รูปแบบอินไลน์:**

```markdown
![](/wiki/shared/flag/AU.gif)
```

**รูปแบบการใช้การอ้างอิง:**

```markdown
![][flag_AU]

[flag_AU]: /wiki/shared/flag/AU.gif "ออสเตรเลีย"
```

รูปภาพควรใช้รูปแบบการเชื่อมโยงแบบอินไลน์ การอ้างอิงไปยังลิงก์อ้างอิงจะต้องอยู่ที่ด้านล่างของบทความ

รูปภาพต้องอยู่ในโฟลเดอร์ชื่อ "img" ซึ่งอยู่ในโฟลเดอร์ของบทความ รูปภาพที่ใช้ในหลายบทความควรเก็บไว้ในโฟลเดอร์ `/wiki/shared/`

### การแคชรูปภาพ

รูปภาพบนเว็บไซต์จะถูกแคชไว้นานถึง 60 วัน รูปภาพที่แคชไว้จะตรงกับ URL ของลิงก์รูปภาพ

เมื่ออัปเดตรูปภาพ ให้เปลี่ยนชื่อรูปภาพหรือต่อท้ายสตริงการสืบค้นไปยัง URL ในทั้งสองกรณี การแปลทั้งหมดที่เชื่อมโยงกับรูปภาพที่อัปเดตควรได้รับการอัปเดตด้วย

### รูปแบบและคุณภาพ

รูปภาพควรใช้รูปแบบ JPG ที่คุณภาพ 8 (80 หรือ 80% ขึ้นอยู่กับโปรแกรม) หากรูปภาพมีความโปร่งใสหรือมีข้อความที่ต้องอ่านได้ ให้ใช้รูปแบบ PNG แทน หากรูปภาพมีแอนิเมชั่น คุณสามารถใช้รูปแบบ GIF ได้ อย่างไรก็ตาม ควรใช้เท่าที่จำเป็น เนื่องจากอาจใช้เวลาในการโหลดนานกว่าหรือใหญ่กว่า [ขนาดไฟล์สูงสุด](#ขนาดไฟล์)

### ขนาดไฟล์

รูปภาพต้องมีขนาดต่ำกว่า 1 เมกะไบต์ มิฉะนั้นจะไม่สามารถโหลดได้ การลดขนาดและการใช้ JPG ที่ 80% มักอยู่ภายใต้ขีดจำกัดของขนาด

รูปภาพทั้งหมดควรได้รับการปรับให้เหมาะสมที่สุดเท่าที่จะทำได้ ใช้ [jpeg-archive](https://github.com/danilgtaylor/jpeg-archive "GitHub") เพื่อบีบอัดภาพ JPEG เพื่อความสอดคล้อง ให้ใช้คำสั่งต่อไปนี้สำหรับ jpeg-archive:

```sh
jpeg-recompress -am smallfry <input> <output>
```

โดยที่ `<input>` คือชื่อไฟล์ที่จะบีบอัด และ `<output>` คือชื่อไฟล์ที่บีบอัด

### ชื่อไฟล์

*หมายเหตุ: นามสกุลไฟล์ต้องใช้อักษรตัวพิมพ์เล็ก มิฉะนั้น จะไม่สามารถโหลดได้!*

ใช้ขีดกลาง (`-`) เมื่อเว้นวรรคคำ และเมื่อตั้งชื่อรูปภาพ ชื่อไฟล์ควรสื่อความหมายได้และมีขนาดสั้น

### การจัดรูปแบบและการวางตำแหน่ง

*หมายเหตุ: ขณะนี้ยังไม่สามารถลอยรูปภาพหรือมีข้อความล้อมรอบได้*

รูปภาพบนเว็บไซต์จะถูกจัดกึ่งกลางเมื่ออยู่ในบรรทัดเดียวด้วยตัวเอง มิฉะนั้น จะวางอยู่ในแนวเดียวกับย่อหน้า ตัวอย่างต่อไปนี้จะวางรูปภาพไว้ตรงกลาง:

```markdown
กำลังติดตั้ง osu! มันง่าย ขั้นแรก ดาวน์โหลดตัวติดตั้งจากหน้าดาวน์โหลด

![](img/download-page.jpg)

จากนั้นค้นหาตัวติดตั้งและเรียกใช้
```

### ข้อความแสดงแทน

รูปภาพควรมีข้อความแสดงแทนเว้นแต่จะใช้เพื่อการตกแต่ง

### คำบรรยาย

รูปภาพจะได้รับคำบรรยายบนเว็บไซต์หากเป็นไปตามเงื่อนไขเหล่านี้:

1. รูปภาพอยู่ด้วยตัวเอง
2. รูปภาพไม่อยู่ในหัวเรื่อง
3. รูปภาพมีหัวข้อชื่อ

คำบรรยายจะถูกสมมติผ่านหัวข้อชื่อซึ่งจะต้องเป็นข้อความธรรมดาเท่านั้น รูปภาพที่มีคำอธิบายภาพจะถูกวางไว้กึ่งกลางบนเว็บไซต์ด้วย

### ความกว้างของภาพสูงสุด

ความกว้างสูงสุดของรูปภาพของเว็บไซต์คือความกว้างของเนื้อหาบทความ รูปภาพไม่ควรกว้างเกิน 800 พิกเซล

### คำอธิบายประกอบภาพ

เมื่อใส่คำอธิบายประกอบรูปภาพ ให้ใช้ *Torus Regular* สำหรับอักขระภาษาจีน เกาหลี ญี่ปุ่น ให้ใช้ *Microsoft YaHei*

ควรหลีกเลี่ยงการใส่คำอธิบายประกอบรูปภาพ เนื่องจากยากสำหรับนักแปล (และบรรณาธิการอื่น ๆ) ในการแก้ไข

#### กำลังแปลรูปภาพที่มีคำอธิบายประกอบ

เมื่อแปลรูปภาพที่มีคำอธิบายประกอบ เวอร์ชันรูปภาพที่แปลแล้วจะต้องอยู่ในไดเรกทอรีเดียวกันกับเวอร์ชันดั้งเดิม (เช่น เวอร์ชันภาษาอังกฤษ) ชื่อไฟล์ของรูปภาพเวอร์ชันแปลต้องขึ้นต้นด้วยชื่อเวอร์ชันดั้งเดิม ตามด้วยยัติภังค์ ตามด้วยอักษรย่อของภาษานั้น (เป็นตัวพิมพ์ใหญ่) ตามตัวอย่างต่อไปนี้:

- `hardrock-mod-vs-easy-mod.jpg` สำหรับภาษาอังกฤษ
- `hardrock-mod-vs-easy-mod-DE.jpg` สำหรับภาษาเยอรมัน
- `hardrock-mod-vs-easy-mod-ZH-TW.jpg` สำหรับภาษาจีนตัวเต็ม

### ภาพหน้าจอของการเล่นเกม

ภาพหน้าจอของการเล่นเกมทั้งหมดต้องทำใน stable build เว้นแต่จะเป็นสำหรับฟีเจอร์เฉพาะที่ไม่พร้อมใช้งานใน stable build และควรใช้ปุ่มถ่ายภาพหน้าจอในเกม (`F12`)

#### การตั้งค่าไคลเอนต์เกม

*หมายเหตุ: หากคุณไม่ต้องการเปลี่ยนการตั้งค่าปัจจุบันสำหรับวิกิ คุณสามารถย้าย `osu!.<ComputerUser>.cfg` ออกจาก osu! โฟลเดอร์และย้ายกลับในภายหลัง*

คุณต้องตั้งค่าเหล่านี้ก่อนที่จะถ่ายภาพหน้าจอของไคลเอนต์เกม (การตั้งค่าที่ไม่ได้ระบุไว้ด้านล่างถือเป็นค่าเริ่มต้น):

- เลือกภาษา: `English`
- ต้องการข้อมูลเมตาในภาษาต้นฉบับ: `เปิด`
- ความละเอียด: `1280x720`
- โหมดเต็มหน้าจอ: `ปิดการใช้งาน`
- พารัลแลกซ์: `ปิดการใช้งาน`
- เคล็ดลับเมนู: `ปิด`
- พื้นหลังตามฤดูกาล: `ไม่เคย`
- แสดงคีย์โอเวอร์เลย์เสมอ: `เปิด`
- สกินปัจจุบัน: `ค่าเริ่มต้น` (ตัวเลือกแรก)

*ประกาศสำหรับนักแปล: หากคุณกำลังแปลบทความที่มีภาพหน้าจอของเกม คุณสามารถตั้งค่าภาษาของไคลเอนต์เกมเป็นภาษาที่คุณกำลังแปลได้*

### ลิงค์รูปภาพ

รูปภาพต้องไม่เป็นส่วนหนึ่งของข้อความลิงก์

ไอคอนธงข้างลิงก์ผู้ใช้ต้องแยกจากข้อความลิงก์ ตามตัวอย่างต่อไปนี้:

```markdown
![][flag_AU] [peppy](https://osu.ppy.sh/users/2)
```

### ไอคอนธง

*สำหรับรายการไอคอนธง โปรดดู: [issue \#328](https://github.com/ppy/osu-wiki/issues/328 "GitHub")*

ไอคอนรูปธงจะใช้รหัสตัวอักษรสองตัว (เป็นตัวพิมพ์ใหญ่ทั้งหมด) และลงท้ายด้วย `.gif` และเมื่อเพิ่มธงในแนวเดียวกับข้อความ ให้ใช้รูปแบบนี้:

```markdown
![](/wiki/shared/flag/xx.gif)
```

โดยที่ `xx` คือรหัสประเทศ[ISO 3166-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2 "Wikipedia") สองตัวอักษรสำหรับธง

ควรเพิ่มชื่อประเทศเต็มในข้อความชื่อ รหัสประเทศในข้อความอื่นเป็นทางเลือก แต่ต้องใช้กับไอคอนธงทั้งหมดในบทความ

## ตาราง

ตารางบนเว็บไซต์รองรับเฉพาะส่วนหัวในแถวแรก

ต้องไม่ตกแต่งตารางให้สวยงาม (ห้ามปูเซลล์ที่มีช่องว่างพิเศษเพื่อทำให้ความกว้างเท่ากัน) ต้องมีแถบแนวตั้ง (`|`) ที่ด้านซ้ายและด้านขวา และข้อความของแต่ละเซลล์จะต้องมีช่องว่างหนึ่งช่องทั้งสองด้าน เซลล์ว่างต้องใช้แถบแนวตั้ง (`|`) ตามด้วยช่องว่างสองช่อง ตามด้วยแถบแนวตั้งอีกอัน (`|`)

แถวตัวคั่น (บรรทัดถัดไปหลังส่วนหัวของตาราง) ต้องใช้อักขระเพียงสามตัวต่อคอลัมน์ (และมีการเว้นวรรคทั้งสองข้าง) ซึ่งต้องมีลักษณะอย่างใดอย่างหนึ่งต่อไปนี้:

- `:--` (สำหรับจัดชิดซ้าย)
- `:-:` (สำหรับการจัดตำแหน่งกึ่งกลาง)
- `--:` (สำหรับการจัดชิดขวา)

---

ต่อไปนี้เป็นตัวอย่างลักษณะของตาราง:

```markdown
| Team "Picturesque" Red | Score | Team "Statuesque" Blue | Average Beatmap Stars |
| :-- | :-: | --: | :-- |
| **peppy** | 5 - 2 | pippi | 9.3 stars |
| Aiko | 1 - 6 | **Alisa** | 4.2 stars |
| Ryūta | 3 - 4 | **Yuzu** | 5.1 stars |
| **Taikonator** | 7 - 0 | Tama | 13.37 stars |
| Maria | No Contest | Mocha |  |
```

## Blockquotes

Blockquote ถูกจำกัดให้อ้างอิงข้อความจากใครบางคน จะต้องไม่ใช้เพื่อจัดรูปแบบข้อความเป็นอย่างอื่น

## ตัวแบ่งเฉพาะเรื่อง

ตัวแบ่งเฉพาะเรื่อง (หรือที่เรียกว่าเส้นแนวนอน) ควรใช้เท่าที่จำเป็น การใช้งานบางส่วนอาจรวมถึง (แต่ไม่จำกัดเพียง):

- การแยกรูปภาพออกจากข้อความ
- แยกรูปภาพหลายๆ รูปที่ตามกัน
- ย้ายหัวข้อภายในส่วน

ต้องมีบรรทัดว่างก่อนและหลังมาร์กอัป ตัวแบ่งเฉพาะเรื่องต้องใช้ยัติภังค์เพียงสามตัวดังที่แสดงด้านล่าง:

```markdown
---
```
