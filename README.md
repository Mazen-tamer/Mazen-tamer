<!-- كارت الهوية الزجاجي المبتكر -->
<div align="center">
  <svg width="600" height="230" viewBox="0 0 600 230" fill="none" xmlns="http://www.w3.org/2000/svg">
    <!-- تعريف التأثيرات والأنيميشن -->
    <defs>
      <!-- أنيميشن توهج النيون -->
      <linearGradient id="neonGradient" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#00f2fe">
          <animate attributeName="stop-color" values="#00f2fe;#4facfe;#00f2fe" dur="4s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#4facfe">
          <animate attributeName="stop-color" values="#4facfe;#00f2fe;#4facfe" dur="4s" repeatCount="indefinite" />
        </stop>
      </linearGradient>
      
      <!-- تأثير الـ Glassmorphism (Blur خلفي) -->
      <filter id="glassBlur">
        <feGaussianBlur stdDeviation="10" />
        <feColorMatrix type="matrix" values="1 0 0 0 0  0 1 0 0 0  0 0 1 0 0  0 0 0 18 -7" />
      </filter>
    </defs>

    <!-- الخلفية المظلمة العميقة للمصممين -->
    <rect width="600" height="230" rx="20" fill="#0d1117" />
    
    <!-- خطوط النيون المتحركة الخلفية -->
    <circle cx="500" cy="50" r="80" fill="url(#neonGradient)" opacity="0.15">
      <animate attributeName="r" values="80;95;80" dur="5s" repeatCount="indefinite" />
    </circle>
    <circle cx="80" cy="180" r="60" fill="url(#neonGradient)" opacity="0.12">
      <animate attributeName="cy" values="180;160;180" dur="4s" repeatCount="indefinite" />
    </circle>

    <!-- جسم الكارت الرئيسي (تأثير زجاجي) -->
    <rect x="20" y="20" width="560" height="190" rx="16" fill="#161b22" fill-opacity="0.7" stroke="url(#neonGradient)" stroke-width="1.5" filter="url(#glassBlur)" />

    <!-- طابع الـ Brand والشعار -->
    <text x="50" y="70" fill="#fff" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="26" font-weight="800" letter-spacing="1">VELTRIX</text>
    <text x="50" y="95" fill="#8b949e" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="14" font-weight="500">Creative Web & 3D Solutions</text>

    <!-- خط فاصل أنيق -->
    <line x1="50" y1="115" x2="300" y2="115" stroke="#30363d" stroke-width="1" />

    <!-- التخصص الحالي -->
    <text x="50" y="145" fill="#4facfe" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="16" font-weight="600" letter-spacing="0.5">Front-End Developer</text>
    
    <!-- الـ Tech Stack في شكل البادجات المودرن -->
    <g transform="translate(50, 165)">
      <!-- HTML -->
      <rect x="0" y="0" width="55" height="22" rx="6" fill="#f16529" fill-opacity="0.1" stroke="#f16529" stroke-width="0.5" />
      <text x="27.5" y="15" fill="#f16529" font-family="sans-serif" font-size="11" font-weight="bold" text-anchor="middle">HTML</text>
      
      <!-- CSS -->
      <rect x="65" y="0" width="50" height="22" rx="6" fill="#2965f1" fill-opacity="0.1" stroke="#2965f1" stroke-width="0.5" />
      <text x="90" y="15" fill="#2965f1" font-family="sans-serif" font-size="11" font-weight="bold" text-anchor="middle">CSS</text>
      
      <!-- JS -->
      <rect x="125" y="0" width="45" height="22" rx="6" fill="#f7df1e" fill-opacity="0.1" stroke="#f7df1e" stroke-width="0.5" />
      <text x="147.5" y="15" fill="#f7df1e" font-family="sans-serif" font-size="11" font-weight="bold" text-anchor="middle">JS</text>
      
      <!-- React -->
      <rect x="180" y="0" width="60" height="22" rx="6" fill="#00d8ff" fill-opacity="0.1" stroke="#00d8ff" stroke-width="0.5" />
      <text x="210" y="15" fill="#00d8ff" font-family="sans-serif" font-size="11" font-weight="bold" text-anchor="middle">React</text>
    </g>

    <!-- الأيقونة التفاعلية اليمنى (لوجو برمجى متحرك) -->
    <g transform="translate(460, 65)">
      <rect width="80" height="80" rx="12" fill="#0d1117" stroke="#30363d" />
      <!-- رمز الـ Code -->
      <text x="40" y="48" fill="#00f2fe" font-family="sans-serif" font-size="28" font-weight="bold" text-anchor="middle">&lt;/&gt;</text>
    </g>
  </svg>
