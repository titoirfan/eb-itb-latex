Template LaTeX Dokumen Tugas Akhir/Tesis Teknik Biomedis ITB
========================================================
templat asli oleh: Petra Novandi <me@petrabarus.net>  
diperbarui oleh: [Dionesius Agung](https://github.com/dionesiusap)  
diadaptasi oleh: [Irfan Tito](https://github.com/titoirfan)

Dokumen ini merupakan templat LaTeX yang ditujukan untuk laporan
tugas akhir atau tesis di program studi Teknik Biomedis ITB. Templat ini 
penulis gunakan dalam penulisan laporan tugas akhir penulis dan dengan semangat
berbagi penulis memutuskan untuk mempublikasikan templat ini agar
dapat digunakan oleh banyak orang.

Silakan mengunduh, menggunakan, memodifikasi, dan menyebarkan
templat ini. :)


Kebutuhan
---------

Program telah diuji dalam sistem operasi Linux Ubuntu 14.04. Untuk melakukan instalasi
perangkat lunak yang dibutuhkan, eksekusi perintah berikut.

> **Update (2020/06/04)** Templat telah diuji dan berjalan dengan baik dalam OS Linux
> Ubuntu 16.04 dan 18.04.
> **Update (2020/09/28)** Templat telah diuji dan berjalan dengan baik dalam OS Linux
> Ubuntu 20.04

```
sudo apt-get -qq update && sudo apt-get install -y --no-install-recommends \
    texlive-fonts-recommended texlive-latex-extra texlive-fonts-extra \
    dvipng texlive-latex-recommended texlive-lang-other \
    texlive-bibtex-extra texlive-plain-generic biber xzdec
```

Penggunaan
----------

Templat ini telah dilengkapi oleh skrip untuk melakukan kompilasi
Makefile. Untuk melakukan kompilasi cukup eksekusi perintah berikut

```
make
```

Hasil kompilasi akan berada pada berkas `output/tesis.pdf`.

Agar menulis dokumen lebih mudah bisa juga menggunakan aplikasi tex editor seperti
[TeXstudio](https://www.texstudio.org/) atau [overleaf](https://www.overleaf.com).

Kontribusi
----------

Templat ini dapat digunakan secara gratis, akan tetapi penulis sangat
berharap adanya kritik serta saran dari pengguna untuk meningkatkan
kualitas hasil dan penggunaan templat ini.

[comment]: <> (temporary change to link biar gk bingung)
Kritik dan saran tersebut dapat dikirim melalui URL
<https://github.com/dionesiusap/if-itb-latex/issues>.

Terima Kasih
-----------

* Steven Lolong atas pemberian templat LaTeX yang asli.
* Peb Ruswono Aryan atas bantuan pelengkapan struktur dokumen.

TO DO
-----
**Feel free to drop suggestions and issues [here](https://github.com/dionesiusap/if-itb-latex/issues) (PRs are also welcome!)**

- [ ] List of Appendices format (see [issue #1](https://github.com/dionesiusap/if-itb-latex/issues/1))
