# tr.gov.uyap.Editor

Flatpak paketi ile ilgili tum problemleri buraya issue olarak acabilirsiniz.

Tuhaf bir sekilde dagittiklari icin pardus repolarindan degil https://uyap.gov.tr/UYAP-Editor sayfasindaki en guncel versiyon pardus icin ne ise oradan almakta.

Build

```
git clone https://github.com/flathub/tr.gov.uyap.Editor && cd tr.gov.uyap.Editor
sudo apt install flatpak flatpak-builder && flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
flatpak install -y org.freedesktop.Platform/x86_64/24.08
flatpak install -y org.freedesktop.Sdk/x86_64/24.08
flatpak install -y org.freedesktop.Sdk.Extension.openjdk11/x86_64/24.08
flatpak-builder --user --install --force-clean build-dir tr.gov.uyap.Editor.yaml
```