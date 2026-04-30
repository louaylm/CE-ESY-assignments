 Circular Buffer-Assignment1
 Description
هذا المشروع عبارة عن تنفيذ Circular Buffer (المخزن الدائري) بلغة C.  
البرنامج يقوم بتخزين اسم المستخدم بعد إضافة CE-ESY ثم يعيد قراءته من المخزن وعرضه.
Features
- تهيئة المخزن
- الكتابة داخل الـ buffer
- القراءة من الـ buffer
- التعامل مع:
 - Overflow 
  - Underflow 

How it works
1. المستخدم يدخل اسمه
2. يتم إضافة  CE-ESY إلى الاسم
3. يتم تخزين الأحرف داخل الـ Circular Buffer
4. يتم قراءة الأحرف وعرضها
5. التأكد أن المخزن أصبح فارغ
 Normal Run
عند استخدام حجم مناسب للـ buffer:
<img width="1242" height="786" alt="success" src="https://github.com/user-attachments/assets/5a25657a-72ef-44fc-93d3-41a685beb060" />


Overflow Case
عند استخدام حجم صغير للـ buffer يظهر خطأ overflow:

<img width="1279" height="765" alt="overflow" src="https://github.com/user-attachments/assets/a6da401f-47ea-4466-9f90-aea01444b9d0" />

 Author
 لؤي العبدالله الحماده
