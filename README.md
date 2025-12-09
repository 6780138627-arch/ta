<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>RSB Activity Transcript System</title>
  <style>
    body { font-family: sans-serif; background:#f5f5f5; margin:0; }
    header { background:#00695c; color:#fff; padding:10px 20px; }
    .container { max-width:900px; margin:0 auto; padding:20px; }
    h1 { margin:5px 0; }
    .role-grid {
      display:grid;
      grid-template-columns: repeat(3, 1fr);
      gap:15px;
      margin-top:20px;
    }
    .card {
      background:#fff;
      border-radius:10px;
      padding:15px;
      border:1px solid #ddd;
    }
    .card h2 { font-size:18px; margin-top:0; }
    .card p { font-size:14px; color:#555; }
    .btn {
      display:inline-block;
      margin-top:10px;
      padding:6px 12px;
      font-size:14px;
      border-radius:20px;
      border:none;
      background:#00695c;
      color:#fff;
      text-decoration:none;
    }
    footer { font-size:12px; color:#777; text-align:center; padding:15px 0; }
    @media (max-width:700px) {
      .role-grid { grid-template-columns:1fr; }
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>RSB Activity Transcript System</h1>
      <div>ระบบต้นแบบการจัดการข้อมูลกิจกรรมของนักเรียน โรงเรียนรัตนโกสินทร์สมโภชบางเขน</div>
    </div>
  </header>

  <div class="container">
    <h2>เลือกหน้าที่ต้องการใช้งาน (Mockup)</h2>
    <p>หน้านี้เป็นหน้าโฮมสำหรับเดโม แยกการทำงานออกเป็น 3 ส่วนหลัก: นักเรียน, ครูผู้รับผิดชอบ, และหน้าดูทรานสคริปกิจกรรม</p>

    <div class="role-grid">
      <div class="card">
        <h2>นักเรียน</h2>
        <p>บันทึกการเข้าร่วมกิจกรรม และดูชั่วโมงกิจกรรมสะสมของตนเอง</p>
        <a href="student.html" class="btn">ไปยังหน้าของนักเรียน</a>
      </div>
      <div class="card">
        <h2>ครูผู้รับผิดชอบ / ครูที่ปรึกษา</h2>
        <p>ตรวจสอบและรับรองกิจกรรมของนักเรียนแบบออนไลน์</p>
        <a href="teacher.html" class="btn">ไปยังหน้าของครู</a>
      </div>
      <div class="card">
        <h2>ทรานสคริปกิจกรรม</h2>
        <p>ดูตัวอย่างรายงานผลกิจกรรมในรูปแบบ Transcript ของนักเรียน</p>
        <a href="transcript.html" class="btn">ดูตัวอย่าง Transcript</a>
      </div>
    </div>
  </div>

  <footer>
    โปรเจกต์รายวิชา 2747745 เทคโนโลยีสารสนเทศและการสื่อสารเพื่อการบริหารการศึกษา
  </footer>
</body>
</html>
