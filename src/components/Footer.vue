<template>
<footer class="footer">
        <div class="footer1">
          <p>România</p>
        </div>
  
        <div class="footer2">
          <ul class="footer2L">
            <li><a href="https://about.google/?utm_source=google-RO&utm_medium=referral&utm_campaign=hp-footer&fg=1" class="footerLink">Despre</a></li>
            <li><a href="https://ads.google.com/intl/ro_ro/home/?subid=ww-ww-et-g-awa-a-g_hpafoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpafooter&fg=1" class="footerLink">Publicitate</a></li>
            <li><a href="https://www.google.com/services/?subid=ww-ww-et-g-awa-a-g_hpbfoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpbfooter&fg=1#?modal_active=none" class="footerLink">Companii</a></li>
            <li><a href="https://www.google.com/search/howsearchworks/?fg=1" class="footerLink">Cum funcționează Căutarea</a></li>
          </ul>
    
          <ul class="footer2R">
            <li><a href="https://policies.google.com/privacy?hl=ro&fg=1" class="footerLink">Confidențialitate</a></li>
            <li><a href="https://policies.google.com/terms?hl=ro&fg=1" class="footerLink">Termeni</a></li>
            <li><a href="#" class="footerLink">Setări</a></li>
          </ul>
        </div>
      </footer>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    msg: String
  }
}
</script>

<style>
@import '/src/styles/footer.css';
</style>