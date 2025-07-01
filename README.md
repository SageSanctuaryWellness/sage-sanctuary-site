<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sage Sanctuary Wellness Pitch Deck</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            -webkit-print-color-adjust: exact;
            print-color-adjust: exact;
        }
        @media print {
            body {
                -webkit-print-color-adjust: exact;
                print-color-adjust: exact;
            }
            .no-print {
                display: none !important;
            }
            .slide {
                page-break-after: always;
                box-shadow: none !important;
                border: none !important;
                margin-bottom: 0 !important;
            }
        }
        .slide {
            width: 100%;
            min-height: 90vh;
            padding: 2rem 4rem 4rem 4rem; /* Adjusted padding */
            margin-bottom: 2rem;
            background-color: white;
            border-radius: 0.5rem;
            box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
            border: 1px solid #e5e7eb;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        .brand-text {
            color: #14532d; /* A deep sage green */
        }
        .brand-bg {
            background-color: #14532d;
        }
        h1, h2, h3 {
            font-weight: 700;
        }
        h2 {
            border-bottom: 2px solid #dcfce7; /* Light green */
            padding-bottom: 0.5rem;
            margin-bottom: 1.5rem;
        }
        /* Spinner for loading state */
        .spinner {
            border: 4px solid rgba(0, 0, 0, 0.1);
            width: 24px;
            height: 24px;
            border-radius: 50%;
            border-left-color: #14532d;
            animation: spin 1s ease infinite;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body class="bg-gray-100 p-4 sm:p-8">

    <!-- Print Button -->
    <div class="fixed bottom-8 right-8 z-50 no-print">
        <button onclick="window.print()" class="brand-bg hover:bg-green-800 text-white font-bold py-3 px-6 rounded-full shadow-lg transition-transform transform hover:scale-105 flex items-center gap-2">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 17h2a2 2 0 002-2v-4a2 2 0 00-2-2H5a2 2 0 00-2 2v4a2 2 0 002 2h2m2 4h6a2 2 0 002-2v-4a2 2 0 00-2-2H9a2 2 0 00-2 2v4a2 2 0 002 2zm8-12V5a2 2 0 00-2-2H9a2 2 0 00-2 2v4h10z" />
            </svg>
            Print to PDF
        </button>
    </div>

    <div class="max-w-4xl mx-auto">

        <!-- Slide 1: Title -->
        <div class="slide text-center bg-green-50">
            <h1 class="text-5xl md:text-6xl font-bold brand-text">Sage Sanctuary Wellness</h1>
            <p class="text-2xl text-gray-600 mt-2">Liberation Labs</p>
            <div class="w-24 h-1 brand-bg mx-auto my-8 rounded"></div>
            <p class="text-3xl md:text-4xl text-gray-700 font-light tracking-wider">PITCH DECK: VISION & MISSION</p>
        </div>

        <!-- Slide 2: Executive Summary -->
        <div class="slide">
            <h2 class="text-3xl brand-text">1. Executive Summary: The Vision</h2>
            <p class="text-lg text-gray-700 leading-relaxed">
                Sage Sanctuary Wellness is pioneering the next generation of corporate wellness. We are moving beyond fragmented, low-ROI programs to embed wellness as a core, measurable part of business infrastructure. Our integrated system combines proprietary, culturally-rooted sensory experiences with a powerful data analytics platform to deliver tangible outcomes: significant cost savings, increased talent retention, measurable risk reduction, and a resilient, thriving company culture. We provide a single, end-to-end solution that is effective, scalable, and compliance-safe for the modern enterprise.
            </p>
        </div>

        <!-- Slide 3: Business Model Canvas -->
        <div class="slide">
            <h2 class="text-3xl brand-text">2. Business Model Canvas</h2>
            <div class="space-y-4 text-sm">
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                    <div class="bg-green-50 p-4 rounded-lg col-span-1 md:col-span-2">
                        <h3 class="font-bold text-green-800">Key Partnerships</h3>
                        <ul class="list-disc list-inside text-gray-700 mt-2">
                            <li>IP Legal Counsel</li>
                            <li>Manufacturing & Supply Chain Partners</li>
                            <li>Academic & Research Institutions</li>
                            <li>Incubators & Business Accelerators</li>
                        </ul>
                    </div>
                    <div class="bg-blue-50 p-4 rounded-lg">
                        <h3 class="font-bold text-blue-800">Key Activities</h3>
                        <ul class="list-disc list-inside text-gray-700 mt-2">
                            <li>Service Delivery & Activations</li>
                            <li>Data & Analytics Reporting</li>
                            <li>Product & IP Development</li>
                            <li>B2B Sales & Business Development</li>
                        </ul>
                    </div>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                     <div class="bg-blue-50 p-4 rounded-lg">
                        <h3 class="font-bold text-blue-800">Key Resources</h3>
                        <ul class="list-disc list-inside text-gray-700 mt-2">
                            <li>Intellectual Property (Trademarks, Copyrights)</li>
                            <li>Physical Assets (Mobile Sauna)</li>
                            <li>Digital Platform (Impact Dashboard)</li>
                            <li>Human Capital & Expertise</li>
                        </ul>
                    </div>
                    <div class="bg-emerald-50 p-4 rounded-lg text-center flex flex-col justify-center">
                        <h3 class="font-bold text-emerald-800">Value Propositions</h3>
                        <p class="text-gray-700 mt-2">Measurable ROI, Risk Reduction, Integrated Infrastructure, Talent Retention, Accessible Healing.</p>
                    </div>
                    <div class="bg-purple-50 p-4 rounded-lg">
                        <h3 class="font-bold text-purple-800">Customer Relationships</h3>
                        <ul class="list-disc list-inside text-gray-700 mt-2">
                            <li>Strategic Partner Model</li>
                            <li>Data-Driven Consultation</li>
                            <li>High-Touch Support</li>
                        </ul>
                    </div>
                </div>
                 <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                    <div class="bg-purple-50 p-4 rounded-lg">
                        <h3 class="font-bold text-purple-800">Channels</h3>
                        <ul class="list-disc list-inside text-gray-700 mt-2">
                            <li>Direct B2B Sales</li>
                            <li>Pilot Programs</li>
                            <li>Strategic Partnerships</li>
                            <li>Crowdfunding (IFundWomen)</li>
                        </ul>
                    </div>
                    <div class="bg-rose-50 p-4 rounded-lg text-center flex flex-col justify-center">
                        <h3 class="font-bold text-rose-800">Customer Segments</h3>
                        <p class="text-gray-700 mt-2">Enterprise B2B Clients (500+ employees) in Tech, Retail, and Professional Services seeking data-driven, compliance-safe wellness solutions.</p>
                    </div>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                    <div class="bg-amber-50 p-4 rounded-lg">
                        <h3 class="font-bold text-amber-800">Cost Structure</h3>
                        <p class="text-gray-700 mt-2">IP & Legal Fees, COGS, CapEx (Sauna), Operational Costs, Platform & Tech, Personnel.</p>
                    </div>
                    <div class="bg-teal-50 p-4 rounded-lg">
                        <h3 class="font-bold text-teal-800">Revenue Streams</h3>
                        <p class="text-gray-700 mt-2">Pilot Program Fees, Enterprise Subscriptions (PEPM), Product Sales, Crowdfunding.</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Slide 4: Demographic & Value Proposition with Gemini Feature -->
        <div class="slide">
            <h2 class="text-3xl brand-text">3. Demographic & Value Proposition</h2>
            <p class="text-lg text-gray-700 leading-relaxed mb-4">
                Our priority demographic is large U.S. corporations grappling with employee burnout, disengagement, and turnover. They have invested heavily in traditional wellness and DEI programs with minimal measurable impact and now face increasing legal scrutiny, forcing them to find effective, brand-safe alternatives.
            </p>
            
            <div class="bg-green-50 p-4 rounded-lg border-l-4 border-green-700 no-print">
                <h3 class="font-bold text-lg text-green-800 mb-2">✨ AI-Powered Value Proposition</h3>
                <p class="text-gray-600 mb-3 text-sm">Enter a target company or industry to see how Gemini can tailor our value proposition instantly.</p>
                <div class="flex flex-col sm:flex-row gap-2">
                    <input id="vp-target-input" type="text" placeholder="e.g., Google, 'the Finance industry'" class="flex-grow p-2 border border-gray-300 rounded-md">
                    <button id="vp-generate-btn" class="brand-bg text-white font-bold py-2 px-4 rounded-md hover:bg-green-800 transition-all flex items-center justify-center gap-2">
                        Tailor for Target
                    </button>
                </div>
                <div id="vp-output" class="mt-4 text-gray-700 leading-relaxed hidden"></div>
                 <div id="vp-loader" class="mt-4 hidden flex justify-center items-center">
                    <div class="spinner"></div>
                    <p class="ml-2 text-gray-600">Generating...</p>
                </div>
            </div>
        </div>
        
        <!-- Slide 5: Interactive Demo: Impact Dashboard -->
        <div class="slide no-print">
            <h2 class="text-3xl brand-text">4. Interactive Demo: Impact Dashboard</h2>
            <p class="text-lg text-gray-700 leading-relaxed mb-4">
                Our Impact Dashboard provides real-time, board-ready reports. Use this demo to generate a mock 60-day pilot report for a potential client.
            </p>

            <div class="bg-blue-50 p-6 rounded-lg border-l-4 border-blue-700">
                <h3 class="font-bold text-lg text-blue-800 mb-3">✨ Generate a Mock Impact Report</h3>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-4">
                    <div>
                        <label for="report-size-input" class="block text-sm font-medium text-gray-700">Company Size (Employees)</label>
                        <input id="report-size-input" type="number" value="500" class="mt-1 block w-full p-2 border border-gray-300 rounded-md">
                    </div>
                    <div>
                        <label for="report-challenge-input" class="block text-sm font-medium text-gray-700">Primary Challenge</label>
                        <select id="report-challenge-input" class="mt-1 block w-full p-2 border border-gray-300 rounded-md bg-white">
                            <option>High Burnout</option>
                            <option>Low Morale</option>
                            <option>Failed DEI Initiatives</option>
                            <option>High Employee Turnover</option>
                        </select>
                    </div>
                </div>
                <button id="report-generate-btn" class="w-full brand-bg text-white font-bold py-3 px-4 rounded-md hover:bg-green-800 transition-all flex items-center justify-center gap-2">
                    Generate Pilot Report
                </button>
                
                <div id="report-loader" class="mt-4 hidden flex justify-center items-center">
                    <div class="spinner"></div>
                    <p class="ml-2 text-gray-600">Calculating projections...</p>
                </div>
                <div id="report-output" class="mt-6 hidden grid grid-cols-2 sm:grid-cols-3 gap-4 text-center">
                    <!-- Results will be injected here -->
                </div>
            </div>
        </div>


        <!-- Slide 6: Strategic Recommendations -->
        <div class="slide">
            <h2 class="text-3xl brand-text">5. Strategic Recommendations & Next Steps</h2>
            <div class="space-y-6">
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">A. Key Gaps & Questions to Address</h3>
                    <ul class="list-decimal list-inside text-gray-700 space-y-1">
                        <li><strong>Pricing Model:</strong> What is the specific pricing structure (PEPM, flat fees)?</li>
                        <li><strong>Scalability Strategy:</strong> How will we scale from a single mobile sauna to multiple enterprise clients?</li>
                        <li><strong>Go-To-Market (GTM) Strategy:</strong> What is the plan to build a sales pipeline beyond direct outreach?</li>
                        <li><strong>Technology Roadmap:</strong> What is the long-term vision for the platform and potential HRIS integrations?</li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">B. Potential Funding & Program Opportunities</h3>
                     <ul class="list-disc list-inside text-gray-700 space-y-1">
                        <li><strong>Funding:</strong> Impact Investors, B2B SaaS VCs, Corporate Grants, Small Business Loans.</li>
                        <li><strong>Incubators/Accelerators:</strong> HR Tech Accelerators, Social Impact Incubators, University-Affiliated Programs.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- Slide 7: Collaboration Map -->
        <div class="slide">
            <h2 class="text-3xl brand-text">6. Proposed Collaboration Map (The Lepage Center)</h2>
            <div class="w-full">
                <table class="w-full border-collapse">
                    <thead>
                        <tr class="border-b-2 border-gray-300">
                            <th class="p-4 text-left text-lg font-semibold text-green-800 bg-green-100 rounded-tl-lg">Where The Lepage Center Can Provide Direct Support</th>
                            <th class="p-4 text-left text-lg font-semibold text-red-800 bg-red-100 rounded-tr-lg">Where External Support is Required</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr class="border-b border-gray-200">
                            <td class="p-4 align-top text-gray-700">Business Model Refinement & Financial Projections</td>
                            <td class="p-4 align-top text-gray-700">Specialized IP Counsel (Filing & Defense)</td>
                        </tr>
                        <tr class="bg-gray-50 border-b border-gray-200">
                            <td class="p-4 align-top text-gray-700">Pitch Deck & Narrative Coaching</td>
                            <td class="p-4 align-top text-gray-700">Manufacturing & Production Partners</td>
                        </tr>
                        <tr class="border-b border-gray-200">
                            <td class="p-4 align-top text-gray-700">Incubator & Funding Pipeline Introductions</td>
                            <td class="p-4 align-top text-gray-700">Fractional CFO / Financial Modeling Expert</td>
                        </tr>
                        <tr class="bg-gray-50">
                            <td class="p-4 align-top text-gray-700 rounded-bl-lg">Network Access (B2B Sales, HR, Ops Mentors)</td>
                            <td class="p-4 align-top text-gray-700 rounded-br-lg">Specialized Insurance Broker (Liability)</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
        
        <!-- Slide 8: Stakeholder Communication Assistant -->
        <div class="slide no-print">
            <h2 class="text-3xl brand-text">7. Stakeholder Communication Assistant</h2>
            <p class="text-lg text-gray-700 leading-relaxed mb-4">
                Move from pitch to proposal. Use this tool to draft communications tailored to key decision-makers, highlighting the metrics and outcomes they care about most.
            </p>
            <div class="bg-purple-50 p-6 rounded-lg border-l-4 border-purple-700">
                 <h3 class="font-bold text-lg text-purple-800 mb-3">✨ Generate a Communication Draft</h3>
                 <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-4">
                    <div>
                        <label for="comm-stakeholder-input" class="block text-sm font-medium text-gray-700">Target Stakeholder</label>
                        <select id="comm-stakeholder-input" class="mt-1 block w-full p-2 border border-gray-300 rounded-md bg-white">
                            <option>CEO (Chief Executive Officer)</option>
                            <option>CFO (Chief Financial Officer)</option>
                            <option>CHRO (Chief Human Resources Officer)</option>
                            <option>COO (Chief Operating Officer)</option>
                        </select>
                    </div>
                    <div>
                        <label for="comm-format-input" class="block text-sm font-medium text-gray-700">Communication Format</label>
                        <select id="comm-format-input" class="mt-1 block w-full p-2 border border-gray-300 rounded-md bg-white">
                            <option>Email Draft</option>
                            <option>Key Talking Points</option>
                        </select>
                    </div>
                </div>
                <div>
                     <label for="comm-notes-input" class="block text-sm font-medium text-gray-700">Optional: Add specific context or notes</label>
                     <textarea id="comm-notes-input" rows="2" class="mt-1 block w-full p-2 border border-gray-300 rounded-md" placeholder="e.g., Mention our upcoming Q3 board meeting..."></textarea>
                </div>
                <button id="comm-generate-btn" class="mt-4 w-full brand-bg text-white font-bold py-3 px-4 rounded-md hover:bg-green-800 transition-all flex items-center justify-center gap-2">
                    Generate Communication
                </button>
                <div id="comm-loader" class="mt-4 hidden flex justify-center items-center">
                    <div class="spinner"></div>
                    <p class="ml-2 text-gray-600">Drafting...</p>
                </div>
                <div id="comm-output" class="mt-4 p-4 bg-white rounded-md border border-gray-200 text-gray-700 leading-relaxed hidden whitespace-pre-wrap"></div>
            </div>
        </div>

    </div>

    <script type="module">
        // --- Gemini API Integration ---

        const vpTargetInput = document.getElementById('vp-target-input');
        const vpGenerateBtn = document.getElementById('vp-generate-btn');
        const vpOutput = document.getElementById('vp-output');
        const vpLoader = document.getElementById('vp-loader');

        const reportSizeInput = document.getElementById('report-size-input');
        const reportChallengeInput = document.getElementById('report-challenge-input');
        const reportGenerateBtn = document.getElementById('report-generate-btn');
        const reportOutput = document.getElementById('report-output');
        const reportLoader = document.getElementById('report-loader');

        const commStakeholderInput = document.getElementById('comm-stakeholder-input');
        const commFormatInput = document.getElementById('comm-format-input');
        const commNotesInput = document.getElementById('comm-notes-input');
        const commGenerateBtn = document.getElementById('comm-generate-btn');
        const commOutput = document.getElementById('comm-output');
        const commLoader = document.getElementById('comm-loader');


        // Function to call the Gemini API
        async function callGemini(prompt) {
            const apiKey = ""; // API key will be provided by the environment
            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;
            
            const payload = {
                contents: [{ role: "user", parts: [{ text: prompt }] }]
            };

            try {
                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                if (!response.ok) {
                    throw new Error(`API call failed with status: ${response.status}`);
                }

                const result = await response.json();
                
                if (result.candidates && result.candidates.length > 0 &&
                    result.candidates[0].content && result.candidates[0].content.parts &&
                    result.candidates[0].content.parts.length > 0) {
                    return result.candidates[0].content.parts[0].text;
                } else {
                    console.error("Unexpected response structure:", result);
                    return "Error: Could not generate a response. Please check the console.";
                }
            } catch (error) {
                console.error("Error calling Gemini API:", error);
                return `Error: ${error.message}. See console for details.`;
            }
        }

        // --- Feature 1: Tailored Value Proposition ---
        vpGenerateBtn.addEventListener('click', async () => {
            const target = vpTargetInput.value.trim();
            if (!target) {
                vpOutput.textContent = "Please enter a target company or industry.";
                vpOutput.classList.remove('hidden');
                return;
            }

            vpLoader.classList.remove('hidden');
            vpOutput.classList.add('hidden');
            vpGenerateBtn.disabled = true;

            const originalVP = `Sage Sanctuary Wellness offers a paradigm shift from typical wellness programs. We deliver an integrated wellness infrastructure that focuses on universal, sensory-based experiences to foster resilience and community—not divisive rhetoric. Our unique value is threefold: 1) Measurable ROI, with a data dashboard that translates wellness activities into board-ready metrics like reduced absenteeism and increased productivity; 2) Risk Reduction, through IP-protected, compliance-safe frameworks; and 3) A Unified System, which replaces a dozen disconnected vendors with one strategic partner. We provide tools for genuine human connection and recovery, while giving leadership the hard data they need to justify the investment.`;

            const prompt = `You are a business strategist for Sage Sanctuary Wellness. Your task is to rewrite the following value proposition to specifically target "${target}". Emphasize how our solutions address their unique challenges. Keep the tone professional, confident, and focused on ROI and risk reduction. Be concise and impactful.

            Original Value Proposition:
            ---
            ${originalVP}
            ---
            
            Your rewritten, targeted value proposition:`;

            const generatedText = await callGemini(prompt);
            vpOutput.innerHTML = generatedText.replace(/\n/g, '<br>'); // Format line breaks
            
            vpLoader.classList.add('hidden');
            vpOutput.classList.remove('hidden');
            vpGenerateBtn.disabled = false;
        });

        // --- Feature 2: Mock Impact Report ---
        reportGenerateBtn.addEventListener('click', async () => {
            const companySize = reportSizeInput.value;
            const primaryChallenge = reportChallengeInput.value;

            reportLoader.classList.remove('hidden');
            reportOutput.classList.add('hidden');
            reportGenerateBtn.disabled = true;
            reportOutput.innerHTML = ''; // Clear previous results

            const prompt = `You are a data analyst for Sage Sanctuary Wellness. Generate a mock 60-day pilot impact report for a company with ${companySize} employees facing the primary challenge of "${primaryChallenge}". 
            
            Our benchmark pilot (300 employees) showed: Stress ↓32%, Inclusion ↑48%, Absenteeism ↓19%, Morale ↑22%, $180K projected annual savings.
            
            Generate plausible, slightly varied results based on this benchmark. The savings should scale logically with company size.
            
            Provide the output as a simple JSON object (no markdown) with these exact keys: "stressReduction", "inclusionIncrease", "absenteeismReduction", "managerMoraleIncrease", "projectedAnnualSavings". The values should be strings. For example: {"stressReduction": "30%", "inclusionIncrease": "45%", "absenteeismReduction": "20%", "managerMoraleIncrease": "25%", "projectedAnnualSavings": "$250,000"}.`;

            const jsonString = await callGemini(prompt);
            
            try {
                // Sanitize the response to ensure it's valid JSON
                const sanitizedJsonString = jsonString.trim().replace(/```json/g, '').replace(/```/g, '');
                const data = JSON.parse(sanitizedJsonString);
                const metrics = [
                    { label: 'Stress Reduction', value: data.stressReduction, change: 'down' },
                    { label: 'Inclusion & Community', value: data.inclusionIncrease, change: 'up' },
                    { label: 'Absenteeism Reduction', value: data.absenteeismReduction, change: 'down' },
                    { label: 'Manager-Rated Morale', value: data.managerMoraleIncrease, change: 'up' },
                ];
                
                metrics.forEach(metric => {
                    const icon = metric.change === 'up' 
                        ? '<svg class="w-6 h-6 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6"></path></svg>'
                        : '<svg class="w-6 h-6 text-red-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 17l-5-5m0 0l5-5m5 5H6"></path></svg>';
                    
                    reportOutput.innerHTML += `
                        <div class="bg-white p-4 rounded-lg shadow">
                            <p class="text-sm text-gray-500">${metric.label}</p>
                            <div class="flex items-center justify-center gap-2 mt-1">
                                ${icon}
                                <p class="text-2xl font-bold text-gray-800">${metric.value}</p>
                            </div>
                        </div>
                    `;
                });

                // Add savings separately as it's a key metric
                reportOutput.innerHTML += `
                    <div class="col-span-2 sm:col-span-3 bg-green-100 p-4 rounded-lg shadow border border-green-200">
                        <p class="text-sm text-green-700 font-semibold">Projected Annual Savings</p>
                        <p class="text-3xl font-bold text-green-800 mt-1">${data.projectedAnnualSavings}</p>
                    </div>
                `;

            } catch (e) {
                console.error("Failed to parse JSON response:", jsonString);
                reportOutput.innerHTML = '<p class="text-red-500 col-span-full">Error: Could not parse the AI response. Please try again.</p>';
            }

            reportLoader.classList.add('hidden');
            reportOutput.classList.remove('hidden');
            reportGenerateBtn.disabled = false;
        });

        // --- Feature 3: Stakeholder Communication Assistant ---
        commGenerateBtn.addEventListener('click', async () => {
            const stakeholder = commStakeholderInput.value;
            const format = commFormatInput.value;
            const notes = commNotesInput.value.trim();

            commLoader.classList.remove('hidden');
            commOutput.classList.add('hidden');
            commGenerateBtn.disabled = true;

            const prompt = `You are an expert communications strategist for Sage Sanctuary Wellness. Your task is to generate a communication draft for the specified stakeholder and format.

            Context: Sage Sanctuary Wellness provides an integrated system combining sensory wellness experiences (like mobile saunas) with a data platform to deliver measurable ROI, talent retention, and risk reduction for large corporations. Our pilot program showed a 32% stress reduction, 48% inclusion increase, and $180K projected annual savings for a 300-employee company.

            Stakeholder: ${stakeholder}
            Format: ${format}
            Additional Notes: ${notes || 'None'}

            Instructions:
            - If the stakeholder is a CFO, focus heavily on the financial metrics: cost savings from reduced absenteeism, ROI, and replacing vendor sprawl with a single, cost-effective contract.
            - If the stakeholder is a CHRO, focus on talent retention, employee morale, burnout reduction, and creating a positive company culture that is also compliance-safe.
            - If the stakeholder is a CEO, provide a high-level summary blending financial ROI, strategic advantage (talent magnet), and brand resilience/risk reduction.
            - If the stakeholder is a COO, focus on operational efficiency: reducing absenteeism, increasing productivity, and the simplicity of an end-to-end system (no vendor sprawl).
            - If the format is an Email Draft, write a complete, professional email with a subject line, greeting, body, and closing.
            - If the format is Key Talking Points, use clear, concise bullet points that are easy to deliver in a meeting.
            - Incorporate any additional notes provided by the user.
            - The tone should be professional, confident, and persuasive.`;

            const generatedText = await callGemini(prompt);
            commOutput.textContent = generatedText;
            
            commLoader.classList.add('hidden');
            commOutput.classList.remove('hidden');
            commGenerateBtn.disabled = false;
        });

    </script>
</body>
</html>
