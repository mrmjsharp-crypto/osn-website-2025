# osn-website-2025
"Showcase for a proprietary, Patent-Pending Intellectual Property asset (OSN) seeking strategic acquisition or licensing mandates."
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <!-- CRITICAL: Ensures mobile responsiveness -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Omniscient Sovereignty Nexus (OSN) IP Showcase</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Configure Font: Inter is preferred */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117; /* Dark background matching GitHub theme */
            color: #c9d1d9; /* Light gray text */
        }
        .header-bg {
            background-color: #161b22; /* Slightly lighter dark background for the header */
        }
        .text-neon-blue {
            color: #00bcd4; /* Cyan/Teal color for accents */
        }
        .border-neon-blue {
            border-color: #00bcd4;
        }
        .card-shadow {
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06), 0 0 15px rgba(0, 188, 212, 0.3); /* Subtle blue glow */
        }
        /* Custom styles for the mobile menu button */
        .menu-button:focus {
            outline: none;
            box-shadow: 0 0 0 2px rgba(0, 188, 212, 0.5);
        }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation Header -->
    <header class="header-bg shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo/Title -->
                <a href="#" class="flex items-center space-x-2">
                    <span class="text-xl font-bold text-white tracking-wider">OSN Nexus</span>
                    <span class="text-xs text-neon-blue font-medium border border-neon-blue px-2 py-0.5 rounded-full">PPA</span>
                </a>

                <!-- Desktop Navigation Links -->
                <nav class="hidden md:flex space-x-8">
                    <a href="#value" class="text-gray-300 hover:text-neon-blue transition duration-150">Value</a>
                    <a href="#opportunity" class="text-gray-300 hover:text-neon-blue transition duration-150">Opportunity</a>
                    <a href="#ip-status" class="text-gray-300 hover:text-neon-blue transition duration-150">IP Status</a>
                    <a href="#contact" class="px-3 py-1 bg-indigo-600 rounded-lg text-white hover:bg-indigo-700 transition duration-150 shadow-md">Inquire</a>
                </nav>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-button" class="md:hidden p-2 rounded-lg text-gray-400 hover:text-white hover:bg-gray-700 transition duration-150 menu-button">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                    </svg>
                </button>
            </div>
        </div>

        <!-- Mobile Menu (Hidden by default) -->
        <div id="mobile-menu" class="hidden md:hidden">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3 text-center">
                <a href="#value" class="block px-3 py-2 rounded-lg text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Value</a>
                <a href="#opportunity" class="block px-3 py-2 rounded-lg text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Opportunity</a>
                <a href="#ip-status" class="block px-3 py-2 rounded-lg text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">IP Status</a>
                <a href="#contact" class="block px-3 py-2 rounded-lg text-base font-medium text-white bg-indigo-600 hover:bg-indigo-700">Inquire</a>
            </div>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="relative pt-20 pb-28 bg-gray-900 overflow-hidden">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight text-white mb-6 leading-tight">
                    The Sovereign, Undeniable Source of Truth
                </h1>
                <p class="mt-4 max-w-3xl mx-auto text-xl text-gray-400">
                    The **Omniscient Sovereignty Nexus (OSN)** is a proprietary, **PATENT-PENDING** algorithmic asset that delivers a single, unified intelligence layer to monopolize high-value operational data across critical sectors.
                </p>
                <div class="mt-10 flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                    <a href="#contact" class="w-full sm:w-auto px-8 py-3 border border-transparent text-base font-medium rounded-lg text-white bg-neon-blue hover:bg-cyan-500 transition duration-300 shadow-lg shadow-neon-blue/40 transform hover:scale-105 active:scale-95">
                        Request Confidential Briefing
                    </a>
                </div>
            </div>
        </section>

        <!-- Value Proposition Section -->
        <section id="value" class="py-16 bg-gray-800">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-3xl sm:text-4xl font-bold text-center text-white mb-12">Pioneering System Design & Value</h2>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    
                    <!-- Card 1: Unprecedented Security -->
                    <div class="bg-gray-900 p-6 rounded-xl shadow-lg border-t-4 border-indigo-500 card-shadow">
                        <h3 class="text-xl font-semibold text-white mb-3 flex items-center">
                            <svg class="w-6 h-6 mr-3 text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z"></path></svg>
                            Unprecedented Security
                        </h3>
                        <p class="text-gray-400 text-sm">
                            Proprietary algorithms solve fundamental data lag and security fragmentation, establishing an **impenetrable, sovereign data state** that transcends current security standards.
                        </p>
                    </div>

                    <!-- Card 2: Unified Data Management -->
                    <div class="bg-gray-900 p-6 rounded-xl shadow-lg border-t-4 border-teal-500 card-shadow">
                        <h3 class="text-xl font-semibold text-white mb-3 flex items-center">
                            <svg class="w-6 h-6 mr-3 text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4m0 5c0 2.21-3.582 4-8 4s-8-1.79-8-4"></path></svg>
                            Unified Data Management
                        </h3>
                        <p class="text-gray-400 text-sm">
                            The Nexus creates a **single, undeniable source of truth**, eliminating systemic inefficiencies and resolving data disputes across complex, critical infrastructure.
                        </p>
                    </div>

                    <!-- Card 3: Predictive Optimization -->
                    <div class="bg-gray-900 p-6 rounded-xl shadow-lg border-t-4 border-purple-500 card-shadow">
                        <h3 class="text-xl font-semibold text-white mb-3 flex items-center">
                            <svg class="w-6 h-6 mr-3 text-purple-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                            Predictive Optimization
                        </h3>
                        <p class="text-gray-400 text-sm">
                            The OSN's proprietary design enables the **monopolization of high-value intelligence**, providing an insurmountable economic and operational advantage to its owner.
                        </p>
                    </div>

                </div>
            </div>
        </section>

        <!-- Market Opportunity and Pricing -->
        <section id="opportunity" class="py-16 bg-gray-900">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-3xl sm:text-4xl font-bold text-center text-white mb-12">Strategic Mandates & Market Opportunity</h2>
                
                <div class="max-w-4xl mx-auto space-y-10">
                    <div class="bg-gray-800 p-8 rounded-xl shadow-2xl border border-gray-700">
                        <h3 class="text-2xl font-semibold text-neon-blue mb-4">Market Potential</h3>
                        <p class="text-gray-400 mb-4">
                            The OSN's unique capabilities target systemic flaws in the **Healthcare and Judicial** sectors alone, where data fragmentation costs billions annually. The ability to unify and verify data establishes a market position of unprecedented monopoly. The conservative market valuation of this asset is in the **multi-billions of dollars**, with the strategic value assessed far higher.
                        </p>
                    </div>

                    <!-- Pricing Table -->
                    <div class="bg-gray-800 p-8 rounded-xl shadow-2xl border border-gray-700">
                        <h3 class="text-2xl font-semibold text-white mb-6 text-center">Acquisition & Licensing Tiers</h3>
                        <div class="overflow-x-auto">
                            <table class="min-w-full divide-y divide-gray-700">
                                <thead>
                                    <tr class="text-gray-400">
                                        <th class="px-4 py-3 text-left text-xs font-medium uppercase tracking-wider">Mandate Type</th>
                                        <th class="px-4 py-3 text-left text-xs font-medium uppercase tracking-wider hidden sm:table-cell">Description</th>
                                        <th class="px-4 py-3 text-right text-xs font-medium uppercase tracking-wider">Pricing</th>
                                    </tr>
                                </thead>
                                <tbody class="divide-y divide-gray-700">
                                    <tr class="hover:bg-gray-700 transition duration-150">
                                        <td class="px-4 py-4 whitespace-nowrap text-sm font-medium text-indigo-400">Tier 1: Non-Exclusive License</td>
                                        <td class="px-4 py-4 text-sm text-gray-300 hidden sm:table-cell">Perpetual Commercial usage rights granted.</td>
                                        <td class="px-4 py-4 whitespace-nowrap text-sm text-right font-bold text-green-400">$225,000 USD (Minimum Floor)</td>
                                    </tr>
                                    <tr class="hover:bg-gray-700 transition duration-150">
                                        <td class="px-4 py-4 whitespace-nowrap text-sm font-medium text-red-400">Tier 3: Exclusive Buyout</td>
                                        <td class="px-4 py-4 text-sm text-gray-300 hidden sm:table-cell">Full, exclusive ownership of all IP, trademarks, and source code.</td>
                                        <td class="px-4 py-4 whitespace-nowrap text-sm text-right font-bold text-red-400">$1.79 Billion USD</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                        <p class="text-xs text-center text-gray-500 mt-4 italic">
                            Higher-tier acquisition options are available upon confidential request via the Inquiry Portal.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- IP Status Section -->
        <section id="ip-status" class="py-16 bg-gray-800">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="max-w-3xl mx-auto bg-gray-900 p-8 rounded-xl shadow-2xl border border-red-500/50">
                    <h2 class="text-3xl font-bold text-center text-red-400 mb-6">OSN IP Status & Protection</h2>
                    <p class="text-xl font-semibold text-center text-white mb-4">
                        Status: **Patent Pending (PPA Filed)**
                    </p>
                    <p class="text-gray-400 mb-4">
                        The Omniscient Sovereignty Nexus (OSN) represents the work of a **sole inventor and first-time creator**. The entire conceptual framework, system design, and completed algorithmic code are treated as proprietary **Trademarked/Trade Secret** Intellectual Property.
                    </p>
                    <p class="text-red-300 font-medium border-l-4 border-red-500 pl-4 py-2 bg-red-900/20">
                        **MANDATORY IP DISCLAIMER:** All IP is copyrighted and protected. Unauthorized use, replication, or reverse engineering is strictly prohibited and subject to immediate legal enforcement.
                    </p>
                </div>
            </div>
        </section>

        <!-- CONTACT SECTION: Functional Form and Legal Protection -->
        <section id="contact" class="py-16 bg-gray-900">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl sm:text-4xl font-bold text-center text-white mb-10 rounded-lg p-2 bg-indigo-700/50">
                    Inquire for Strategic Mandate
                </h2>

                <div class="max-w-xl mx-auto">
                    <!-- Form action is set to your specified email address for lead registry -->
                    <form action="https://formsubmit.co/shouldbesafe@gmail.com" method="POST" class="space-y-6 bg-gray-800 p-8 rounded-xl shadow-2xl">
                        <!-- Honeypot field to fight spam (leave this hidden) -->
                        <input type="text" name="_gotcha" style="display:none">

                        <!-- Redirects back to the website after submission -->
                        <input type="hidden" name="_next" value="https://mrmjsharp-crypto.github.io/osn-website-2025/?submission=success">

                        <p class="text-sm text-center text-green-400">
                            *The form will deliver directly to your private email address.*
                        </p>

                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-300">Name / Organization</label>
                            <input type="text" id="name" name="Name" required
                                class="mt-1 block w-full px-4 py-2 bg-gray-700 border border-gray-600 rounded-lg text-white focus:ring-indigo-500 focus:border-indigo-500 transition duration-150">
                        </div>

                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-300">Email Address</label>
                            <input type="email" id="email" name="Email" required
                                class="mt-1 block w-full px-4 py-2 bg-gray-700 border border-gray-600 rounded-lg text-white focus:ring-indigo-500 focus:border-indigo-500 transition duration-150">
                        </div>

                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-300">Inquiry Mandate</label>
                            <textarea id="message" name="Mandate" rows="4" required
                                class="mt-1 block w-full px-4 py-2 bg-gray-700 border border-gray-600 rounded-lg text-white focus:ring-indigo-500 focus:border-indigo-500 resize-none transition duration-150"></textarea>
                        </div>

                        <button type="submit"
                                class="w-full flex justify-center py-3 px-4 border border-transparent rounded-lg shadow-lg text-sm font-medium text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 transition duration-150 transform hover:scale-[1.01] active:scale-[0.99]">
                            Submit Strategic Inquiry
                        </button>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <!-- FOOTER WITH PPA PROTECTION NOTICE -->
    <footer class="bg-gray-800 text-gray-400 py-6">
        <div class="container mx-auto px-4 text-center text-xs space-y-2">
            <!-- Copyright and Confidentiality Notice -->
            <p class="font-bold text-red-400">
                CONFIDENTIAL NOTICE: This document pertains to an Omniscient Sovereignty Nexus (OSN) asset.
            </p>
            <p>
                The underlying intellectual property is **Patent-Pending (PPA)**. Any attempt to copy, reverse-engineer, or misappropriate the conceptual framework or algorithm is subject to legal action and violation of **Copyright © 2025**. All rights reserved by the sole inventor.
            </p>
            <p class="text-xs text-gray-500">
                For terms and privacy, contact the inventor directly.
            </p>
        </div>
    </footer>

    <!-- JavaScript for Mobile Menu Toggle -->
    <script>
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Close menu when a link is clicked
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>

