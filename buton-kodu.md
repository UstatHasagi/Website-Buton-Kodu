Bu kodları istediğiniz gibi değiştirebilirsiniz ama kurcalamanızı tavsiye etmiyorum. href="..." kodunun içindeki noktaları silip tıklandığında gidiceğin bağlantıyı yaz. "İstediğini Yaz" yazan yerde butonun üstünde gözüken yazıdır. Onu silip kendi istediğini yazabilirsin.

HTML SAYFASI İÇİN:

<a
        class="button"
        type="button"
        href="..."
        >İstediğini Yaz</a
      >

STYLE SAYFASI İÇİN:

.button {
  background-color: #35363A;
  width: 110px;
  height: 55px;
  padding: 10px 10px 0px;
  border: solid 5px yellow;
  border-radius: 35px;
  text-decoration: none;
  color: yellow;
  margin-top: 10px;
}
