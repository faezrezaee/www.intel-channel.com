# www.intel-channel.com
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
	<div class="navbar">
  <ul class="menu">
    <li>
      <a href="#link1"></a>
    </li>
    <li>
      <a href="#link2">درباره ما</a>
    </li>
    <li>
      <a href="#link3">ثبت نام</a>
        <li>
          <a href="link3-1"> آموزش ها</a>
        </li>
        <li>
          <a href="link3-2"> مطالب</a>
        </li>
      </ul>
</div>

	   <meta http-equiv="content-type" content="text/html; charset=utf-8" />
   <link rel="stylesheet" href="font-awesome-4.7.0/font-awesome-4.7.0/css/font-awesome.css" />
   <link rel="stylesheet" href="tester.css" />
   <title>Tanasan.com</title>
   <style >
   	
2
3
   .navbar {background: #797979;direction: rtl;text-align: right;padding-right: 30px;}
  ul.menu li { display: inline-block;list-style: none; }
  ul.menu li a { display:inline-block;padding: 12px;color: #fff;text-decoration: none; }
         margin: 0px;
         padding: 0px;
         box-sizing: border-box;
      }
      section {
         margin: 50px;
      }
      input {
         position: relative;
         background-color: #fff;
         padding: 17px 10px;
         border-radius: 4px;
         border: none;
         outline: none;
         text-align: right;
         width: 350px;
         color: #858585;
         font-size: 15px;
         box-shadow: 1px 1px 7px 0px #c9c9ca;
      }
      ::placeholder {
         font-size: 15px;
         color: #858585;
      }
      button {
         border: none;
         outline: none;
         background-color: RoyalBlue;
         color: #fff;
         padding: 8px 20px;
         border-radius: 4px;
         position: absolute;
         right: 520px;
         left: 55px;
         margin-top: 4px;
         border: 3px solid #e8c40e;
         transition: background-color 0.3s;
      }
      button:hover {
         cursor: pointer;
         background-color: #e8c40e !important;
      }
   </style>
</head>
<body>

   <section>
      <input type="text" placeholder="جستجو در سایت..." id="ValueInput">
      <button onclick="setTimeout(Atbar,1000)" id="btn">جستجو</button>
   </section>

<script>
   var button = document.getElementById("btn");
   button.addEventListener("click", function() {
      button.style.backgroundColor = "RoyalBlue";
   });

   var input = document.getElementById("ValueInput");
   function Atbar() {
      if (input.value == null || input.value == "") {
         alert("فیلد خالی میباشد.");
      }
   }
  <meta charset="UTF-10">
  <title>Aco Source</title>
  <link rel="stylesheet" href="./style.css">

</head>

<button class="bubbly-button">دانلود</button>

  <script  src="./script.js"></script>
<h2>تمام مطالب<h2>
</body>
</html>
