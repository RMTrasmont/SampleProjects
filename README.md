
<!-- NAME STREET FGHTER 2 -->
# 🎮 Street Fighter II Character Catalog – Manually Animated iOS App

<!--TOP INTRO GIF IMAGE -->
<p align="center">
<img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/ccab9b78-c8cb-4856-9b5f-fd27f51ace87" alt="SF2IntroGif" width="300" height="600">
</p>

</p>

### Summary:
A retro-themed, manually animated iOS app inspired by Street Fighter II, designed as a scrollable character catalog featuring detailed bios, stats, and special moves. Each fighter is brought to life using 750+ individually cropped and resized animation frames, edited by hand and animated using a custom timer-based system in SwiftUI — no sprite sheets or third-party libraries required.
The project highlights deep control over frame-by-frame animation, manual asset processing, and precise timing loops — all done within SwiftUI’s modern UI architecture.

### Built With:
- SwiftUI: A fully native iOS interface using Apple's modern declarative UI framework.
- Timer-Based Image Animation: Custom animation system using Timer.publish and Image arrays to replicate motion frame-by-frame.
- Pixlr: Every character’s animation frame was manually processed (cropped/resized) using this online photo editor.
- Custom Animation Logic: Loops through static image arrays to recreate fighter animations with frame-accurate timing.
- Local Asset Management: Assets are organized, named, and rendered manually — no use of SpriteKit or animation libraries.

<!-- ADD IMAGES FOR INTRO -->
<p align="center">
<img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/41a12b41-82cb-4bfb-a858-74f5c3371ef7" alt="SF2ListGif" width="200" height="400">
    <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/5115c73a-a1a3-46e8-bfbc-3da78707eec1" alt="SF2InfoGif" width="200" height="400">
        <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/c44db048-94f8-4432-8598-4d188ccdc54a" alt="SF2MovesGif" width="200" height="400">
</p>

<p align="center">
<img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/9c48a386-faeb-45ff-9ec3-897a59ce1cf9" >
</p>

### What It Does:
- Presents a scrollable list of iconic Street Fighter II characters.
- Each character includes:
- Name, bio, origin, fighting style
- Special move list and signature fighting traits
- Frame-by-frame animation of the idle stance or signature motion
- All animations are performed using Timer-driven cycling through static frames.
- Entirely offline — all images and data are locally stored.

### Focus Areas:
- Manual Craftsmanship: Every frame was hand-edited and processed to preserve the 16-bit pixel art style.
- Pure SwiftUI Animation: No SpriteKit, Lottie, or UIKit — just native SwiftUI views and logic.
- Retro UI Design: Fonts, colors, and layout choices mimic the arcade cabinet experience.
- Precision Animation Control: Fine-tuned frame timing for authentic retro feel.
- Organized Asset Management: Structured image arrays and logic that can scale to support other games or characters.

<!-- ADD IMAGES/GIFS FOR FEATURES -->

<div align="center">
  INTRO & FIGHTER LIST
