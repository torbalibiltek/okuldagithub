# MEB Okulda Github Ayarları

## Sertifika Probleminin Çözümü

Burada meb bağlı okullarda github kullanırken oluşan sertifika hatasının çözümünü bulabilirsiniz.

## Git SSL Sertifikası Yapılandırması

Eğer Git ile SSL bağlantı hatası alıyorsanız, sistemde bir sertifika eklemeniz gerekebilir. Aşağıdaki adımları takip ederek bu hatayı çözebilirsiniz:

1. **SSL Sertifikasını İndir**: İlk olarak gerekli sertifika dosyasını edinmeniz gerekmektedir. Genellikle, `.crt` uzantılı bir dosya olacaktır.
[Dosyayı İndir](https://github.com/torbalibiltek/okuldagithub/raw/main/MEB_SERTIFIKASI.zip)


3. **Sertifikayı Yapılandırın**:
    Komut istemcisine aşağıdaki komutu girin:
    Komut istemcisi penceresini yönetici olarak çalıştırın.
   
    ```bash
    git config --system http.sslCAinfo C:\MEB_SERTIFIKASI.crt
    ```

    Bu komut, Git'in sistem düzeyinde SSL sertifikasını kullanmasını sağlar.

5. **Git Yapılandırmasını Kontrol Edin**:
    Yapılandırmanın doğru olduğundan emin olmak için şu komutu çalıştırabilirsiniz:

    ```bash
    git config --list
    ```

    Bu komut, yapılandırmanızın doğru şekilde uygulandığını gösterecektir.
### VsCode Ayarları
Aşağıdaki resimdeki ayarları vscode üzerinden gerçekleştirin. Sonrasında vscode kullanarak uzak depoları kullanabilirsiniz.

![Proje Resmi](https://github.com/torbalibiltek/okuldagithub/raw/main/vscodeayar.png)

*Bu resim, vscode ile uzak depoya erişim için problemin çözümünü gösterir.*

## Sonuç

Hepsi bu kadar, iyi çalışmalar!
