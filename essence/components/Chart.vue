<template>
  <div class="grid grid-cols-2 gap-8 items-center mt-6">
    <div class="flex justify-center">
      <canvas ref="chartRef" class="w-72 h-72 md:w-96 md:h-96"></canvas>
    </div>
    <div class="text-left">
      <ul class="mt-4 space-y-2 text-sm">
        <li class="flex items-center space-x-2">
          <span class="inline-block px-2 py-1 text-xs font-medium text-white rounded-full bg-green-600">
            Analisi alla cieca
          </span>
          <span class="text-sm text-gray-500">Fotografia della posizione.</span>
        </li>
        <li class="flex items-center space-x-2">
          <span class="inline-block px-2 py-1 text-xs font-medium text-white rounded-full bg-green-700">
            Analisi post mortem
          </span>
          <span class="text-gray-500">Comprensione degli errori.</span>
        </li>
        <li class="flex items-center space-x-2">
          <span class="inline-block px-2 py-1 text-xs font-medium text-white rounded-full bg-green-800">
            Lettura e ricerca
          </span>
          <span class="text-gray-500">Studio delle partite commentate.</span>
        </li>
        <li class="flex items-center space-x-2">
          <span class="inline-block px-2 py-1 text-xs font-medium text-white rounded-full bg-blue-400">
            Pattern
          </span>
          <span class="text-gray-500">Schemi base e combinazione di più temi.</span>
        </li>
        <li class="flex items-center space-x-2">
          <span class="inline-block px-2 py-1 text-xs font-medium text-white rounded-full bg-blue-500">
            Strutture pedonali
          </span>
          <span class="text-gray-500">Conoscenza delle strutture.</span>
        </li>
        <li class="flex items-center space-x-2">
          <span class="inline-block px-2 py-1 text-xs font-medium text-white rounded-full bg-blue-600">
            Attività dei pezzi
          </span>
          <span class="text-gray-500">Dinamicità dei movimenti.</span>
        </li>
        <li class="flex items-center space-x-2">
          <span class="inline-block px-2 py-1 text-xs font-medium text-white rounded-full bg-blue-700">
            Sicurezza del Re
          </span>
          <span class="text-gray-500">Bilanciamento difesa e attacco.</span>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import { Chart, DoughnutController, ArcElement, Tooltip, Legend } from "chart.js";

Chart.register(DoughnutController, ArcElement, Tooltip, Legend);

export default {
  name: "PieChartStatic",
  mounted() {
    const ctx = this.$refs.chartRef.getContext("2d");
    new Chart(ctx, {
      type: "doughnut",
      data: {
        labels: [
          "Analisi alla cieca",
          "Analisi post mortem",
          "Lettura e ricerca",
          "Pattern base e complessi",
          "Strutture pedonali",
          "Attività dei pezzi",
          "Sicurezza del Re",
        ],
        datasets: [
          {
            data: [11, 11, 10, 17, 17, 17, 17],
            backgroundColor: [
              "#22c55e", // green-500
              "#16a34a", // green-600
              "#15803d", // green-700
              "#60a5fa", // blue-400
              "#3b82f6", // blue-500
              "#2563eb", // blue-600
              "#1d4ed8", // blue-700
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
          tooltip: {
            callbacks: {
              label: function (tooltipItem) {
                const descriptions = [
                  "Fotografia della posizione.",
                  "Comprensione degli errori.",
                  "Studio delle partite commentate.",
                  "Schemi base e combinazione di più temi.",
                  "Conoscenza delle strutture.",
                  "Dinamicità dei movimenti.",
                  "Difesa e protezione del Re.",
                ];
                return descriptions[tooltipItem.dataIndex];
              },
            },
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
