<a href="javascript:void(0);" onclick="copyToClipboard('[256dfb6d-03b7-4ff9-bd6c-6f05b1c111a7]')">Pagar via PIX</a>

<script>
function copyToClipboard(text) {
  var dummy = document.createElement("textarea");
  document.body.appendChild(dummy);
  dummy.value = text;
  dummy.select();
  document.execCommand("copy");
  document.body.removeChild(dummy);
  alert("O código PIX foi copiado para a área de transferência. Cole no app do seu banco para fazer o pagamento.");
}
</script>
