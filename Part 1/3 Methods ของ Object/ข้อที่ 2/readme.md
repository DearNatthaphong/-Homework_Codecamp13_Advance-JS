### Codecamp # 13
    1. นาย ณัฐพงษ์ ทองพึง
    2. Advance JS Part 1_Methods ของ Object Lab # 2
        2.1  การทำงานของ code ดังกล่าวจะได้อะไรออกมา

            function makeUser() {
                return {
                    name: "John",
                    ref: this
                };
            };

            let user = makeUser();

            alert(user.ref.name); 
            // undefined เพราะคนเรียก object คือ Window
 