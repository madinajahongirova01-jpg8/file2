# file2
#  ● This 
### • This in keywordi Javas cript ast, va az yak chand holat iborat ast.
## ✓ 1️⃣ Дар метод — this = ҳамон объект // this объектеро нишон медиҳад, ки метод ба он тааллуқ дорад.
# <img src="./img/Снимок экрана 2026-05-31 002936.png">
## ✓ 2️⃣ Дар функсияи оддӣ — this = window ё undefined // Функсияи оддӣ глобалӣ даъват шавад — this мешавад window. Бо "use strict" — undefined.
# <img src="./img/Снимок экрана 2026-05-31 004538.png">
## ✓ 3️⃣ Arrow function — this-ро аз берун мегирад //  Arrow function this-и худашро надорад — аз контексти берунӣ (дар ин ҷо window) мегирад.
# <img src="./img/Снимок экрана 2026-05-31 004722.png">
## ✓ 4️⃣ bind / call / apply — this-ро дастӣ медиҳем //
# ▼ Фарқ
## • call ⇨ аргументҳо алоҳида: f.call(obj, a, b)
## • apply ⇨ аргументҳо массив: f.apply(obj, [a, b])
## • bind ⇨ функсияи нав месозад, фавран иҷро намекунад
# <img src="./img/Снимок экрана 2026-05-31 004919.png">
## ✓ 5️⃣ new — this = объекти нав  // new истифода шавад — JavaScript объекти холӣ месозад, this ба ҳамон объект ишора мекунад ва онро бармегардонад.
# <img src="./img/Снимок экрана 2026-05-31 005024.png">
## ✓ 📋 Хулоса:
#  Ҳолат —————————————————— this
# ——————————————————————————
# ▼ Фарқ
## • obj.method()  ⇨  obj
## • func() ⇨  window / undefined
## • () => {} ⇨  аз берун
## • call/apply/bind ⇨ он чизе ки додӣ
## • new Func() ⇨ объекти нав