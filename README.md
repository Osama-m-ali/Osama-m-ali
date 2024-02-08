<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>استبيان الرقابة المالية حسب معايير الانتوساي</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>استبيان الرقابة المالية حسب معايير الانتوساي</h1>
  <p>يرجى الإجابة على الأسئلة التالية بصدق ودقة.</p>
  <form action="submit.php" method="post">
    <h2>الجزء الأول: المعلومات العامة</h2>
    <label for="name">اسمك:</label>
    <input type="text" id="name" name="name" required>
    <label for="email">بريدك الإلكتروني:</label>
    <input type="email" id="email" name="email" required>
    <label for="position">منصبك:</label>
    <input type="text" id="position" name="position" required>
    <label for="organization">اسم المنظمة التي تعمل بها:</label>
    <input type="text" id="organization" name="organization" required>

    <h2>الجزء الثاني: أسئلة الاستبيان</h2>

    <h3>المعيار 1: مبادئ الرقابة المالية</h3>
    <p>يرجى تقييم مدى تطبيق مبادئ الرقابة المالية التالية في منظمتك على مقياس من 1 إلى 5، حيث 1 يعني "لا يتم تطبيقها على الإطلاق" و 5 يعني "يتم تطبيقها بشكل كامل".</p>
    <table border="1">
      <tr>
        <th>مبدأ الرقابة المالية</th>
        <th>التقييم</th>
      </tr>
      <tr>
        <td>المسؤولية</td>
        <td><input type="radio" name="responsibility" value="1"> 1</td>
        <td><input type="radio" name="responsibility" value="2"> 2</td>
        <td><input type="radio" name="responsibility" value="3"> 3</td>
        <td><input type="radio" name="responsibility" value="4"> 4</td>
        <td><input type="radio" name="responsibility" value="5"> 5</td>
      </tr>
      <tr>
        <td>النزاهة</td>
        <td><input type="radio" name="integrity" value="1"> 1</td>
        <td><input type="radio" name="integrity" value="2"> 2</td>
        <td><input type="radio" name="integrity" value="3"> 3</td>
        <td><input type="radio" name="integrity" value="4"> 4</td>
        <td><input type="radio" name="integrity" value="5"> 5</td>
      </tr>
      <tr>
        <td>الموضوعية</td>
        <td><input type="radio" name="objectivity" value="1"> 1</td>
        <td><input type="radio" name="objectivity" value="2"> 2</td>
        <td><input type="radio" name="objectivity" value="3"> 3</td>
        <td><input type="radio" name="objectivity" value="4"> 4</td>
        <td><input type="radio" name="objectivity" value="5"> 5</td>
      </tr>
      <tr>
        <td>المسؤولية المهنية</td>
        <td><input type="radio" name="professionalism" value="1"> 1</td>
        <td><input type="radio" name="professionalism" value="2"> 2</td>
        <td><input type="radio" name="professionalism" value="3"> 3</td>
        <td><input type="radio" name="professionalism" value="4"> 4</td>
        <td><input type="radio" name="professionalism" value="5"> 5</td>
      </tr>
    </table>

    <button type="submit">إرسال الاستبيان</button>
  </form>
</
