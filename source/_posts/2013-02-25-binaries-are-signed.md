---
author: XhmikosR
title: Binaries are signed
---

Thanks to **[Certum](http://www.certum.eu/certum/cert,eindex_en.xml)** binaries will be digitally signed!

Starting from nightly build 1.6.6.6735 (fceef5c) the binaries are digitally
signed. You can easily verify that the file you downloaded hasn't been modified
in any way, by verifying its signature. The stable version 1.6.5 isn't signed
since I got the certificate at a later time. So for stable builds, version
1.6.6 will be the first one signed.

After downloading the files, right-click on the installer or the exe/dll files
after you extract the archive and choose *"Properties"* from the explorer's
context menu. In the properties dialog, go to the *"Signatures"* tab and verify
that the file is signed by <!--googleoff: all-->*"Fotis Zafiropoulos"*<!--googleon: all-->
and that the signature is valid. If you don't see the *"Signatures"* tab,
then the file isn't compiled by us since it's not signed, and thus you downloaded
a custom build or a potential *scam* file.

<div class="row gallery">
    <div class="col-xs-12 col-sm-4 text-center">
        <a class="thumbnail" href="/assets/img/news/properties-signature.png" title="Windows Explorer Properties Signature tab">
            <img class="defer" src="data:image/svg+xml;charset=utf-8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20xmlns%3Axlink%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxlink%22%20viewBox%3D%220%200%20300%20200%22%3E%3Cdefs%3E%3Csymbol%20id%3D%22a%22%20viewBox%3D%220%200%2090%2066%22%20opacity%3D%22.3%22%3E%3Cpath%20d%3D%22M85%205v56H5V5h80m5-5H0v66h90V0z%22%2F%3E%3Ccircle%20cx%3D%2218%22%20cy%3D%2220%22%20r%3D%226%22%2F%3E%3Cpath%20d%3D%22M56%2014L37%2039l-8-6-17%2023h67z%22%2F%3E%3C%2Fsymbol%3E%3C%2Fdefs%3E%3Cuse%20width%3D%2220%25%22%20x%3D%2240%25%22%20xlink%3Ahref%3D%22%23a%22%2F%3E%3C%2Fsvg%3E" data-src="/assets/img/news/properties-signature-thumb.png" width="300" height="241" alt="Windows Explorer Properties Signature tab">
            <noscript><img src="/assets/img/news/properties-signature-thumb.png" width="300" height="241" alt="Windows Explorer Properties Signature tab"></noscript>
        </a>
    </div>
</div>

Windows verifies the signature during installation, if UAC is enabled.
If the prompt dialog does not say that the signature is valid, cancel the
installation and download the file again from our [*downloads*](/downloads/).

<div class="row gallery">
    <div class="col-xs-12 col-sm-4 text-center">
        <a class="thumbnail" href="/assets/img/news/install-uac.png" title="Install UAC prompt">
            <img class="defer" src="data:image/svg+xml;charset=utf-8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20xmlns%3Axlink%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxlink%22%20viewBox%3D%220%200%20300%20200%22%3E%3Cdefs%3E%3Csymbol%20id%3D%22a%22%20viewBox%3D%220%200%2090%2066%22%20opacity%3D%22.3%22%3E%3Cpath%20d%3D%22M85%205v56H5V5h80m5-5H0v66h90V0z%22%2F%3E%3Ccircle%20cx%3D%2218%22%20cy%3D%2220%22%20r%3D%226%22%2F%3E%3Cpath%20d%3D%22M56%2014L37%2039l-8-6-17%2023h67z%22%2F%3E%3C%2Fsymbol%3E%3C%2Fdefs%3E%3Cuse%20width%3D%2220%25%22%20x%3D%2240%25%22%20xlink%3Ahref%3D%22%23a%22%2F%3E%3C%2Fsvg%3E" data-src="/assets/img/news/install-uac-thumb.png" width="300" height="183" alt="Install UAC prompt">
            <noscript><img src="/assets/img/news/install-uac-thumb.png" width="300" height="183" alt="Install UAC prompt"></noscript>
        </a>
    </div>
</div>
