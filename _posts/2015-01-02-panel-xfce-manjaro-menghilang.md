---
layout: post
title: Panel XFCE menghilang! LOL
---
Setelah kemarin Manjaro XFCE saya diupgrade, dan sekarang baru teken tombol power lagi, seperti biasa login dan masukkan password. Nunggu beberapa lama langsung agak sedikit kaget, lah kok ini xfce4-panel-nya ilang? aplikasi yg sudah diatur autostart kenapa ga bisa ditutup atau diminimize (yg pojok kanan atas 3 icon)

setelah direboot karena berpikir mungkin ahh paling direboot nanti ilang sendiri masalahnya, ternyata masalahnya masih muncul. Kepikiran langsung Bebekin (DuckDuckGo) akar masalahnya di Firefox yg udah kebuka, akhirnya setelah pencarian kedua problem solved, diforum ubuntu (official) disuruh ketik ini diterminal:
xfwm4 --replace
dan aman sentosan kawan-kawan :cool
