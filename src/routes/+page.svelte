<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-wak-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-wak-primary)]"></span>
                        <span class="text-white text-sm font-medium">20-Minute Install</span>
                        <span class="text-gray-400 text-sm">Guaranteed</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Transform compressors into intelligent systems.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        Patented IoT sensors and predictive diagnostics that prevent unexpected failures and costly downtime. The WAK Service Management Platform helps compressor service entities efficiently manage customers and reduce overhead.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Get Started
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            View Demo
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 - Pressure Monitor -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500 uppercase">Compressor #1247</div>
                                <div class="h-8 w-20 bg-green-100 rounded text-green-700 text-xs flex items-center justify-center font-bold">HEALTHY</div>
                            </div>
                            <div class="space-y-4">
                                <div class="bg-gradient-to-br from-blue-50 to-blue-100 rounded-lg p-4">
                                    <div class="text-xs text-gray-600 mb-1">Pressure (PSI)</div>
                                    <div class="text-3xl font-bold text-blue-600">125</div>
                                    <div class="mt-2 h-1 bg-blue-200 rounded-full overflow-hidden">
                                        <div class="h-full bg-blue-500 w-4/5"></div>
                                    </div>
                                </div>
                                <div class="grid grid-cols-2 gap-3">
                                    <div class="text-xs">
                                        <div class="text-gray-500">Temperature</div>
                                        <div class="font-bold text-gray-900">185°F</div>
                                    </div>
                                    <div class="text-xs">
                                        <div class="text-gray-500">Runtime</div>
                                        <div class="font-bold text-gray-900">847 hrs</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) - Dashboard -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-[var(--color-wak-primary)] p-6">
                                <div class="flex justify-between items-center">
                                    <div class="text-white font-bold">WAK Dashboard</div>
                                    <div class="h-8 w-8 bg-white/20 rounded-full flex items-center justify-center">
                                        <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"></path></svg>
                                    </div>
                                </div>
                            </div>
                            <div class="p-6 flex-grow">
                                <div class="space-y-3">
                                    <div class="flex items-center justify-between p-3 bg-yellow-50 rounded-lg border border-yellow-200">
                                        <div class="flex items-center gap-2">
                                            <div class="w-2 h-2 rounded-full bg-yellow-500"></div>
                                            <span class="text-sm font-medium text-gray-900">Maintenance Due</span>
                                        </div>
                                        <span class="text-xs text-gray-600">2 days</span>
                                    </div>
                                    <div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                                        <div class="flex items-center gap-2">
                                            <div class="w-2 h-2 rounded-full bg-green-500"></div>
                                            <span class="text-sm font-medium text-gray-900">All Systems Normal</span>
                                        </div>
                                        <span class="text-xs text-gray-600">12 units</span>
                                    </div>
                                    <div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                                        <div class="flex items-center gap-2">
                                            <div class="w-2 h-2 rounded-full bg-blue-500"></div>
                                            <span class="text-sm font-medium text-gray-900">Active Monitoring</span>
                                        </div>
                                        <span class="text-xs text-gray-600">24/7</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 - Alert -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500 uppercase">Predictive Alert</div>
                                <div class="h-8 w-20 bg-orange-100 rounded text-orange-700 text-xs flex items-center justify-center font-bold">ACTION</div>
                            </div>
                            <div class="space-y-4">
                                <div class="bg-gradient-to-br from-orange-50 to-orange-100 rounded-lg p-4">
                                    <div class="text-xs text-gray-600 mb-1">Valve Wear Detected</div>
                                    <div class="text-xl font-bold text-orange-600">Replace in 7 days</div>
                                </div>
                                <div class="space-y-2 text-xs">
                                    <div class="flex justify-between">
                                        <span class="text-gray-600">Part Number</span>
                                        <span class="font-semibold text-gray-900">VLV-2847</span>
                                    </div>
                                    <div class="flex justify-between">
                                        <span class="text-gray-600">Est. Cost</span>
                                        <span class="font-semibold text-gray-900">$245</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by leading service providers and car wash operators</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-50 grayscale">
                    <!-- Industry Partner Logos -->
                    <div class="h-8 w-32 bg-white/10 rounded flex items-center justify-center text-white text-xs font-bold">PARTNER 1</div>
                    <div class="h-8 w-32 bg-white/10 rounded flex items-center justify-center text-white text-xs font-bold">PARTNER 2</div>
                    <div class="h-8 w-32 bg-white/10 rounded flex items-center justify-center text-white text-xs font-bold">PARTNER 3</div>
                    <div class="h-8 w-32 bg-white/10 rounded flex items-center justify-center text-white text-xs font-bold">PARTNER 4</div>
                    <div class="h-8 w-32 bg-white/10 rounded flex items-center justify-center text-white text-xs font-bold">PARTNER 5</div>
                </div>
            </div>
        </section>

        <!-- WAK Platform Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-wak-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">WAK Platform</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Intelligent compressor monitoring.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Predictive maintenance.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Blue Card with IoT Visualization -->
                    <div class="bg-gradient-to-br from-[#0EA5E9] to-[#0369A1] rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract IoT Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Sensor Dashboard -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="flex items-center justify-between mb-4">
                                    <div class="text-white/60 text-xs uppercase tracking-wider font-medium">Live Monitoring</div>
                                    <div class="w-2 h-2 rounded-full bg-green-400 animate-pulse"></div>
                                </div>
                                <div class="grid grid-cols-2 gap-4 relative z-10">
                                    <div class="bg-white/5 rounded-lg p-3">
                                        <div class="text-white/60 text-[10px] uppercase mb-1">Pressure</div>
                                        <div class="text-white font-bold text-2xl">125</div>
                                        <div class="text-white/60 text-[10px]">PSI</div>
                                    </div>
                                    <div class="bg-white/5 rounded-lg p-3">
                                        <div class="text-white/60 text-[10px] uppercase mb-1">Temp</div>
                                        <div class="text-white font-bold text-2xl">185</div>
                                        <div class="text-white/60 text-[10px]">°F</div>
                                    </div>
                                </div>
                                <div class="mt-4 h-12 flex items-end gap-1">
                                    {#each [60, 65, 58, 70, 68, 75, 72, 78] as h}
                                        <div class="w-full bg-white/20 rounded-t" style="height: {h}%"></div>
                                    {/each}
                                </div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-blue-100 flex items-center justify-center text-blue-600">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M2 11a1 1 0 011-1h2a1 1 0 011 1v5a1 1 0 01-1 1H3a1 1 0 01-1-1v-5zM8 7a1 1 0 011-1h2a1 1 0 011 1v9a1 1 0 01-1 1H9a1 1 0 01-1-1V7zM14 4a1 1 0 011-1h2a1 1 0 011 1v12a1 1 0 01-1 1h-2a1 1 0 01-1-1V4z"/></svg>
                                    </div>
                                    IoT Sensors
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-cyan-500/30 flex items-center justify-center text-cyan-200">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z"/><path fill-rule="evenodd" d="M4 5a2 2 0 012-2 3 3 0 003 3h2a3 3 0 003-3 2 2 0 012 2v11a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm9.707 5.707a1 1 0 00-1.414-1.414L9 12.586l-1.293-1.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/></svg>
                                    </div>
                                    Predictive AI
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Prevent failures before they happen.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Our patented IoT sensors continuously monitor your compressors, using predictive diagnostics to identify issues before they cause costly downtime. Keep your operations running smoothly with real-time insights and automated alerts.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">WAK Platform</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Complete visibility and control over your compressed air systems.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">From anywhere.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Explore our platform
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-wak-primary)]"></span>
                                IoT Sensors
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Predictive Diagnostics</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Service Management</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Parts Ordering</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Customer Portal</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Analytics Dashboard</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="IoT Sensors" 
                            description="Real-time monitoring at your fingertips. Our patented IoT sensors continuously track pressure, temperature, and performance metrics to give you complete visibility into compressor health."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Predictive Diagnostics" 
                            description="Stop failures before they start. Advanced AI algorithms analyze sensor data to predict maintenance needs and component failures days or weeks in advance, eliminating unexpected downtime."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Service Management Platform" 
                            description="Streamline your operations. The WAK Service Management Platform helps service entities efficiently manage customers, schedule maintenance, track service history, and reduce operational overhead."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Automated Parts Ordering" 
                            description="Never run out of critical parts. Our system automatically identifies needed parts and facilitates ordering, ensuring you have what you need when you need it."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Customer Portal" 
                            description="Transparency builds trust. Give your customers 24/7 access to their compressor performance data, maintenance schedules, and service history through an intuitive web portal."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Analytics Dashboard" 
                            description="Make data-driven decisions. Comprehensive analytics and reporting tools help you optimize performance, reduce costs, and demonstrate value to your customers."
                            icon="guard"
                            image="guard"
                        />
                    </div>
                </div>

                <!-- Installation Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-blue-100 to-cyan-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-blue-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Install in 20 minutes. Start monitoring immediately. No technical expertise required.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        Watch installation video
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by service providers and car wash operators nationwide.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Testimonial Card (Large) -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-end">
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-2xl tracking-tight">CleanWash Pro</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-wak-primary)] flex items-center justify-center text-white font-bold">+</div>
                                    <div class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
                                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <circle cx="12" cy="12" r="9" stroke="white" stroke-width="2"/>
                                            <path d="M12 6v6l4 2" stroke="white" stroke-width="2" stroke-linecap="round"/>
                                            <circle cx="12" cy="12" r="2" fill="white"/>
                                        </svg>
                                        WAK Digital
                                    </div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-4 max-w-md">
                                    "WAK Digital eliminated our unexpected downtime and saved us thousands in emergency repairs."
                                </h3>
                                <p class="text-gray-400 mb-4 max-w-md">
                                    — Mike Johnson, Owner, CleanWash Pro Car Wash
                                </p>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-blue-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <p class="text-white font-semibold mb-2">"Installation took 15 minutes. We were monitoring within the hour."</p>
                                    <p class="text-gray-400 text-sm">— Service Manager</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-12 h-12 rounded-full bg-blue-400/20 blur-xl absolute -left-2 -bottom-2"></div>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-green-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <p class="text-white font-semibold mb-2">"Predictive alerts saved us from a major failure during peak season."</p>
                                    <p class="text-gray-400 text-sm">— Car Wash Owner</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-12 h-12 rounded-full bg-green-400/20 blur-xl absolute -left-2 -bottom-2"></div>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-cyan-500/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-blue-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Deploy at scale. <span class="text-[var(--color-wak-primary)]">Reduce overhead.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Start with service entities and scale to broad adoption. Monthly subscription per connected asset with automated parts ordering and service management.
                        </p>
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                            Platform Documentation
                            <kbd class="bg-black/30 px-1.5 py-0.5 rounded text-xs text-gray-400 font-mono">D</kbd>
                        </div>
                    </div>
                </div>

                <!-- Compatibility -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        Works with all major compressor brands.<br>
                        <span class="text-gray-400">Universal compatibility.<br>No brand restrictions.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        View compatible models
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['Kaeser', 'Atlas Copco', 'Ingersoll Rand', 'Quincy', 'Sullivan', 'Champion', 'Gardner Denver', 'Sullair'] as brand}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-xl uppercase tracking-wider">{brand}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Learn about predictive maintenance and IoT.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-blue-100 to-cyan-200 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <div class="absolute inset-0 flex items-center justify-center">
                                    <div class="grid grid-cols-6 gap-4 opacity-50">
                                        {#each Array(24) as _}
                                            <svg class="w-6 h-6 text-blue-600 transform rotate-45" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                                        {/each}
                                    </div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Industry Insights</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-blue-600 transition-colors">The true cost of compressor downtime in car wash operations</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="flex gap-4">
                                    <div class="w-16 h-16 rounded-full bg-cyan-400 blur-xl opacity-80"></div>
                                    <div class="w-20 h-20 rounded-full bg-blue-400 blur-xl opacity-80"></div>
                                    <div class="w-12 h-12 rounded-full bg-sky-400 blur-xl opacity-80"></div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Industry Insights</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-blue-600 transition-colors">How predictive diagnostics prevent unexpected failures</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

