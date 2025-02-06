<template>
  <div class="grid grid-cols-2 gap-8 items-center mt-6">
    <div class="flex justify-center">
      <canvas ref="chartRef" class="w-72 h-72 md:w-96 md:h-96"></canvas>
    </div>
    <div class="text-left">
      <div class="grid grid-cols-3 gap-2 text-xs">
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-green-500">
          Pedone isolato
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-green-600">
          Struttura Carlsbad
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-green-700">
          Stonewall
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-green-800">
          Struttura Caro-Kann
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-green-900">
          Struttura Slava
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-blue-600">
          Siciliana aperta
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-blue-700">
          Siciliana chiusa
        </span>        
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-yellow-600">
          Italiana
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-yellow-700">
          Spagnola
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-yellow-800">
          Russa
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-purple-300">
          Benko
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-purple-500">
          Francese
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-purple-700">
          Benoni
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-stone-500">
          Est Indiana
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-cyan-600">
          Pedoni sospesi
        </span>
        <span class="inline-block px-2 py-1 font-medium text-white rounded-full bg-cyan-800">
          Panov
        </span>
      </div>
    </div>
  </div>
</template>

<script>
import { Chart, DoughnutController, ArcElement, Tooltip, Legend } from "chart.js";

Chart.register(DoughnutController, ArcElement, Tooltip, Legend);

export default {
  name: "PieChart",
  mounted() {
    const ctx = this.$refs.chartRef.getContext("2d");
    new Chart(ctx, {
      type: "doughnut",
      data: {
        labels: [
          "Pedone isolato",
          "Struttura Carlsbad",
          "Stonewall",
          "Struttura Caro-Kann",
          "Struttura Slava",
          "Siciliana aperta",
          "Siciliana chiusa",          
          "Italiana",
          "Spagnola",
          "Russa",
          "Benko",
          "Francese",
          "Benoni",
          "Est Indiana",
          "Pedoni sospesi",
          "Panov"
        ],
        datasets: [
          {
            data: new Array(16).fill(100 / 16),
            backgroundColor: [
              "#22c55e", "#16a34a", "#15803d", "#166534", "#14532D",
              "#2563eb", "#1d4ed8",
              "#d97706", "#b45309",  "#854D0E", 
              "#D8B4FE", "#A855F7", "#7e22ce",
              "#78716C", 
              "#0891B2", "#155E75"
            ],
            hoverOffset: 6,
          },
        ],
      },
      options: {
        cutout: "50%",
        plugins: {
          legend: {
            display: false,
          },
        },
      },
    });
  },
};
</script>

<style scoped>
canvas {
  max-width: 300px;
  max-height: 300px;
}
</style>
