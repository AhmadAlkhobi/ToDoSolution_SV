# مشروع n-tier لإدارة المهام (نسخة الطالب)

## المهام المنفذة:

1. ✅ **تنفيذ ميزة حذف المهمة**:

   - تم إكمال دالة `Delete` في `TaskRepository.cs`
   - تم ربط الحذف في `TaskService.cs`
   - تم تنفيذ `DeleteTask` في `HomeController.cs`
   - تم إضافة زر "حذف" بجانب كل مهمة داخل `Index.cshtml`
   - الكوميت: `Added (Delete Task Feauture)`

2. ✅ **تنفيذ ميزة تعديل المهمة**:
   - تم تنفيذ `EditTask` (GET + POST) في `HomeController.cs`
   - تم إنشاء الصفحة `EditTask.cshtml` لتعديل المهمة
   - تم ربط زر "تعديل" بكل مهمة في `Index.cshtml`
   - تم تحديث عنوان المهمة عند الحفظ
   - الكوميت: `added edit task feauture`

## خطوات الاختبار:

- تم تشغيل المشروع باستخدام `dotnet run`
- تم التأكد من أن حذف وتعديل المهام يعملان بشكل صحيح من خلال الواجهة

## رفع المشروع:

- ✅ تم رفع المشروع على GitHub في المستودع التالي:
  [رابط المستودع](https://github.com/AhmadAlkhobi/ToDoSolution_SV.git)
