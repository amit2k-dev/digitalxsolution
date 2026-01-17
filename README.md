🔴 CASE 1: PAYMENT NAHI AAYA
index.html
<script>
  const PAYMENT_RECEIVED = false;

  if (PAYMENT_RECEIVED === false) {
    window.location.replace("maintenance.html");
  }
</script>

maintenance.html
<script>
  const PAYMENT_RECEIVED = false;

  if (PAYMENT_RECEIVED === true) {
    window.location.replace("index.html");
  }
</script>


👉 Result:

Site maintenance page par rahegi

Index kabhi nahi khulegi

🟢 CASE 2: PAYMENT AA GAYA
index.html
<script>
  const PAYMENT_RECEIVED = true;

  if (PAYMENT_RECEIVED === false) {
    window.location.replace("maintenance.html");
  }
</script>

maintenance.html
<script>
  const PAYMENT_RECEIVED = true;

  if (PAYMENT_RECEIVED === true) {
    window.location.replace("index.html");
  }
</script>
