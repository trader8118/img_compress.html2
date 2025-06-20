<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Free online image compression tool. Reduce image file size while maintaining quality. Supports JPG, PNG, and WebP formats.">
    <meta name="keywords" content="image compressor, reduce image size, optimize images, free image tool, online photo compressor">
    <meta name="author" content="ImageCompressorPro">
    <meta name="robots" content="index, follow">
    <meta property="og:title" content="Free Online Image Compression Tool">
    <meta property="og:description" content="Compress your images online for free with adjustable quality settings.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://yourwebsite.com/image-compressor">
    <title>ImageCompressorPro | Free Online Image Optimization Tool</title>
    <link rel="canonical" href="https://yourwebsite.com/image-compressor">
    <style>
        :root {
            --primary-color: #4285f4;
            --secondary-color: #34a853;
            --accent-color: #ea4335;
            --light-gray: #f5f5f5;
            --dark-gray: #333;
            --medium-gray: #757575;
        }
        
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: var(--dark-gray);
            background-color: #f9f9f9;
            padding: 0;
            margin: 0;
        }
        
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--primary-color);
            text-decoration: none;
        }
        
        .logo span {
            color: var(--accent-color);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 1.5rem;
        }
        
        nav ul li a {
            text-decoration: none;
            color: var(--dark-gray);
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: var(--primary-color);
        }
        
        main {
            padding: 2rem 0;
            min-height: calc(100vh - 150px);
        }
        
        .hero {
            text-align: center;
            margin-bottom: 2rem;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: var(--dark-gray);
        }
        
        .hero p {
            font-size: 1.1rem;
            color: var(--medium-gray);
            max-width: 700px;
            margin: 0 auto 1.5rem;
        }
        
        .compressor-container {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            padding: 2rem;
            margin-bottom: 2rem;
        }
        
        .upload-area {
            border: 2px dashed var(--primary-color);
            border-radius: 8px;
            padding: 3rem 1rem;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            margin-bottom: 1.5rem;
            position: relative;
            background-color: rgba(66, 133, 244, 0.05);
        }
        
        .upload-area:hover {
            background-color: rgba(66, 133, 244, 0.1);
        }
        
        .upload-area i {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 1rem;
            display: block;
        }
        
        .upload-area p {
            margin-bottom: 0.5rem;
        }
        
        #file-input {
            display: none;
        }
        
        .controls {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            margin-bottom: 1.5rem;
        }
        
        .control-group {
            flex: 1;
            min-width: 250px;
        }
        
        .control-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 500;
        }
        
        .slider-container {
            display: flex;
            align-items: center;
            gap: 1rem;
        }
        
        .slider-container input[type="range"] {
            flex: 1;
        }
        
        .slider-container span {
            min-width: 40px;
            text-align: center;
        }
        
        select, button {
            width: 100%;
            padding: 0.75rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1rem;
            background-color: white;
        }
        
        button {
            background-color: var(--primary-color);
            color: white;
            border: none;
            cursor: pointer;
            font-weight: 500;
            transition: background-color 0.3s;
        }
        
        button:hover {
            background-color: #3367d6;
        }
        
        button:disabled {
            background-color: var(--medium-gray);
            cursor: not-allowed;
        }
        
        .results {
            display: none;
            margin-top: 2rem;
            border-top: 1px solid #eee;
            padding-top: 1.5rem;
        }
        
        .comparison {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            margin-bottom: 1.5rem;
        }
        
        .image-box {
            flex: 1;
            min-width: 300px;
            text-align: center;
        }
        
        .image-box img {
            max-width: 100%;
            max-height: 300px;
            border-radius: 4px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }
        
        .image-info {
            margin-top: 0.5rem;
            font-size: 0.9rem;
            color: var(--medium-gray);
        }
        
        .stats {
            display: flex;
            justify-content: space-around;
            background-color: var(--light-gray);
            padding: 1rem;
            border-radius: 4px;
            margin-bottom: 1.5rem;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-value {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary-color);
        }
        
        .stat-label {
            font-size: 0.8rem;
            color: var(--medium-gray);
        }
        
        .download-btn {
            display: inline-block;
            background-color: var(--secondary-color);
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 500;
            transition: background-color 0.3s;
        }
        
        .download-btn:hover {
            background-color: #2d9246;
        }
        
        .ad-container {
            margin: 2rem 0;
            text-align: center;
            background-color: var(--light-gray);
            padding: 1rem;
            border-radius: 4px;
        }
        
        .ad-label {
            font-size: 0.8rem;
            color: var(--medium-gray);
            margin-bottom: 0.5rem;
            text-transform: uppercase;
        }
        
        footer {
            background-color: var(--dark-gray);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        .footer-content {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .footer-links {
            display: flex;
            gap: 1.5rem;
            margin: 1rem 0;
        }
        
        .footer-links a {
            color: white;
            text-decoration: none;
        }
        
        .footer-links a:hover {
            text-decoration: underline;
        }
        
        .copyright {
            font-size: 0.9rem;
            color: #aaa;
        }
        
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 1rem;
                justify-content: center;
            }
            
            nav ul li {
                margin: 0 0.75rem;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .controls {
                flex-direction: column;
                gap: 1rem;
            }
            
            .comparison {
                flex-direction: column;
            }
        }
        
        /* Loading spinner */
        .spinner {
            display: none;
            width: 40px;
            height: 40px;
            margin: 0 auto;
            border: 4px solid rgba(0, 0, 0, 0.1);
            border-radius: 50%;
            border-top: 4px solid var(--primary-color);
            animation: spin 1s linear infinite;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        /* Breadcrumb */
        .breadcrumb {
            padding: 1rem 0;
            font-size: 0.9rem;
        }
        
        .breadcrumb a {
            color: var(--primary-color);
            text-decoration: none;
        }
        
        .breadcrumb a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <div class="container header-content">
            <a href="/" class="logo">Image<span>Compressor</span>Pro</a>
            <nav>
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/features">Features</a></li>
                    <li><a href="/blog">Blog</a></li>
                    <li><a href="/contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <main class="container">
        <div class="breadcrumb">
            <a href="/">Home</a> &gt; <span>Image Compressor</span>
        </div>
        
        <div class="hero">
            <h1>Free Online Image Compression Tool</h1>
            <p>Reduce your image file size without sacrificing quality. Perfect for websites, social media, and email attachments.</p>
        </div>
        
        <!-- Top Ad Banner -->
        <div class="ad-container">
            <div class="ad-label">Advertisement</div>
            <!-- Replace with your Google AdSense code -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_ADSENSE_ID"
                crossorigin="anonymous"></script>
            <!-- ImageCompressor_Top_Banner -->
            <ins class="adsbygoogle"
                style="display:block"
                data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                data-ad-slot="YOUR_AD_SLOT_ID"
                data-ad-format="auto"
                data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
        
        <div class="compressor-container">
            <div class="upload-area" id="upload-area">
                <i>📁</i>
                <p>Drag & drop your image here or click to browse</p>
                <p class="small">Supports JPG, PNG, GIF, and WebP formats</p>
                <input type="file" id="file-input" accept="image/*">
            </div>
            
            <div class="controls">
                <div class="control-group">
                    <label for="quality">Compression Level</label>
                    <div class="slider-container">
                        <input type="range" id="quality" min="0" max="100" value="80">
                        <span id="quality-value">80%</span>
                    </div>
                </div>
                
                <div class="control-group">
                    <label for="format">Output Format</label>
                    <select id="format">
                        <option value="auto">Auto (Same as input)</option>
                        <option value="jpeg">JPEG</option>
                        <option value="png">PNG</option>
                        <option value="webp">WebP (Recommended)</option>
                    </select>
                </div>
            </div>
            
            <button id="compress-btn" disabled>Compress Image</button>
            
            <div class="spinner" id="spinner"></div>
            
            <div class="results" id="results">
                <div class="stats">
                    <div class="stat-item">
                        <div class="stat-value" id="original-size">0 KB</div>
                        <div class="stat-label">Original Size</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-value" id="compressed-size">0 KB</div>
                        <div class="stat-label">Compressed Size</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-value" id="reduction">0%</div>
                        <div class="stat-label">Reduction</div>
                    </div>
                </div>
                
                <div class="comparison">
                    <div class="image-box">
                        <h3>Original Image</h3>
                        <img id="original-img" src="" alt="Original image">
                        <div class="image-info" id="original-info"></div>
                    </div>
                    <div class="image-box">
                        <h3>Compressed Image</h3>
                        <img id="compressed-img" src="" alt="Compressed image">
                        <div class="image-info" id="compressed-info"></div>
                    </div>
                </div>
                
                <div style="text-align: center; margin-top: 1.5rem;">
                    <a href="#" class="download-btn" id="download-btn">Download Compressed Image</a>
                </div>
            </div>
        </div>
        
        <!-- Middle Ad Banner -->
        <div class="ad-container">
            <div class="ad-label">Advertisement</div>
            <!-- Replace with your Google AdSense code -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_ADSENSE_ID"
                crossorigin="anonymous"></script>
            <!-- ImageCompressor_Middle_Banner -->
            <ins class="adsbygoogle"
                style="display:block"
                data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                data-ad-slot="YOUR_AD_SLOT_ID"
                data-ad-format="auto"
                data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
        
        <section class="info-section">
            <h2>How to Compress Images Online</h2>
            <p>Our free image compressor helps you reduce image file size while maintaining good quality. Follow these simple steps:</p>
            <ol>
                <li>Upload your image by dragging and dropping or clicking the upload area</li>
                <li>Adjust the compression level using the slider (higher = better quality, larger file)</li>
                <li>Select your preferred output format (WebP recommended for best compression)</li>
                <li>Click "Compress Image" and wait a few seconds</li>
                <li>Download your optimized image</li>
            </ol>
            
            <h2>Why Compress Images?</h2>
            <p>Image compression is essential for:</p>
            <ul>
                <li><strong>Faster website loading:</strong> Smaller images load faster, improving user experience and SEO</li>
                <li><strong>Reduced bandwidth usage:</strong> Save on hosting costs and mobile data</li>
                <li><strong>Better storage efficiency:</strong> Store more images in the same space</li>
                <li><strong>Improved email deliverability:</strong> Smaller attachments are more likely to be delivered</li>
            </ul>
        </section>
        
        <!-- Bottom Ad Banner -->
        <div class="ad-container">
            <div class="ad-label">Advertisement</div>
            <!-- Replace with your Google AdSense code -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_ADSENSE_ID"
                crossorigin="anonymous"></script>
            <!-- ImageCompressor_Bottom_Banner -->
            <ins class="adsbygoogle"
                style="display:block"
                data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                data-ad-slot="YOUR_AD_SLOT_ID"
                data-ad-format="auto"
                data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
    </main>
    
    <footer>
        <div class="container footer-content">
            <a href="/" class="logo" style="color: white;">Image<span style="color: #fbbc05;">Compressor</span>Pro</a>
            <div class="footer-links">
                <a href="/privacy">Privacy Policy</a>
                <a href="/terms">Terms of Service</a>
                <a href="/contact">Contact Us</a>
                <a href="/faq">FAQ</a>
            </div>
            <p class="copyright">© 2023 ImageCompressorPro. All rights reserved.</p>
        </div>
    </footer>
    
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // DOM elements
            const uploadArea = document.getElementById('upload-area');
            const fileInput = document.getElementById('file-input');
            const qualitySlider = document.getElementById('quality');
            const qualityValue = document.getElementById('quality-value');
            const formatSelect = document.getElementById('format');
            const compressBtn = document.getElementById('compress-btn');
            const spinner = document.getElementById('spinner');
            const results = document.getElementById('results');
            const originalImg = document.getElementById('original-img');
            const compressedImg = document.getElementById('compressed-img');
            const originalInfo = document.getElementById('original-info');
            const compressedInfo = document.getElementById('compressed-info');
            const originalSize = document.getElementById('original-size');
            const compressedSize = document.getElementById('compressed-size');
            const reduction = document.getElementById('reduction');
            const downloadBtn = document.getElementById('download-btn');
            
            let originalFile = null;
            let compressedBlob = null;
            
            // Update quality value display
            qualitySlider.addEventListener('input', function() {
                qualityValue.textContent = this.value + '%';
            });
            
            // Handle drag and drop
            uploadArea.addEventListener('dragover', function(e) {
                e.preventDefault();
                this.style.backgroundColor = 'rgba(66, 133, 244, 0.2)';
            });
            
            uploadArea.addEventListener('dragleave', function() {
                this.style.backgroundColor = 'rgba(66, 133, 244, 0.05)';
            });
            
            uploadArea.addEventListener('drop', function(e) {
                e.preventDefault();
                this.style.backgroundColor = 'rgba(66, 133, 244, 0.05)';
                
                if (e.dataTransfer.files.length) {
                    handleFile(e.dataTransfer.files[0]);
                }
            });
            
            // Handle click to browse
            uploadArea.addEventListener('click', function() {
                fileInput.click();
            });
            
            // Handle file selection
            fileInput.addEventListener('change', function() {
                if (this.files.length) {
                    handleFile(this.files[0]);
                }
            });
            
            // Handle file processing
            function handleFile(file) {
                // Check if file is an image
                if (!file.type.match('image.*')) {
                    alert('Please select an image file (JPEG, PNG, GIF, or WebP)');
                    return;
                }
                
                originalFile = file;
                
                // Display original image
                const reader = new FileReader();
                reader.onload = function(e) {
                    originalImg.src = e.target.result;
                    
                    // Display file info
                    const fileSize = (file.size / 1024).toFixed(2);
                    originalInfo.textContent = `${file.name} (${fileSize} KB)`;
                    originalSize.textContent = `${fileSize} KB`;
                    
                    // Enable compress button
                    compressBtn.disabled = false;
                    
                    // Hide previous results
                    results.style.display = 'none';
                };
                reader.readAsDataURL(file);
            }
            
            // Handle compression
            compressBtn.addEventListener('click', function() {
                if (!originalFile) return;
                
                // Show loading spinner
                spinner.style.display = 'block';
                compressBtn.disabled = true;
                
                // Use setTimeout to allow UI to update before compression starts
                setTimeout(() => {
                    compressImage(originalFile);
                }, 100);
            });
            
            // Image compression function
            function compressImage(file) {
                const quality = parseInt(qualitySlider.value) / 100;
                const format = formatSelect.value === 'auto' 
                    ? file.type.split('/')[1] 
                    : formatSelect.value;
                
                const reader = new FileReader();
                reader.onload = function(event) {
                    const img = new Image();
                    img.onload = function() {
                        const canvas = document.createElement('canvas');
                        const ctx = canvas.getContext('2d');
                        
                        // Calculate new dimensions if needed (for very large images)
                        let width = img.width;
                        let height = img.height;
                        const maxDimension = 2000; // Max width or height
                        
                        if (width > height && width > maxDimension) {
                            height *= maxDimension / width;
                            width = maxDimension;
                        } else if (height > maxDimension) {
                            width *= maxDimension / height;
                            height = maxDimension;
                        }
                        
                        canvas.width = width;
                        canvas.height = height;
                        
                        // Draw image on canvas
                        ctx.drawImage(img, 0, 0, width, height);
                        
                        // Compress image
                        canvas.toBlob(function(blob) {
                            compressedBlob = blob;
                            
                            // Display compressed image
                            const compressedUrl = URL.createObjectURL(blob);
                            compressedImg.src = compressedUrl;
                            
                            // Calculate and display stats
                            const originalSizeBytes = file.size;
                            const compressedSizeBytes = blob.size;
                            const reductionPercent = ((originalSizeBytes - compressedSizeBytes) / originalSizeBytes * 100).toFixed(2);
                            
                            compressedSize.textContent = `${(compressedSizeBytes / 1024).toFixed(2)} KB`;
                            reduction.textContent = `${reductionPercent}%`;
                            
                            // Set download link
                            const compressedFileName = file.name.replace(/\.[^/.]+$/, '') + '_compressed.' + format;
                            downloadBtn.href = compressedUrl;
                            downloadBtn.download = compressedFileName;
                            
                            // Display file info
                            compressedInfo.textContent = `${compressedFileName} (${(compressedSizeBytes / 1024).toFixed(2)} KB)`;
                            
                            // Hide spinner and show results
                            spinner.style.display = 'none';
                            results.style.display = 'block';
                            compressBtn.disabled = false;
                            
                            // Track download event
                            downloadBtn.addEventListener('click', function() {
                                // You could add analytics here
                                console.log('Downloaded compressed image');
                            });
                            
                        }, `image/${format}`, quality);
                    };
                    
                    img.src = event.target.result;
                };
                
                reader.readAsDataURL(file);
            }
            
            // Initialize tooltips or other UI elements if needed
            // Add any additional initialization code here
        });
    </script>
    
    <!-- Schema.org markup for SEO -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "WebApplication",
        "name": "ImageCompressorPro - Free Online Image Compression Tool",
        "url": "https://yourwebsite.com/image-compressor",
        "description": "Free online tool to compress and optimize your images. Reduce file size while maintaining quality for websites, social media, and email.",
        "applicationCategory": "ImageEditor",
        "operatingSystem": "Any",
        "offers": {
            "@type": "Offer",
            "price": "0",
            "priceCurrency": "USD"
        },
        "creator": {
            "@type": "Organization",
            "name": "ImageCompressorPro"
        }
    }
    </script>
</body>
</html>
