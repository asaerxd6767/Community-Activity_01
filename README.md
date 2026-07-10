# 🚀 Weekly Challenge Guide / دليل التحدي الأسبوعي

اختر لغتك المفضلة لقراءة التعليمات وسير العمل:
* [اللغة العربية (Arabic Version)](#-دليل-خطوات-العمل-باللغة-العربية)
* [English Version](#-english-step-by-step-guide)

---

## 🇸🇦 دليل خطوات العمل باللغة العربية

أهلاً بك في تحدي هذا الأسبوع! الهدف من هذا النشاط هو تطوير مهاراتك في البرمجة وحل المشكلات، بالإضافة إلى تدريبك على كيفية التعامل مع أداة Git ومنصة GitHub كأنك تعمل ضمن فريق برمجيات حقيقي.

الرجاء اتباع الخطوات التالية بدقة لضمان رفع حلك بشكل صحيح ومنظم وبدون أي تداخل مع حلول زملائك.

### 🛠️ الخطوات بالتفصيل:

#### 1️⃣ تحميل المشروع على جهازك (Clone)
افتح مبادئ الأوامر (Terminal / Git Bash) في المجلد الذي تريده على جهازك، ثم اكتب الأمر التالي لتحميل نسخة من هذا المستودع:
```bash
git clone <repository-url>
cd <repository-name>
```

*(استبدل `<repository-url>` برابط هذا المستودع، واستبدل `<repository-name>` باسم المجلد).*

#### 2️⃣ إنشاء فرع جديد باسمك (Create Branch)

**تنبيه هام:** لا تقم بالتعديل أو الكتابة على الفرع الرئيسي (`main`). يجب عليك إنشاء فرع خاص بك يحمل اسمك حتى لا تختلط الأكواد:

```bash
git checkout -b solution/your-name

```

*(استبدل `your-name` باسمك الثنائي باللغة الإنجليزية، مثلاً: `solution/ahmed-mohamed`).*

#### 3️⃣ كتابة الحل وتسمية الملف

* قم بإنشاء ملف جديد واكتب فيه كود الحل الخاص بك باللغة البرمجية التي تفضلها.
* يُفضل تسمية الملف باسمك ليكون واضحاً، مثل: `ahmed_solution.cpp` أو `ahmed_sol.dart`.

#### 4️⃣ حفظ التغييرات ورفعها (Commit & Push)

بعد التأكد من أن الكود يعمل بشكل صحيح، قم بحفظ التعديلات برفعها إلى حسابك على GitHub باستخدام الأوامر التالية بالتوالي:

```bash
git add .
git commit -m "Add [Your Name]'s solution for this week"
git push origin solution/your-name

```

*(تأكد من كتابة اسم الفرع الخاص بك بدلاً من `solution/your-name` في أمر الـ push).*

#### 5️⃣ تقديم طلب دمج الحل (Pull Request)

* توجه إلى صفحة هذا المستودع (Repository) على موقع GitHub.
* ستلاحظ ظهور شريط أصفر في الأعلى يحتوي على زر **"Compare & pull request"**، قم بالضغط عليه.
* اكتب عنواناً بسيطاً لطلبك ثم اضغط على **"Create pull request"**.
* سيقوم مشرف التحدي بمراجعة كودك ودمجه مع الفرع الرئيسي!

بالتوفيق للجميع! 🚀

---

## 🇺🇸 English Step-by-Step Guide

Welcome to this week's challenge! This activity is designed to sharpen your coding skills while giving you practical, hands-on experience with Git and GitHub workflows—mirroring how professional development teams collaborate.

Please follow these steps carefully to ensure your solution is submitted correctly without causing conflicts with others.

### 🛠️ Detailed Workflow:

#### 1️⃣ Clone the Repository

Open your Terminal, Command Prompt, or Git Bash, navigate to your preferred directory, and run the following commands to download the project:

```bash
git clone <repository-url>
cd <repository-name>

```

*(Replace `<repository-url>` with this repository's link, and `<repository-name>` with the folder name).*

#### 2️⃣ Create a New Branch

**Important:** Never write or commit code directly to the `main` branch. You must create a unique branch named after yourself to keep your work isolated:

```bash
git checkout -b solution/your-name

```

*(Replace `your-name` with your actual name, for example: `solution/john-doe`).*

#### 3️⃣ Write Your Solution

* Create a new file and write your solution in your preferred programming language.
* Name the file clearly using your name, for example: `john_solution.py` or `john_sol.cpp`.

#### 4️⃣ Commit and Push Your Changes

Once your code is verified and running successfully, save your progress and push your branch to GitHub by running:

```bash
git add .
git commit -m "Add [Your Name]'s solution for this week"
git push origin solution/your-name

```

*(Make sure to use your specific branch name instead of `solution/your-name` in the push command).*

#### 5️⃣ Submit a Pull Request (PR)

* Go to the main page of this GitHub repository.
* You will see a yellow banner at the top with a button that says **"Compare & pull request"**. Click on it.
* Add a brief title or comment if you like, then click **"Create pull request"**.
* The reviewer will check your solution, leave feedback if necessary, and merge it into the main project!

Happy Coding! 💻🔥

```

```
