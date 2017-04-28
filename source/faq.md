---
title: FAQ
permalink: /faq/
slug: faq
description: Frequently Asked Questions
---

{::comment}
This is an abbreviation definition
{:/comment}

*[EVR CP]: Enhanced Video Renderer (custom presenter)

# FAQ
{:.no_toc}

<div class="alert alert-info" role="alert">
    <h4><span class="fa fa-info-circle" aria-hidden="true"></span> Note</h4>
    <p>
        <a href="https://github.com/mpc-hc/mpc-hc.org" class="alert-link">Help us add more information to this page</a>.
   </p>
</div>

---

## Contents
{:.no_toc}

* Comment to trigger ToC generation
{:toc}

---

### What are the requirements for MPC-HC?

In order to run MPC-HC you must have an SSE capable CPU. MPC-HC will work on
Windows<sup>&reg;</sup> XP Service Pack 3, Vista, 7, 8, 8.1 and 10, both 32-bit (x86) and 64-bit (x64).

### How can I check the validity of the binaries?

See the relevant [news post](/2013/02/25/binaries-are-signed/).

### MPC-HC just crashed, what can I do?

See our [Crash Reporter](/crash-reporter/) page for more information.

### My picture is up-side down, how do I fix it?

Try updating your video card drivers.

### How can I rotate a video?

Make sure you are using a renderer that supports rotation, like EVR CP or Sync Renderer;
you should see a green tick for the selected renderer in **Options &rarr; Output**.

<div class="row gallery">
    <div class="col-xs-12 col-sm-4 text-center">
        <a class="thumbnail" href="/assets/img/faq/options-output.png" title="Options &rarr; Output tab">
            <img class="defer" src="data:image/svg+xml;charset=utf-8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20xmlns%3Axlink%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxlink%22%20viewBox%3D%220%200%20300%20200%22%3E%3Cdefs%3E%3Csymbol%20id%3D%22a%22%20viewBox%3D%220%200%2090%2066%22%20opacity%3D%22.3%22%3E%3Cpath%20d%3D%22M85%205v56H5V5h80m5-5H0v66h90V0z%22%2F%3E%3Ccircle%20cx%3D%2218%22%20cy%3D%2220%22%20r%3D%226%22%2F%3E%3Cpath%20d%3D%22M56%2014L37%2039l-8-6-17%2023h67z%22%2F%3E%3C%2Fsymbol%3E%3C%2Fdefs%3E%3Cuse%20width%3D%2220%25%22%20x%3D%2240%25%22%20xlink%3Ahref%3D%22%23a%22%2F%3E%3C%2Fsvg%3E" data-src="/assets/img/faq/options-output-thumb.png" width="300" height="227" alt="Options &rarr; Output tab">
            <noscript><img src="/assets/img/faq/options-output-thumb.png" width="300" height="227" alt="Options &rarr; Output tab"></noscript>
        </a>
    </div>
</div>

Then, use <kbd>Alt+1</kbd> to rotate left, <kbd>Alt+3</kbd> to rotate right, <kbd>5</kbd> to reset.
Note, that the numbers correspond to the **numpad** ones.

### Why is there suddenly a different seekbar in fullscreen?

You have accidentally enabled D3D Fullscreen, go to **Options &rarr; Output**
and disable the D3D Fullscreen checkbox.

### Why am I seeing tearing in the video?

The video display is experiencing a synchronisation issue, try enabling V-Sync by pressing <kbd>V</kbd>.
If you have more than one monitor connected make sure you extend the screen instead of duplicating it.

### Why am I seeing strange glitches in the video?

Hardware acceleration is most likely not working correctly.
Try going to **Options &rarr; Internal Filters**, click **Video decoder**,
set "Hardware decoder to use:" to "None" and then reload the video (<kbd>Ctrl+E</kbd> or manually).
If this does not solve your issue, and your video plays correctly in other
video players then please make a bug report.

### Will MPC-HC support Windows RT or Metro?

Supporting these new platforms require many changes and this is simply
not possible for us in the near future, with the current manpower.
