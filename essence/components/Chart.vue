<template>
  <div class="grid grid-cols-2 gap-8 items-center mt-6">
    <div class="flex justify-center">
      <canvas ref="chartRef" class="w-72 h-72 md:w-96 md:h-96"></canvas>
    </div>
    <div class="text-left">
      <ul class="mt-4 space-y-2 text-sm">
        <li>
          <span class="text-blue-500 font-bold">Analisi alla cieca</span>: Migliora la memoria visiva e la capacità di fotografare una posizione.
        </li>
        <li>
          <span class="text-blue-700 font-bold">Analisi post mortem</span>: Comprendi e correggi i tuoi errori.
        </li>
        <li>
          <span class="text-yellow-500 font-bold">Lettura e ricerca</span>: Scopri nuove idee e strategie studiando le partite dei grandi giocatori.
        </li>
        <li>
          <span class="text-red-500 font-bold">Puzzle e posizioni complesse</span>:
          <ul class="ml-4 space-y-1">
            <li>Pattern base</li>
            <li>Pattern complessi</li>
            <li>Strutture pedonali</li>
          </ul>
        </li>
        <li>
          <span class="text-stone-400 font-bold">Aperture</span>: Impostare la partita su binari noti, garantendo una transizione fluida verso il mediogioco.
        </li>
        <li>
          <span class="text-teal-500 font-bold">Finali</span>: Come sfruttare il potenziale dei pezzi rimasti in gioco.
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import { Chart, DoughnutController, ArcElement, Tooltip, Legend } from "chart.js";

Chart.register(DoughnutController, ArcElement, Tooltip, Legend);

export default {
  name: "CreativityChart",
  mounted() {
    const ctx = this.$refs.chartRef.getContext("2d");
    new Chart(ctx, {
      type: "doughnut",
      data: {
        labels: [
          "Analisi alla cieca",
          "Analisi post mortem",
          "Lettura e ricerca",
          "Pattern base",
          "Pattern complessi",
          "Strutture pedonali",
          "Finali",
          "Aperture",
        ],
        datasets: [
          {
            data: [11, 11, 13, 13, 13, 13, 13, 8], 
            backgroundColor: [
              "rgb(59, 130, 246)", // Blu
              "rgb(29, 78, 216)",
              "rgb(234, 179, 8)",  // Giallo              
              "rgb(252, 165, 165)", // Rosso chiaro
              "rgb(239, 68, 68)",  // Rosso
              "rgb(153, 27, 27)", // Rosso scuro
              "rgb(13, 148, 136)", // Teal
              "rgb(168 162 158)", // Stone
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
                  "Fotografia visiva della posizione.",
                  "Comprensione degli errori.",
                  "Studio delle partite dei grandi.",
                  "Imparare schemi base ricorrenti.",
                  "Gestione di combinazione di più temi. ",
                  "Conoscenza delle strutture.",
                  "Imparare manovre tecniche.",
                  "Solida base per le aperture.",
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
