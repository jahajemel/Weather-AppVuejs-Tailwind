<template>
    <div class="text-white mb-8 w-1/4">
        <div class="places-input">
            <input type="text" class="w-full">
        </div>
        <div class="weather-container font-sans w-128 max-w-lg overflow-hidden rounded-lg bg-gray-900 shadow-lg mt-4">
            <div class="current-weather flex items-center justify-between px-6 py-8">
                <div class="flex items-center"> 
                    <div>
                        <div class="text-6xl font-semibold">8°C</div>
                        <div>Feels like 2°C</div>
                    </div>
                    <div class="mx-5">
                        <div class="font-semibold">
                            Cloudy
                        </div>
                        <div>Toronto, Canada</div>
                    </div>
                </div>
                <div> icon </div>
            </div> <!-- end current weather -->
            <div class="future-weather text-sm bg-gray-800 px-6 py-8 overflow-hidden">
                <div class="flex items-center">
                    <div class="w-1/6 text-lg text-gray-200">MON</div>
                    <div class="w-4/6 px-4 flex items-center">
                        <div>icon</div>
                        <div class="ml-3">Cloudy with a chance of showers</div>
                    </div>
                    <div class="w-1/6 text-right">
                        <div>3°C</div>
                        <div>-2°C</div>
                    </div>
                </div>
                <div class="flex items-center mt-8">
                    <div class="w-1/6 text-lg text-gray-200">MON</div>
                    <div class="w-4/6 px-4 flex items-center">
                        <div>icon</div>
                        <div class="ml-3">Cloudy with a chance of showers</div>
                    </div>
                    <div class="w-1/6 text-right">
                        <div>3°C</div>
                        <div>-2°C</div>
                    </div>
                </div>
                <div class="flex items-center mt-8">
                    <div class="w-1/6 text-lg text-gray-200">MON</div>
                    <div class="w-4/6 px-4 flex items-center">
                        <div>icon</div>
                        <div class="ml-3">Cloudy with a chance of showers</div>
                    </div>
                    <div class="w-1/6 text-right">
                        <div>3°C</div>
                        <div>-2°C</div>
                    </div>
                </div>
            </div> <!-- end future weather -->
        </div>  <!-- end weather container -->
    </div>
</template>

<script>
    export default {
        mounted() {
          this.fetchData()
        },

        methods: {
            
        }
    }
</script>  
