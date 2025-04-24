
# منصة تحليل أداء اللاعبين الناشئين باستخدام الذكاء الاصطناعي | Youth Player Performance Analysis Platform Using AI

## المقدمة | Introduction
تم تطوير هذا المشروع كجزء من مشاركتنا في مسابقة دوري سكاي للذكاء الاصطناعي، بهدف تمكين الأندية والمدارس والكشافين من تقييم أداء اللاعبين الناشئين بدقة وعدالة باستخدام تقنيات الذكاء الاصطناعي وتحليل الفيديو.
This project was developed as part of our participation in the Sky AI League competition, aiming to enable clubs, schools, and scouts to evaluate youth players' performance accurately and fairly using AI and video analysis.

## الفريق | Team
- لمى طه القحطاني | Lama Taha Alqahtani  
- رزان معيض الشلوي | Razan Muayd Alshlowi  
- رغد علي الشمري | Raghad Ali Alshammari  

## المشكلة | Problem
في كثير من البطولات، تبرز مواهب كروية ناشئة لا تحصل على فرص حقيقية بسبب غياب أدوات تقييم دقيقة وعادلة.
In many tournaments, emerging football talents do not receive real opportunities due to the lack of accurate and fair evaluation tools.

## الحل | Solution
قمنا بتطوير منصة ذكية تعتمد على تحليل الفيديو باستخدام نماذج YOLOv8 وMediaPipe لتتبع أداء اللاعبين وتصنيفهم تلقائيًا.
We developed a smart platform that uses YOLOv8 and MediaPipe to analyze video, track player performance, and classify them automatically.

## التقنيات المستخدمة | Technologies Used
- YOLOv8 (Video analysis and object detection)
- MediaPipe Pose (Pose and joint analysis)
- Python / Visual Studio Code
- Roboflow (Dataset preparation)
- Flask (Prototype web interface)

## البيانات | Data
اعتمدنا على مجموعة بيانات من Roboflow تحت اسم:
We used a dataset from Roboflow named:

**ball-player-gk-scoreboard-ref**

- تدريب | Training: 10065 صور | images  
- تحقق | Validation: 976 صور | images  
- اختبار | Testing: 231 صور | images

## آلية العمل | How it Works
1. رفع فيديو اللاعب عبر المنصة | Upload video.
2. استخراج عناصر الحركة باستخدام YOLOv8 | Extract motion with YOLOv8.
3. تحليل المفاصل باستخدام MediaPipe | Analyze joints with MediaPipe.
4. تصنيف اللاعب تلقائيًا | Auto-classification of the player.

## الاستخدامات المستقبلية | Future Use Cases
- **المدارس | Schools**: لاكتشاف المواهب مبكرًا | Early talent discovery
- **الأندية | Clubs**: تقييم الأداء قبل التعاقد | Pre-contract evaluation
- **اللاعبين | Players**: تحسين الأداء الذاتي | Self-performance improvement
- **الكشافين | Scouts**: تقليل التحيز في التقييم | Reduce evaluation bias

## رسالتنا | Our Message
نطمح لأن نكون عدسة محايدة لاكتشاف الإمكانيات الحقيقية لكل لاعب.
We aim to be a neutral lens for discovering every player’s true potential.

---

