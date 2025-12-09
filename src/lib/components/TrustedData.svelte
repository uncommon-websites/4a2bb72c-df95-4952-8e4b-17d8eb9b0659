<script>
    const partners = [
        { name: "SAP", icon: "S", color: "bg-blue-600" },
        { name: "Oracle NetSuite", icon: "O", color: "bg-red-600" },
        { name: "Microsoft Dynamics", icon: "M", color: "bg-blue-500" },
        { name: "QuickBooks", icon: "Q", color: "bg-green-600" },
        { name: "Sage", icon: "S", color: "bg-green-700" },
        { name: "Epicor", icon: "E", color: "bg-blue-700" },
        { name: "Infor", icon: "I", color: "bg-red-700" },
        { name: "Acumatica", icon: "A", color: "bg-purple-600" },
        { name: "Zendesk", icon: "Z", color: "bg-gray-900" },
        { name: "Salesforce", icon: "S", color: "bg-blue-400" },
        { name: "Shopify", icon: "S", color: "bg-green-500" },
        { name: "Custom ERP Systems", icon: "🔧" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">Pre-Built Integrations</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                Commerce Systems connects seamlessly with leading ERP and business platforms. Our pre-built connectors eliminate integration complexity, so you can start automating workflows in days, not months.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each partners as partner}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${partner.color ? partner.color : 'bg-gray-200 text-gray-600'}`}>
                        {partner.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{partner.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
