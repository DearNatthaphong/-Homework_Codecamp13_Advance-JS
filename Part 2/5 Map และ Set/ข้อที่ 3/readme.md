### Codecamp # 13
    1. นาย ณัฐพงษ์ ทองพึง
    2. Advance JS Part 2_Map และ Set Lab # 3
        2.1 เราได้ array จาก map.keys() แต่ไม่สามารถใช้ push ได้ เราจะทำยังไงให้ key.push สามารถทำงานได้

            let map = new Map();

            map.set("name", "John");

            let keys = map.keys();

            // Error: keys.push is not a function
            keys.push("more");