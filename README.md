
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Instagram UI Practice</title>
<style>
body{
  font-family: Arial,sans-serif;
  background:#fafafa;
  display:flex;
  justify-content:center;
  align-items:center;
  height:100vh;
}
.box{
  background:white;
  border:1px solid #ddd;
  padding:30px;
  width:300px;
  text-align:center;
}
.logo{
  font-size:36px;
  font-weight:bold;
  margin-bottom:20px;
}
input{
  width:100%;
  padding:10px;
  margin:6px 0;
  border:1px solid #ccc;
  border-radius:6px;
}
button{
  width:100%;
  padding:10px;
  background:#0095f6;
  color:white;
  border:none;
  border-radius:6px;
}
</style>
</head>
<body>

<div class="box">
  <div class="logo">Instagram</div>
  <input type="text" placeholder="Phone, username or email">
  <input type="password" placeholder="Password">
  <button>Log in</button>
</div>

</body>
</html>
