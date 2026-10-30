---
layout: default
title: Support
---

<div style="text-align: right; margin-bottom: 20px;">
    <button onclick="switchLang('en')" style="padding:5px 10px; cursor:pointer;">EN</button>
    <button onclick="switchLang('tr')" style="padding:5px 10px; cursor:pointer;">TR</button>
</div>

<div class="lang-en" style="margin-bottom: 30px;">
    <a href="./">Home</a> | <a href="privacy.html">Privacy Policy</a>
</div>
<div class="lang-tr" style="margin-bottom: 30px; display:none;">
    <a href="./">Ana Sayfa</a> | <a href="privacy.html">Gizlilik Politikası</a>
</div>

<div class="lang-en">
    <h2>Support & Contact</h2>
    <p>If you are experiencing any issues with the app, have feature requests, or just want to say hi, we are here to help!</p>
    <p>The fastest way to reach us is via email: <a href="mailto:iletisim@uygulamaniz.com">iletisim@uygulamaniz.com</a></p>
</div>

<div class="lang-tr" style="display:none;">
    <h2>Destek ve İletişim</h2>
    <p>Uygulamayla ilgili herhangi bir sorun yaşıyorsanız, yeni bir özellik talebiniz varsa veya sadece merhaba demek istiyorsanız, buradayız!</p>
    <p>Bize ulaşmanın en hızlı yolu e-posta göndermektir: <a href="mailto:iletisim@uygulamaniz.com">iletisim@uygulamaniz.com</a></p>
</div>

<script>
    function switchLang(lang) {
        document.querySelectorAll('.lang-en').forEach(el => el.style.display = lang === 'en' ? 'block' : 'none');
        document.querySelectorAll('.lang-tr').forEach(el => el.style.display = lang === 'tr' ? 'block' : 'none');
        localStorage.setItem('appLang', lang);
    }
    document.addEventListener("DOMContentLoaded", () => {
        const savedLang = localStorage.getItem('appLang') || (navigator.language.startsWith('tr') ? 'tr' : 'en');
        switchLang(savedLang);
    });
</script>
