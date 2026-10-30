---
layout: default
title: Privacy Policy
---

<div style="text-align: right; margin-bottom: 20px;">
    <button onclick="switchLang('en')" style="padding:5px 10px; cursor:pointer;">EN</button>
    <button onclick="switchLang('tr')" style="padding:5px 10px; cursor:pointer;">TR</button>
</div>

<div class="lang-en" style="margin-bottom: 30px;">
    <a href="./">Home</a> | <a href="support.html">Support</a>
</div>
<div class="lang-tr" style="margin-bottom: 30px; display:none;">
    <a href="./">Ana Sayfa</a> | <a href="support.html">Destek</a>
</div>

<div class="lang-en">
    <h2>Privacy Policy</h2>
    <p><strong>Last Updated:</strong> October 2026</p>
    <p>We respect your privacy. This application does not collect, store, or share any personal data. All timer data and workout configurations are saved locally on your device.</p>
    <h3>Camera and Video Access</h3>
    <p>If you use the video recording features, the application processes the video locally to add watermarks. These videos remain on your device and are not uploaded to our servers.</p>
</div>

<div class="lang-tr" style="display:none;">
    <h2>Gizlilik Politikası</h2>
    <p><strong>Son Güncelleme:</strong> Ekim 2026</p>
    <p>Gizliliğinize saygı duyuyoruz. Bu uygulama hiçbir kişisel veriyi toplamaz, saklamaz veya paylaşmaz. Tüm sayaç verileri ve antrenman yapılandırmaları cihazınızda yerel olarak kaydedilir.</p>
    <h3>Kamera ve Video Erişimi</h3>
    <p>Video kayıt özelliklerini kullanmanız durumunda, uygulama videoları yerel olarak işleyerek filigran ekler. Bu videolar cihazınızda kalır ve sunucularımıza yüklenmez.</p>
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
