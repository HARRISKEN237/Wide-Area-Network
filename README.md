# Wide-Area-Network
ASSESMENTS 2
Name: OTANG DESMOND HARRISKEN
Matricule: ICTU20234300

1. What are Cloud Services?
In simple terms, a cloud service is like renting computing power over the internet instead of owning and running your own expensive hardware. Companies like Amazon, Microsoft, and Google own and maintain huge data centers. They let you use their servers, storage, and software on an as-needed basis. This means you can easily get more power when you need it and scale back when you don't, all without a big upfront cost.

	A Real-World Example: Think about healthcare. Hospitals now use the cloud to securely store patient records. This means a doctor can pull up a patient's full medical history from any hospital computer, or even a clinic in a different town. This helps medical teams work together better because everyone has the same up-to-date information, which leads to improved patient care.

	How Cloud Changes Our Lives: The cloud has basically put powerful technology within reach for everyone. Because you only pay for what you use (a "pay-as-you-go" model), it's affordable for everyone from giant corporations to a single student. It's the reason we can work from anywhere and why services like Netflix for streaming or Slack for team communication work so smoothly.

 
 
 2. A Problem in Our Community:
There's a major issue holding back our farmers here in Yaoundé: the system for getting food from farms to markets is inefficient and lacks clear information. Cameroon is often called the "Granary of Central Africa," and farming is a huge part of our economy. But our local farmers run into big problems:

	It's hard to get accurate, up-to-date information from rural areas about what crops are available, their prices, and how to transport them.
	Different governments and private groups often use systems that don't "talk" to each other, either because they aren't using digital tools or because they work in isolation.
	This disconnect and lack of shared information leads to a lot of food going to be wasted, farmers earning less money, and you and I paying higher prices on the market.



3. Detailed Project Description: The Yaoundé Digital Agriculture Platform:
The Yaoundé Digital Agriculture Platform is a comprehensive, cloud-based solution designed to directly address the critical inefficiencies within our local agricultural supply chain. The core problem is one of fragmentation: farmers, transporters, traders, and government bodies operate in informational silos. This project aims to create a centralized digital "town square" where all these actors can connect, share data, and transact, thereby reducing waste, increasing farmers' incomes, and stabilizing market prices.

The project's architecture is intentionally designed for scalability and resilience, built on a hybrid cloud model. This means we leverage the immense power and flexibility of global public cloud services (like Google Cloud Platform) for data processing and analytics, while also maintaining a local data server here in Yaoundé. This local node is crucial. It ensures that our platform remains fast and responsive for users across the city and its surrounding rural areas by reducing latency. Furthermore, it addresses national data sovereignty concerns by keeping sensitive agricultural and user data securely within Cameroon's borders, aligning with governmental digital governance initiatives.

The platform itself is structured in three interconnected layers:

The User Application Layer (SaaS): This is the face of the project—a simple, intuitive mobile app and website accessible on smartphones and basic tablets. The interface will use clear icons and local languages to ensure ease of use for farmers with varying levels of digital literacy. Through this app, farmers can instantly list their available produce (e.g., "100kg of ripe tomatoes from Mfoundi"), view real-time price data from major markets, and request transportation services. Buyers and cooperatives can browse these listings, contact farmers directly, and place bulk orders.

The Core Platform Layer (PaaS): This is the "brain" of the operation, hosted on a cloud Platform-as-a-Service. Our development team will build and manage the application logic here without the burden of maintaining underlying hardware or operating systems. This layer is responsible for integrating all the data, running analytics to generate insights like price trends and optimal delivery routes, and managing user accounts and security.

The Connectivity & Infrastructure Layer (WAN): A robust Wide Area Network (WAN) is the project's backbone. To ensure reliable service, especially in peri-urban and rural zones with unstable internet, we will deploy a multi-technology approach. This includes using microwave radio links to create a high-speed, carrier-independent backbone between our main data center and key agricultural collection points, a method proven effective in Cameroon. We are also evaluating partnerships with satellite internet providers like Starlink to provide connectivity to the most remote pilot cooperatives, ensuring no one is left offline.

Implementation and Impact:
Deployment will be phased, starting with a pilot program partnering with three major farmer cooperatives in the Yaoundé region. We will equip these cooperatives with ruggedized tablets and provide comprehensive training. The pilot phase will focus on refining the platform based on user feedback.

The expected impact is transformative. By creating market transparency, the platform empowers farmers to negotiate from a position of knowledge, directly increasing their profitability. The efficient matching of supply with demand and transport will significantly reduce post-harvest losses. For the first time, government agencies will have access to a reliable, real-time dashboard of regional agricultural data, enabling informed policy-making, strategic food reserve planning, and targeted support. This project is more than a technological tool; it is a foundational step towards building a resilient, data-driven, and prosperous agricultural economy for Yaoundé, fully supporting the ambitions of Cameroon's Vision 2035.

System Architecture Description:
Top Layer: User Access Layer
On the left, draw icons of different users: A Farmer (with a smartphone), A Transporter (with a truck), A Buyer/Merchant (with a market stall).
From each user icon, draw an arrow pointing towards a central cloud icon labeled "User Application (SaaS)".
Label this entire section: "Access via Mobile App & Web Portal".

Middle Layer: Core Processing & Cloud Layer
Draw a large cloud shape in the center. Inside the cloud, place the following components:
A server rack icon labeled "Core Platform (PaaS - Google Cloud/Azure)".
A cylinder/database icon labeled "Central Cloud Database".
A brain icon or chart icon labeled "Analytics & Insights Engine".
Below the central cloud, draw a server rack on the ground labeled "Local Yaoundé Data Center". Connect this local server to the central cloud with a two-way arrow, labeling the connection "Secure Data Sync".

Bottom Layer: Connectivity & Physical Infrastructure Layer
Draw a series of towers with microwave waves between them, labeled "Microwave Network Backbone".
You can also draw a satellite icon beaming a signal down to a dish, labeled "Satellite Internet (e.g., Starlink) for Remote Areas".
Draw arrows from these connectivity icons pointing up towards the User Access Layer, showing how the connection is established.

Connecting the Layers:
Use a two-way arrow to connect the "User Application (SaaS)" in the Top Layer down to the "Core Platform (PaaS)" in the Middle Layer.
Ensure the "Local Yaoundé Data Center" has a direct connection line to the users in the Top Layer, symbolizing low-latency access.
This diagram visually summarizes the entire technical proposal, showing how users connect through a simple app to a powerful, hybrid cloud brain, which is itself supported by a resilient network.
