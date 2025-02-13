# MEB Okulda Github Ayarları

## Sertifika Probleminin Çözümü

Burada meb bağlı okullarda github kullanırken oluşan sertifika hatasının çözümünü bulabilirsiniz.

## Git SSL Sertifikası Yapılandırması

Eğer Git ile SSL bağlantı hatası alıyorsanız, sistemde bir sertifika eklemeniz gerekebilir. Aşağıdaki adımları takip ederek bu hatayı çözebilirsiniz:

1. **SSL Sertifikasını İndir**: İlk olarak gerekli sertifika dosyasını edinmeniz gerekmektedir. Genellikle, `.crt` uzantılı bir dosya olacaktır.
![MEB Sertifika Dosyası(CRT)](https://github.com/torbalibiltek/okuldagithub/mebsertifika.crt)

3. **Sertifikayı Yapılandırın**:
    Komut istemcisine aşağıdaki komutu girin:

    ```bash
    git config --system http.sslCAinfo C:\MEB_SERTIFIKASI.crt
    ```

    Bu komut, Git'in sistem düzeyinde SSL sertifikasını kullanmasını sağlar.

4. **Git Yapılandırmasını Kontrol Edin**:
    Yapılandırmanın doğru olduğundan emin olmak için şu komutu çalıştırabilirsiniz:

    ```bash
    git config --list
    ```

    Bu komut, yapılandırmanızın doğru şekilde uygulandığını gösterecektir.
### VsCode Ayarları

![Proje Resmi](https://github.com/torbalibiltek/okuldagithub/vscodeayar.png)

*Bu resim, vscode ile uzak depoya erişim için problemin çözümünü gösterir.*

## İletişim

Projem hakkında soru sormak veya bana ulaşmak için aşağıdaki yöntemleri kullanabilirsiniz:

- [E-posta](mailto:email@example.com)
- [LinkedIn](https://www.linkedin.com/in/kullanici)

Teşekkürler!
