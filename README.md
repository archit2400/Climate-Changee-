<!DOCTYPE html>
<html>
<head>
    <title>Climate Change Website</title>
    
    <style>
        
        body {
            font-family: Arial, sans-serif;
            background-color: #F0F8FF;
            margin: 0;
            padding: 0;
        }

        
        header {
            background-color: #4682B4;
            color: white;
            text-align: center;
            padding: 20px;
        }

        
        nav {
            background-color: #B0C4DE;
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 10px;
        }

        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            
            
        }
        
        nav a:hover{
            color: black;

        }
        section {
            
            display: flex;
            justify-content: center;
            align-items: center;
            color: black;
            font-weight: 700;
            padding: 0%;
            margin: 0%;
            font-size: 25px;
            
        }
        section:nth-child(odd){
            background: #B0C4DE;
        }
        
        
        main {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 20px;
        }

        
        article {
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 80%;
            max-width: 800px;
            margin: 10px;
            padding: 20px;
        }

        
        article h2 {
            color: #4682B4;
            margin: 0;
            padding: 0;
        }

        
        article img {
            width: 500px;
            height: 250px;
        }

        
        footer {
            background-color: #4682B4;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    
    <header>
        <h1>Climate Change Website</h1>
        <p>This is a website that gives information about climate change, its effects, and its causes.</p>
    </header>
    <header>
    <nav>
        <a href="#home">Home</a>
        <a href="#effects">Effects</a>
        <a href="#Causes">Causes</a>
        <a href="#prevention">Prevention</a>
        <a href="#contact">Contact</a>
    </nav>
    </header>
    <section id="#home" class="active">Home</section>
    <main>
        
        <article>
            <h2>What is climate change?</h2><br>

            <img src="https://www.westend61.de/images/0001566666i/temperature-rising-on-global-warming-thermometer-CAIF30648.jpg" alt="A picture of the Earth with a thermometer showing rising temperatures">
            <p>Climate change is the long-term change in the average weather patterns that have come to define Earth’s local, regional and global climates. These changes have a broad range of observed effects that are synonymous with the term.</p>
            <p>Climate change is caused by factors such as biotic processes, variations in solar radiation received by Earth, plate tectonics, and volcanic eruptions. Certain human activities have also been identified as significant causes of recent climate change, often referred to as global warming.</p>
            <p>Climate change is one of the most urgent and complex challenges facing humanity today. It affects every aspect of our lives, from our health and well-being, to our food and water security, to our economy and environment. It also poses serious risks and threats to the biodiversity and ecosystems that sustain life on Earth.</p>
        </article>

        <section id="#effects" class="active">Effects</section>
    

        
        <article>
            <h2>What are the effects of climate change?</h2>
            <img src="data:image/jpeg;base64,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" alt="A picture of a flooded city, a drought-stricken land, a melting glacier, and a forest fire">
            <p>Climate change has a wide range of impacts on the natural and human systems across the world. Some of the effects of climate change are:</p>
            <ul>
                <li>Rising temperatures and heat waves, which increase the risk of heat-related illnesses and deaths, reduce crop yields, and affect the quality and availability of water.</li>
                <li>Changing precipitation patterns and extreme weather events, such as floods, droughts, storms, and wildfires, which damage infrastructure, disrupt livelihoods, and increase the spread of diseases and pests.</li>
                <li>Sea level rise and coastal erosion, which threaten the lives and properties of millions of people living in low-lying areas, and affect the health and productivity of marine and coastal ecosystems.</li>
                <li>Glacier melt and ice loss, which reduce the freshwater supply for millions of people, and affect the habitats and migration patterns of wildlife.</li>
                <li>Ocean acidification and warming, which alter the chemistry and temperature of the oceans, and affect the survival and distribution of marine life, especially coral reefs and fisheries.</li>
                <li>Loss of biodiversity and ecosystem services, which reduce the resilience and adaptability of nature, and affect the provision of essential goods and services for human well-being, such as food, water, medicine, and recreation.</li>
            </ul>
        </article>

        <section id="#Causes" class="active">Causes</section>
    
        
        <article>
            <h2>What are the causes of climate change?</h2>
            <img src="https://media.istockphoto.com/id/1315059532/video/industrial-landscape-the-pipes-of-the-thermal-power-plant-at-sunset.jpg?s=640x640&k=20&c=D0hMo6qhjrBS5cFfBqRIdTjiPw7NMeP_SFEdQa8MOkk=" alt="A picture of a factory emitting smoke, a car emitting exhaust, a cow emitting methane, and a deforested land">
            <p>Climate change is largely caused by the increase in the concentration of greenhouse gases (GHGs) in the atmosphere, which trap heat and warm the planet. The main sources of GHGs are:</p>
            <ul>
                <li>Burning of fossil fuels, such as coal, oil, and gas, for energy production, transportation, and industry, which emit carbon dioxide (CO2), the most abundant and important GHG.</li>
                <li>Agriculture, forestry, and land use change, which emit methane (CH4) and nitrous oxide (N2O), two potent GHGs, and also reduce the capacity of plants and soils to absorb CO2.</li>
                <li>Industrial processes and waste management, which emit fluorinated gases (F-gases), such as hydrofluorocarbons (HFCs), perfluorocarbons (PFCs), and sulfur hexafluoride (SF6), which have very high global warming potentials.</li>
            </ul>
            <p>Human activities are responsible for about 76% of the total GHG emissions, while natural processes account for the remaining 24%. The current level of atmospheric CO2 is about 414 parts per million (ppm), which is the highest in at least 800,000 years.</p>
        </article>
        <section id="#prevention" class="active">Prevention</section>
        
        <article>
            <h2>What are the prevention of climate change?</h2>
            <img src="data:image/jpeg;base64,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" alt="A picture of a wind farm, a solar panel, a bicycle, and a tree">
            <p>Climate change can be prevented or slowed down by reducing the emissions of GHGs and enhancing the removal of CO2 from the atmosphere. Some of the prevention measures are:</p>
            <ul>
                <li>Switching to renewable and clean sources of energy, such as solar, wind, hydro, and geothermal, which do not emit GHGs or other pollutants.</li>
                <li>Improving the energy efficiency and conservation of buildings, appliances, vehicles, and industries, which reduce the demand and consumption of fossil fuels.</li>
                <li>Promoting the use of public transportation, cycling, walking, and electric vehicles, which reduce the emissions from the transport sector.</li>
                <li>Adopting a low-carbon and plant-based diet, which reduce the emissions from the agriculture and livestock sector.</li>
                <li>Reducing, reusing, and recycling the waste materials, which reduce the emissions from the waste management sector.</li>
                <li>Protecting and restoring the forests, wetlands, grasslands, and oceans, which enhance the carbon sinks and provide other ecosystem services.</li>
                <li>Supporting the research and innovation of low-carbon technologies and practices, which enable the transition to a green and sustainable economy.</li>
                <li>Educating and raising awareness of the public and policymakers about the causes, effects, and solutions of climate change, which foster the behavioral and systemic changes needed to address the challenge.</li>
            </ul>
        </article>
    </main>
    <section id="#contacts" class="active">Contacts</section>
    <footer class="contact-section">
        <h2>Contact Us</h2>
        <p>Email: aks@gmail.com</p>
        <p>Phone: +91 1234567890</p>
       
      </footer>

    <footer>
        <p>© 2023 Climate Change Website. All rights reserved.</p>
    </footer>
<script src="script.js"></script> 
</body>
</html>
