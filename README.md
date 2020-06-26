<!DOCTYPE html>
<head>
  <title>Form Order WhatsApp</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    * {
      margin: 0px;
      padding: 0px;
      box-sizing: border-box;
    }
    body,
    html {
      height: 100%;
      font-family: Helvetica, sans-serif;
    }
    /*---------------------------------------------*/
    a {
      font-family: Helvetica, sans-serif;
      font-size: 14px;
      line-height: 1.7;
      color: #666666;
      margin: 0px;
      transition: all 0.4s;
      -webkit-transition: all 0.4s;
      -o-transition: all 0.4s;
      -moz-transition: all 0.4s;
    }
    a:focus {
      outline: none !important;
    }
    a:hover {
      text-decoration: none;
    }
    /*---------------------------------------------*/
    h1,
    h2,
    h3,
    h4,
    h5,
    h6 {
      margin: 0px;
    }
    p {
      font-family: Helvetica, sans-serif;
      font-size: 14px;
      line-height: 1.7;
      color: #666666;
      margin: 0px;
    }
    ul,
    li {
      margin: 0px;
      list-style-type: none;
    }
    /*---------------------------------------------*/
    input {
      outline: none;
      border: none;
    }
    textarea {
      outline: none;
      border: none;
    }
    textarea:focus,
    input:focus {
      border-color: transparent !important;
    }
    input:focus::-webkit-input-placeholder {
      color: transparent;
    }
    input:focus:-moz-placeholder {
      color: transparent;
    }
    input:focus::-moz-placeholder {
      color: transparent;
    }
    input:focus:-ms-input-placeholder {
      color: transparent;
    }
    textarea:focus::-webkit-input-placeholder {
      color: transparent;
    }
    textarea:focus:-moz-placeholder {
      color: transparent;
    }
    textarea:focus::-moz-placeholder {
      color: transparent;
    }
    textarea:focus:-ms-input-placeholder {
      color: transparent;
    }
    input::-webkit-input-placeholder {
      color: #adadad;
    }
    input:-moz-placeholder {
      color: #adadad;
    }
    input::-moz-placeholder {
      color: #adadad;
    }
    input:-ms-input-placeholder {
      color: #adadad;
    }
    textarea::-webkit-input-placeholder {
      color: #adadad;
    }
    textarea:-moz-placeholder {
      color: #adadad;
    }
    textarea::-moz-placeholder {
      color: #adadad;
    }
    textarea:-ms-input-placeholder {
      color: #adadad;
    }
    /*---------------------------------------------*/
    button {
      outline: none !important;
      border: none;
      background: transparent;
    }
    button:hover {
      cursor: pointer;
    }
    iframe {
      border: none !important;
    }
    /*---------------------------------------------*/
    .container {
      max-width: 1200px;
    }
    /*//////////////////////////////////////////////////////////////////
[ Contact ]*/
    .container-contact100 {
      width: 100%;
      min-height: 100vh;
      display: -webkit-box;
      display: -webkit-flex;
      display: -moz-box;
      display: -ms-flexbox;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      padding: 15px;
      background: #a64bf4;
      background: -webkit-linear-gradient(45deg, #00dbde, #fc00ff);
      background: -o-linear-gradient(45deg, #00dbde, #fc00ff);
      background: -moz-linear-gradient(45deg, #00dbde, #fc00ff);
      background: linear-gradient(45deg, #00dbde, #fc00ff);
    }
    .wrap-contact100 {
      width: 500px;
      background: #fff;
      border-radius: 10px;
      overflow: hidden;
      padding: 42px 55px 45px 55px;
    }
    /*------------------------------------------------------------------
[ Form ]*/
    .contact100-form {
      width: 100%;
    }
    .contact100-form-title {
      display: block;
      font-family: Helvetica, sans-serif;
      font-size: 35px;
      font-weight: 900;
      color: #333333;
      line-height: 1.2;
      text-align: center;
      padding-bottom: 44px;
    }
    /*------------------------------------------------------------------
[ Input ]*/
    .wrap-input100 {
      width: 100%;
      position: relative;
      border-bottom: 2px solid #d9d9d9;
      padding-bottom: 13px;
      margin-bottom: 27px;
    }
    .label-input100 {
      font-family: Helvetica, sans-serif;
      font-size: 13px;
      color: #666666;
      line-height: 1.5;
      padding-left: 5px;
    }
    .input100 {
      display: block;
      width: 100%;
      background: transparent;
      font-family: Helvetica, sans-serif;
      font-size: 18px;
      color: #333333;
      line-height: 1.2;
      padding: 0 5px;
    }
    .focus-input100 {
      position: absolute;
      display: block;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      pointer-events: none;
    }
    .focus-input100::before {
      content: "";
      display: block;
      position: absolute;
      bottom: -2px;
      left: 0;
      width: 0;
      height: 2px;
      -webkit-transition: all 0.4s;
      -o-transition: all 0.4s;
      -moz-transition: all 0.4s;
      transition: all 0.4s;
      background: #7f7f7f;
    }
    /*---------------------------------------------*/
    input.input100 {
      height: 40px;
    }
    textarea.input100 {
      min-height: 110px;
      padding-top: 9px;
      padding-bottom: 13px;
    }
    .input100:focus+.focus-input100::before {
      width: 100%;
    }
    .has-val.input100+.focus-input100::before {
      width: 100%;
    }
    /*------------------------------------------------------------------
[ Button ]*/
    .container-contact100-form-btn {
      display: -webkit-box;
      display: -webkit-flex;
      display: -moz-box;
      display: -ms-flexbox;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding-top: 13px;
    }
    .wrap-contact100-form-btn {
      width: 100%;
      display: block;
      position: relative;
      z-index: 1;
      border-radius: 25px;
      overflow: hidden;
      margin: 0 auto;
    }
    .contact100-form-bgbtn {
      position: absolute;
      z-index: -1;
      width: 300%;
      height: 100%;
      background: #a64bf4;
      background: -webkit-linear-gradient(left, #00dbde, #fc00ff, #00dbde, #fc00ff);
      background: -o-linear-gradient(left, #00dbde, #fc00ff, #00dbde, #fc00ff);
      background: -moz-linear-gradient(left, #00dbde, #fc00ff, #00dbde, #fc00ff);
      background: linear-gradient(left, #00dbde, #fc00ff, #00dbde, #fc00ff);
      top: 0;
      left: -100%;
      -webkit-transition: all 0.4s;
      -o-transition: all 0.4s;
      -moz-transition: all 0.4s;
      transition: all 0.4s;
    }
    .contact100-form-btn {
      display: -webkit-box;
      display: -webkit-flex;
      display: -moz-box;
      display: -ms-flexbox;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 0 20px;
      width: 100%;
      height: 50px;
      font-family: Helvetica, sans-serif;
      font-size: 16px;
      font-weight: 700;
      color: #fff;
      line-height: 1.2;
    }
    .wrap-contact100-form-btn:hover .contact100-form-bgbtn {
      left: 0;
    }
    .contact100-form-btn i {
      -webkit-transition: all 0.4s;
      -o-transition: all 0.4s;
      -moz-transition: all 0.4s;
      transition: all 0.4s;
    }
    .contact100-form-btn:hover i {
      -webkit-transform: translateX(10px);
      -moz-transform: translateX(10px);
      -ms-transform: translateX(10px);
      -o-transform: translateX(10px);
      transform: translateX(10px);
    }
    /*------------------------------------------------------------------
[ Responsive ]*/
    @media (max-width: 576px) {
      .wrap-contact100 {
        padding: 72px 15px 65px 15px;
      }
    }
  </style>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
</head>
<body>
  <div class="container-contact100">
    <div class="wrap-contact100">
      <form class="contact100-form validate-form" id="whatsapp">
        <span class="contact100-form-title">
          Order via WA
        </span>
        <input class="tujuan" type="hidden" id="noAdmin">
        <div class="wrap-input100">
          <span class="label-input100">Nama</span>
          <label>
            <input class="input100 nama" type="text" placeholder="Masukkan nama Anda">
          </label>
          <span class="focus-input100"></span>
        </div>
        <div class="wrap-input100">
          <span class="label-input100">Alamat</span>
          <label>
            <input class="input100 nowhatsapp" type="text" placeholder="masukan alamat anda">
          </label>
          <span class="focus-input100"></span>
        </div>
        <div class="wrap-input100">
          <span class="label-input100">Type Pesanan</span>
          <label>
            <textarea class="input100 alamat" placeholder="Masukkan deskripsi atau pesanan anda"></textarea>
          </label>
          <span class="focus-input100"></span>
        </div>
        <div class="container-contact100-form-btn">
          <div class="wrap-contact100-form-btn">
            <div class="contact100-form-bgbtn"></div>
            <a class="contact100-form-btn submit">Kirim</a>
          </div>
        </div>
      </form>
    </div>
  </div>
  <script>
    //no wa admin
    $("#noAdmin").val("081313555151");
    $('.whatsapp-btn').click(function () {
      $('#whatsapp').toggleClass('toggle');
    });
    // Onclick Whatsapp Sent!
    $('#whatsapp .submit').click(WhatsApp);
    $("#whatsapp input, #whatsapp textarea").keypress(function () {
      if (event.which == 13) WhatsApp();
    });
    var reg = /^([A-Za-z0-9_\-\.])+\@([A-Za-z0-9_\-\.])+\.([A-Za-z]{2,4})$/;
    function WhatsApp() {
      var ph = '';
      if ($('#whatsapp .nama').val() == '') { // Cek Nama
        ph = $('#whatsapp .nama').attr('placeholder');
        alert('Silahkan tulis ' + ph);
        $('#whatsapp .nama').focus();
        return false;
      } else if ($('#whatsapp .nowhatsapp').val() == '') { // Cek Whatsapp
        ph = $('#whatsapp .nowhatsapp').attr('placeholder');
        alert('Silahkan tulis ' + ph);
        $('#whatsapp .nowhatsapp').focus();
        return false;
      } else if ($('#whatsapp .alamat').val() == '') { // Cek Alamat
        ph = $('#whatsapp .alamat').attr('placeholder');
        alert('Silahkan tulis ' + ph);
        $('#whatsapp .alamat').focus();
        return false;
      } else {
        // Check Device (Mobile/Desktop)
        var url_wa = 'https://web.whatsapp.com/send';
        if (/Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent)) {
          url_wa = 'whatsapp://send/';
        }
        // Get Value
        var tujuan = $('#whatsapp .tujuan').val(),
          via_url = location.href,
          nama = $('#whatsapp .nama').val(),
          nowhatsapp = $('#whatsapp .nowhatsapp').val(),
          alamat = $('#whatsapp .alamat').val();
        $(this).attr('href', url_wa + '?phone=62 ' + tujuan + '&text=Nama: ' + nama + ' %0ANo. Whatsapp: ' + nowhatsapp + '%0AAlamat: ' + alamat + ' %0A%0Avia ' + via_url);
        var w = 960,
          h = 540,
          left = Number((screen.width / 2) - (w / 2)),
          tops = Number((screen.height / 2) - (h / 2)),
          popupWindow = window.open(this.href, '', 'toolbar=no, location=no, directories=no, status=no, menubar=no, scrollbars=yes, resizable=1, copyhistory=no, width=' + w + ', height=' + h + ', top=' + tops + ', left=' + left);
        popupWindow.focus();
        return false;
      }
    }
  </script>
</body>
</html>
