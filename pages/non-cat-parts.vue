<template>
  <div>
    <Navbar/>
    <div class="container mx-auto lg:mb-32 md:mb-16 mb-8 px-8">
      <h2 class="lg:text-6xl text-yellow-400 font-bold lg:mb-64 md:mb-32 sm:mb-16 mb-8">FORESTRY</h2>
      <a class="bg-yellow-400 text-white lg:py-3 py-1 lg:px-6 px-2 lg:rounded-lg rounded" href="#">Request Quote</a>
    </div>
    <div class="bg-gray-300">
      <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
        <h3 class="lg:text-4xl font-bold">FORESTRY</h3>
        <div class="pt-8">
          Indonesia is gifted with vast forestry resources. Along with advances in the country’s sustainable forest governance for green environment, Indonesia’s forestry resources are classified into two segments which are Natural Forests and Timber Estate. For each segment, Trakindo can provide solutions for more effective and efficient end to end operations, from Land Preparation to Mill Yard Operation. We are ready to advance your business forward.
        </div>
      </div>
    </div>
    <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
      <h3 class="lg:text-4xl font-bold">FORESTRY VALUE CHAIN</h3>
      <div class="pt-8">
        Forestry value chain describes primary and supporting activities in Forestry industry to deliver product or service to the market. This value chain will help you choose the right Cat machines for your business needs
      </div>
      <div class="pt-8">
        <div class="flex flex-wrap border-2 border-yellow-400">
          <div class="w-full">
            <ul class="flex mb-0 list-none pb-4 flex-wrap flex-row">
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs(1)" v-bind:class="{'text-black bg-yellow-400': openTab !== 1, 'text-black bg-white': openTab === 1}">
                  TIMBER ESTATE
                </a>
              </li>
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs(2)" v-bind:class="{'text-black bg-yellow-400': openTab !== 2, 'text-black bg-white': openTab === 2}">
                  TIMBER ESTATE
                </a>
              </li>
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs(3)" v-bind:class="{'text-black bg-yellow-400': openTab !== 3, 'text-black bg-white': openTab === 3}">
                  TIMBER ESTATE
                </a>
              </li>
            </ul>
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6">
              <div class="px-4 flex-auto">
                <div class="tab-content tab-space">
                  <div v-bind:class="{'hidden': openTab !== 1, 'block': openTab === 1}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">1. Investing</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools  maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">2. Harvesting</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">3. Extraction</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">4. Loading</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">5. Hauling</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">6. Mill</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                  </div>
                  <div v-bind:class="{'hidden': openTab !== 2, 'block': openTab === 2}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">1. Investing</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools  maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">2. Harvesting</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">3. Extraction</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">4. Loading</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">5. Hauling</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">6. Mill</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                  </div>
                  <div v-bind:class="{'hidden': openTab !== 3, 'block': openTab === 3}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">1. Investing</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools  maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">2. Harvesting</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">3. Extraction</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">4. Loading</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">5. Hauling</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">6. Mill</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Prior to extract the tree from Natural Forest, the first thing must be built is access road, canal, base camp for worker and workshop for equipment and tools maintenance. PT Trakindo Utama has the best option for infrastructure preparation through Cat Hydraulic Excavator (320D2), Cat Track Type Tractors / Dozer (D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
    <hr class="bg-gray-300 p-3">
    <div class="container mx-auto lg:mb-12 md:mb-6 mb-3 lg:py-16 md:py-8 py-4 px-8">
      <div class="flex space-x-4 place-content-center">
        <div class="w-3/4 mr-2">
          <h3 class="lg:text-4xl">FINANCING</h3>
          <div class="pt-8 mb-8">
            To support our forestry customers in purchasing our Cat equipment, Trakindo can assist you in engaging with our well-known financial partners. We will ensure your business gets the best financial solution, which will be catered according to your needs and requirements in your forestry operations.
          </div>
          <a class="bg-yellow-400 text-white lg:py-3 py-1 lg:px-6 px-2 lg:rounded-lg rounded" href="#">Cat Financial</a>
        </div>
        <div class="w-3/12">
          <img class="lg:h-64 md:h-56 sm:h-44 h-32 lg:w-64 md:w-56 sm:w-44 w-32" src="https://fajarcorp.com/wp-content/uploads/2021/11/Financing_3-1-400x253.png" alt="">
        </div>
      </div>
      
    </div>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'NonCatParts',
  data () {
    return {
      title: 'Non Cat Parts - Fajar Corp',
      openTab: 1
    }
  },
  head () {
    return {
      title: this.title,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Fajar Corp - Melayani Dengan Teknologi, Mutu, dan Harga Terbaik'
        }
      ]
    }
  },
  methods: {
    toggleTabs: function(tabNumber) {
      this.openTab = tabNumber
    }
  }
}
</script>
