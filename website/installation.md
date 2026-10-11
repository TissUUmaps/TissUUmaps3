---
title: Installation
layout: installation
aside: false
aside: false
---

<script type="application/javascript">

function resizeIFrameToFitContent( iFrame ) {

    setTimeout(()=>{
        iFrame.height = iFrame.contentWindow.document.getElementsByTagName('section')[0].scrollHeight
    }, 0);
}

window.addEventListener('DOMContentLoaded', function(e) {

    var iFrame = document.getElementById( 'iFrameDoc' );
    resizeIFrameToFitContent( iFrame );
} );

</script>

<iframe id="iFrameDoc" src="https://tissuumaps.github.io/TissUUmaps-docs/docs/intro/installation.html" style="width:100%;height:100%;"></iframe>