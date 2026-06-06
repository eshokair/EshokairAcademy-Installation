<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=3B6D11,639922,97C459&height=180&section=header&text=Eshokair%20Academy&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Oracle%20APEX%20Installation%20%7C%20دليل%20التثبيت%20الاحترافي&descAlignY=60&descSize=16&animation=fadeIn" width="100%" />

# ⚙️ EshokairAcademy — Installation & Setup
### إعداد بيئة Oracle Technology Stack | Oracle DB · Oracle APEX · ORDS

[![YouTube](https://img.shields.io/badge/YouTube-Eshokair--Academy-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Eshokair-Academy)
[![Playlist](https://img.shields.io/badge/▶%20Installation%20Playlist-Watch%20Now-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/playlist?list=PLiWqBB1AHOGAY-NffpkdTuk5iaoxbFs2x)
[![Oracle APEX](https://img.shields.io/badge/Oracle%20APEX-26-F80000?style=flat-square&logo=oracle&logoColor=white)](https://github.com/eshokair/EshokairAcademy-Installation)
[![Oracle DB](https://img.shields.io/badge/Oracle%20Database-26-F80000?style=flat-square&logo=oracle&logoColor=white)](https://github.com/eshokair/EshokairAcademy-Installation)
[![ORDS](https://img.shields.io/badge/ORDS-Latest-F80000?style=flat-square&logo=oracle&logoColor=white)](https://github.com/eshokair/EshokairAcademy-Installation)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-639922?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/)

</div>

---

## 📖 About This Repository &nbsp;|&nbsp; عن هذا المستودع

<table>
<tr>
<td width="50%">

### 🇬🇧 English

This is the **official installation and environment setup guide** for Eshokair Academy — a comprehensive technical reference for correctly setting up the complete **Oracle Technology Stack**: Oracle Database, Oracle APEX, and ORDS.

A correct installation is the **foundation for everything**. Skipping steps or misconfiguring components leads to hard-to-diagnose performance issues later. This guide ensures a stable, compatible, and professional environment from day one.

</td>
<td width="50%">

### 🇸🇦 بالعربية

هذا هو **الدليل الرسمي للتثبيت وإعداد بيئة العمل** في أكاديمية شقير — مرجع تقني شامل لإعداد **Oracle Technology Stack** بشكل صحيح: Oracle Database و Oracle APEX و ORDS.

التثبيت الصحيح هو **الأساس لكل شيء**. تخطي الخطوات أو الإعداد الخاطئ يؤدي إلى مشاكل أداء يصعب تشخيصها لاحقاً. هذا الدليل يضمن بيئة عمل مستقرة ومتوافقة واحترافية من اليوم الأول.

</td>
</tr>
</table>

---

## 🗺️ Installation Roadmap &nbsp;|&nbsp; خارطة طريق التثبيت

```
Step 1 ──────────────────────────────────────────────────────────────► Step 3
  │                          │                              │
  ▼                          ▼                              ▼
🗄️ Oracle Database 26    📦 Oracle APEX 26           🔗 Oracle ORDS
  Install & Configure     Install & Configure          Install & Configure
  (Foundation Layer)      (Application Layer)          (Web Access Layer)
                                                              │
                                                              ▼
                                                     ✅ Ready to Develop!
                                                     Oracle APEX accessible
                                                     via browser
```

> ⚠️ **Important:** Always follow this order — Database → APEX → ORDS. Installing out of sequence causes compatibility issues.
>
> ⚠️ **هام:** اتبع هذا الترتيب دائماً — قاعدة البيانات ← APEX ← ORDS. التثبيت بترتيب مختلف يسبب مشاكل توافق.

---

## 📋 Installation Guides &nbsp;|&nbsp; أدلة التثبيت

### 🗄️ Step 1 — Oracle Database 26

<table>
<tr><td width="30%"><b>Guide</b></td><td>Full installation and configuration of Oracle Database 26</td></tr>
<tr><td><b>الدليل</b></td><td>تثبيت وإعداد Oracle Database 26 بشكل كامل</td></tr>
<tr><td><b>Covers</b></td><td>Installation wizard, listener configuration, SID setup, user creation, DBA privileges</td></tr>
<tr><td><b>يشمل</b></td><td>معالج التثبيت، إعداد الـ Listener، إعداد الـ SID، إنشاء المستخدمين، صلاحيات DBA</td></tr>
<tr><td><b>Difficulty</b></td><td>⭐⭐ Intermediate</td></tr>
<tr><td><b>Video</b></td><td><a href="https://www.youtube.com/watch?v=D1KODcsZajo&list=PLiWqBB1AHOGAY-NffpkdTuk5iaoxbFs2x&index=3&t=4s">▶ Watch on YouTube — تهيئة قاعدة البيانات</a></td></tr>
</table>

---

### 📦 Step 2 — Oracle APEX 26

<table>
<tr><td width="30%"><b>Guide</b></td><td>Full installation and configuration of Oracle APEX 26 on top of Oracle Database</td></tr>
<tr><td><b>الدليل</b></td><td>تثبيت وتهيئة Oracle APEX 26 فوق قاعدة البيانات</td></tr>
<tr><td><b>Covers</b></td><td>APEX schema setup, workspace creation, admin configuration, compatibility checks</td></tr>
<tr><td><b>يشمل</b></td><td>إعداد الـ Schema، إنشاء الـ Workspace، إعداد المدير، فحوصات التوافق</td></tr>
<tr><td><b>Difficulty</b></td><td>⭐⭐ Intermediate</td></tr>
<tr><td><b>Video</b></td><td><a href="https://www.youtube.com/watch?v=oDVFjed8uNE&list=PLiWqBB1AHOGAY-NffpkdTuk5iaoxbFs2x&index=2&t=12s">▶ Watch on YouTube — إعداد Oracle APEX</a></td></tr>
</table>

---

### 🔗 Step 3 — Oracle ORDS

<table>
<tr><td width="30%"><b>Guide</b></td><td>Installing and configuring Oracle REST Data Services (ORDS) to enable browser access to APEX</td></tr>
<tr><td><b>الدليل</b></td><td>تثبيت وإعداد ORDS لتمكين الوصول إلى APEX عبر المتصفح</td></tr>
<tr><td><b>Covers</b></td><td>ORDS installation, database pool configuration, port setup, SSL, service startup</td></tr>
<tr><td><b>يشمل</b></td><td>تثبيت ORDS، إعداد Connection Pool، إعداد المنفذ، SSL، تشغيل الخدمة</td></tr>
<tr><td><b>Difficulty</b></td><td>⭐⭐⭐ Advanced</td></tr>
<tr><td><b>Video</b></td><td><a href="https://www.youtube.com/watch?v=AB9L_b12JO0&list=PLiWqBB1AHOGAY-NffpkdTuk5iaoxbFs2x&index=1">▶ Watch on YouTube — إعداد Oracle ORDS</a></td></tr>
</table>

---

## 🛠️ System Requirements &nbsp;|&nbsp; متطلبات النظام

<div align="center">

| Component | Minimum | Recommended |
|:---|:---:|:---:|
| RAM | 4 GB | 8 GB+ |
| Disk Space | 20 GB | 50 GB+ |
| OS | Windows 10 / Linux | Windows Server / Linux Server |
| Java | JDK 11+ | JDK 17+ |
| Browser | Any modern browser | Chrome / Firefox latest |

</div>

---

## 💡 Pro Tips &nbsp;|&nbsp; نصائح احترافية

```
✅ DO:    Always check Oracle version compatibility between DB, APEX, and ORDS
✅ DO:    Configure your Listener correctly before starting APEX installation
✅ DO:    Create a dedicated tablespace for APEX
✅ DO:    Test DB connectivity before installing ORDS
✅ DO:    Keep all installation logs for troubleshooting

❌ AVOID: Installing APEX before the database is fully configured
❌ AVOID: Using the default SYSTEM tablespace for APEX
❌ AVOID: Skipping the ORDS connection pool configuration
❌ AVOID: Ignoring firewall / port access settings
```

> 💬 **Stuck during installation?** Check the [Solving Issues repo](https://github.com/eshokair/EshokairAcademy-Solving--Issues) or comment on the YouTube video!
>
> 💬 **واجهت مشكلة أثناء التثبيت؟** راجع [مستودع حل المشكلات](https://github.com/eshokair/EshokairAcademy-Solving--Issues) أو علّق على الفيديو!

---

## 📺 Full Installation Playlist &nbsp;|&nbsp; قائمة تشغيل التثبيت

<div align="center">

[![Watch Full Playlist](https://img.shields.io/badge/▶%20Watch%20Full%20Installation%20Playlist-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/playlist?list=PLiWqBB1AHOGAY-NffpkdTuk5iaoxbFs2x)

</div>

---

## 🔗 More from Eshokair Academy &nbsp;|&nbsp; المزيد من الأكاديمية

| Repository | Description | الوصف |
|:---|:---|:---|
| [EshokairAcademy-Apps](https://github.com/eshokair/EshokairAcademy-Apps) | Full Oracle APEX app development series | سلسلة بناء تطبيقات Oracle APEX الكاملة |
| [EshokairAcademy-Solving--Issues](https://github.com/eshokair/EshokairAcademy-Solving--Issues) | Common issues & permanent fixes | المشكلات الشائعة وحلولها الدائمة |
| [Eshokair Profile](https://github.com/eshokair) | Main academy profile | الصفحة الرئيسية للأكاديمية |

---

## 👨‍🏫 About the Instructor &nbsp;|&nbsp; عن المدرب

<div align="center">

**Essam Gad Hassan Shokair** — ITIL Expert · PMP · PRINCE2 · Oracle APEX Developer

*30+ years of IT management experience — Oil & Gas · Banking · Software Development*

[![YouTube](https://img.shields.io/badge/Subscribe-Eshokair--Academy-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Eshokair-Academy)
[![GitHub](https://img.shields.io/badge/Follow-@eshokair-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/eshokair)
[![Email](https://img.shields.io/badge/Contact-Eshokair%40Gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Eshokair@Gmail.Com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=3B6D11,639922,97C459&height=100&section=footer&animation=fadeIn" width="100%" />

<sub>© Eshokair Academy — شقير للتعليم والتطوير والتدريب &nbsp;|&nbsp; All educational content rights reserved</sub>

</div>
