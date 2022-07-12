<template>
    <div>
        <div class="flex flex-shrink-0">
            <div class="w-full md:w-9/12 lg:pl-32 md:pl-16 sm:pl-8 pl-4 py-5 right-cut">
                <div class="flex space-x-4">
                    <div class="flex space-x-2 z-10">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="mt-1" viewBox="0 0 16 16">
                            <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10zm0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6z"/>
                        </svg>
                        <div class="text-white">
                            Banyuwangi, Indonesia
                        </div>
                    </div>
                    <div class="flex space-x-2 z-10">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="mt-1" viewBox="0 0 16 16">
                            <path d="M2.97 1.35A1 1 0 0 1 3.73 1h8.54a1 1 0 0 1 .76.35l2.609 3.044A1.5 1.5 0 0 1 16 5.37v.255a2.375 2.375 0 0 1-4.25 1.458A2.371 2.371 0 0 1 9.875 8 2.37 2.37 0 0 1 8 7.083 2.37 2.37 0 0 1 6.125 8a2.37 2.37 0 0 1-1.875-.917A2.375 2.375 0 0 1 0 5.625V5.37a1.5 1.5 0 0 1 .361-.976l2.61-3.045zm1.78 4.275a1.375 1.375 0 0 0 2.75 0 .5.5 0 0 1 1 0 1.375 1.375 0 0 0 2.75 0 .5.5 0 0 1 1 0 1.375 1.375 0 1 0 2.75 0V5.37a.5.5 0 0 0-.12-.325L12.27 2H3.73L1.12 5.045A.5.5 0 0 0 1 5.37v.255a1.375 1.375 0 0 0 2.75 0 .5.5 0 0 1 1 0zM1.5 8.5A.5.5 0 0 1 2 9v6h1v-5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v5h6V9a.5.5 0 0 1 1 0v6h.5a.5.5 0 0 1 0 1H.5a.5.5 0 0 1 0-1H1V9a.5.5 0 0 1 .5-.5zM4 15h3v-5H4v5zm5-5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-3zm3 0h-2v3h2v-3z"/>
                        </svg>
                        <div class="text-white">
                            PT. Fajar Corp
                        </div>
                    </div>
                </div>
            </div>
            <div class="hidden md:block w-1/4 lg:pl-16 md:pl-8 sm:pl-4 pl-2 py-5 text-white left-cut">
                <a href="#">Kontak Kami</a>
            </div>
        </div>
        
        <nav class="flex flex-wrap justify-between px-4 py-8 lg:mx-28 md:mx-auto bg-white">
            <div>
                <NuxtLink to="/" class="flex items-center lg:pt-4 md:pt-4">
                    <img src="/logo.png" alt="Logo" class="h-8 w-8 mr-2">
                    <span class="lg:text-3xl md:text-xl text-lg font-black text-black">FAJAR GROUP</span>
                </NuxtLink>
            </div>

            <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 cursor-pointer md:hidden block"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                @click="handleClick"
            >
                <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M4 6h16M4 12h16M4 18h16"
                />
            </svg>

            <div :class="toggle ? '' : 'hidden'" class="w-full md:flex md:items-center md:w-auto">
                <ul v-if="!searchBar" class="md:flex md:justify-between md:pt-0">
                    <li @mouseover="dropdown_industri = true" @mouseleave="dropdown_industri = false">
                        <div class="relative    ">
                            <!-- Dropdown toggle button -->
                            <NuxtLink class="flex md:p-4 py-2" to="industri">
                                <span>Industri</span>
                                <svg class="w-5 h-5 pt-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                    <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                                </svg>
                            </NuxtLink>
                            <transition
                                enter-active-class="transition ease-out duration-300"
                                enter-class="transform opacity-0 scale-95"
                                enter-to-class="transform opacity-100 scale-100"
                                leave-active-class="transition ease-in duration-75"
                                leave-class="transform opacity-100 scale-100"
                                leave-to-class="transform opacity-0 scale-95"
                            >
                                <!-- Dropdown menu -->
                                <div v-if="dropdown_industri" class="absolute border border-t-0 rounded-b-lg bg-white p-2 w-auto z-10">
                                    <NuxtLink class="md:p-4 py-2 block" to="kehutanan">Kehutanan</NuxtLink>
                                    <NuxtLink class="md:p-4 py-2 block" to="pertanian">Pertanian</NuxtLink>
                                    <NuxtLink class="md:p-4 py-2 block" to="angkutan">Angkutan</NuxtLink>
                                </div>
                            </transition>
                        </div>
                    </li>

                    <li @mouseover="dropdown_produk = true" @mouseleave="dropdown_produk = false">
                        <div class="relative">
                            <!-- Dropdown toggle button -->
                            <NuxtLink class="flex md:p-4 py-2" to="produk">
                                <span>Produk</span>
                                <svg class="w-5 h-5 pt-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                    <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                                </svg>
                            </NuxtLink>
                            <!-- Dropdown menu -->
                            <transition
                                enter-active-class="transition ease-out duration-300"
                                enter-class="transform opacity-0 scale-95"
                                enter-to-class="transform opacity-100 scale-100"
                                leave-active-class="transition ease-in duration-75"
                                leave-class="transform opacity-100 scale-100"
                                leave-to-class="transform opacity-0 scale-95"
                            >
                                <div v-if="dropdown_produk" class="absolute border border-t-0 rounded-b-lg bg-white p-2 w-auto z-20">
                                    <NuxtLink class="md:p-4 py-2 block" to="machines">Alat</NuxtLink>
                                    <span class="flex" @mouseover="dropdown_produk_sukuCadang = true" @mouseleave="dropdown_produk_sukuCadang = false">
                                        <!-- Dropdown toggle button -->
                                        <NuxtLink class="flex md:p-4 py-2" to="sukucadang">
                                            <span>Suku Cadang</span>
                                            <svg class="w-5 h-5 pt-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                                            </svg>
                                        </NuxtLink>
                                        <transition
                                            enter-active-class="transition ease-out duration-300"
                                            enter-class="transform opacity-0 scale-95"
                                            enter-to-class="transform opacity-100 scale-100"
                                            leave-active-class="transition ease-in duration-75"
                                            leave-class="transform opacity-100 scale-100"
                                            leave-to-class="transform opacity-0 scale-95"
                                        >
                                            <!-- Dropdown menu -->
                                            <div v-if="dropdown_produk_sukuCadang" class="absolute border border-t-0 rounded-b-lg bg-white p-2 w-auto z-30 left-90ps">
                                                <NuxtLink class="md:p-4 py-2 block" to="cat-parts">Cat Parts</NuxtLink>
                                                <NuxtLink class="md:p-4 py-2 block" to="used-parts">Used Parts</NuxtLink>
                                                <NuxtLink class="md:p-4 py-2 block" to="parts-exchange">Parts Exchange</NuxtLink>
                                                <NuxtLink class="md:p-4 py-2 block" to="non-cat-parts">No Cat Parts</NuxtLink>
                                                <NuxtLink class="md:p-4 py-2 block" to="promotions">Promotions</NuxtLink>
                                            </div>
                                        </transition>
                                    </span>
                                </div>
                            </transition>
                        </div>
                    </li>

                    <li @mouseover="dropdown_layanan = true" @mouseleave="dropdown_layanan = false">
                        <div class="relative">
                            <!-- Dropdown toggle button -->
                            <NuxtLink class="flex md:p-4 py-2" to="layanan">
                                <span>Layanan</span>
                                <svg class="w-5 h-5 pt-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                    <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                                </svg>
                            </NuxtLink>
                            <transition
                                enter-active-class="transition ease-out duration-300"
                                enter-class="transform opacity-0 scale-95"
                                enter-to-class="transform opacity-100 scale-100"
                                leave-active-class="transition ease-in duration-75"
                                leave-class="transform opacity-100 scale-100"
                                leave-to-class="transform opacity-0 scale-95"
                            >
                                <!-- Dropdown menu -->
                                <div v-if="dropdown_layanan" class="absolute border border-t-0 rounded-b-lg bg-white p-2 w-auto z-40">
                                    <NuxtLink class="md:p-4 py-2 block" to="solusi-equipment-management">Solusi Equipment Management</NuxtLink>
                                    <NuxtLink class="md:p-4 py-2 block" to="machine-rebuild">Machine Rebuild</NuxtLink>
                                    <NuxtLink class="md:p-4 py-2 block" to="component-rebuild">Component Rebuild</NuxtLink>
                                    <NuxtLink class="md:p-4 py-2 block" to="preventive-maintenance-kits">Preventive Maintenance Kits</NuxtLink>
                                    <NuxtLink class="md:p-4 py-2 block" to="perawatan-perbaikan">Perawatan Perbaikan</NuxtLink>
                                    <span class="flex" @mouseover="dropdown_layanan_pelatihan = true" @mouseleave="dropdown_layanan_pelatihan = false">
                                        <!-- Dropdown toggle button -->
                                        <NuxtLink class="flex md:p-4 py-2" to="pelatihan">
                                            <span>Pelatihan</span>
                                            <svg class="w-5 h-5 pt-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                                            </svg>
                                        </NuxtLink>
                                        <transition
                                            enter-active-class="transition ease-out duration-300"
                                            enter-class="transform opacity-0 scale-95"
                                            enter-to-class="transform opacity-100 scale-100"
                                            leave-active-class="transition ease-in duration-75"
                                            leave-class="transform opacity-100 scale-100"
                                            leave-to-class="transform opacity-0 scale-95"
                                        >
                                            <!-- Dropdown menu -->
                                            <div v-if="dropdown_layanan_pelatihan" class="absolute border rounded-b-lg bg-white p-2 w-auto z-30 left-90ps">
                                                <NuxtLink class="md:p-4 py-2 block" to="pelatihan-untuk-pelanggan">Pelatihan Untuk Pelanggan</NuxtLink>
                                                <NuxtLink class="md:p-4 py-2 block" to="pusat-pelatihan">Pusat Pelatihan</NuxtLink>
                                            </div>
                                        </transition>
                                    </span>
                                </div>
                            </transition>
                        </div>
                    </li>
                    
                    <li><NuxtLink class="md:p-4 py-2 block" to="karier">Karier</NuxtLink></li>
                    
                    <li @mouseover="dropdown_tentangKami = true" @mouseleave="dropdown_tentangKami = false">
                        <div class="relative">
                            <!-- Dropdown toggle button -->
                            <NuxtLink class="flex md:p-4 py-2" to="tentangkami">
                                <span>Tentang Kami</span>
                                <svg class="w-5 h-5 pt-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                    <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                                </svg>
                            </NuxtLink>
                            <transition
                                enter-active-class="transition ease-out duration-300"
                                enter-class="transform opacity-0 scale-95"
                                enter-to-class="transform opacity-100 scale-100"
                                leave-active-class="transition ease-in duration-75"
                                leave-class="transform opacity-100 scale-100"
                                leave-to-class="transform opacity-0 scale-95"
                            >
                                <!-- Dropdown menu -->
                                <div v-if="dropdown_tentangKami" class="absolute border border-t-0 rounded-b-lg bg-white p-2 w-auto z-50">
                                    <NuxtLink class="md:p-4 py-2 block" to="visi-misi">Visi &amp; Misi</NuxtLink>
                                    <NuxtLink class="md:p-4 py-2 block" to="dokumentasi-acara">Dokumentasi Acara</NuxtLink>
                                </div>
                            </transition>
                        </div>
                    </li>
                </ul>
                <button v-if="!searchBar">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 cursor-pointer" fill="currentColor" viewBox="0 0 24 24" stroke="currentColor" @click="searchBar = !searchBar">
                        <path d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"/>
                    </svg>
                </button>
                <div v-if="searchBar" class="flex items-center justify-center text-black bg-white">
                    <div class="border rounded overflow-hidden flex">
                        <input type="text" class="px-4 py-2" placeholder="Search...">
                        <button class="flex items-center justify-center pl-2 pt-2 border-l">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 cursor-pointer" fill="currentColor" viewBox="0 0 24 24" stroke="currentColor" @click="searchBar = !searchBar">
                                <path fill-rule="evenodd" d="M13.854 2.146a.5.5 0 0 1 0 .708l-11 11a.5.5 0 0 1-.708-.708l11-11a.5.5 0 0 1 .708 0Z"/>
                                <path fill-rule="evenodd" d="M2.146 2.146a.5.5 0 0 0 0 .708l11 11a.5.5 0 0 0 .708-.708l-11-11a.5.5 0 0 0-.708 0Z"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>
        </nav>
    </div>
    
</template>

<style>
    .right-cut {
        background: green;
        position: relative;
    }
    .right-cut:before {
        z-index: 0;
        content: '';
        position: absolute;
        bottom: 0;
        right: 0;
        border-bottom: 70px solid orange;
        border-left: 70px solid green;
    }
    .left-cut {
        background: orange;
    }
    .left-90ps {
        left: 90%;
    }
</style>

<script>
export default {
    name: 'Navbar',
    data () {
        return {
            toggle: false,
            searchBar: false,
            dropdown_industri: false,
            dropdown_produk: false,
            dropdown_produk_sukuCadang: false,
            dropdown_layanan: false,
            dropdown_layanan_pelatihan: false,
            dropdown_tentangKami: false
        }
    },
    methods: {
        handleClick(e) {
            e.preventDefault();
            this.toggle = !this.toggle
        }
    }
}
</script>