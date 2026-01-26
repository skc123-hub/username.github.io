# username.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Shri Khatushyam Computers</title>

<style>
body{
  font-family: Arial, sans-serif;
  margin:0;
  background:#f5f5f5;
}

/* HEADER */
.header{
  background:white;
  text-align:center;
  padding:15px;
}
.header img{
  width:130px;
}
.header h2{
  margin:10px 0 5px;
}
.header p{
  margin:0;
  font-size:14px;
}

/* SERVICES */
.services{
  padding:15px;
}
.service-btn{
  width:100%;
  padding:14px;
  background:#0a4cff;
  color:white;
  border:none;
  font-size:17px;
  margin-top:10px;
  cursor:pointer;
  text-align:left;
}
.service-details{
  display:none;
  background:white;
  padding:12px;
  border-left:4px solid #0a4cff;
}

/* FOOTER */
.footer{
  background:#222;
  color:white;
  text-align:center;
  padding:10px;
  margin-top:20px;
}
</style>
</head>

<body>

<!-- LOGO + SHOP INFO -->
<div class="header">
  <img src="logo.png" alt="Shri Khatushyam Computers">
  <h2>Shri Khatushyam Computers</h2>
  <p>Sony Colony, Amankhedi Road, Bhikangaon</p>
</div>

<!-- SERVICES -->
<div class="services">

<button class="service-btn">PAN Card Services</button>
<div class="service-details">
  ✔ New PAN Card Apply<br>
  ✔ PAN Correction (Name, DOB)<br>
  ✔ Lost PAN Reprint<br>
  ⏱ Time: 7–10 Days<br>
  💰 Charges: As per Govt
</div>

<button class="service-btn">Aadhaar Card Services</button>
<div class="service-details">
  ✔ Aadhaar Update<br>
  ✔ Address / Mobile Update<br>
  ✔ Aadhaar Print
</div>

<button class="service-btn">MP Online Services</button>
<div class="service-details">
  ✔ Caste / Income / Domicile<br>
  ✔ Samagra / Scholarship<br>
  ✔ Govt Forms
</div>

<button class="service-btn">CSC Services</button>
<div class="service-details">
  ✔ Digital Seva Portal Work<br>
  ✔ Insurance / Pension Help
</div>

<button class="service-btn">Online Form Filling</button>
<div class="service-details">
  ✔ Govt & Private Forms<br>
  ✔ Exam / Job Forms
</div>

<button class="service-btn">Printing & Scanning</button>
<div class="service-details">
  ✔ B/W & Color Print<br>
  ✔ Scan / Lamination
</div>

</div>

<!-- FOOTER -->
<div class="footer">
  © Shri Khatushyam Computers
</div>

<!-- SCRIPT -->
<script>
document.querySelectorAll(".service-btn").forEach(btn=>{
  btn.addEventListener("click",()=>{
    const next = btn.nextElementSibling;
    next.style.display = next.style.display==="block" ? "none" : "block";
  });
});
</script>

</body>
</html>
