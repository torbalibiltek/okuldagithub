# MEB Okulda Github Ayarları

## Sertifika Probleminin Çözümü

Burada çeşitli projelerimi bulabilirsiniz. Her bir proje, üzerinde çalıştığım yazılım ve uygulamalara dair detayları içeriyor. Aşağıda bu projelerimden bazılarını inceleyebilirsiniz.

### Projemin Görseli

![Proje Resmi](https://github.com/kullaniciAdi/depoadi/raw/main/proje-resmi.png)

*Bu resim, depomda bulunan bir dosyayı göstermektedir.*

## Git SSL Sertifikası Yapılandırması

Eğer Git ile SSL bağlantı hatası alıyorsanız, sistemde bir sertifika eklemeniz gerekebilir. Aşağıdaki adımları takip ederek bu hatayı çözebilirsiniz:

1. **SSL Sertifikasını İndir**: İlk olarak gerekli sertifika dosyasını edinmeniz gerekmektedir. Genellikle, `.crt` uzantılı bir dosya olacaktır.

2. **Sertifikayı Yapılandırın**:
    Komut istemcisine aşağıdaki komutu girin:

    ```bash
    git config --system http.sslCAinfo C:\MEB_SERTIFIKASI.crt
    ```

    Bu komut, Git'in sistem düzeyinde SSL sertifikasını kullanmasını sağlar.

3. **Git Yapılandırmasını Kontrol Edin**:
    Yapılandırmanın doğru olduğundan emin olmak için şu komutu çalıştırabilirsiniz:

    ```bash
    git config --list
    ```

    Bu komut, yapılandırmanızın doğru şekilde uygulandığını gösterecektir.

## İletişim

Projem hakkında soru sormak veya bana ulaşmak için aşağıdaki yöntemleri kullanabilirsiniz:

- [E-posta](mailto:email@example.com)
- [LinkedIn](https://www.linkedin.com/in/kullanici)

Teşekkürler!
