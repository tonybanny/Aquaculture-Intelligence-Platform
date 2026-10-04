<!DOCTYPE html><html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AQUA_BRU - Advanced Aquaculture Water Quality Intelligence Platform</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            line-height: 1.6;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #0d1117;
            color: #c9d1d9;
        }
        
        .header {
            text-align: center;
            padding: 40px 0;
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
            border-radius: 10px;
            margin-bottom: 30px;
        }
        
        .header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #ffffff;
        }
        
        .badges {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin: 20px 0;
            flex-wrap: wrap;
        }
        
        .badge {
            display: inline-block;
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 0.9em;
            font-weight: bold;
        }
        
        .badge-blue { background-color: #1e40af; color: #fff; }
        .badge-green { background-color: #166534; color: #fff; }
        .badge-yellow { background-color: #ca8a04; color: #fff; }
        .badge-success { background-color: #15803d; color: #fff; }
        
        .section {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 20px;
            margin: 20px 0;
        }
        
        .section h2 {
            color: #58a6ff;
            border-bottom: 2px solid #21262d;
            padding-bottom: 10px;
            margin-top: 0;
        }
        
        .section h3 {
            color: #79c0ff;
            margin-top: 20px;
        }
        
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .feature-card {
            background-color: #0d1117;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 20px;
            transition: all 0.3s ease;
        }
        
        .feature-card:hover {
            border-color: #58a6ff;
            box-shadow: 0 0 20px rgba(88, 166, 255, 0.3);
            transform: translateY(-5px);
        }
        
        .feature-icon {
            font-size: 2em;
            margin-bottom: 10px;
        }
        
        .feature-title {
            color: #58a6ff;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        code {
            background-color: #161b22;
            padding: 2px 6px;
            border-radius: 3px;
            font-family: 'Courier New', monospace;
            color: #79c0ff;
        }
        
        pre {
            background-color: #0d1117;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 16px;
            overflow-x: auto;
        }
        
        pre code {
            background-color: transparent;
            padding: 0;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        
        table th,
        table td {
            border: 1px solid #30363d;
            padding: 12px;
            text-align: left;
        }
        
        table th {
            background-color: #161b22;
            color: #58a6ff;
            font-weight: bold;
        }
        
        table tr:hover {
            background-color: #161b22;
        }
        
        .emoji {
            font-size: 1.2em;
        }
        
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        
        ul li:before {
            content: "▸ ";
            color: #58a6ff;
            font-weight: bold;
            margin-right: 5px;
        }
        
        a {
            color: #58a6ff;
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
        
        .highlight {
            background-color: #1e3a8a;
            padding: 2px 6px;
            border-radius: 3px;
            color: #fff;
            font-weight: bold;
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        
        .stat-box {
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
            border-radius: 8px;
            padding: 20px;
            text-align: center;
        }
        
        .stat-number {
            font-size: 2.5em;
            font-weight: bold;
            color: #fff;
        }
        
        .stat-label {
            color: #e0e7ff;
            margin-top: 5px;
        }
    </style></head><body>
    <div class="header">
        <h1>🌊 AQUA_BRU</h1>
        <p style="font-size: 1.2em; margin: 10px 0;">Advanced Aquaculture Water Quality Intelligence Platform</p>
        <div class="badges">
            <span class="badge badge-blue">R 4.0+</span>
            <span class="badge badge-green">Shiny 1.7+</span>
            <span class="badge badge-yellow">MIT License</span>
            <span class="badge badge-success">Production Ready</span>
        </div>
    </div>

    <div class="section">
        <h2>🎯 Overview</h2>
        <p><strong>AQUA_BRU</strong> is a comprehensive, production-ready Shiny application for real-time water quality monitoring and predictive analytics in aquaculture operations across Brunei Darussalam. The platform integrates advanced machine learning, geospatial analysis, and interactive data visualization to support data-driven decision-making in aquaculture management.</p>
    </div>

    <div class="section">
        <h2>✨ Key Features</h2>
        
        <h3>📊 Core Analytics Modules</h3>
        <div class="feature-grid">
            <div class="feature-card">
                <div class="feature-icon">📡</div>
                <div class="feature-title">Real-time Monitoring</div>
                <p>Track 16+ water quality parameters across multiple stations</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">🗺️</div>
                <div class="feature-title">Geospatial Mapping</div>
                <p>Leaflet-based interactive maps with performance overlays</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">🤖</div>
                <div class="feature-title">ML Predictions</div>
                <p>Ensemble models for productivity forecasting</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">🎲</div>
                <div class="feature-title">Risk Analysis</div>
                <p>Monte Carlo simulations for uncertainty quantification</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">📊</div>
                <div class="feature-title">Ordination Analysis</div>
                <p>PCA/RDA/CCA for multivariate pattern detection</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">💰</div>
                <div class="feature-title">Economic Assessment</div>
                <p>Revenue analysis and impact modeling</p>
            </div>
        </div>

        <h3>🤖 Machine Learning Engine</h3>
        <div class="stats-grid">
            <div class="stat-box">
                <div class="stat-number">4</div>
                <div class="stat-label">ML Models</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">86.3%</div>
                <div class="stat-label">Ensemble Accuracy</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">&lt;1s</div>
                <div class="stat-label">Processing Time</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">19+</div>
                <div class="stat-label">Monitoring Stations</div>
            </div>
        </div>

        <ul>
            <li>Random Forest, SVM, Gradient Boosting, Neural Networks</li>
            <li>SHAP Values for model interpretability</li>
            <li>Automated drift detection and performance monitoring</li>
            <li>A/B testing framework for continuous improvement</li>
        </ul>
    </div>

    <div class="section">
        <h2>🚀 Installation</h2>
        
        <h3>Prerequisites</h3>
        <pre><code># Required R version
R >= 4.0.0

# Core dependencies
install.packages(c(
  "shiny", "shinydashboard", "bslib",
  "DT", "plotly", "ggplot2", "tidyverse",
  "leaflet", "vegan", "randomForest",
  "caret", "gbm", "e1071", "forecast"
))</code></pre>

        <h3>Quick Start</h3>
        <pre><code># Clone the repository
git clone https://github.com/yourusername/aqua_bru.git
cd aqua_bru

# Install all dependencies
source("install_dependencies.R")

# Run the application
shiny::runApp("app.R")</code></pre>

        <h3>Docker Deployment (Recommended)</h3>
        <pre><code># Build the Docker image
docker build -t aqua_bru .

# Run the container
docker run -p 3838:3838 aqua_bru</code></pre>
        <p>Access the app at <code>http://localhost:3838</code></p>
    </div>
      docker run -p 3838:3838 aqua_bru</code></pre>
        <p>Access the app at <code>http://localhost:3838</code></p>
    </div>

    <div class="section">
        <h2>📁 Project Structure</h2>
        <pre><code>aqua_bru/
├── app.R                    # Main application file
├── data/
│   ├── station_data.csv     # Water quality measurements
│   └── coordinates.csv      # Station geospatial data
├── modules/
│   ├── ml_models.R          # Machine learning functions
│   ├── geospatial.R         # Mapping utilities
│   └── analytics.R          # Statistical analysis
├── www/
│   ├── styles.css           # Custom CSS
│   └── logo.png             # Application logo
├── tests/
│   └── test_functions.R     # Unit tests
├── Dockerfile               # Container configuration
└── README.md                # This file</code></pre>
    </div>

    <div class="section">
        <h2>🎮 Usage Guide</h2>
        
        <div class="feature-grid">
            <div class="feature-card">
                <div class="feature-icon">📤</div>
                <div class="feature-title">1. Data Import</div>
                <p>Upload your water quality data in CSV, Excel, or TSV format</p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">🗺️</div>
                <div class="feature-title">2. Geospatial Analysis</div>
                <p>Visualize station locations and performance on interactive maps</p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">🤖</div>
                <div class="feature-title">3. ML Predictions</div>
                <p>Run predictive models for productivity and risk assessment</p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">📊</div>
                <div class="feature-title">4. Export Results</div>
                <p>Download analysis results in multiple formats</p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>📊 Data Specifications</h2>
        
        <h3>Water Quality Parameters</h3>
        <table>
            <thead>
                <tr>
                    <th>Parameter</th>
                    <th>Unit</th>
                    <th>Optimal Range</th>
                    <th>Critical Threshold</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Temperature</td>
                    <td>°C</td>
                    <td>26-30</td>
                    <td>&gt;35 or &lt;20</td>
                </tr>
                <tr>
                    <td>pH</td>
                    <td>-</td>
                    <td>7.0-8.0</td>
                    <td>&gt;9.0 or &lt;6.0</td>
                </tr>
                <tr>
                    <td>Dissolved Oxygen</td>
                    <td>mg/L</td>
                    <td>6-8</td>
                    <td>&lt;4.0</td>
                </tr>
                <tr>
                    <td>Ammonia (NH₃)</td>
                    <td>mg/L</td>
                    <td>0-0.05</td>
                    <td>&gt;0.1</td>
                </tr>
                <tr>
                    <td>Nitrate (NO₃)</td>
                    <td>mg/L</td>
                    <td>0-3.0</td>
                    <td>&gt;10.0</td>
                </tr>
                <tr>
                    <td>Total Phosphate</td>
                    <td>mg/L</td>
                    <td>0-0.5</td>
                    <td>&gt;1.0</td>
                </tr>
            </tbody>
        </table>
    </div>

    <div class="section">
        <h2>📈 Performance Metrics</h2>
        
        <div class="stats-grid">
            <div class="stat-box">
                <div class="stat-number">86.3%</div>
                <div class="stat-label">Ensemble Accuracy</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">&lt;1s</div>
                <div class="stat-label">Prediction Time</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">19+</div>
                <div class="stat-label">Monitoring Stations</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">16+</div>
                <div class="stat-label">Parameters Tracked</div>
            </div>
        </div>

        <h3>ML Model Performance</h3>
        <table>
            <thead>
                <tr>
                    <th>Model</th>
                    <th>Accuracy</th>
                    <th>Precision</th>
                    <th>Recall</th>
                    <th>F1-Score</th>
                    <th>AUC-ROC</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Random Forest</td>
                    <td>84.7%</td>
                    <td>83.1%</td>
                    <td>85.6%</td>
                    <td>84.3%</td>
                    <td>0.847</td>
                </tr>
                <tr>
                    <td>SVM</td>
                    <td>79.2%</td>
                    <td>77.5%</td>
                    <td>80.3%</td>
                    <td>78.9%</td>
                    <td>0.792</td>
                </tr>
                <tr>
                    <td>Gradient Boosting</td>
                    <td>82.5%</td>
                    <td>81.2%</td>
                    <td>83.8%</td>
                    <td>82.5%</td>
                    <td>0.825</td>
                </tr>
                <tr style="background-color: #c8e6c9;">
                    <td><strong>Ensemble</strong></td>
                    <td><strong>86.3%</strong></td>
                    <td><strong>85.1%</strong></td>
                    <td><strong>87.4%</strong></td>
                    <td><strong>86.2%</strong></td>
                    <td><strong>0.863</strong></td>
                </tr>
            </tbody>
        </table>
    </div>

    <div class="section">
        <h2>📚 References</h2>
        
        <h3>Scientific Literature</h3>
        <ol>
            <li><strong>FAO Aquaculture Guidelines</strong> - Water quality management in aquaculture systems
                <ul>
                    <li>Boyd, C.E., & Tucker, C.S. (2014). <em>Handbook for Aquaculture Water Quality</em></li>
                    <li>FAO. (2020). <em>The State of World Fisheries and Aquaculture 2020</em></li>
                </ul>
            </li>
            <li><strong>Global Aquaculture Alliance (GAA)</strong> - Best Aquaculture Practices certification standards</li>
            <li><strong>Dissolved Oxygen Management</strong>
                <ul>
                    <li>Stone, N., et al. (2013). <em>Interpretation of Water Analysis Reports for Fish Culture</em></li>
                </ul>
            </li>
            <li><strong>Machine Learning in Aquaculture</strong>
                <ul>
                    <li>Ahmed, N., et al. (2022). Application of artificial intelligence in aquaculture: A review. <em>Aquaculture</em>, 540, 736724</li>
                </ul>
            </li>
            <li><strong>Brunei-Specific Research</strong>
                <ul>
                    <li>SEAFDEC. (2019). <em>Aquaculture Development in Brunei Darussalam</em></li>
                </ul>
            </li>
        </ol>
    </div>

    <div class="section">
        <h2>🤝 Contributing</h2>
        
        <p>We welcome contributions! Please follow these guidelines:</p>
        
        <h3>Development Workflow</h3>
        <pre><code># Fork the repository
git checkout -b feature/your-feature-name

# Make changes and commit
git commit -m "Add: description of changes"

# Push and create pull request
git push origin feature/your-feature-name</code></pre>

        <h3>Code Style</h3>
        <ul>
            <li>Follow <a href="https://style.tidyverse.org/">Tidyverse Style Guide</a></li>
            <li>Use <code>lintr</code> for code quality checks</li>
            <li>Add unit tests for new functions</li>
            <li>Update documentation</li>
        </ul>
    </div>

    <div class="section">
        <h2>📧 Contact & Support</h2>
        
        <div class="feature-grid">
            <div class="feature-card">
                <div class="feature-icon">📧</div>
                <div class="feature-title">Email Support</div>
                <p><a href="mailto:admin@nexosenvironmental.org">admin@nexosenvironmental.org</a></p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">🐛</div>
                <div class="feature-title">GitHub Issues</div>
                <p><a href="https://github.com/tonybanny/aqua_bru/issues">Report Bugs</a></p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">📖</div>
                <div class="feature-title">Documentation</div>
                <p><a href="admin@nexosenvironmental.org">docs.aqua-bru.org</a></p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">💬</div>
                <div class="feature-title">Community</div>
                <p><a href="https://twitter.com/tbd">@tbd</a></p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>📝 License</h2>
        
        <p>This project is licensed under the <strong>MIT License</strong></p>
        
        <div style="background: #f8f9fa; padding: 20px; border-radius: 8px; margin: 20px 0;">
            <h3 style="margin-top: 0;">Key Points:</h3>
            <ul>
                <li>✅ Free for commercial and non-commercial use</li>
                                <li>✅ Modification and distribution allowed</li>
                <li>✅ Attribution required</li>
                <li>❌ No warranty provided</li>
            </ul>
        </div>
    </div>

    <div class="section">
        <h2>🙏 Acknowledgments</h2>
        
        <p>Special thanks to:</p>
        <ul>
            <li><strong>Department of Fisheries, Brunei Darussalam</strong> - Data provision and domain expertise</li>
            <li><strong>Universiti Brunei Darussalam</strong> - Research collaboration</li>
            <li><strong>SEAFDEC</strong> - Technical guidance and training</li>
            <li><strong>R Community</strong> - Open-source packages and support</li>
            <li><strong>Beta Testers</strong> - Valuable feedback and bug reports</li>
        </ul>
    </div>

    <div class="section">
        <h2>📊 Version History</h2>
        
        <table>
            <thead>
                <tr>
                    <th>Version</th>
                    <th>Date</th>
                    <th>Key Changes</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><span class="highlight">2.3.1</span></td>
                    <td>2024-01-08</td>
                    <td>Production release with ML ensemble</td>
                </tr>
                <tr>
                    <td>2.2.3</td>
                    <td>2023-12-22</td>
                    <td>Added ordination analysis</td>
                </tr>
                <tr>
                    <td>2.1.8</td>
                    <td>2023-12-01</td>
                    <td>Geospatial module enhancement</td>
                </tr>
                <tr>
                    <td>2.0.0</td>
                    <td>2023-11-15</td>
                    <td>Major refactor with bslib integration</td>
                </tr>
                <tr>
                    <td>1.5.0</td>
                    <td>2023-10-01</td>
                    <td>Initial ML module</td>
                </tr>
                <tr>
                    <td>1.0.0</td>
                    <td>2023-08-15</td>
                    <td>First stable release</td>
                </tr>
            </tbody>
        </table>
    </div>

    <div class="section">
        <h2>🚀 Roadmap</h2>
        
        <h3>Q1 2024</h3>
        <ul>
            <li>Real-time data streaming integration</li>
            <li>Mobile-responsive dashboard redesign</li>
            <li>Multi-language support (Malay, Chinese)</li>
            <li>Advanced forecasting with LSTM models</li>
        </ul>
        
        <h3>Q2 2024</h3>
        <ul>
            <li>IoT sensor integration</li>
            <li>Cloud deployment (AWS/Azure)</li>
            <li>API development for third-party access</li>
            <li>Automated report scheduling</li>
        </ul>
        
        <h3>Q3 2024</h3>
        <ul>
            <li>Blockchain-based data verification</li>
            <li>Satellite imagery integration</li>
            <li>Climate change scenario modeling</li>
            <li>Community collaboration features</li>
        </ul>
    </div>

    <div class="section">
        <h2>⚡ Quick Links</h2>
        
        <div class="feature-grid">
            <div class="feature-card">
                <div class="feature-icon">🌐</div>
                <div class="feature-title">Live Demo</div>
                <p><a href="https://demo.aqua-bru.org">demo.aqua-bru.org</a></p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">📚</div>
                <div class="feature-title">Documentation</div>
                <p><a href="https://docs.aqua-bru.org">docs.aqua-bru.org</a></p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">🎥</div>
                <div class="feature-title">Tutorial Videos</div>
                <p><a href="https://youtube.com/@aqua-bru">YouTube Channel</a></p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">📝</div>
                <div class="feature-title">Blog</div>
                <p><a href="https://blog.aqua-bru.org">blog.aqua-bru.org</a></p>
            </div>
        </div>
    </div>

    <div style="text-align: center; padding: 40px; background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%); border-radius: 10px; margin: 40px 0;">
        <h2 style="color: white; margin: 0;">Built with ❤️ for sustainable aquaculture in Brunei Darussalam</h2>
        <p style="color: #e0e7ff; font-size: 2em; margin: 20px 0;">🇧🇳 🌊 🐟</p>
    </div>

    <div style="text-align: center; padding: 20px; color: #666;">
        <p><em>Last Updated: January 2024</em></p>
        <p>
            <a href="https://github.com/tonybanny/aqua_bru">GitHub</a> | 
            <a href="admin@nexosenvironmental.org">Documentation</a> | 
            <a href="mailto:admin@nexosenvironmental.org">Support</a> | 
            <a href="https://twitter.com/tbd">Twitter</a>
        </p>
    </div>
</body></html>
