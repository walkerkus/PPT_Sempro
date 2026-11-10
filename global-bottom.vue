<template>
  <footer
    v-if="$slidev.nav.currentPage !== 1 && $slidev.nav.currentPage !== $slidev.nav.total"
    class="absolute bottom-3 left-6 right-6 flex justify-between items-center text-xs text-gray-400 font-sans border-t border-gray-500/15 pt-2"
  >
    <div class="truncate max-w-sm text-gray-400/80">
      Sidang Skripsi • Sistem Rekomendasi Berbasis AI
    </div>
    <div class="font-mono bg-gray-500/10 px-2 py-0.5 rounded text-gray-400">
      {{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }}
    </div>
  </footer>
</template>

