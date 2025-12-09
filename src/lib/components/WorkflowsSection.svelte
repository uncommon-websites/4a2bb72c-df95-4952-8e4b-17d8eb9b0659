<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Automate Operations<br />Across Your Business
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: ERP Automation -->
            <div class="group">
                <div class="mb-6 bg-gray-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-green-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">Process Purchase Orders</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 text-xs text-green-700">
                                <Check size={12} /> <span class="text-gray-600">Running workflow...</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Validating supplier data</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Updating ERP records</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Sending confirmations</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">ERP Automation</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Ezra integrates directly into your ERP system to automate purchase orders, invoicing, and data entry. Reduce manual work and eliminate errors while maintaining full control over your business processes.
                </p>
            </div>

            <!-- Card 2: Inventory Management -->
            <div class="group">
                <div class="mb-6 bg-gray-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">Low stock items across warehouses</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-gray-900 rounded flex items-center justify-center text-white text-[8px]">AI</div>
                            <span class="text-[10px] text-gray-400">Updated 2 min ago</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>SKU</div>
                                <div class="col-span-2 text-right">Stock Level</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> SKU-2847</div>
                                <div class="col-span-2 h-1.5 bg-gray-100 rounded"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> SKU-1923</div>
                                <div class="col-span-2 h-1.5 bg-gray-100 rounded w-2/3 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> SKU-4156</div>
                                <div class="col-span-2 h-1.5 bg-gray-100 rounded w-1/2 ml-auto"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Inventory Management</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Real-time inventory tracking and automated reordering across all locations. Ezra monitors stock levels, predicts demand, and syncs with your ERP to prevent stockouts and optimize warehouse operations.
                </p>
            </div>

            <!-- Card 3: Customer Support -->
            <div class="group">
                <div class="mb-6 bg-gray-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-gray-900 rounded flex items-center justify-center text-white text-[8px]">C</div>
                            <span class="text-[10px] text-gray-500">Responding to customer...</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            I've checked your order status. Your shipment left our warehouse this morning and will arrive by Friday. Here's your tracking number.
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-gray-700 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Order #45892</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-gray-700 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Tracking: 1Z999AA1...</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Customer Support</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Claire handles customer inquiries in Zendesk with instant, accurate responses. Trained on your company data and brand voice, it augments your CX team to resolve issues faster and improve satisfaction.
                </p>
            </div>
        </div>
    </div>
</section>
