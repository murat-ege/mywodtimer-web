---
layout: default
title: Home
---

<div style="text-align: right; margin-bottom: 20px;">
    <button onclick="switchLang('en')" style="padding:5px 10px; cursor:pointer;">EN</button>
    <button onclick="switchLang('tr')" style="padding:5px 10px; cursor:pointer;">TR</button>
</div>

<!-- Menü -->
<div class="lang-en" style="margin-bottom: 30px;">
    <a href="./">Home</a> | 
    <a href="privacy.html">Privacy Policy</a> | 
    <a href="support.html">Support</a>
</div>
<div class="lang-tr" style="margin-bottom: 30px; display:none;">
    <a href="./">Ana Sayfa</a> | 
    <a href="privacy.html">Gizlilik Politikası</a> | 
    <a href="support.html">Destek</a>
</div>

<!-- İçerik -->
<div class="lang-en">
    <h2>Ultimate WOD Timer</h2>
    <p>The perfect companion for your CrossFit workouts. AMRAP, EMOM, TABATA and Custom intervals with seamless display synchronization.</p>
    <p>
        <a href="#">Download on App Store</a><br>
        <a href="#">Get it on Google Play</a>
    </p>
</div>

<div class="lang-tr" style="display:none;">
    <h2>En Gelişmiş WOD Sayacı</h2>
    <p>CrossFit antrenmanlarınız için mükemmel yol arkadaşı. AMRAP, EMOM, TABATA ve kesintisiz ekran senkronizasyonu ile özel aralıklar.</p>
    <p>
        <a href="#">App Store'dan İndir</a><br>
        <a href="#">Google Play'den Al</a>
    </p>
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
