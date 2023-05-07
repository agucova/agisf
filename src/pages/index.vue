<script setup lang="ts">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div class="relative z-1 mb-20 mt-10">
    <svg class="absolute left-0 right-0 top--30 z-[-1] mx-auto h-sm max-w-[300px] w-full" viewBox="0 0 895 779" fill="none" xmlns="http://www.w3.org/2000/svg">
      <g filter="url(#filter0_f_4_246)">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M488.127 161.887C579.503 170.998 693.875 182.596 724.498 246.447C757.27 314.777 691.245 387.753 620.774 438.464C554.542 486.125 461.753 513.335 370.492 501.191C288.076 490.225 233.89 436.52 195.499 381.874C163.485 336.305 145.169 278.47 184.124 235.913C217.965 198.943 295.749 223.461 353.339 209.437C403.117 197.316 436.159 156.705 488.127 161.887Z" fill="#AB71F4" />
      </g>
      <g style="mix-blend-mode:overlay" filter="url(#filter1_f_4_246)">
        <ellipse cx="447.5" cy="483" rx="262.5" ry="114" fill="url(#paint0_linear_4_246)" />
      </g>
      <defs>
        <filter id="filter0_f_4_246" x="0.709106" y="0.0623779" width="893.803" height="665.383" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
          <feGaussianBlur stdDeviation="80.685" result="effect1_foregroundBlur_4_246" />
        </filter>
        <filter id="filter1_f_4_246" x="3" y="187" width="889" height="592" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
          <feGaussianBlur stdDeviation="91" result="effect1_foregroundBlur_4_246" />
        </filter>
        <linearGradient id="paint0_linear_4_246" x1="447.5" y1="369" x2="447.5" y2="597" gradientUnits="userSpaceOnUse">
          <stop offset="0.46875" stop-color="#34FEFE" />
          <stop offset="1" stop-color="#D9D9D9" stop-opacity="0" />
        </linearGradient>
      </defs>
    </svg>

    <p mb-2 text-xl>
      Programa
    </p>
    <h1 font-bol mb-12 text-5xl>
      AGI Safety <br> Fundamentals
    </h1>
    <p mb-12 text-2xl>
      El primer programa de <br><span font-bold>Seguridad en IA</span> en la UC.
    </p>
    <p mb-4>
      Postulaciones hasta este miércoles.
    </p>
    <div mx-auto mt-8 max-w-md flex flex-row justify-center gap-4>
      <a type="button" href="https://www.agisafetyfundamentals.com/ai-alignment-curriculum" class="btn">
        Programa
        <div text-white class="i-ic-baseline-arrow-forward" />
      </a>
      <a type="button" href="https://forms.gle/27tTFSXCdDr14Hhv9" from-blue-700 to-violet-600 bg-gradient-to-r btn>
        Postular
        <div text-white class="i-ic-baseline-arrow-forward" />
      </a>
    </div>
  </div>
  <!-- <div>
    <h2 mb-2 text-2xl font-bold>
      Sobre el programa
    </h2>
    <div class="mx-auto max-w-md w-full flex flex-col gap-4">
      <p>
        7 semanas de teoría basada en papers de DeepMind, OpenAI y Anthropic
      </p>
      <p>
        4 semanas desarrollando un proyecto de investigación guiado
      </p>
      <p>
        Charlas con expertos internacionales
      </p>
    </div>
  </div> -->
</template>
