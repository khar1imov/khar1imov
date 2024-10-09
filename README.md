kitoblar = []
print("Yoqtirgan kitoblaringizni kiriting (to'xtatish uchun 'stop' deb yozing):")
while True:
        kitob = input("> ")
        if kitob.lower() == 'stop':
            break
kitoblar.append(kitob)

if kitoblar:
        print("Sizning yoqtirgan kitoblaringiz:")
for k in kitoblar:
    print(f"- {k}")
else:
        print("Hech qanday kitob kiritilmadi.")



<!---
khar1imov/khar1imov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
