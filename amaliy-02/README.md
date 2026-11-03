9-variant
Talaba: Matchonova Shakarjon Maqsud qizi Guruh: 941-24
1-masala. Sonlar · oson
Funksiya: raqamlarKopaytmasi(n)
Musbat butun son berilgan. Uning raqamlari ko‘paytmasini qaytaring.
raqamlarKopaytmasi(2345) // → 120
raqamlarKopaytmasi(105) // → 0
2-masala. Satrlar · oson
Funksiya: unlilarSoni(s)
Satr berilgan. Undagi unli harflar (a, e, i, o, u) sonini qaytaring. Katta va kichik harflar farqlanmaydi.
unlilarSoni("Dasturlash") // → 3
unlilarSoni("OSMON") // → 2
3-masala. Massivlar · oson
Funksiya: takrorsizBirlashtir(a, b)
Ikki massiv berilgan. Ularni birlashtirib, takrorlanuvchi elementlarsiz yangi massiv qaytaring. Elementlar
birinchi uchragan tartibda qolsin.
takrorsizBirlashtir([1, 2, 3], [2, 3, 4]) // → [1, 2, 3, 4]
takrorsizBirlashtir(["html"], ["css", "html"]) // → ["html", "css"]
4-masala. Satrlar va sonlar · o‘rtacha
Funksiya: sozlarTartibiniTeskari(s)
Gap berilgan. So‘zlar tartibini teskari qiling, so‘zlarning o‘zi o‘zgarmasin. Ortiqcha bo‘sh joylar olib 
tashlansin.
sozlarTartibiniTeskari("bugun javascript darsi boshlandi")
// → "boshlandi darsi javascript bugun"
sozlarTartibiniTeskari(" bir ikki ") // → "ikki bir"
5-masala. Massivlar va obyektlar · o‘rtacha
Funksiya: engKopTakrorlangan(arr)
Massiv berilgan. Eng ko‘p uchragan elementni qaytaring. Bir nechta bo‘lsa, massivda birinchi 
uchraganini.
engKopTakrorlangan([3, 7, 3, 1, 7, 3]) // → 3
engKopTakrorlangan(["a", "b", "b", "a"]) // → "a"
Web dasturlash