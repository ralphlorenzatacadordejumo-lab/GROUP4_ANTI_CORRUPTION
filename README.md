# GROUP4_ANTI_CORRUPTION
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Climate Action Advocacy</title>
    <style>
        /* Basic reset and layout */
        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f9f4; /* Light green background */
            color: #333;
        }
        /* Header styling */
        header {
            background-color: #2e7d32; /* Dark green */
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.2rem;
        }
        header p {
            margin: 5px 0 0;
            font-size: 1.1rem;
        }
        /* Main container */
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        /* Sections */
        .section {
            margin-bottom: 40px;
        }
        .section h2 {
            color: #1b5e20;
            border-bottom: 2px solid #a5d6a7;
            padding-bottom: 5px;
        }
        /* Images grid */
        .image-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .image-card {
            flex: 1 1 300px; /* Responsive flex */
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            overflow: hidden;
            text-align: center;
        }
        .image-card img {
            width: 100%;
            height: 200px; /* Fixed height for consistency */
            object-fit: cover;
            display: block;
        }
        .image-card p {
            padding: 10px;
            font-size: 0.95rem;
            margin: 0;
        }
        /* Video embed container – responsive 16:9 */
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 */
            height: 0;
            overflow: hidden;
            border-radius: 8px;
            background: #000;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }
        /* Call‑to‑action list */
        ul.actions {
            list-style: disc;
            margin-left: 20px;
        }
        /* Footer */
        footer {
            background-color: #1b5e20;
            color: #fff;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Climate Action Advocacy</h1>
    <p>Join the movement to protect our planet for future generations</p>
</header>

<div class="container">

    <!-- Introduction -->
    <div class="section">
        <h2>Why Climate Action Matters</h2>
        <p>
            Climate change is one of the greatest challenges of our time. Rising temperatures, 
            extreme weather events, and melting ice caps threaten ecosystems, economies, and human health. 
            Taking decisive action now can mitigate the worst impacts and create a sustainable, 
            resilient future for all.
        </p>
    </div>

    <div class="section">
        <h2>Examples of Climate Action</h2>
        <p>People around the world are already making a difference. Here are some inspiring examples:</p>
        
        <div class="image-grid">
            <!-- Photo 1: Solar Energy (Added missing image) -->
            <div class="image-card">
                <img src="https://images.unsplash.com/photo-1509391366360-2e959784a276?auto=format&fit=crop&w=600&q=80" 
                     alt="Solar panels on a roof">
                <p><strong>Renewable Energy:</strong> Installing solar panels reduces reliance on fossil fuels and lowers carbon emissions.</p>
            </div>
            
            <!-- Photo 2: Tree Planting -->
            <div class="image-card">
                <img src="https://images.unsplash.com/photo-1542601906990-b4d3fb778b09?auto=format&fit=crop&w=600&q=80" 
                     alt="Community tree planting event">
                <p><strong>Reforestation:</strong> Community tree planting sequesters carbon, improves air quality, and restores habitats.</p>
            </div>

            <!-- Photo 3: Wind Energy (New) -->
            <div class="image-card">
                <img src="https://images.unsplash.com/photo-1466611653911-95081537e5b7?auto=format&fit=crop&w=600&q=80" 
                     alt="Wind turbines in a field">
                <p><strong>Wind Power:</strong> Harnessing wind energy provides a clean, renewable source of electricity without emissions.</p>
            </div>

            <!-- Photo 4: Recycling (New) -->
            <div class="image-card">
                <img src="https://images.unsplash.com/photo-1532996122724-e3c354a0b15b?auto=format&fit=crop&w=600&q=80" 
                     alt="Recycling sorting facility">
                <p><strong>Recycling & Waste Reduction:</strong> Proper waste management and recycling reduce landfill usage and save resources.</p>
            </div>
        </div>
    </div>

    <!-- Embedded YouTube Video -->
    <div class="section">
        <h2>Watch: Why Climate Action Is Crucial</h2>
        <div class="video-container">
            <iframe 
                src="https://www.youtube.com/embed/lU9grZFexes" 
                title="Climate Action Video" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
            </iframe>
        </div>
    </div>

    <!-- Call to Action -->
    <div class="section">
        <h2>Take Action</h2>
        <p>Every small step adds up. Here are some ways you can contribute:</p>
        <ul class="actions">
            <!-- Completed the cut-off sentence from your code -->
            <li>Reduce your energy consumption at home (turn off lights, use energy-efficient appliances) and unplug electronics when not in use.</li>
            <li>Choose sustainable transportation: walk, bike, carpool, or use public transit.</li>
            <li>Support local and organic food producers to reduce the carbon footprint of your diet.</li>
            <li>Participate in community clean-up events to protect local waterways and parks.</li>
            <li>Educate others about climate change and advocate for green policies in your community.</li>
        </ul>
    </div>

</div>

<footer>
    <p>&copy; 2023 Climate Action Advocacy. Together we can make a difference.</p>
</footer>

</body>
</html>
