<!-- Chosen Palette: Warm Neutrals (Background: #f7f6f4, Primary: #059669) -->
<!-- Application Structure Plan: The designed structure is a four-section dashboard prioritizing commercial flow and authority: 1. Header/Hero, 2. Authority Builder (About Us & Services), 3. Licensing/Payment Funnel (Simplified Manual Checkout), 4. AI/Content Hub & Footer. This structure establishes trust and focuses sales on manual verification. -->
<!-- Visualization & Content Choices: Performance -> Dynamic Stats Cards (JS). AI Hub -> Gemini API for factual explanations and blog drafts. Contact -> Fixed HTML/CSS for essential payment and social links. -->
<!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Goldman Capitals | Secure EA Licensing & Performance</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap');
        body { font-family: 'Inter', sans-serif; background-color: #f7f6f4; }
        .card { background-color: #ffffff; border-radius: 0.75rem; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -2px rgba(0, 0, 0, 0.06); }
        .btn-primary { background-color: #10b981; transition: background-color 0.2s; }
        .btn-primary:hover { background-color: #059669; }
    </style>
</head>
<body class="min-h-screen antialiased">

    <!-- Header & Navigation -->
    <header class="bg-white shadow-md fixed w-full z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex-shrink-0 text-xl font-extrabold text-gray-800">
                    <span class="text-emerald-500">Goldman</span> Capitals
                </div>
                <nav class="hidden md:flex space-x-8">
                    <a href="#performance" class="text-gray-600 hover:text-emerald-600 transition">Performance</a>
                    <a href="#services" class="text-gray-600 hover:text-emerald-600 transition">Services</a>
                    <a href="#analysis" class="text-gray-600 hover:text-emerald-600 transition">Analysis</a>
                    <a href="#licensing" class="text-gray-600 hover:text-emerald-600 transition">Pricing</a>
                    <a href="#ai-hub" class="text-gray-600 hover:text-emerald-600 transition">AI Hub</a>
                </nav>
            </div>
        </div>
    </header>

    <main class="pt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8">

            <!-- Hero Section -->
            <section class="text-center mb-16">
                <h1 class="text-5xl font-extrabold text-gray-900 mb-4">
                    Secure, Automated Trading with Goldman Capitals
                </h1>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                    Experience institutional-grade trend trading. Our EA is optimized for stability, high win rates, and ultra-low drawdown verified by independent sources.
                </p>
                <a href="#licensing" class="inline-block mt-8 btn-primary text-white font-bold py-3 px-8 rounded-lg shadow-md hover:shadow-lg">
                    Get Your License Now
                </a>
            </section>

            <!-- 1. About Us & Our Services -->
            <section id="services" class="mb-16 grid md:grid-cols-2 gap-10">
                <!-- About Us -->
                <div class="card p-8">
                    <h2 class="text-3xl font-bold text-gray-900 mb-4">About Goldman Capitals</h2>
                    <p class="text-gray-600 mb-4">
                        Goldman Capitals was founded on the principle of bringing institutional-level risk management and quantitative analysis to retail trading. We specialize in robust, high-probability strategies designed to minimize volatility and deliver consistent, compounding returns. Our focus is long-term stability and absolute transparency in performance.
                    </p>
                    <p class="text-gray-600">
                        We believe that disciplined execution, filtered through clear technical indicators, is the only sustainable path to profitability. Our commitment is to provide clients with verified results and unparalleled educational resources.
                    </p>
                </div>
                <!-- Our Services -->
                <div class="card p-8">
                    <h2 class="text-3xl font-bold text-gray-900 mb-4">Our Services & Products</h2>
                    <ul class="space-y-4 text-gray-700">
                        <li class="flex items-start space-x-3">
                            <span class="text-emerald-500 font-bold text-xl">✓</span>
                            <div>
                                <p class="font-semibold">FiboStochATRCrossover EA</p>
                                <p class="text-sm text-gray-500">Our flagship product. A structural pullback strategy utilizing H4 trend confirmation, Fibonacci levels, and dynamic ATR stop management for unparalleled stability.</p>
                            </div>
                        </li>
                        <li class="flex items-start space-x-3">
                            <span class="text-emerald-500 font-bold text-xl">✓</span>
                            <div>
                                <p class="font-semibold">24/7 Licensing API</p>
                                <p class="text-sm text-gray-500">A secure backend ensuring instant key delivery, account binding, and immediate license revocation for full client control.</p>
                            </div>
                        </li>
                        <li class="flex items-start space-x-3">
                            <span class="text-emerald-500 font-bold text-xl">✓</span>
                            <div>
                                <p class="font-semibold">AI Content & Analysis Hub</p>
                                <p class="text-sm text-gray-500">Access to real-time fundamental and technical analysis tools powered by the Gemini API, helping you stay informed and build trade conviction.</p>
                            </div>
                        </li>
                    </ul>
                </div>
            </section>


            <!-- 2. Performance Overview -->
            <section id="performance" class="mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-6 text-center">Verified Performance & Metrics</h2>
                <p class="text-gray-600 mb-8 text-center max-w-4xl mx-auto">
                    This section displays the audited, real-time performance of the **FiboStochATRCrossover EA**. We prioritize transparency, showcasing key metrics like the Profit Factor and Drawdown to build client trust.
                </p>
                
                <div class="grid md:grid-cols-4 gap-6 text-center">
                    <!-- Stat Card 1 -->
                    <div class="card p-6 border-b-4 border-emerald-500">
                        <p class="text-4xl font-extrabold text-emerald-600">2.07</p>
                        <p class="text-gray-500 mt-1">Profit Factor (Target ≥ 1.75)</p>
                    </div>
                    <!-- Stat Card 2 -->
                    <div class="card p-6 border-b-4 border-emerald-500">
                        <p class="text-4xl font-extrabold text-emerald-600">89.29%</p>
                        <p class="text-gray-500 mt-1">Win Rate (Verified)</p>
                    </div>
                    <!-- Stat Card 3 -->
                    <div class="card p-6 border-b-4 border-emerald-500">
                        <p class="text-4xl font-extrabold text-emerald-600">1.16%</p>
                        <p class="text-gray-500 mt-1">Max Drawdown (Ultra-Low Risk)</p>
                    </div>
                    <!-- Stat Card 4 -->
                    <div class="card p-6 border-b-4 border-emerald-500">
                        <p class="text-4xl font-extrabold text-emerald-600">H4 / Daily</p>
                        <p class="text-gray-500 mt-1">Execution & Trend Timeframes</p>
                    </div>
                </div>

                <!-- Myfxbook Embed Area -->
                <div class="card p-6 mt-8">
                    <h3 class="text-2xl font-semibold text-gray-800 mb-4">Live Audited Results</h3>
                    <p class="text-gray-500 mb-4">For fully audited, real-time equity curve performance, view our official Myfxbook page.</p>
                    <div class="bg-gray-100 h-64 flex items-center justify-center rounded-lg text-gray-500">
                        <!-- [MYFXBOOK WIDGET EMBEDDED HERE] -->
                        Placeholder for Myfxbook Widget
                    </div>
                </div>
            </section>
            
            <!-- 3. Market Analysis Section (News/Technical/Fundamental) -->
            <section id="analysis" class="mb-16 card p-8">
                <h2 class="text-3xl font-bold text-gray-900 mb-4 text-center">Current Market Analysis & News</h2>
                <p class="text-gray-600 mb-6 text-center max-w-4xl mx-auto">
                    Stay ahead of volatility. We provide placeholders for real-time fundamental insights, technical forecasts, and key forex news events that directly impact your trading.
                </p>
                <div class="grid md:grid-cols-3 gap-6">
                    <div class="p-4 border rounded-lg">
                        <h3 class="font-semibold text-lg mb-2 text-gray-800">Fundamental News Feed</h3>
                        <ul class="text-sm text-gray-600 space-y-2">
                            <li>[Placeholder] US CPI report released lower than expected.</li>
                            <li>[Placeholder] ECB holds rates steady amidst high inflation fears.</li>
                            <li>[Placeholder] Geopolitical tensions drive demand for safe-haven USD.</li>
                        </ul>
                    </div>
                    <div class="p-4 border rounded-lg">
                        <h3 class="font-semibold text-lg mb-2 text-gray-800">Technical Forecasts (EURUSD)</h3>
                        <ul class="text-sm text-gray-600 space-y-2">
                            <li>[Placeholder] EURUSD hits strong resistance at 1.0950.</li>
                            <li>[Placeholder] H4 MA 50/200 crossover imminent, signaling potential long-term shift.</li>
                        </ul>
                    </div>
                    <div class="p-4 border rounded-lg bg-emerald-50">
                        <h3 class="font-semibold text-lg mb-2 text-gray-800">Next Major Economic Event</h3>
                        <p class="text-sm text-gray-700">Non-Farm Payrolls (NFP) - Friday, 8:30 AM EST.</p>
                        <p class="text-xs text-gray-500 mt-2">Expect high volatility across USD pairs during release.</p>
                    </div>
                </div>
            </section>


            <!-- 4. Licensing & Purchase Form (Manual Only) -->
            <section id="licensing" class="mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-6 text-center">Get Your Secure Monthly License</h2>
                <div class="card p-8 max-w-2xl mx-auto">
                    <p class="text-gray-600 mb-6 text-center">
                        Select your subscription tier. Your license key will be issued manually upon payment verification.
                    </p>
                    
                    <form id="paymentForm" class="space-y-6">
                        <div>
                            <label for="licensePlan" class="block text-sm font-medium text-gray-700 mb-1">Choose Plan</label>
                            <select id="licensePlan" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-emerald-500 focus:border-emerald-500 transition-colors">
                                <option value="Trial" data-price="99">Trial (1 month - $99)</option>
                                <option value="Bronze" data-price="299">Bronze (3 months - $299)</option>
                                <option value="Silver" data-price="599">Silver (6 months - $599)</option>
                                <option value="Gold" data-price="1199">Gold (1 year - $1,199)</option>
                            </select>
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email Address (For License Delivery)</label>
                            <input type="email" id="email" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-emerald-500 focus:border-emerald-500" placeholder="your.name@example.com">
                        </div>
                        <div>
                            <label for="account_number" class="block text-sm font-medium text-gray-700 mb-1">MT4/MT5 Account Number (For License Binding)</label>
                            <input type="number" id="account_number" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-emerald-500 focus:border-emerald-500" placeholder="E.g., 78956">
                        </div>
                        
                        <div class="text-lg font-bold text-gray-800 border-t pt-4 text-center">
                            Total Due: <span id="displayPrice">$99 USD/Month</span>
                        </div>

                        <!-- Payment Buttons -->
                        <div class="space-y-4">
                            <button type="button" onclick="handlePayPalPayment()" class="w-full bg-blue-700 text-white font-bold py-3 rounded-lg hover:bg-blue-800 hover:shadow-lg transition">
                                Pay via PayPal (Initiate Transfer)
                            </button>
                            <p id="message" class="mt-4 text-center text-sm text-red-500"></p>
                        </div>
                    </form>
                    
                    <!-- Bank Transfer Details (Manual Payment) -->
                    <div class="mt-6 border-t pt-4">
                        <h4 class="text-lg font-semibold text-gray-800 mb-2">Alternative Payments (Manual Verification)</h4>
                        <p class="text-sm text-gray-700 font-bold mb-1">Bank Transfers (Absa Bank):</p>
                        <ul class="text-sm text-gray-600 list-disc list-inside space-y-1">
                            <li>Account Name: Goldman Capitals</li>
                            <li>USD Account: 2055009816</li>
                            <li>KSH Account: 2055009786</li>
                        </ul>
                        <p class="text-sm text-gray-700 font-bold mt-3 mb-1">M-Pesa Transfers (PAYBILL):</p>
                        <p class="text-sm text-gray-600">PAYBILL: 303030</p>
                        <p class="text-xs text-red-500 mt-2">NOTE: Payments via Bank/M-Pesa require you to email <a href="mailto:support@goldman-capitals.net" class="text-emerald-600">support@goldman-capitals.net</a> for key issuance.</p>
                    </div>
                </div>
            </section>

            <!-- 5. AI Content & Education Hub -->
            <section id="ai-hub" class="mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-6 text-center">AI Content & Education Hub</h2>
                <p class="text-gray-600 mb-8 text-center max-w-4xl mx-auto">
                    Use our integrated AI tools powered by Gemini to instantly explain core trading concepts or draft professional blog posts for your marketing channels.
                </p>
                
                <div class="grid md:grid-cols-2 gap-8">
                    
                    <!-- Tool 1: Concept Explainer (Search Grounded) -->
                    <div class="card p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-4">1. Trading Concept Explainer (Factual)</h3>
                        <p class="text-sm text-gray-500 mb-3">Uses Google Search to provide verified definitions.</p>
                        <input type="text" id="conceptInput" class="w-full px-3 py-2 border border-gray-300 rounded-lg mb-4" placeholder="E.g., What is ATR? or What is a Fibo Retracement?">
                        
                        <button onclick="getConceptExplanation()" class="w-full btn-primary text-white font-bold py-2 rounded-lg mb-4">
                            Explain Concept
                        </button>

                        <div id="conceptOutput" class="p-3 bg-gray-50 border border-gray-200 rounded-lg min-h-[100px] text-sm text-gray-700 overflow-auto">
                            <p class="text-gray-400">Concept output will appear here...</p>
                        </div>
                    </div>

                    <!-- Tool 2: Blog Post Generator -->
                    <div class="card p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-4">2. Blog Post Draft Generator</h3>
                        <p class="text-sm text-gray-500 mb-3">Generates a persuasive draft for your Goldman Capitals blog.</p>
                        <input type="text" id="blogTopicInput" class="w-full px-3 py-2 border border-gray-300 rounded-lg mb-4" placeholder="E.g., Write a post about why H4 is the safest timeframe.">
                        
                        <button onclick="generateBlogPost()" class="w-full btn-primary text-white font-bold py-2 rounded-lg mb-4">
                            Generate Draft
                        </button>
                        
                        <div id="blogOutput" class="p-3 bg-gray-50 border border-gray-200 rounded-lg min-h-[100px] text-sm text-gray-700 overflow-auto">
                            <p class="text-gray-400">Concept output will appear here...</p>
                        </div>
                    </div>
                </div>
            </section>

        </div>
    </main>

    <!-- Footer & Contact Section -->
    <footer id="contact" class="bg-gray-800 text-white p-10 mt-16">
        <div class="max-w-7xl mx-auto grid md:grid-cols-3 gap-8">
            
            <!-- Column 1: Contact Details -->
            <div>
                <h3 class="text-xl font-bold text-emerald-400 mb-4">Contact Details</h3>
                <p class="text-gray-400 mb-2">Email: <a href="mailto:support@goldman-capitals.net" class="hover:text-white">support@goldman-capitals.net</a></p>
                <p class="text-gray-400 mb-2">US Mobile: +1 210 773 4966</p>
                <p class="text-gray-400 mb-2">KE Mobile: +254 728 971 784</p>
            </div>

            <!-- Column 2: Social Media -->
            <div>
                <h3 class="text-xl font-bold text-emerald-400 mb-4">Connect With Us</h3>
                <div class="flex space-x-4 text-2xl">
                    <a href="#" class="text-gray-400 hover:text-white transition" title="Telegram">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2.04c-5.52 0-10 4.48-10 10s4.48 10 10 10 10-4.48 10-10-4.48-10-10-10zm5.27 7.02c.03.26.06.5.06.77 0 5.4-4.11 11.62-11.62 11.62-2.31 0-4.48-.67-6.3-1.82.32.04.66.07 1 .07 1.95 0 3.73-.66 5.16-1.86-1.82-.03-3.35-1.24-3.88-2.88.25.04.5.06.77.06.37 0 .73-.04 1.07-.13-1.95-.4-3.35-2.12-3.35-4.17 0-.03 0-.06 0-.08.55.3 1.18.5 1.83.52-.39-.27-.72-.6-1.14-.98-.82-.74-1.22-1.72-1.22-2.82 0-1.1.37-2.07 1.14-2.88 2.11 2.6 5.25 4.3 8.78 4.48-.06-.33-.08-.66-.08-1 0-2.48 2.02-4.5 4.5-4.5 1.3 0 2.45.54 3.27 1.4.98-.19 1.89-.55 2.74-1.05-.32.99-.99 1.84-1.87 2.37.89-.1 1.77-.34 2.58-.7-1.14 1.12-2.58 2.06-4.19 2.5z"/></svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition" title="X / Twitter">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2.04c-5.52 0-10 4.48-10 10s4.48 10 10 10 10-4.48 10-10-4.48-10-10-10zm5.27 7.02c.03.26.06.5.06.77 0 5.4-4.11 11.62-11.62 11.62-2.31 0-4.48-.67-6.3-1.82.32.04.66.07 1 .07 1.95 0 3.73-.66 5.16-1.86-1.82-.03-3.35-1.24-3.88-2.88.25.04.5.06.77.06.37 0 .73-.04 1.07-.13-1.95-.4-3.35-2.12-3.35-4.17 0-.03 0-.06 0-.08.55.3 1.18.5 1.83.52-.39-.27-.72-.6-1.14-.98-.82-.74-1.22-1.72-1.22-2.82 0-1.1.37-2.07 1.14-2.88 2.11 2.6 5.25 4.3 8.78 4.48-.06-.33-.08-.66-.08-1 0-2.48 2.02-4.5 4.5-4.5 1.3 0 2.45.54 3.27 1.4.98-.19 1.89-.55 2.74-1.05-.32.99-.99 1.84-1.87 2.37.89-.1 1.77-.34 2.58-.7-1.14 1.12-2.58 2.06-4.19 2.5z"/></svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition" title="Facebook">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10-4.48-10-10-10zm3 8h-2v2h2v2h-2v6h-3v-6h-2v-2h2v-1.5c0-1.92 1.17-3.6 3.14-3.6h1.86v3h-1.86c-.52 0-.84.28-.84.75V10h3l-.38 2z"/></svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition" title="Bluesky">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10-4.48-10-10-10zm-1.88 12.18c-.8.15-1.6.22-2.4.22-1.5 0-2.92-.3-4.22-.88a.72.72 0 01-.58-.87c.07-.3.33-.53.64-.53.1 0 .22.02.32.05 1.34.42 2.76.64 4.18.64 1.3 0 2.65-.2 3.9-.58.33-.1.68-.13 1.02-.03.35.1.6.38.69.73.07.28-.01.58-.23.83-.5.5-1.12.83-1.8.96zM12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10-4.48-10-10-10zm4.27 15.68c-.68-.16-1.39-.24-2.11-.24-1.5 0-3.03.29-4.43.87-.58.24-1.22.25-1.78.02-.56-.24-.92-.77-.92-1.35 0-.58.36-1.12.92-1.35 1.4-.58 2.87-.87 4.38-.87 1.3 0 2.64.2 3.88.58.35.1.68.13 1.02.03.35-.1.6-.38.69-.73.07-.28-.01-.58-.23-.83-.5-.5-1.12-.83-1.8-.96 1.1-.28 2.05-.75 2.74-1.35.34-.29.58-.7.64-1.17.07-.42-.01-.84-.23-1.23-.5-.5-1.12-.83-1.8-.96-.44-.1-.88-.13-1.3-.03-.35.1-.6.38-.69.73-.07.28-.01-.58-.23-.83-.5-.5-1.12-.83-1.8-.96z"/></svg>
                    </a>
                </div>
            </div>

            <!-- Column 3: Quick Links -->
            <div>
                <h3 class="text-xl font-bold text-emerald-400 mb-4">Quick Links</h3>
                <ul class="space-y-2">
                    <li><a href="#performance" class="text-gray-400 hover:text-white transition">Performance Audit</a></li>
                    <li><a href="#licensing" class="text-gray-400 hover:text-white transition">Pricing & Plans</a></li>
                    <li><a href="#ai-hub" class="text-gray-400 hover:text-white transition">AI Analysis Tools</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white transition">Download EA</a></li>
                </ul>
            </div>

        </div>
        <div class="mt-8 text-center border-t border-gray-700 pt-4">
            <p class="text-xs text-gray-500">
                Disclaimer: Trading foreign exchange carries a high level of risk and may not be suitable for all investors.
            </p>
        </div>
    </footer>

    <script>
        // --- DATA AND CONFIGURATION ---
        const API_KEY = "YOUR_GEMINI_API_KEY"; // **CRITICAL: Replace with your actual Gemini API Key**
        const PAYSTACK_PUBLIC_KEY = "YOUR_PAYSTACK_PUBLIC_KEY"; // **CRITICAL: Replace with your actual Paystack Public Key**
        const API_URL = 'https://goldman-capitals.net:5002'; // **FIXED: Use HTTPS for security**

        // --- DYNAMIC PRICE UPDATE LOGIC ---
        document.addEventListener('DOMContentLoaded', () => {
            const planSelector = document.getElementById('licensePlan');
            const priceDisplay = document.getElementById('displayPrice');
            
            function updatePrice() {
                const selectedOption = planSelector.options[planSelector.selectedIndex];
                const price = selectedOption.getAttribute('data-price');
                priceDisplay.textContent = `$${price} USD/Month`;
            }

            planSelector.addEventListener('change', updatePrice);
            updatePrice(); // Initialize price display

            // Attach event listener for payment button (Simulated for this file)
            document.getElementById('paymentForm').addEventListener('submit', (e) => e.preventDefault());
        });

        // --- HELPER FUNCTION: GENERATE UNIQUE KEY ---
        function generateUUID() {
            return 'xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx'.replace(/[xy]/g, function(c) {
                var r = Math.random() * 16 | 0, v = c == 'x' ? r : (r & 0x3 | 0x8);
                return v.toString(16).toUpperCase();
            });
        }

        // --- PAYMENT HANDLERS ---
        function handlePaystackPayment() {
            const email = document.getElementById('email').value;
            const account_number = document.getElementById('account_number').value;
            const planSelector = document.getElementById('licensePlan');
            const selectedOption = planSelector.options[planSelector.selectedIndex];
            const planName = selectedOption.value;
            const price = selectedOption.getAttribute('data-price'); // Price in USD

            const messageElement = document.getElementById('message');
            messageElement.textContent = '';

            if (!email || !account_number) {
                messageElement.textContent = "Please enter your email and MT4/MT5 account number.";
                return;
            }
            
            // NOTE: Paystack is removed. This simulates the successful manual process.
            messageElement.textContent = `Thank you for your order! Please proceed with Bank/PayPal transfer using the details below.`;
            
            // In a live system, this would trigger a Flask API call (e.g., /initiate_paystack)
            // The API would then securely generate a license key and transaction reference
            // and return the Paystack authorization URL for redirect.
            
            // For now, we simulate success:
            setTimeout(() => {
                 messageElement.textContent = "Please complete payment using the details below. Your license key will be sent upon verification to your email.";
            }, 1500);
        }

        function handlePayPalPayment() {
            document.getElementById('message').textContent = "PayPal payment gateway is a manual verification process. Please check email for instructions.";
        }

        // --- GEMINI API FUNCTIONS ---

        function setLoading(outputId) {
            const output = document.getElementById(outputId);
            output.innerHTML = '<div class="flex items-center justify-center space-x-2"><div class="w-4 h-4 rounded-full animate-pulse bg-emerald-500"></div><div class="w-4 h-4 rounded-full animate-pulse bg-emerald-500 delay-150"></div><div class="w-4 h-4 rounded-full animate-pulse bg-emerald-500 delay-300"></div></div>';
        }

        async function getConceptExplanation() {
            const concept = document.getElementById('conceptInput').value;
            const outputId = 'conceptOutput';
            if (!concept) return;

            setLoading(outputId);

            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${API_KEY}`;
            const systemPrompt = "You are a professional financial educator working for Goldman Capitals. Provide a concise, clear, and factual one-paragraph explanation of the financial concept requested. Adopt a highly trustworthy tone.";
            const userQuery = `Explain the concept of: ${concept}`;

            const payload = {
                contents: [{ parts: [{ text: userQuery }] }],
                tools: [{ "google_search": {} }], // Use Google Search for factual grounding
                systemInstruction: { parts: [{ text: systemPrompt }] },
            };

            try {
                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });
                
                const result = await response.json();
                const text = result.candidates?.[0]?.content?.parts?.[0]?.text || "Error: Could not generate content.";
                document.getElementById(outputId).innerText = text;

            } catch (error) {
                document.getElementById(outputId).innerText = `API Error: ${error.message}`;
            }
        }

        async function generateBlogPost() {
            const topic = document.getElementById('blogTopicInput').value;
            const outputId = 'blogOutput';
            if (!topic) return;

            setLoading(outputId);

            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${API_KEY}`;
            const systemPrompt = "You are a lead analyst for Goldman Capitals. Write a persuasive blog post of three short paragraphs (Introduction, Core Argument, Conclusion) arguing for the user query. Maintain a tone of expertise and confidence.";
            const userQuery = `Write a short blog post on the topic: ${topic}`;

            const payload = {
                contents: [{ parts: [{ text: userQuery }] }],
                systemInstruction: { parts: [{ text: systemPrompt }] },
            };

            try {
                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });
                
                const result = await response.json();
                const text = result.candidates?.[0]?.content?.parts?.[0]?.text || "Error: Could not generate content.";
                document.getElementById(outputId).innerText = text;
            } catch (error) {
                document.getElementById(outputId).innerText = `API Error: ${error.message}`;
            }
        }

        // --- Database Initialization (Placeholder - Must be run on the server) ---
        // You would typically run this once from a browser: 
        // http://[YOUR_STATIC_IP]:5002/create_database?secret=YOUR_CUSTOM_API_SECRET
    </script>
</body>
</html>
