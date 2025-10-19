# htmldeneme
<!DOCTYPE html>
<html lang"tr">
        <title>İlk HTML Sayfam</title>
        <meta charset="utf8">
  

    </head> 
    <style>
        body {
            background-color: rgb(97, 147, 212);
        }
    </style>

    <body>
        <form action="" method="get">
            <fieldset> 
                <legend>Giriş Yap</legend>
        <label for="Kullanıcıadı" style="color: aliceblue;">Kullanıcı Adı</label> 
        <input name="Kullanıcıadı" id="Kullanıcıadı" required type="text" style="color:pink;text-align:center ;"> <br>
        <label for="şife"  style="color:white ;>Şifre</label>
        <input name="şifre" id="şifre" required type="password" maxlength="10" minlength="6"  style="color:pink;text-align:center;> <br>
        <label for="email" id="Email"  style="color:white;>E-Mail</label>
        <input name="eposta" required type="email"  style="color:pink;text-align:center ;> <br>
            </fieldset>
        <label> 
            <input type="checkbox"  style="color:pink;text-align:center ;> Kuralları Kabul Ediyorum
        </label> <br>
        <label>
            <input type="radio" name="cinsiyet" value="Erkek">Erkek 
            </label>
        <label> 
            <input type="radio" name="cinsiyet" value="Kız">Kız
        </label> <br>
        <input type="submit" value="Gönder">
        <input type="reset" value="Sıfırla">
        <br> <br> <br>
        <label>
            <input list="diller" name="diller">
        <datalist id"diller">
            <option value="HTML">
            <option value="CSS">
            <option value="JavaScript">
       </datalist>
        </label> <br> <br>
        <textarea name="" id="" cols="20" rows="20"></textarea>
        <button name="submit">Gönder</button>
        <button name="reset">Sıfırla</button>
    </body>
</html>
<!--
    KENDİME NOT!
 (:kullanıcı adı girildi şifre girildi email girildi ilk denemem:)
 HTML İLE CSS BİRLİŞTİRİLDİ
-->
