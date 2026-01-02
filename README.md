# UYAP Editor

___Edit and view UDF documents___

UYAP Document Editor is a document viewer for the Turkish Ministry of Justice's legal document format (UDF).

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub tr.gov.uyap.Editor
flatpak run tr.gov.uyap.Editor
```

## Building

```bash
git clone git@github.com:flathub/tr.gov.uyap.Editor.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install tr.gov.uyap.Editor.yaml
```

