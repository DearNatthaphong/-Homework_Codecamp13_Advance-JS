### Codecamp # 13
    1. นาย ณัฐพงษ์ ทองพึง
    2. Advance JS Part 1_Methods ของ Object Lab # 1
        2.1  การทำงานของ code ดังกล่าวจะได้อะไรออกมา

            let user = {
                name: "John",
                go: function() { alert(this.name) }
            }

            (user.go)() // Error เพราะ ไม่มี ; หลังประกาศ object ที่ชื่อ user
  