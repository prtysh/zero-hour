<script>
</script>

<div class="blob">
  <svg viewBox="0 0 800 400" xmlns="http://www.w3.org/2000/svg">
    <path
      fill="#ff3e00"
      d="M27.7,-44C39.1,-41.5,53.8,-40.5,63.2,-33.4C72.6,-26.3,76.8,-13.2,69.8,-4.1C62.8,5.1,44.5,10.1,35.6,18.1C26.8,26.2,27.3,37.2,22.9,45.6C18.5,54.1,9.3,60,0.2,59.6C-8.9,59.3,-17.8,52.8,-26,46.6C-34.3,40.3,-41.8,34.4,-41.6,26.7C-41.4,19,-33.4,9.5,-29.9,2C-26.4,-5.5,-27.4,-10.9,-30.1,-23C-32.8,-35.1,-37.3,-53.8,-32.6,-60.1C-27.9,-66.5,-13.9,-60.6,-2.9,-55.6C8.2,-50.6,16.3,-46.5,27.7,-44Z"
      transform="translate(100 100)"
    />
  </svg>
</div>

<style>
  .blob {
    position: absolute;
    width: 100%;
    z-index: -10;
    animation: move 30s ease-in-out infinite;
    transform-origin: 50% 50%;
  }

  @keyframes move {
    0% {
      transform: scale(0.5) translate(10px, -30px);
    }
    40% {
      transform: scale(0.8, 1) translate(30vw, 30vh) rotate(160deg);
    }
    80% {
      transform: scale(1.3) translate(0vw, 30vh) rotate(-20deg);
    }
    100% {
      transform: scale(1) translate(10px, -30px);
    }
  }
</style>
