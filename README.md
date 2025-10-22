<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fatal Error - S.T.A.L.K.E.R. Anomaly Addon</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --light-color: #ecf0f1;
            --dark-color: #1a252f;
            --success-color: #27ae60;
            --warning-color: #f39c12;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
            padding: 20px;
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        
        h1, h2, h3 {
            color: var(--primary-color);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        h2 {
            border-bottom: 2px solid var(--secondary-color);
            padding-bottom: 10px;
            margin-top: 30px;
        }
        
        h3 {
            color: var(--secondary-color);
            margin-top: 25px;
        }
        
        .section {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .feature-card {
            background-color: var(--light-color);
            padding: 15px;
            border-radius: 6px;
            border-left: 4px solid var(--secondary-color);
        }
        
        .requirement-list {
            list-style-type: none;
            padding-left: 0;
        }
        
        .requirement-list li {
            margin-bottom: 10px;
            padding-left: 25px;
            position: relative;
        }
        
        .requirement-list li:before {
            content: "✓";
            color: var(--success-color);
            position: absolute;
            left: 0;
            font-weight: bold;
        }
        
        .incompatible-list li:before {
            content: "✗";
            color: var(--accent-color);
        }
        
        .warning {
            background-color: #fff3cd;
            border-left: 4px solid var(--warning-color);
            padding: 15px;
            margin: 15px 0;
            border-radius: 4px;
        }
        
        .info {
            background-color: #d1ecf1;
            border-left: 4px solid var(--secondary-color);
            padding: 15px;
            margin: 15px 0;
            border-radius: 4px;
        }
        
        .center {
            text-align: center;
        }
        
        .spoiler {
            background-color: #f8f9fa;
            border: 1px solid #dee2e6;
            padding: 10px;
            border-radius: 4px;
            margin: 10px 0;
        }
        
        .changelog {
            max-height: 400px;
            overflow-y: auto;
            padding: 15px;
            background-color: var(--light-color);
            border-radius: 6px;
        }
        
        .version {
            font-weight: bold;
            color: var(--secondary-color);
        }
        
        .date {
            font-style: italic;
            color: #7f8c8d;
        }
        
        .btn {
            display: inline-block;
            background-color: var(--secondary-color);
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 4px;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #2980b9;
        }
        
        .image-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        
        .image-gallery img {
            width: 100%;
            height: auto;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        
        .pda-table-image {
            width: 100%;
            max-width: 800px;
            margin: 20px auto;
            display: block;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Fatal Error</h1>
        <p>An immersive device management and failure system for S.T.A.L.K.E.R. Anomaly</p>
        <a href="#download" class="btn">Download Now</a>
    </header>
    
    <div class="section">
        <h2>Overview</h2>
        <p>Fatal Error transforms how electronic devices function in the Zone, adding realistic failure mechanics, battery management, and a comprehensive PDA system with different tiers and capabilities. Experience the Zone where your equipment is as vulnerable as you are.</p>
        
        <div class="warning">
            <strong>Important:</strong> This addon requires STALKER-Anomaly-modded-exes version 2025.08.23 or later. Make sure to delete your shader cache in the launcher after installation.
        </div>
    </div>
    
    <div class="section">
        <h2>Key Features</h2>
        
        <div class="feature-grid">
            <div class="feature-card">
                <h3>Realistic Device Failures</h3>
                <p>PDAs and other electronic devices can break from emissions, psi-storms, electra anomalies, pulse anomalies, and radiation exposure. Different PDA tiers have varying resistance levels.</p>
            </div>
            
            <div class="feature-card">
                <h3>Battery Management System</h3>
                <p>Devices require specific battery types (AAA, AA, C, D, F) with unique capacities. Use the Universal Power Device (UPD) to charge batteries and manage power efficiently.</p>
            </div>
            
            <div class="feature-card">
                <h3>PDA Tiers & Capabilities</h3>
                <p>Multiple PDA models with different functionality levels - from basic information display to advanced features like squad tracking and autocomplete functions.</p>
            </div>
            
            <div class="feature-card">
                <h3>Device Damage & Repair</h3>
                <p>Devices can become damaged or completely broken. Use Device Repair Kits or visit technicians for repairs. Damaged devices may randomly shut off or malfunction.</p>
            </div>
            
            <div class="feature-card">
                <h3>PDA BIOS System</h3>
                <p>Access the PDA BIOS to view system information, toggle features like beeping, and even overclock your device (with associated risks).</p>
            </div>
            
            <div class="feature-card">
                <h3>Dynamic Glitch Effects</h3>
                <p>Visual glitches that vary by PDA model and are triggered by damage, radiation, electrical anomalies, or passive unreliability.</p>
            </div>
            
            <div class="feature-card">
                <h3>Upgrade System</h3>
                <p>Install upgrades to protect your devices from specific threats like emissions, radiation, or electrical damage.</p>
            </div>
            
            <div class="feature-card">
                <h3>Reboot Mechanics</h3>
                <p>When your PDA encounters errors, you can reboot it (default key: M) to restore functionality after a waiting period.</p>
            </div>
        </div>
    </div>
    
    <div class="section">
        <h2>Requirements & Compatibility</h2>
        
        <div class="feature-grid">
            <div>
                <h3>Requirements</h3>
                <ul class="requirement-list">
                    <li>STALKER-Anomaly-modded-exes (2025.08.23 or later)</li>
                    <li>Anomaly Mod Configuration Menu (MCM)</li>
                    <li>Shader cache cleared after installation</li>
                </ul>
            </div>
            
            <div>
                <h3>Incompatible Addons</h3>
                <ul class="requirement-list incompatible-list">
                    <li>PDA Reanimation/Reposition addons</li>
                    <li>2D PDA Mode</li>
                    <li>Warfare mode (potential issues)</li>
                </ul>
            </div>
        </div>
    </div>
    
    <div class="section">
        <h2>PDA Tiers & Capabilities</h2>
        
        <img src="https://media.moddb.com/images/members/5/4252/4251450/profile/B38C3043-883E-4ED3-8042-AF8C305.png" alt="PDA Tiers Comparison Table" class="pda-table-image">
        
        <div class="info">
            <p>The table shows the progression of PDA models available in Fatal Error, from basic Tier I devices to advanced Tier VI military-grade equipment. Each tier offers different capabilities, battery requirements, and resistance to environmental hazards.</p>
        </div>
    </div>
    
    <div class="section">
        <h2>Battery System</h2>
        
        <div class="feature-grid">
            <div class="feature-card">
                <h3>AAA Batteries</h3>
                <p><strong>Capacity:</strong> 540 mAh<br>
                <strong>Weight:</strong> 0.125<br>
                <strong>Cost:</strong> 1,080 RU<br>
                <strong>Uses:</strong> Old PDAs, flashlights, basic detectors</p>
            </div>
            
            <div class="feature-card">
                <h3>AA Batteries</h3>
                <p><strong>Capacity:</strong> 1,100 mAh<br>
                <strong>Weight:</strong> 0.250<br>
                <strong>Cost:</strong> 2,200 RU<br>
                <strong>Uses:</strong> Most PDAs, headlamps, electronic compasses</p>
            </div>
            
            <div class="feature-card">
                <h3>C Batteries</h3>
                <p><strong>Capacity:</strong> 3,800 mAh<br>
                <strong>Weight:</strong> 0.300<br>
                <strong>Cost:</strong> 3,800 RU<br>
                <strong>Uses:</strong> Modern PDAs, 1st-gen NVGs, detectors</p>
            </div>
            
            <div class="feature-card">
                <h3>D Batteries</h3>
                <p><strong>Capacity:</strong> 8,000 mAh<br>
                <strong>Weight:</strong> 0.375<br>
                <strong>Cost:</strong> 8,000 RU<br>
                <strong>Uses:</strong> Sophisticated PDAs, 2nd-gen NVGs, field radios</p>
            </div>
            
            <div class="feature-card">
                <h3>F Batteries</h3>
                <p><strong>Capacity:</strong> 10,500 mAh<br>
                <strong>Weight:</strong> 0.800<br>
                <strong>Cost:</strong> 10,500 RU<br>
                <strong>Uses:</strong> Latest NVGs, PDAs, elite detectors</p>
            </div>
            
            <div class="feature-card">
                <h3>UPD (Universal Power Device)</h3>
                <p><strong>Capacity:</strong> 5,000 mAh<br>
                <strong>Weight:</strong> 0.500<br>
                <strong>Cost:</strong> 20,000 RU<br>
                <strong>Uses:</strong> Universal charger for all battery types</p>
            </div>
        </div>
        
        <div class="info">
            <p><strong>Universal Power Device (UPD):</strong> This portable power unit can transfer energy between different battery types. Simply drag batteries onto the UPD or vice versa to charge/discharge them.</p>
        </div>
    </div>
    
    <div class="section">
        <h2>Device Failure & Damage System</h2>
        
        <div class="feature-grid">
            <div class="feature-card">
                <h3>Failure Causes</h3>
                <ul>
                    <li>Emissions and Psi-Storms</li>
                    <li>Electrical anomalies (Electra, Pulse)</li>
                    <li>Radiation exposure</li>
                    <li>Physical damage (head shots for head devices)</li>
                    <li>Passive unreliability (random failures)</li>
                </ul>
            </div>
            
            <div class="feature-card">
                <h3>Damage States</h3>
                <ul>
                    <li><strong>Damaged:</strong> Devices may randomly shut off or malfunction</li>
                    <li><strong>Broken:</strong> Complete failure requiring repair</li>
                    <li><strong>BSOD:</strong> PDA-specific blue screen of death</li>
                    <li><strong>Screen Damage:</strong> Cracked display with visual glitches</li>
                </ul>
            </div>
            
            <div class="feature-card">
                <h3>Repair Options</h3>
                <ul>
                    <li>Device Repair Kit (craftable)</li>
                    <li>Technician services (cost varies by PDA tier)</li>
                    <li>PDA reboot for software issues (M key)</li>
                </ul>
            </div>
        </div>
    </div>
    
    <div class="section">
        <h2>Media Gallery</h2>
        
        <div class="image-gallery">
            <img src="https://media.moddb.com/images/members/5/4252/4251450/profile/90.png" alt="Fatal Error Interface">
            <img src="https://media.moddb.com/images/members/5/4252/4251450/profile/0798675ytrg.jpg" alt="PDA BIOS Screen">
            <img src="https://media.moddb.com/images/members/5/4252/4251450/profile/2.jpg" alt="Device Failure">
            <img src="https://media.moddb.com/images/members/5/4252/4251450/profile/4.jpg" alt="Battery System">
            <img src="https://media.moddb.com/images/members/5/4252/4251450/profile/31242twr.jpg" alt="PDA Tiers">
            <img src="https://media.moddb.com/images/members/5/4252/4251450/profile/e2qr3wtgthgfn.jpg" alt="Visual Glitches">
        </div>
        
        <div class="center">
            <iframe width="600" height="338" src="https://www.youtube.com/embed/NLTEHxSCfso" frameborder="0" allowfullscreen></iframe>
        </div>
    </div>
    
    <div class="section">
        <h2>Installation</h2>
        
        <p>Fatal Error uses a modular FOMOD installer with the following components:</p>
        
        <div class="feature-grid">
            <div class="feature-card">
                <h3>Main Module</h3>
                <p>Core gameplay features including device failures, battery system, and PDA mechanics.</p>
            </div>
            
            <div class="feature-card">
                <h3>Storyline</h3>
                <p>Additional quest line in Red Forest with unique PDA reward.</p>
            </div>
            
            <div class="feature-card">
                <h3>G.A.M.M.A. Cumulative Patch</h3>
                <p>For G.A.M.M.A. players with all 518 addons enabled.</p>
            </div>
            
            <div class="feature-card">
                <h3>Compatibility Patches</h3>
                <p>Various patches for popular addons like Beef's NVG, Milspec PDA, etc.</p>
            </div>
            
            <div class="feature-card">
                <h3>Fixes</h3>
                <p>Various bug fixes and improvements.</p>
            </div>
        </div>
        
        <div class="warning">
            <p><strong>Important:</strong> After installation, delete your shader cache through the Anomaly launcher to prevent visual issues.</p>
        </div>
    </div>
    
    <div class="section">
        <h2>Storyline Component</h2>
        
        <p>The optional storyline adds a quest beginning in Red Forest that rewards a unique high-end PDA. Follow clues to discover the story of a lost stalker and his advanced technology.</p>
        
        <div class="spoiler">
            <p><strong>SPOILER:</strong> The quest begins with finding a broken PDA in a mine in Red Forest.</p>
        </div>
        
        <div class="center">
            <iframe width="600" height="338" src="https://www.youtube.com/embed/2TlquOHK7BM" frameborder="0" allowfullscreen></iframe>
        </div>
    </div>
    
    <div class="section">
        <h2>Configuration</h2>
        
        <p>Fatal Error is highly configurable through the Mod Configuration Menu (MCM):</p>
        
        <div class="feature-grid">
            <div class="feature-card">
                <h3>PDA Frying</h3>
                <p>Configure failure chances for different PDA tiers from emissions, electrical damage, and radiation.</p>
            </div>
            
            <div class="feature-card">
                <h3>Device Frying</h3>
                <p>Set failure chances for all electronic devices from various hazards.</p>
            </div>
            
            <div class="feature-card">
                <h3>Other Settings</h3>
                <p>Adjust radiation effects, reboot times, damage chances, and device unreliability.</p>
            </div>
        </div>
    </div>
    
    <div class="section">
        <h2 id="download">Download & Links</h2>
        
        <div class="center">
            <a href="https://www.moddb.com/mods/stalker-anomaly/addons/fatal-error" class="btn">Download on ModDB</a>
            <a href="https://github.com/Ncenka/Fatal-Error" class="btn">GitHub Repository</a>
            <a href="https://boosty.to/ncenka-sdt" class="btn">Support on Boosty</a>
        </div>
        
        <h3>Useful Links</h3>
        <ul>
            <li><a href="https://github.com/themrdemonized/xray-monolith">Modded Exes (Required)</a></li>
            <li><a href="https://www.moddb.com/mods/stalker-anomaly/addons/anomaly-mod-configuration-menu">Mod Configuration Menu (Required)</a></li>
            <li><a href="https://discord.com/channels/912320241713958912/1387494277218566454">G.A.M.M.A. Discord Topic</a></li>
            <li><a href="https://discord.com/channels/456765861953536020/1372913212114206870">Anomaly Discord Topic</a></li>
            <li><a href="https://www.moddb.com/mods/stalker-anomaly/addons/fatal-error-and-bas-hud-fix">BaS Compatibility Fix</a></li>
        </ul>
    </div>
    
    <div class="section">
        <h2>Credits & Acknowledgments</h2>
        
        <div class="feature-grid">
            <div class="feature-card">
                <h3>Original Models & Assets</h3>
                <ul>
                    <li><strong>DAR213</strong> - PDA models from PDA REPLACER - BTTR</li>
                    <li><strong>Cr3pis</strong> - Icons from Cr3pis Icon Pack</li>
                    <li><strong>Lexus2411</strong> - Kulon PDA model from Epilogue</li>
                </ul>
            </div>
            
            <div class="feature-card">
                <h3>Development Support</h3>
                <ul>
                    <li><strong>Lexus2411</strong> - Testing, sounds, models</li>
                    <li><strong>VodoXleb</strong> - Development assistance</li>
                    <li><strong>ᛈᚴᛖᛊᚹᛊᚶᚺⰓᛆᛋ</strong> - Testing and feedback</li>
                    <li><strong>OsterK</strong> - G.A.M.M.A. cumulative patch</li>
                </ul>
            </div>
            
            <div class="feature-card">
                <h3>Voice Acting</h3>
                <ul>
                    <li><strong>ReyYn</strong></li>
                    <li><strong>Melkumov</strong></li>
                    <li><strong>DЁS</strong></li>
                    <li><strong>Dungeon Master</strong></li>
                </ul>
            </div>
            
            <div class="feature-card">
                <h3>Localization</h3>
                <ul>
                    <li><strong>Jevgenikus</strong> - Ukrainian</li>
                    <li><strong>Thundard</strong> - French</li>
                    <li><strong>ntrance</strong> - Russian improvements</li>
                    <li><strong>No_Data & Stewbs</strong> - Future localization framework</li>
                </ul>
            </div>
        </div>
    </div>
    
    <div class="section">
        <h2>Changelog</h2>
        
        <div class="changelog">
            <p><span class="version">1.7.9</span> <span class="date">(22/10/2025)</span></p>
            <ul>
                <li>Texture optimization (reduced from 500MB to 240MB)</li>
                <li>Device damage system improvements</li>
                <li>Devices Unreliability setting (renamed from Passive Glitch)</li>
                <li>Shutdown timers configuration</li>
                <li>BIOS CPU crash fixes</li>
                <li>PDA model fixes</li>
                <li>Companion icons processing improvements</li>
                <li>Autocomplete and PAW integration adjustments</li>
            </ul>
            
            <p><span class="version">1.7.8.5</span> <span class="date">(05/10/2025)</span></p>
            <ul>
                <li>AOEngine BSOD crash fix</li>
                <li>FDDA and vanilla NVGs crash fixes</li>
                <li>MHz CPU detection fix</li>
                <li>Player map marker fix for G.A.M.M.A.</li>
                <li>MAC integration updates</li>
                <li>Technicians can now fix BSOD</li>
                <li>Dynamic PDA apps based on model</li>
            </ul>
            
            <p><span class="version">1.7.8</span> <span class="date">(23/08/2025)</span></p>
            <ul>
                <li>Extreme script changes - framework-based system</li>
                <li>Requires latest modded exes (2025.08.23+)</li>
                <li>UI setter for PDA - unique interfaces per model</li>
                <li>PDA generations system</li>
                <li>Device configuration tutorial file</li>
                <li>Storyline logic improvements</li>
            </ul>
            
            <!-- Additional version entries would continue here -->
            
            <p><span class="version">1.0</span> <span class="date">(11/03/2025)</span></p>
            <ul>
                <li>Initial release</li>
            </ul>
        </div>
    </div>
    
    <div class="section">
        <div class="center">
            <h3>Want to support development?</h3>
            <p>Consider supporting the developer on Boosty to help with future updates and features.</p>
            <a href="https://boosty.to/ncenka-sdt" class="btn">Support on Boosty</a>
        </div>
        
        <div class="info">
            <p><strong>For modpack creators:</strong> You may include Fatal Error in your modpack without explicit permission, but please do not separate or repackage individual components.</p>
        </div>
    </div>
</body>
</html>
