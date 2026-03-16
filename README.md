<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>STEPCON Abstract Submission Form</title>
<style>
body{
font-family: Arial, Helvetica, sans-serif;
background:#f2f5f9;
margin:0;
padding:0;
}

.header{
background:#0b5ed7;
color:white;
padding:20px;
text-align:center;
}

.container{
max-width:800px;
margin:30px auto;
background:white;
padding:30px;
border-radius:10px;
box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

h2{
margin-top:0;
}

label{
font-weight:bold;
display:block;
margin-top:15px;
}

input, select, textarea{
width:100%;
padding:10px;
margin-top:5px;
border-radius:5px;
border:1px solid #ccc;
font-size:14px;
}

textarea{
resize:vertical;
}

.row{
display:grid;
grid-template-columns:1fr 1fr;
gap:15px;
}

button{
margin-top:25px;
background:#0b5ed7;
color:white;
border:none;
padding:12px;
font-size:16px;
border-radius:6px;
cursor:pointer;
}

button:hover{
background:#094bb5;
}

.footer{
text-align:center;
font-size:13px;
color:#666;
margin-top:20px;
}

@media(max-width:700px){
.row{
grid-template-columns:1fr;
}
}
</style>
</head>

<body>

<div class="header">
<h1>STEPCON II</h1>
<p>Abstract Submission Form</p>
</div>

<div class="container">

<form action="https://formspree.io/f/yourID" method="POST">

<h2>Author Information</h2>

<label>Full Name</label>
<input type="text" name="name" required>

<div class="row">
<div>
<label>Email Address</label>
<input type="email" name="email" required>
</div>

<div>
<label>Phone Number</label>
<input type="tel" name="phone">
</div>
</div>

<label>Institution / Organization</label>
<input type="text" name="institution">

<label>Department</label>
<input type="text" name="department">

<h2>Abstract Details</h2>

<label>Abstract Title</label>
<input type="text" name="title" required>

<label>Presentation Type</label>
<select name="presentation_type">
<option>Oral Presentation</option>
<option>Poster Presentation</option>
</select>

<label>Theme / Category</label>
<select name="theme">
<option>Pharmaceutical Sciences</option>
<option>Clinical Pharmacy</option>
<option>Pharmacology</option>
<option>Pharmaceutics</option>
<option>Pharmaceutical Chemistry</option>
</select>

<label>Co-Authors (if any)</label>
<textarea name="coauthors" rows="3"></textarea>

<label>Abstract (Max 300 words)</label>
<textarea name="abstract" rows="6" required></textarea>

<label>Upload Abstract File (PDF)</label>
<input type="file" name="file">

<button type="submit">Submit Abstract</button>

</form>

<div class="footer">
<p>STEPCON Conference Submission Portal</p>
</div>

</div>

</body>
</html>
