# Tool
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Enhanced SEO Meta Tags -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Free online tool to compress JPG, PNG & WebP images. Reduce file size up to 90% while maintaining quality. No registration required.">
    <meta name="keywords" content="image compressor, photo size reducer, optimize images, free image tool, webp converter, jpg optimizer, png compressor">
    <meta name="author" content="ImageCompressorPro">
    <meta name="robots" content="index, follow">
    <meta name="theme-color" content="#4285f4">
    
    <!-- Open Graph / Social Media Meta Tags -->
    <meta property="og:title" content="ImageCompressorPro | Free Online Image Compression Tool">
    <meta property="og:description" content="Compress your images online for free. Reduce file size without losing quality. Supports JPG, PNG, and WebP formats.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://yourdomain.com">
    <meta property="og:image" content="https://yourdomain.com/images/compressor-preview.jpg">
    <meta property="og:site_name" content="ImageCompressorPro">
    
    <!-- Twitter Card Meta Tags -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="ImageCompressorPro | Free Online Image Compression Tool">
    <meta name="twitter:description" content="Compress your images online for free. Reduce file size without losing quality.">
    <meta name="twitter:image" content="https://yourdomain.com/images/compressor-preview.jpg">
    
    <!-- Canonical URL -->
    <link rel="canonical" href="https://yourdomain.com">
    
    <!-- Favicon -->
    <link rel="icon" href="/favicon.ico" type="image/x-icon">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    
    <!-- Structured Data -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "WebApplication",
      "name": "ImageCompressorPro",
      "url": "https://yourdomain.com",
      "description": "Free online tool to compress and optimize your images",
      "applicationCategory": "UtilityApplication",
      "operatingSystem": "Any",
      "offers": {
        "@type": "Offer",
        "price": "0",
        "priceCurrency": "USD"
      }
    }
    </script>
    
    <title>ImageCompressorPro | Free Online Image Compression Tool</title>
    
    <style>
        :root {
            --primary-color: #4285f4;
            --primary-light: #e8f0fe;
            --secondary-color: #34a853;
            --accent-color: #ea4335;
            --light-gray: #f8f9fa;
            --medium-gray: #e9ecef;
            --dark-gray: #212529;
            --text-color: #2d3748;
            --text-light: #718096;
            --shadow-sm: 0 1px 3px rgba(0,0,0,0.12);
            --shadow-md: 0 4px 6px rgba(0,0,0,0.1);
            --shadow-lg: 0 10px 15px rgba(0,0,0,0.1);
            --radius-sm: 4px;
            --radius-md: 8px;
            --radius-lg: 12px;
            --transition: all 0.2s ease-in-out;
        }
        
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: #f9f9f9;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }
        
        @supports (font-variation-settings: normal) {
            body { font-family: 'Inter var', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif; }
        }
        
        /* Typography */
        h1, h2, h3, h4 {
            font-weight: 700;
            line-height: 1.2;
            margin-bottom: 1rem;
            color: var(--dark-gray);
        }
        
        h1 { font-size: 2.5rem; }
        h2 { font-size: 2rem; }
        h3 { font-size: 1.5rem; }
        
        p {
            margin-bottom: 1rem;
            color: var(--text-light);
        }
        
        a {
            color: var(--primary-color);
            text-decoration: none;
            transition: var(--transition);
        }
        
        a:hover {
            color: #3367d6;
            text-decoration: underline;
        }
        
        /* Layout */
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1.5rem;
        }
        
        /* Header */
        header {
            background-color: white;
            box-shadow: var(--shadow-sm);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.5rem;
            font-weight: 800;
            color: var(--primary-color);
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .logo svg {
            width: 28px;
            height: 28px;
        }
        
        nav {
            display: flex;
            gap: 1.5rem;
        }
        
        nav a {
            font-weight: 500;
            color: var(--dark-gray);
        }
        
        nav a:hover {
            color: var(--primary-color);
            text-decoration: none;
        }
        
        /* Main Content */
        main {
            padding: 2.5rem 0;
        }
        
        /* Hero Section */
        .hero {
            text-align: center;
            margin-bottom: 3rem;
        }
        
        .hero h1 {
            font-size: 2.75rem;
            margin-bottom: 1.5rem;
            background: linear-gradient(90deg, #4285f4, #34a853, #fbbc05, #ea4335);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .hero p {
            font-size: 1.25rem;
            max-width: 700px;
            margin: 0 auto 2rem;
        }
        
        /* Ad Banners */
        .ad-banner {
            background-color: var(--light-gray);
            padding: 1rem;
            text-align: center;
            margin: 2rem 0;
            border-radius: var(--radius-md);
            overflow: hidden;
        }
        
        /* Compressor Container */
        .compressor-container {
            background-color: white;
            border-radius: var(--radius-lg);
            box-shadow: var(--shadow-md);
            padding: 2.5rem;
            margin-bottom: 2.5rem;
            transition: var(--transition);
        }
        
        .compressor-container:hover {
            box-shadow: var(--shadow-lg);
        }
        
        /* Upload Area */
        .upload-area {
            border: 2px dashed var(--medium-gray);
            border-radius: var(--radius-md);
            padding: 3rem 1rem;
            text-align: center;
            cursor: pointer;
            transition: var(--transition);
            margin-bottom: 2rem;
            background-color: var(--light-gray);
            position: relative;
            overflow: hidden;
        }
        
        .upload-area:hover {
            border-color: var(--primary-color);
            background-color: var(--primary-light);
        }
        
        .upload-area.active {
            border-color: var(--secondary-color);
            background-color: rgba(52, 168, 83, 0.05);
        }
        
        .upload-icon {
            font-size: 3.5rem;
            color: var(--primary-color);
            margin-bottom: 1.5rem;
        }
        
        .upload-area h3 {
            margin-bottom: 0.5rem;
        }
        
        #file-input {
            display: none;
        }
        
        /* Controls */
        .controls {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-bottom: 2rem;
        }
        
        .control-group {
            display: flex;
            flex-direction: column;
        }
        
        label {
            display: block;
            margin-bottom: 0.75rem;
            font-weight: 600;
            color: var(--dark-gray);
        }
        
        select, input[type="range"] {
            width: 100%;
            padding: 0.875rem 1rem;
            border: 1px solid var(--medium-gray);
            border-radius: var(--radius-sm);
            font-size: 1rem;
            background-color: white;
            transition: var(--transition);
        }
        
        select:focus, input[type="range"]:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 3px rgba(66, 133, 244, 0.2);
        }
        
        input[type="range"] {
            padding: 0;
            -webkit-appearance: none;
            height: 8px;
            background: var(--medium-gray);
            border-radius: 4px;
            margin-top: 0.5rem;
        }
        
        input[type="range"]::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 20px;
            height: 20px;
            background: var(--primary-color);
            border-radius: 50%;
            cursor: pointer;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: var(--transition);
        }
        
        input[type="range"]::-webkit-slider-thumb:hover {
            transform: scale(1.1);
        }
        
        .range-value {
            display: inline-block;
            margin-left: 0.5rem;
            font-weight: bold;
            color: var(--primary-color);
        }
        
        /* Buttons */
        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            padding: 0.875rem 1.75rem;
            font-size: 1rem;
            font-weight: 600;
            border-radius: var(--radius-sm);
            cursor: pointer;
            transition: var(--transition);
            border: none;
            text-align: center;
        }
        
        .btn-primary {
            background-color: var(--primary-color);
            color: white;
        }
        
        .btn-primary:hover {
            background-color: #3367d6;
            transform: translateY(-1px);
            box-shadow: var(--shadow-sm);
        }
        
        .btn-primary:disabled {
            background-color: #b3caf5;
            cursor: not-allowed;
            transform: none;
            box-shadow: none;
        }
        
        .btn-secondary {
            background-color: var(--secondary-color);
            color: white;
        }
        
        .btn-secondary:hover {
            background-color: #2d9249;
            transform: translateY(-1px);
            box-shadow: var(--shadow-sm);
        }
        
        .btn-block {
            width: 100%;
        }
        
        /* Results Section */
        .results {
            display: none;
            margin-top: 2.5rem;
            animation: fadeIn 0.5s;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .comparison {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 2.5rem;
        }
        
        .image-box {
            display: flex;
            flex-direction: column;
        }
        
        .image-box img {
            width: 100%;
            height: auto;
            border-radius: var(--radius-md);
            box-shadow: var(--shadow-sm);
            margin-bottom: 1rem;
        }
        
        .image-info {
            padding: 1.25rem;
            background-color: var(--light-gray);
            border-radius: var(--radius-md);
            flex-grow: 1;
        }
        
        /* Stats Cards */
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin-top: 2.5rem;
        }
        
        .stat-card {
            padding: 1.5rem;
            background-color: white;
            border-radius: var(--radius-md);
            box-shadow: var(--shadow-sm);
            text-align: center;
            transition: var(--transition);
        }
        
        .stat-card:hover {
            transform: translateY(-3px);
            box-shadow: var(--shadow-md);
        }
        
        .stat-value {
            font-size: 2.25rem;
            font-weight: 800;
            margin-bottom: 0.5rem;
        }
        
        .quality-stat { color: var(--primary-color); }
        .savings-stat { color: var(--secondary-color); }
        .size-stat { color: var(--accent-color); }
        
        .stat-label {
            color: var(--text-light);
            font-size: 0.95rem;
        }
        
        /* Ad Sidebar */
        .ad-sidebar {
            background-color: var(--light-gray);
            padding: 1.5rem;
            border-radius: var(--radius-md);
            margin-bottom: 2.5rem;
            text-align: center;
            overflow: hidden;
        }
        
        /* Footer */
        footer {
            background-color: var(--dark-gray);
            color: white;
            padding: 3rem 0 2rem;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }
        
        .footer-column h4 {
            color: white;
            margin-bottom: 1.25rem;
            font-size: 1.25rem;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 0.75rem;
        }
        
        .footer-links a {
            color: #adb5bd;
        }
        
        .footer-links a:hover {
            color: white;
            text-decoration: none;
        }
        
        .copyright {
            text-align: center;
            color: #adb5bd;
            font-size: 0.9rem;
            padding-top: 2rem;
            border-top: 1px solid #495057;
        }
        
        /* Responsive Adjustments */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 1rem;
            }
            
            nav {
                gap: 1rem;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1.1rem;
            }
            
            .compressor-container {
                padding: 1.5rem;
            }
            
            .upload-area {
                padding: 2rem 1rem;
            }
        }
        
        @media (max-width: 480px) {
            .container {
                padding: 0 1rem;
            }
            
            .hero h1 {
                font-size: 1.75rem;
            }
            
            .controls {
                grid-template-columns: 1fr;
            }
            
            .comparison {
                grid-template-columns: 1fr;
            }
        }
        
        /* Loading Animation */
        .loading {
            display: none;
            text-align: center;
            margin: 1rem 0;
        }
        
        .loading-spinner {
            display: inline-block;
            width: 40px;
            height: 40px;
            border: 4px solid rgba(66, 133, 244, 0.2);
            border-radius: 50%;
            border-top-color: var(--primary-color);
            animation: spin 1s ease-in-out infinite;
        }
        
        @keyframes spin {
            to { transform: rotate(360deg); }
        }
        
        /* Tooltip */
        .tooltip {
            position: relative;
            display: inline-block;
            margin-left: 0.5rem;
            cursor: help;
        }
        
        .tooltip-icon {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 18px;
            height: 18px;
            background-color: var(--medium-gray);
            color: var(--text-light);
            border-radius: 50%;
            font-size: 0.75rem;
            font-weight: bold;
        }
        
        .tooltip-text {
            visibility: hidden;
            width: 200px;
            background-color: var(--dark-gray);
            color: white;
            text-align: center;
            border-radius: var(--radius-sm);
            padding: 0.5rem;
            position: absolute;
            z-index: 1;
            bottom: 125%;
            left: 50%;
            transform: translateX(-50%);
            opacity: 0;
            transition: opacity 0.3s;
            font-size: 0.875rem;
            font-weight: normal;
        }
        
        .tooltip:hover .tooltip-text {
            visibility: visible;
            opacity: 1;
        }
    </style>
