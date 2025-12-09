<script>
    // Icons replaced with CSS shapes for pixel-perfect custom visuals
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                AI Agents Built for<br />Commerce Operations
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- ERP Connectors -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">ERP Connectors</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-4">
                        {#each [1, 2, 3, 4, 5, 6] as i}
                            <div class="h-10 w-10 bg-white rounded-full shadow-sm flex items-center justify-center text-gray-400">
                                <div class="h-4 w-4 bg-gray-200 rounded-sm"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Pre-built connectors for SAP, Oracle, Microsoft Dynamics, and other leading ERP systems. Start automating in days with zero custom development required.
                </p>
            </div>

            <!-- AI Agents -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">AI Agents</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px] space-y-2">
                        <div class="h-2 bg-gray-100 rounded w-1/3 mb-4"></div>
                        {#each [1, 2, 3, 4, 5] as i}
                            <div class="flex items-center gap-2">
                                <div class="h-2 w-2 rounded-full bg-gray-200"></div>
                                <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Ezra for ERP operations and Claire for customer support. Each agent understands your business context and automates workflows specific to your industry.
                </p>
            </div>

            <!-- Workflow Automation -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Workflow Automation</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="flex -space-x-2">
                        <div class="h-10 w-10 rounded-full bg-gray-100 border-2 border-white flex items-center justify-center text-gray-600 text-xs">1</div>
                        <div class="h-10 w-10 rounded-full bg-gray-100 border-2 border-white flex items-center justify-center text-gray-600 text-xs">2</div>
                        <div class="h-10 w-10 rounded-full bg-gray-100 border-2 border-white flex items-center justify-center text-gray-600 text-xs">3</div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Automate purchase orders, invoicing, inventory updates, and customer communications. Reduce manual work while maintaining accuracy and control.
                </p>
            </div>

            <!-- Business Context -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Business Context</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <!-- Tree structure visualization -->
                        <div class="flex justify-center gap-4 mb-4">
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                        </div>
                        <div class="flex justify-center mb-4">
                            <div class="h-8 w-px bg-gray-300"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-8 w-8 bg-gray-900 rounded flex items-center justify-center text-white text-xs">AI</div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    AI agents trained on wholesale and manufacturing workflows. Understands your industry terminology, business rules, and operational requirements.
                </p>
            </div>

            <!-- Role-Based Access -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Role-Based Access</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="flex justify-between mb-4">
                            <div class="text-[10px] font-bold">Users</div>
                            <div class="text-[10px] font-bold">Roles</div>
                        </div>
                        <div class="space-y-2">
                            <div class="h-px bg-gray-100 w-full"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-1/2"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-2/3"></div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Control who can access what with granular permissions. Set up roles for operations, purchasing, warehouse, and management teams with appropriate access levels.
                </p>
            </div>

            <!-- Flexible Deployment -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Flexible Deployment</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-1">
                        {#each [1, 2, 3, 4, 5, 6, 7, 8, 9] as i}
                            <div class={`h-8 w-8 border border-gray-200 ${i === 5 ? 'bg-gray-900 flex items-center justify-center' : 'bg-white'}`}>
                                {#if i === 5}
                                    <div class="h-2 w-2 bg-white rounded-full"></div>
                                {/if}
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Deploy on cloud, on-premise, or hybrid environments. Choose the setup that matches your security requirements and IT infrastructure.
                </p>
            </div>
        </div>
    </div>
</section>