</div> 
<!-- GIF SOURCE INTRO
![sfintro1](https://github.com/user-attachments/assets/725d6ea5-34ff-45f5-8d67-d729b6018d4e)
![sfIntro2](https://github.com/user-attachments/assets/7135701f-627a-4f05-90e2-3494260f140e)
![sfIntro3](https://github.com/user-attachments/assets/cb6be351-f584-452b-9a42-289d42f49f6b)
-->
<p align="center">
     <img src="https://github.com/user-attachments/assets/725d6ea5-34ff-45f5-8d67-d729b6018d4e" alt="sfintro1" width="200" height="400">
        <img src="https://github.com/user-attachments/assets/7135701f-627a-4f05-90e2-3494260f140e" alt="sfIntro2" width="200" height="400">
         <img src="https://github.com/user-attachments/assets/cb6be351-f584-452b-9a42-289d42f49f6b" alt="sfIntro3" width="200" height="400">
</p>


<div align="center">
      FIGHTER INFO
</div> 
<!-- GIF SOURCE INFO
![sfInfo1](https://github.com/user-attachments/assets/1952e4cb-7918-47e4-959f-b48a0c8d92e5)
![sfInfo2](https://github.com/user-attachments/assets/9fc3d279-30ed-4851-8b67-69bb8ef8941d)
![sfInfo3](https://github.com/user-attachments/assets/631bf30b-89a4-42d4-b83a-84dc3cccc881)
-->

<p align="center">
    <img src="https://github.com/user-attachments/assets/1952e4cb-7918-47e4-959f-b48a0c8d92e5" alt="sfInfo1" width="200" height="400">
        <img src="https://github.com/user-attachments/assets/9fc3d279-30ed-4851-8b67-69bb8ef8941d" alt="sfInfo2" width="200" height="400">
             <img src="https://github.com/user-attachments/assets/631bf30b-89a4-42d4-b83a-84dc3cccc881" alt="sfInfo3" width="200" height="400">
</p>

<div align="center">
      MOVES LIST
</div> 

<!-- GIF SOURCE MOVES
![sfMoves1](https://github.com/user-attachments/assets/f50e4b75-42de-4bf5-b397-a137d4ab54c6)
![sfMoves2](https://github.com/user-attachments/assets/81afe401-d704-4cf4-9ee9-c8a56870f379)
![sfMoves3](https://github.com/user-attachments/assets/f6954d1a-7c2c-4365-a500-689ef58d8e9f)
-->

<p align="center">
    <img src="https://github.com/user-attachments/assets/f50e4b75-42de-4bf5-b397-a137d4ab54c6" alt="sfMoves1" width="200" height="400">
        <img src="https://github.com/user-attachments/assets/81afe401-d704-4cf4-9ee9-c8a56870f379" alt="sfMoves2" width="200" height="400">
             <img src="https://github.com/user-attachments/assets/f6954d1a-7c2c-4365-a500-689ef58d8e9f" alt="sfMoves3" width="200" height="400">
</p>


<div align="center">
  CUTTING & PROCESSING EACH IMAGE
</div>  

<p align="center">
  <img src = "https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/52108527-d30a-49f2-89e3-beb53863aed6" >
     <img src = "https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/7720b78f-8106-432c-ae0b-8485504e7822" width="300" height="300" > 
     <img src = "https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/d9419895-0c03-449b-bc4f-e3d46a820322" width="300" height="300" >
     <img src = "https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/449b1dd7-f729-43de-8e84-0e83e84fa064" width="150" height="300" >
</p>

### - Contributors
Only Self, Source code can be provided upon request of recruiter or manager

<!-- --------------------------------------------------------- END --------------------------------------------------------- -->

# Fetch Project
<p align="center">
<img src="https://github.com/user-attachments/assets/02d66525-325f-4f45-8c7e-5a96dd6ffa3e" alt="FetchIntro" width="200" height="400"> 
  <img src="https://github.com/user-attachments/assets/ce1215c6-815e-4c35-b692-7c2ea09f7b6d" alt="FetchIntroTwo" width="200" height="400"> 
</p>

### Summary:
Fetch.com take home project -- A recipes app that fetches food items from the server. The food items are displayed in a grid that can be sorted and searched. Clicking a food item reveals details such as recipes, image, videos, country of origin and an added wiki description. Links opens to webpages and video player.  

### Focus Areas:
  - Modern Swift Concurrency: used asyn/await to fetch JSON data from server. Async Image to fetch and display Images of food items.
  - NSCache: Caching Images fetched from server after initial request.
  - UIViewRepresentable: Needed to use UIViewRepresentable to work with Webkit and embed Youtube Videos in the app.
  - WebView: Used to Display sources of resipes.
  - UnitTest: Created Unit test for All Non-View files, Models, NSCaching, Mocking API Fetches, Mocking URL Session for 100% Code Coverage for all non view files.     

### Additional Info:
- How to run the project:
  1. Three Buttons on the app fetches from the three endpoints provided in the instructions (Complete, Malformed & Empty).
  2. All three responses have been handled with a default value or actions to provide a video or source.
  3. Select one of the buttons and the app will fetch and display all recipes, an empty endpoint will show an alert.
  4. After the Initial fetch, the recipes will be cached to minimize network calls.
  5. The items are in a grid and can be sorted by name, country of origin & favourites.
  6. Items can also be searched for by name or country of origin
  7. Click the items to go into it's details. There will be a brief summary from wikipedia, a large image, an option to add to favourites, a source webview link and a link to an embeded youtube player.
- Dependencies:
    There are NO dependencies.


### Extras:
- Extra Added Features:
  1. Added Alerts to handle using empty endpoints and trying to sort or search an empty recipes.
  2. Added function to automatically search for recipes in google if the source-variable is missing by using the name of the item. (malformed endpoint items: 2,3,21,27,29)
  3. Added function to automatically search for videos in youtube if the videoURL-variable is missing by using the name of the item. (malformed endpoint items: 10,35,40,57)
  4. Added Sorting be name,country of origin, or favourites.
  5. Added Search by name or country of origin.
  6. Added Favourites Option.
  7. Added Embeded Youtube Video View & Source Webview
  8. Added Refreshable method by pulling scrollview down or tool bar "Show all"
  9. Added Wikipedia summary for the food items.

<!-- VIDS FIRST SET -->
<h3 align="center">Play Youtube Video and Display Source</h3>

<p align="center">
  <img src="https://github.com/user-attachments/assets/66a52207-dfd3-4eb4-bf1b-653f95030750" alt="FetchYoutubeVid" width="200" height="400" style="margin-right: 20px;" >
  <img src="https://github.com/user-attachments/assets/83641464-b43c-423d-b233-eae929b3ed79" alt="FetchSourceVid" width="200" height="400">
</p>

<!-- VIDS SECOND SET -->
<h3 align="center">Search By Name & Country of Origin</h3>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cea7e77d-ac11-43e2-b91a-1a62077ff8ea" alt="FetchByName" width="200" height="400" style="margin-right: 20px;" >
  <img src="https://github.com/user-attachments/assets/abd2d1cb-db1b-4bb9-a5b2-105d17f43ba2" alt="FetchByOrigin" width="200" height="400">
</p>

<!-- VIDS THIRD SET -->
<h3 align="center">Applied Sorting and Refreshable Option</h3>

<p align="center">
  <img src="https://github.com/user-attachments/assets/84392dc0-480e-4448-8f35-98f1e1483f92" alt="FetchSort" width="200" height="400" style="margin-right: 20px;" >
  <img src="https://github.com/user-attachments/assets/446a6ddf-2c95-4690-be72-e467be958741" alt="FetchRefrehable" width="200" height="400">
</p>


<!-- VIDS FOURTH SET -->
<h3 align="center">Handle Missing Youtube URL & Missing Source URL (Malformed Endpoint) </h3>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7d9a56a5-dcdc-45f7-b73e-ee068c673526" alt="FetchMissingSource" width="200" height="400" style="margin-right: 20px;" >
  <img src="https://github.com/user-attachments/assets/f806e1de-8fb0-49c8-9c41-9ffb9f5859de" alt="FetchMissingVid" width="200" height="400">
</p>


### - Contributors
Only Self, Source code can be provided upon request of recruiter or manager

<!-- --------------------------------------------------------------END----------------------------------------------------------------------------------- -->

<!-- GLOBAL WEATHER & MAP-->
# Interactive Weather & Map Explorer – Location-Based iOS App

<!-- APP NAME AND IMAGE HERE -->

<!--
<p align="center">
    <img alt="BOSS CORE DATA" title="APP ANME TITLE" src="<URL OF IMG/GIF PASTED TO GITHUB>" width="300">
  </a>
</p>
-->

<!--
HOW TO:

PASTE SOURCE
![RossIntroGif](https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/b1007a7f-5c5e-450c-a0fa-c5e601940d3b)


HOW TO USE
<img src="<SOURCE URL INSDE the QUOTES>" alt="SF2_4" width="300" height="600">
-->

<!--TOP INTRO GIF IMAGE -->
<p align="center">
<img src="https://github.com/user-attachments/assets/8da41519-6d1e-49df-9760-53db5e0edd68" alt="WeatherMapIntroGif" width="300" height="600">
</p>


</p>

### Summary:
An interactive weather and map exploration app built with SwiftUI and MapKit, allowing users to view real-time weather based on any city they enter. It integrates live data from the OpenWeather API, and dynamically displays an interactive map with search functionality, zoom controls, and multiple view modes. The app also features point-of-interest search (hotels, restaurants, etc.) with detailed location info including address and contact data.
This project showcases a blend of custom UI, API-driven data, and map-based interactivity — combining practical utility with a smooth user experience.

###  Built With:
- SwiftUI: Clean and reactive interface for modern iOS UI.
- OpenWeather API: Retrieves live temperature, humidity, wind, and condition data by city name.
- MapKit + SwiftUI Integration: Displays city location with satellite, hybrid, and standard map modes.
- Custom UI Components: Styled weather displays, toggles for map view modes, and result cards.
- Geocoding & Reverse Geocoding: Converts city names into coordinates and vice versa.
- Asynchronous Networking: Uses async/await and URLSession for clean API integration.
- Searchable Map Points: Supports finding hotels, restaurants, and other landmarks with detail popups.

<!-- ADD IMAGES/GIF FOR INTRO -->

<p align="center">
<img src="https://github.com/user-attachments/assets/8d0ebce0-0931-4b6b-a04a-0e6612186d85" alt="InitialSearchGif" width="200" height="400">
<img src="https://github.com/user-attachments/assets/0c74633d-9bfc-4083-875c-4cb4a811f4f8" alt="MapExplore" width="200" height="400">
<img src="https://github.com/user-attachments/assets/76eb534d-926d-4b33-99be-f482f53538ca" alt="DetailView" width="200" height="400">
</p>

### What It Does:
- Users can search any city by name to:
- View current weather details (condition, temperature, wind, humidity)
- See the location on an interactive map
Supports:
- Zoomable map with pinch gestures
- Toggle between map types: standard, satellite, hybrid
- Local POI search (e.g., "restaurant") with marker pins and info cards
- Updates UI dynamically using SwiftUI’s state system

### Focus Areas:
- Real-World API Integration: Weather data fetched via OpenWeather and parsed live.
- Map-Based Interaction: Combines location-based UI with POI search to enrich user experience.
- Modern iOS Design: Built from the ground up with SwiftUI and Apple’s best practices.
- Asynchronous Networking: Uses Swift Concurrency for clean, maintainable data flows.
- Location Intelligence: Combines geocoding, POI lookup, and map overlays.

<!-- ADD IMAGES/GIFS FOR FEATURES -->
<!--
![Search1](https://github.com/user-attachments/assets/d87a6eff-4b52-4eb3-a690-173638054259)
![Search2](https://github.com/user-attachments/assets/5d3f14b1-8bf8-4e81-b4c8-191649154d83)
![Search3](https://github.com/user-attachments/assets/69a5e158-8bf0-488b-8d55-954bdec06913)

![Explore1](https://github.com/user-attachments/assets/81754f35-14bb-43ab-9fa3-0ef545ec9f23)
![Explore2](https://github.com/user-attachments/assets/b8c3283c-c1d3-4630-b983-7ab18bd09133)
![Explore3](https://github.com/user-attachments/assets/208690fb-09b9-4be1-96dd-b2dd463d7f6d)

![Detail1](https://github.com/user-attachments/assets/37784486-5a01-4155-9e86-8cfbbda19ab4)
![Detail2](https://github.com/user-attachments/assets/570bab68-018c-4f89-90d5-435c7db8f483)
![Detail3](https://github.com/user-attachments/assets/51ae5b36-a570-4023-92b7-050628ca21c7)

-->


<div align="center">
  CITY SEARCH
</div>    

<p align="center">
    <img src="https://github.com/user-attachments/assets/d87a6eff-4b52-4eb3-a690-173638054259" alt="Search1" width="200" height="400">
        <img src="https://github.com/user-attachments/assets/5d3f14b1-8bf8-4e81-b4c8-191649154d83" alt="Search2" width="200" height="400">
         <img src="https://github.com/user-attachments/assets/69a5e158-8bf0-488b-8d55-954bdec06913" alt="Search3" width="200" height="400">
    
</p>

<div align="center">
  EXPLORE MAP
</div> 

<p align="center">
     <img src="https://github.com/user-attachments/assets/81754f35-14bb-43ab-9fa3-0ef545ec9f23" alt="Explore1" width="200" height="400">
        <img src="https://github.com/user-attachments/assets/b8c3283c-c1d3-4630-b983-7ab18bd09133" alt="Explore2" width="200" height="400">
         <img src="https://github.com/user-attachments/assets/208690fb-09b9-4be1-96dd-b2dd463d7f6d" alt="Explore3" width="200" height="400">   

</p>


<div align="center">
  WEATHER DETAIL
</div> 

<p align="center">
     <img src="https://github.com/user-attachments/assets/37784486-5a01-4155-9e86-8cfbbda19ab4" alt="Detail1" width="200" height="400">
        <img src="https://github.com/user-attachments/assets/570bab68-018c-4f89-90d5-435c7db8f483" alt="Detail2" width="200" height="400">
         <img src="https://github.com/user-attachments/assets/51ae5b36-a570-4023-92b7-050628ca21c7" alt="Detail3" width="200" height="400">  
</p>

### - Contributors
Only Self, Source code can be provided upon request of recruiter or manager


<!-- ---------------------------------------------------------END--------------------------------------------------------- -->

<!-- NAME -->
# Rolex Daytona w/ Chronograph Simulator – Precision-Coded Mechanical Watch UI

<!-- APP NAME AND IMAGE HERE -->

<!--
<p align="center">
    <img alt="ROLAEX DAYTONA" title="APP ANME TITLE" src="<URL OF IMG/GIF PASTED TO GITHUB>" width="300">
  </a>
</p>
-->

<!--
HOW TO:

PASTE SOURCE
![RossIntroGif](https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/b1007a7f-5c5e-450c-a0fa-c5e601940d3b)


HOW TO USE
<img src="<SOURCE URL INSDE the QUOTES>" alt="SF2_4" width="300" height="600">
-->

<!--  ![IntroGif](https://github.com/user-attachments/assets/3304f50f-61d2-446d-ab35-314df5ee3570) -->

<!--TOP INTRO GIF IMAGE -->
<p align="center">
<img src="https://github.com/user-attachments/assets/247f1fc4-5e50-42c7-96f3-c9da53c45142" alt="intro" width="300" height="600">
</p>



### Summary:
A fully code-driven, recise mechanical simulation of the Rolex Daytona Caliber 4130 chronograph, engineered entirely in SwiftUI, with working chronograph that starts, stops and snaps back from timer to watch. — with no image assets, no Core Animation, and no external libraries.
Every visible element — from the dial markings and hand shadows to the tick marks and sub-dial numerals — is drawn programmatically using geometric and trigonometric calculations. The chronograph system operates from a *SINGLE-Timer, advancing the second hand through 480 discrete micro-steps per minute to authentically replicate the high-beat motion (28,800 vibrations per hour) of the real 4130 movement.
The chronograph system isn’t static — it fully functions like the real watch, seamlessly entering and exiting chronograph mode and snapping all hands back to zero when reset, just like a genuine mechanical movement.
The result is a pixel-perfect, mechanically faithful chronograph that achieves centisecond-level accuracy in its timer logic, hand synchronization, and tick cadence.
This project demonstrates SwiftUI rendering, math-driven motion control, timer coordination, and code-based visual design, photorealistic mechanical simulation can be achieved purely in SwiftUI.

### Built With:
- SwiftUI: Declarative rendering of all UI components, including the chronograph dial, subdials, and hands.
- Timer-Based Rotation System: Simulates mechanical hand movement using Timer.publish with exact tick intervals.
- Programmatic Drawing: Every tick mark, number, and dial layout was drawn with SwiftUI shapes and geometry — no assets or sprites.
- Math-Driven UI: Circular layout calculations using degrees, trigonometry, and polar coordinate conversions.
- Synchronized Motion: All watch hands run in perfect sync, using a single timing source for realism and performance.
- High-Fidelity Simulation: Models a real chronograph’s behavior, including pause, reset, and lap interactions (if implemented).

<!-- ADD IMAGES/GIF FOR INTRO -->
<p align="center">

</p>
### What It Does:
- Accurately simulates:
    Main chronograph second hand ticking at 480 BPM (beats per minute)
    Subdials for elapsed minutes/hours (if included)
- Smooth and continuous rotation using step-based updates
- Tick marks and dial indicators precisely positioned via trigonometric formulas
- Entire interface runs without image files or third-party libraries
- Layout adapts across screen sizes while maintaining mechanical accuracy

### Focus Areas:
- Mathematical Rendering: All visual elements placed using geometry and trigonometry with high angular precision.
- Mechanical Fidelity: Mimics the real-world Rolex Daytona movement's tick rate and hand behavior.
- Code-Only UI: Every pixel and curve rendered natively with SwiftUI views — zero visual assets used.
- Timer Synchronization: Centralized timing logic drives all hands consistently and efficiently.
- UI Engineering: Combines timing, geometry, and real-world mechanical reference into a working Swift-based chronograph simulator.

<!-- ADD IMAGES/GIFS FOR FEATURES -->
    
<div align="center">
     Enter, Start, Stop, Reset Chrono 
</div> 

<p align="center">
  <img src="https://github.com/user-attachments/assets/475dbb44-4b80-48d5-8e23-678e2aea5b14" alt="EnterStopStartReset" width="200" height="400">
    
</p>

<div align="center">
    ALL CODED TICK MARKS and WATCH FACE , NOT POSTED IMAGES!
</div> 

<p align="center">
   <img src="https://github.com/user-attachments/assets/914d7954-f084-4cc0-989a-a62b788d8129" alt="face1" width="200" height="400">
    <img src="https://github.com/user-attachments/assets/32728b08-a346-4ff3-a095-8c55aba4e44d" alt="face2" width="200" height="400">
    <img src="https://github.com/user-attachments/assets/2a973f2a-70c9-4762-af3e-88af5b00ba2a" alt="face3" width="200" height="400">
</p>

<div align="center">
  CODED HANDS & SUBVIEWS
</div> 

<p align="center">
    <img src="https://github.com/user-attachments/assets/b5020827-39f2-4e67-bc56-2a7cc671058a" alt="web1" width="200" height="400">
    <img src="https://github.com/user-attachments/assets/bb99b9c9-4955-463b-a0ed-c3de4eaf39bc" alt="web2" width="200" height="400">
    <img src="https://github.com/user-attachments/assets/628178ff-8c30-408f-b296-72d219a89f74" alt="web3" width="200" height="400">
</p>

### - Contributors
Only Self, Source code can be provided upon request of recruiter or manager


<!-- ---------------------------------------------------------END--------------------------------------------------------- -->
# AI Weather and Outfit App

<p align="center">
<img src="https://github.com/user-attachments/assets/7f54843e-e06c-4f59-a07b-8639393c725c" alt="WeatherOutfit Sample 1" width="200" height="400"> 
  <img src="https://github.com/user-attachments/assets/d00185fe-88a3-4c03-a381-85473305be26" alt="WeatherOutfit Sample 2" width="200" height="400"> 
</p>

### Summary:
A smart weather-based outfit recommendation app that helps users decide what to wear based on live weather data. Powered by AI, the app personalizes outfit suggestions using the user's **gender**, **age range**, and the **current weather** at their location.  
It combines real-time weather forecasts, natural language outfit suggestions, and curated fashion images — all running securely on Google Cloud with Firebase Authentication.

### Built With:
- **SwiftUI & Async/Await:** Modern, responsive iOS UI built using SwiftUI and Swift Concurrency.
- **OpenWeather API:** Retrieves the latest weather for your current location.
- **OpenAI (ChatGPT API):** AI-generated outfit suggestions tailored to weather, gender, and age.
- **Pexels API:** Visual display of AI-recommended outfits using royalty-free fashion images.
- **Firebase Authentication:** Secure, scalable sign-in system for users.
- **Firebase Secret Manager:** Keeps API keys secure and away from client-side code.
- **Google Cloud Run:** Backend endpoints deployed on a serverless Google Cloud instance, handling all external API calls.
- **Firebase Hosting + Logging:** Backend analytics and logs monitored via Firebase Console and Cloud Logs.

---

### What It Does:
1. Auto-detects your location and current weather.
2. Lets you input age range and select gender or use gender-neutral mode.
3. Generates natural-sounding clothing suggestions using AI.
4. Shows matching outfit photos from Pexels.
5. Allows user authentication (sign in/sign up).
6. Everything runs through a secure backend on Google Cloud.

---

### Focus Areas:
- **User-first design:** Built for clarity and fast decisions — see your weather and your outfit instantly.
- **AI + Weather + Visuals:** Seamlessly combines data, intelligence, and design to solve a real-life daily problem.
- **Security:** API keys are stored in Firebase Secret Manager and never exposed in the app.
- **Scalable Cloud Architecture:** All data fetching is offloaded to Google Cloud Run, improving speed and security.

### Firebase + Google Cloud Integration Proof:
- Video and screenshots available in the `/media` folder showing:
  - Real-time requests logged in Google Cloud Console.
  - API traffic routed through Cloud Run.
  - Firebase Authentication in action.
  - Secure access to API keys using Secret Manager.
 
### Proof of Google Firebase/Cloud Integration Logs 
- Click to Expand -
<p align="center">
  <img src="https://github.com/user-attachments/assets/1499d260-f95a-41c4-b271-68aa9820eaf5" alt="FetchIntro" width="900" height="500"> 
</p>

<!-- --------------------------------------------------------- END --------------------------------------------------------- -->

<!-- NAME BOSS CORE DATA-->
# Boss - Themed To-Do List – Persistent Task Manager App
<!-- APP NAME AND IMAGE HERE -->

<!--
<p align="center">
    <img alt="BOSS CORE DATA" title="APP ANME TITLE" src="<URL OF IMG/GIF PASTED TO GITHUB>" width="300">
  </a>
</p>
-->

<!--
HOW TO:

PASTE SOURCE
![RossIntroGif](https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/b1007a7f-5c5e-450c-a0fa-c5e601940d3b)


HOW TO USE
<img src="<SOURCE URL INSDE the QUOTES>" alt="SF2_4" width="300" height="600">
-->

<!--TOP INTRO GIF IMAGE -->
<p align="center">
<img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/b1007a7f-5c5e-450c-a0fa-c5e601940d3b" alt="RossIntroGif" width="300" height="600">
</p>


</p>
### Summary:
A sleek, gesture-driven to-do list app built with SwiftUI and Core Data, designed to help users manage tasks effortlessly with smooth interactions and stylish UI. Users can create, complete, and delete tasks — with data stored locally for offline use. The app features custom animations, intuitive swipe gestures, and a bold visual theme to make daily planning feel powerful and efficient.
This project showcases local data persistence, gesture handling, and a polished SwiftUI interface designed for real-world usability.

### Built With:
- SwiftUI: Declarative UI for responsive, modern iOS interfaces.
- Core Data: Native Apple framework for local storage and data persistence.
- Gestures: Swipe-to-complete, swipe-to-delete, and tap interactions for task control.
- Smooth Scroll Views: Optimized list navigation and animations for long task lists.
- Custom Animations: Transitions and effects to enhance interactivity and UX.

<!-- ADD IMAGES/GIF FOR INTRO -->

<p align="center">
<img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/eff72844-2e7a-44b8-9109-9000dae88d62" alt="RossGifPart1" width="250" height="500">
<img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/e4ce8c49-80cc-41c4-a21b-d04a739ab08a" alt="RossGifPart2" width="250" height="500">
</p>

### What It Does:
Allows users to:
  - Add new tasks instantly via an input field
  - Swipe to mark tasks as completed
  - Swipe to delete tasks from the list
  - Smooth animated transitions between task states
All data is stored on-device using Core Data, supporting:
  - Offline usage
  - Persistent task history
  - Fast app performance without cloud sync

### Focus Areas:
- Data Persistence: All tasks are saved locally and survive app restarts using Core Data.
- User-Centric Design: Clean layout, large tap targets, and accessible UX.
- Gesture-Driven UI: Designed for fast input and control using common swipe interactions.
- Thematic Styling: Visually bold and consistent design aesthetic inspired by “boss-mode” productivity.
- SwiftUI Mastery: Takes full advantage of state-driven views, binding, and animation.

<!-- ADD IMAGES/GIFS FOR FEATURES -->

<div align="center">
  SWIPE TO ENTER
</div>    

    
<p align="center">
  <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/cc7cf7c5-95b7-49a1-a4b5-2b31ed23c763" alt="Ross_1" width="200" height="400">
    <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/8ae7eb9d-9bdf-49b1-aca4-1db408b1a48c" alt="Ross_3" width="200" height="400">
     <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/8c338440-fd3c-4eac-8b10-9e33f30c0e14" alt="Ross_4" width="200" height="400">
    
</p>

<div align="center">
  CREATE & SAVE TO CORE DATA
</div>    


<p align="center">
    <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/f70ee310-da45-4a85-b8f7-17fadeece46e" alt="Ross_5" width="200" height="400">
    <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/7ce4e371-70d6-4320-93dd-123f17f08d04" alt="Ross_6" width="200" height="400">
    <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/c9183a92-651b-4a38-9b20-8981df855edd" alt="Ross_7" width="200" height="400">
</p>

<div align="center">
  DELETE & REMOVE FROM COREDATA
</div>    


<p align="center">
    <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/cda4061e-f55b-4198-b08e-f03f4527c750" alt="Ross_9" width="200" height="400">
    <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/654bc6e6-7dc8-4aef-aa7c-1a844d573f48" alt="Ross_10" width="200" height="400">
    <img src="https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/7efcfe7e-0d5b-4d41-a9d4-472df9e1cf01" alt="Ross_11" width="200" height="400">
</p>

### - Contributors
Only Self, Source code can be provided upon request of recruiter or manager


<!-- ---------------------------------------------------------END--------------------------------------------------------- -->

<!-- NAME DNN NEWS -->
# DNN - Themed News Reader – Topic-Focused iOS App

<!-- APP NAME AND IMAGE HERE -->

<!--
<p align="center">
    <img alt="BOSS CORE DATA" title="APP ANME TITLE" src="<URL OF IMG/GIF PASTED TO GITHUB>" width="300">
  </a>
</p>
-->

<!--
HOW TO:

PASTE SOURCE
![RossIntroGif](https://github.com/RMTrasmont/FuckingGitHubTest/assets/25352404/b1007a7f-5c5e-450c-a0fa-c5e601940d3b)


HOW TO USE
<img src="<SOURCE URL INSDE the QUOTES>" alt="SF2_4" width="300" height="600">
-->

<!-- IMAGE SOURCE
![DNNIntrogif](https://github.com/user-attachments/assets/64928b84-a0dd-4fc4-a25e-f3beed6623a1) 
-->
<!--TOP INTRO GIF IMAGE -->
<p align="center">
<img src="https://github.com/user-attachments/assets/64928b84-a0dd-4fc4-a25e-f3beed6623a1" alt="DNNIntrogif" width="300" height="600">
</p>


</p>
### Summary:
A clean and focused news-reading app built with SwiftUI, designed to fetch and display the top 100 articles from NewsAPI.org based on a specific topic. The app presents articles in a scrollable, date-ordered list with headlines and brief summaries. Users can tap on any entry to view extended details and open the full article in a WebView — all wrapped in a smooth, intuitive reading experience.
This project demonstrates strong skills in API integration, async networking, dynamic data presentation, and embedded web content handling in iOS apps.

### Built With:
- SwiftUI: Lightweight, modern interface for a seamless reading experience.
- NewsAPI.org: Fetches the latest 100 topic-specific news articles via RESTful API.
- Async Networking: Swift Concurrency (async/await) for efficient data fetching.
- WebView Integration: Opens full articles in an in-app browser using SafariViewController.
- List & Navigation Views: Tap-to-expand interface from summary to full article with dynamic view transitions.

<!-- ADD IMAGES/GIF FOR INTRO -->
<!-- IMAGE SOURCE
![Front](https://github.com/user-attachments/assets/7ac630f0-f449-4b48-aa14-8749af5e7afd)
![News](https://github.com/user-attachments/assets/4199f122-1db5-4ef9-9418-014f33ddc1d6)
![Web](https://github.com/user-attachments/assets/c2991708-e97d-4a05-a7f5-444e2c1f999b)
-->

<p align="center">
    <img src="https://github.com/user-attachments/assets/7ac630f0-f449-4b48-aa14-8749af5e7afd" alt="Front" width="250" height="500">
        <img src="https://github.com/user-attachments/assets/4199f122-1db5-4ef9-9418-014f33ddc1d6" alt="News" width="250" height="500">
            <img src="https://github.com/user-attachments/assets/c2991708-e97d-4a05-a7f5-444e2c1f999b" alt="Web" width="250" height="500">
</p>

### What It Does:
- Automatically fetches top 100 articles on a chosen topic.
Displays:
  - Headline
  - Publication date
  - A rticle summary or excerpt
Tapping an article:
  - Opens a detailed view with extended text
  - Includes a button to open the full article in a WebView
Supports light/dark mode and responsive layout scaling

### Focus Areas:
- Clean UI & UX: Prioritizes readability, simplicity, and minimal distraction.
- Live News Integration: Demonstrates ability to work with real-world APIs and live content.
- Efficient Data Handling: Uses async/await for responsive and modern networking.
- Smooth Navigation: Tap-to-detail transitions built entirely in SwiftUI.
- Web Integration: Embeds full article access without leaving the app.

<!-- ADD IMAGES/GIFS FOR FEATURES -->

<div align="center">
     INTRO
</div> 

<p align="center">
  <img src="https://github.com/user-attachments/assets/40f04b8a-ceb1-43a4-ad30-0b6e9a4db1c0" alt="intro" width="200" height="400">
    
</p>

<div align="center">
     NEWS RESULTS 
</div> 

<p align="center">
   <img src="https://github.com/user-attachments/assets/688b2b25-db4a-4dc9-a2d0-53c6022066c6" alt="results1" width="200" height="400">
    <img src="https://github.com/user-attachments/assets/4ef1ba0f-8027-4739-b919-f8e147c9a786" alt="results2" width="200" height="400">
    <img src="https://github.com/user-attachments/assets/86832596-32d2-4af2-90c5-371aef3c939e" alt="results3" width="200" height="400">
</p>

<div align="center">
    SUMMARY & FULL ARTICLE 
</div> 


<p align="center">
    <img src="https://github.com/user-attachments/assets/ece5e24d-eae7-42ec-baf6-7037866b388b" alt="web1" width="200" height="400">
    <img src="https://github.com/user-attachments/assets/f431ca2a-c371-46e7-a778-6cc03689adbe" alt="web2" width="200" height="400">
    <img src="https://github.com/user-attachments/assets/4eb90727-6fd2-4e4f-9567-199b35321802" alt="web3" width="200" height="400">
</p>

### - Contributors
Only Self, Source code can be provided upon request of recruiter or manager


<!-- ---------------------------------------------------------END--------------------------------------------------------- -->



<!-- ---------------------------------------------------------END--------------------------------------------------------- -->
   

