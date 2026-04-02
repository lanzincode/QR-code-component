<script>
  import QrCode from "./lib/components/QrCode.svelte";
  import qrCode from "./assets/image-qr-code.png";
</script>

<QrCode
  image={qrCode}
  alt="QR code linking to Frontend Mentor homepage"
  title="Improve your front-end skills by building projects"
  description="Scan the QR code to visit Frontend Mentor and take your coding skills to the next level."
/>