</head>
<body>
    <header>
        <div class="container header-content">
            <a href="/" class="logo">
                <svg viewBox="0 0 24 24" fill="currentColor">
                    <path d="M5 3h14a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2zm2 4v2h10V7H7zm0 4v2h10v-2H7zm0 4v2h7v-2H7z"/>
                </svg>
                ImageCompressorPro
            </a>
            <nav>
                <a href="#">Home</a>
                <a href="#">Features</a>
                <a href="#">Guide</a>
                <a href="#">Contact</a>
            </nav>
        </div>
    </header>
    
    <div class="container">
        <!-- Top Banner Ad -->
        <div class="ad-banner">
            <!-- AdSense Code -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_PUBLISHER_ID"></script>
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-YOUR_PUBLISHER_ID"
                 data-ad-slot="YOUR_AD_SLOT_ID"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
        
        <main>
            <section class="hero">
                <h1>Optimize Your Images in Seconds</h1>
                <p>Reduce image file sizes without sacrificing quality. Perfect for websites, social media, and email attachments.</p>
            </section>
            
            <div class="compressor-container">
                <div class="upload-area" id="upload-area">
                    <div class="upload-icon">📁</div>
                    <h3>Drag & Drop Your Images Here</h3>
                    <p>or click to select files (JPG, PNG, WebP supported)</p>
                    <input type="file" id="file-input" accept="image/*">
                </div>
                
                <div class="controls">
                    <div class="control-group">
                        <label for="format">
                            Output Format
                            <span class="tooltip">
                                <span class="tooltip-icon">?</span>
                                <span class="tooltip-text">WebP offers best compression, JPEG is most compatible, PNG preserves transparency</span>
                            </span>
                        </label>
                        <select id="format">
                            <option value="auto">Auto (Recommended)</option>
                            <option value="jpeg">JPEG</option>
                            <option value="png">PNG</option>
                            <option value="webp">WebP</option>
                        </select>
                    </div>
                    
                    <div class="control-group">
                        <label for="quality">
                            Quality: <span id="quality-value" class="range-value">80</span>%
                            <span class="tooltip">
                                <span class="tooltip-icon">?</span>
                                <span class="tooltip-text">Higher values preserve more quality but result in larger files</span>
                            </span>
                        </label>
                        <input type="range" id="quality" min="1" max="100" value="80">
                    </div>
                    
                    <div class="control-group">
                        <label for="resize">
                            Resize (Max Width)
                            <span class="tooltip">
                                <span class="tooltip-icon">?</span>
                                <span class="tooltip-text">Resize images to specific dimensions while maintaining aspect ratio</span>
                            </span>
                        </label>
                        <select id="resize">
                            <option value="original">Original Size</option>
                            <option value="800">800px (Social Media)</option>
                            <option value="1200">1200px (Blog Content)</option>
                            <option value="1920">1920px (HD Displays)</option>
                            <option value="custom">Custom Size</option>
                        </select>
                        <input type="number" id="custom-size" style="display: none; margin-top: 0.5rem;" placeholder="Enter width in pixels" min="100">
                    </div>
                </div>
                
                <button id="compress-btn" class="btn btn-primary btn-block" disabled>
                    <span id="btn-text">Compress Image</span>
                </button>
                
                <div class="loading" id="loading">
                    <div class="loading-spinner"></div>
                    <p>Processing your image...</p>
                </div>
                
                <div class="results" id="results">
                    <h2>Compression Results</h2>
                    <p>See how much you've saved while maintaining great quality</p>
                    
                    <div class="comparison">
                        <div class="image-box">
                            <h3>Original Image</h3>
                            <img id="original-img" src="" alt="Original image before compression">
                            <div class="image-info">
                                <p id="original-size">Size: 0 KB</p>
                                <p id="original-dimensions">Dimensions: 0 × 0 px</p>
                                <p id="original-format">Format: -</p>
                            </div>
                        </div>
                        
                        <div class="image-box">
                            <h3>Compressed Image</h3>
                            <img id="compressed-img" src="" alt="Compressed image after optimization">
                            <div class="image-info">
                                <p id="compressed-size">Size: 0 KB</p>
                                <p id="compressed-dimensions">Dimensions: 0 × 0 px</p>
                                <p id="compressed-format">Format: -</p>
                                <button class="btn btn-secondary" id="download-btn">Download Compressed Image</button>
                            </div>
                        </div>
                    </div>
                    
                    <div class="stats">
                        <div class="stat-card">
                            <div class="stat-value quality-stat" id="quality-percent">0%</div>
                            <div class="stat-label">Quality Preserved</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-value savings-stat" id="savings-percent">0%</div>
                            <div class="stat-label">File Size Reduction</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-value size-stat" id="savings-kb">0 KB</div>
                            <div class="stat-label">Total Savings</div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Sidebar Ad -->
            <div class="ad-sidebar">
                <!-- AdSense Code -->
                <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_PUBLISHER_ID"></script>
                <ins class="adsbygoogle"
                     style="display:block"
                     data-ad-client="ca-pub-YOUR_PUBLISHER_ID"
                     data-ad-slot="YOUR_AD_SLOT_ID"
                     data-ad-format="auto"
                     data-full-width-responsive="true"></ins>
                <script>
                     (adsbygoogle = window.adsbygoogle || []).push({});
                </script>
            </div>
            
            <!-- Features Section -->
            <section class="compressor-container">
                <h2>Why Use Our Image Compressor?</h2>
                <div class="comparison">
                    <div class="image-box">
                        <h3>⚡ Faster Websites</h3>
                        <p>Optimized images load quicker, improving your site's performance and SEO rankings.</p>
                    </div>
                    <div class="image-box">
                        <h3>📱 Mobile Friendly</h3>
                        <p>Reduce data usage for mobile visitors with properly sized images.</p>
                    </div>
                    <div class="image-box">
                        <h3>🔒 Privacy Focused</h3>
                        <p>All processing happens in your browser - your images never leave your device.</p>
                    </div>
                </div>
            </section>
        </main>
    </div>
    
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h4>ImageCompressorPro</h4>
                    <p>The fastest way to optimize your images for web and mobile.</p>
                </div>
                <div class="footer-column">
                    <h4>Quick Links</h4>
                    <ul class="footer-links">
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Features</a></li>
                        <li><a href="#">How It Works</a></li>
                        <li><a href="#">FAQ</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h4>Resources</h4>
                    <ul class="footer-links">
                        <li><a href="#">Image Optimization Guide</a></li>
                        <li><a href="#">WebP vs JPEG</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                        <li><a href="#">Terms of Service</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h4>Connect</h4>
                    <ul class="footer-links">
                        <li><a href="#">Contact Us</a></li>
                        <li><a href="#">Twitter</a></li>
                        <li><a href="#">GitHub</a></li>
                        <li><a href="#">Feedback</a></li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>© 2023 ImageCompressorPro. All rights reserved.</p>
            </div>
        </div>
    </footer>
    
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // DOM Elements
            const uploadArea = document.getElementById('upload-area');
            const fileInput = document.getElementById('file-input');
            const compressBtn = document.getElementById('compress-btn');
            const btnText = document.getElementById('btn-text');
            const loading = document.getElementById('loading');
            const resultsSection = document.getElementById('results');
            const qualitySlider = document.getElementById('quality');
            const qualityValue = document.getElementById('quality-value');
            const formatSelect = document.getElementById('format');
            const resizeSelect = document.getElementById('resize');
            const customSizeInput = document.getElementById('custom-size');
            
            // Results elements
            const originalImg = document.getElementById('original-img');
            const compressedImg = document.getElementById('compressed-img');
            const originalSize = document.getElementById('original-size');
            const originalDimensions = document.getElementById('original-dimensions');
            const originalFormat = document.getElementById('original-format');
            const compressedSize = document.getElementById('compressed-size');
            const compressedDimensions = document.getElementById('compressed-dimensions');
            const compressedFormat = document.getElementById('compressed-format');
            const downloadBtn = document.getElementById('download-btn');
            const savingsPercent = document.getElementById('savings-percent');
            const savingsKB = document.getElementById('savings-kb');
            const qualityPercent = document.getElementById('quality-percent');
            
            // Event Listeners
            uploadArea.addEventListener('click', () => fileInput.click());
            uploadArea.addEventListener('dragover', (e) => {
                e.preventDefault();
                uploadArea.classList.add('active');
            });
            uploadArea.addEventListener('dragleave', () => {
                uploadArea.classList.remove('active');
            });
            uploadArea.addEventListener('drop', (e) => {
                e.preventDefault();
                uploadArea.classList.remove('active');
                if (e.dataTransfer.files.length) {
                    fileInput.files = e.dataTransfer.files;
                    handleFileSelection();
                }
            });
            
            fileInput.addEventListener('change', handleFileSelection);
            qualitySlider.addEventListener('input', updateQualityValue);
            resizeSelect.addEventListener('change', toggleCustomSize);
            compressBtn.addEventListener('click', compressImage);
            downloadBtn.addEventListener('click', downloadImage);
            
            // Functions
            function updateQualityValue() {
                qualityValue.textContent = qualitySlider.value;
                qualityPercent.textContent = `${qualitySlider.value}%`;
            }
            
            function toggleCustomSize() {
                customSizeInput.style.display = resizeSelect.value === 'custom' ? 'block' : 'none';
            }
            
            function handleFileSelection() {
                if (fileInput.files && fileInput.files[0]) {
                    const file = fileInput.files[0];
                    if (!file.type.match('image.*')) {
                        alert('Please select an image file (JPEG, PNG, WebP, etc.)');
                        return;
                    }
                    
                    // Display original image
                    const reader = new FileReader();
                    reader.onload = function(e) {
                        originalImg.src = e.target.result;
                        
                        // Get image dimensions and format
                        const img = new Image();
                        img.onload = function() {
                            originalDimensions.textContent = `Dimensions: ${img.width} × ${img.height} px`;
                            originalSize.textContent = `Size: ${formatFileSize(file.size)}`;
                            originalFormat.textContent = `Format: ${getFileType(file.type)}`;
                            
                            // Enable compress button
                            compressBtn.disabled = false;
                        };
                        img.src = e.target.result;
                    };
                    reader.readAsDataURL(file);
                }
            }
            
            function compressImage() {
                if (!fileInput.files || !fileInput.files[0]) {
                    alert('Please select an image first');
                    return;
                }
                
                const file = fileInput.files[0];
                const quality = parseInt(qualitySlider.value) / 100;
                const format = formatSelect.value === 'auto' ? getBestFormat(file.type) : formatSelect.value;
                
                // Get resize dimensions
                let maxWidth = null;
                if (resizeSelect.value === 'custom') {
                    maxWidth = parseInt(customSizeInput.value) || null;
                    if (maxWidth && maxWidth < 100) {
                        alert('Minimum width is 100px');
                        return;
                    }
                } else if (resizeSelect.value !== 'original') {
                    maxWidth = parseInt(resizeSelect.value);
                }
                
                // UI Updates
                compressBtn.disabled = true;
                btnText.textContent = 'Compressing...';
                loading.style.display = 'block';
                resultsSection.style.display = 'none';
                
                // Create an image element to work with
                const img = new Image();
                img.onload = function() {
                    // Create canvas for compression
                    const canvas = document.createElement('canvas');
                    const ctx = canvas.getContext('2d');
                    
                    // Calculate new dimensions if resizing
                    let width = img.width;
                    let height = img.height;
                    if (maxWidth && img.width > maxWidth) {
                        const ratio = maxWidth / img.width;
                        width = maxWidth;
                        height = img.height * ratio;
                    }
                    
                    canvas.width = width;
                    canvas.height = height;
                    
                    // Draw image on canvas
                    ctx.drawImage(img, 0, 0, width, height);
                    
                    // Determine output format
                    let mimeType;
                    switch(format) {
                        case 'jpeg': mimeType = 'image/jpeg'; break;
                        case 'png': mimeType = 'image/png'; break;
                        case 'webp': mimeType = 'image/webp'; break;
                        default: mimeType = 'image/jpeg';
                    }
                    
                    // Compress image
                    canvas.toBlob(function(blob) {
                        const compressedUrl = URL.createObjectURL(blob);
                        
                        // Display compressed image
                        compressedImg.src = compressedUrl;
                        compressedDimensions.textContent = `Dimensions: ${width} × ${height} px`;
                        compressedSize.textContent = `Size: ${formatFileSize(blob.size)}`;
                        compressedFormat.textContent = `Format: ${format.toUpperCase()}`;
                        
                        // Calculate savings
                        const savings = file.size - blob.size;
                        const savingsPercentage = ((savings / file.size) * 100).toFixed(1);
                        
                        savingsPercent.textContent = `${savingsPercentage}%`;
                        savingsKB.textContent = `${formatFileSize(savings)}`;
                        
                        // Show results
                        loading.style.display = 'none';
                        resultsSection.style.display = 'block';
                        
                        // Reset button
                        compressBtn.disabled = false;
                        btnText.textContent = 'Compress Another Image';
                        
                        // Update download button functionality
                        downloadBtn.onclick = function() {
                            const link = document.createElement('a');
                            link.href = compressedUrl;
                            
                            // Set the download filename
                            const originalFilename = fileInput.files[0].name;
                            const filenameWithoutExt = originalFilename.lastIndexOf('.') > 0 
                                ? originalFilename.substring(0, originalFilename.lastIndexOf('.')) 
                                : originalFilename;
                            
                            link.download = `${filenameWithoutExt}-compressed.${format}`;
                            document.body.appendChild(link);
                            link.click();
                            document.body.removeChild(link);
                        };
                    }, mimeType, quality);
                };
                
                img.src = URL.createObjectURL(file);
            }
            
            function downloadImage() {
                if (!compressedImg.src) return;
                // This function is updated in the compressImage function
            }
            
            // Helper functions
            function formatFileSize(bytes) {
                if (bytes === 0) return '0 Bytes';
                const k = 1024;
                const sizes = ['Bytes', 'KB', 'MB', 'GB'];
                const i = Math.floor(Math.log(bytes) / Math.log(k));
                return parseFloat((bytes / Math.pow(k, i)).toFixed(2)) + ' ' + sizes[i];
            }
            
            function getBestFormat(mimeType) {
                if (mimeType.includes('jpeg') || mimeType.includes('jpg')) return 'jpeg';
                if (mimeType.includes('png')) return 'png';
                if (mimeType.includes('webp')) return 'webp';
                return 'jpeg'; // default
            }
            
            function getFileType(mimeType) {
                if (mimeType.includes('jpeg') || mimeType.includes('jpg')) return 'JPEG';
                if (mimeType.includes('png')) return 'PNG';
                if (mimeType.includes('webp')) return 'WebP';
                return mimeType.split('/')[1].toUpperCase() || 'Unknown';
            }
            
            function getFileExtension(filename) {
                return filename.split('.').pop().toLowerCase();
            }
        });
    </script>
</body>
</html>
