# SchoolManager
------------------------------------
با صحبتی که با یکی از مدارس شیراز داشتیم ، قرار شد سیستم مدیریت معلمین و دانش آموزان را برای این مدرسه پایه ریزی کنیم . طبقه گفتگو با مدیر مدرسه چیزی که مدیر در لحظه اول میخواهد این است : 
1. مدیریت دانش آموزان
2. مدیریت معلمین
3. مدیریت دروس
4. وارد کردن نمرات دانش آموزان
5. وارد کردن ورود و خروج معلمین
7. صادر کردن کارنامه دانش آموزان
8. دیدن برنامه کلاسی به نسبت هر درس یا هر کلاس یا هر معلم

## در قدم اول شما به عنوان شخص فنی باید بتوانید داده های مورد نظر هر بخش را تحلیل کرده و سیستم مورد نیاز برای هر بخش درست کنید . 

----------------------------------------------------
## راهنمایی : 
###1. Manage students : 
- Entity Student :
  - Name
  - Nationnal Id
  - Family
  - Cell-Phone
  - Phone
  - Address
  - FatherName
  - Father-Phone
- Api Student :
    - Get by Id
    - Get by national id
    - Gets by filter
        - if empty filter then get all students base pagination
    - Add a new student
    - Update a new student
    - Delete a new Student
- Test Student :
    - Write some integration test for APIS 
