<!-- Glowing, wind-blown ash text effect -->
<style>
  @keyframes windAsh {
    0% {
      opacity: 1;
      transform: translateX(0) translateY(0) scale(1);
      text-shadow: 0 0 8px rgba(54, 188, 247, 0.8), 0 0 20px rgba(54, 188, 247, 0.4);
    }
    60% {
      opacity: 0.4;
      transform: translateX(40px) translateY(-15px) scale(0.95);
      text-shadow: 0 0 4px rgba(255, 255, 255, 0.4);
    }
    100% {
      opacity: 0;
      transform: translateX(80px) translateY(-30px) scale(0.9);
      text-shadow: none;
    }
  }

  .ash-text {
    display: inline-block;
    font-family: 'Fira Code', monospace;
    font-size: 22px;
    color: #36BCF7;
    animation: windAsh 3.5s ease-out infinite;
  }
</style>

<span class="ash-text">Blowing away like glowing ash...</span>

</div>