</div>

<br>

---

### 🛠️ لوحة التحكم والمشاريع (تفاعلية بدون جافاسكريبت)

<!-- القائمة التدلية الأولى: عني -->
<details open>
  <summary style="font-size: 18px; font-weight: bold; color: #4facfe; cursor: pointer; padding: 10px; background-color: #161b22; border-radius: 8px; margin-bottom: 8px; list-style: none; border: 1px solid #30363d;">
    🚀 نبذة سريعة
  </summary>
  <div style="padding: 15px; background: #0d1117; border-left: 3px solid #00f2fe; border-radius: 0 0 8px 8px; margin-top: -8px; margin-bottom: 15px;">
    <p dir="rtl">أنا مطور واجهات مستخدم شغوف بتحويل الأفكار المعقدة إلى تجارب ويب تفاعلية وسلسة. أركز بشكل أساسي على بناء تطبيقات متكاملة باستخدام <b>React</b> مع تقديم أنيميشن وتصاميم واجهات (UI/UX) مبتكرة تلفت الأنظار.</p>
  </div>
</details>

<!-- القائمة التدلية الثانية: المشاريع المميزة -->
<details>
  <summary style="font-size: 18px; font-weight: bold; color: #4facfe; cursor: pointer; padding: 10px; background-color: #161b22; border-radius: 8px; margin-bottom: 8px; list-style: none; border: 1px solid #30363d;">
    📁 أهم المشاريع الحالية
  </summary>
  <div style="padding: 15px; background: #0d1117; border-left: 3px solid #4facfe; border-radius: 0 0 8px 8px; margin-top: -8px; margin-bottom: 15px;">
    
    <!-- مشروع 1 -->
    <div style="margin-bottom: 15px;">
      <h4 style="margin: 0; color: #ffffff;">🌐 Veltrix Web Solutions Platform</h4>
      <p dir="rtl" style="font-size: 14px; color: #8b949e; margin: 5px 0;">مشروع متكامل لتقديم حلول الويب المتقدمة والدمج بين تقنيات الـ Front-End والتصاميم ثلاثية الأبعاد.</p>
      <code>React</code> <code>CSS Keyframes</code> <code>Web Solutions</code>
    </div>
    
    <!-- مشروع 2 -->
    <div>
      <h4 style="margin: 0; color: #ffffff;">📱 Interactive QR & Web Systems</h4>
      <p dir="rtl" style="font-size: 14px; color: #8b949e; margin: 5px 0;">نظام ويب مخصص للأعمال التجارية لربط المواقع التفاعلية بأنظمة المسح السريع QR Code لتحسين تجربة المستخدم.</p>
      <code>HTML5</code> <code>JavaScript</code> <code>UI System</code>
    </div>

  </div>
</details>

<!-- القائمة التدلية الثالثة: تواصل معي -->
<details>
  <summary style="font-size: 18px; font-weight: bold; color: #4facfe; cursor: pointer; padding: 10px; background-color: #161b22; border-radius: 8px; margin-bottom: 8px; list-style: none; border: 1px solid #30363d;">
    ✉️ تواصل معي
  </summary>
  <div style="padding: 15px; background: #0d1117; border-left: 3px solid #f7df1e; border-radius: 0 0 8px 8px; margin-top: -8px; margin-bottom: 15px;" align="center">
    <p dir="rtl">يسعدني دائماً التعاون في مشاريع إبداعية وتطوير أفكار برمجية جديدة.</p>
    <a href="https://linkedin.com" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" fill="#0077B5" /></a>
    <a href="https://instagram.com" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
  </div>
</details>
