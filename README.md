# Weather-Application
INTRODUCTION 

1.1 Project Overview 
       The Weather App is an Android application developed in Kotlin that provides real-time 
      weather updates based on the user's current location. It leverages the OpenWeatherMap 
      API to fetch temperature, location, and basic weather conditions, displaying them in a clean 
      and intuitive interface. 
1.2 Motivation & Purpose 
    • Problem Statement: Many weather apps are either too complex, loaded with ads, or 
       require unnecessary permissions. 
    • Solution: A lightweight, privacy-conscious weather app that shows only essential 
       weather data with minimal permissions. 
    • Target Audience: General users who need quick weather updates without excessive 
       features. 
1.3 Key Statistics & Facts 
    • API Used: OpenWeatherMap (Free Tier: 60 calls/minute, 1,000,000 calls/month) 
    • Location Accuracy: Uses FusedLocationProviderClient (Google Play Services) for 
      high-precision GPS/data-based location. 
    • Response Time: Typically under 1-2 seconds for weather data retrieval. 
    • App Size: ~5-8 MB (Lightweight, no bloatware). 
    
2. Problem Description
   
2.1 Existing Challenges in Weather Apps 
     1. Over-Permissioning: Many apps request unnecessary permissions (contacts, storage, 
        etc.). 
     2. Slow Performance: Heavy apps with ads and animations lead to slow loading. 
     3. Lack of Offline Support: Most apps fail to work without an internet connection. 
     4. Privacy Concerns: Some apps track user location even when not in use. 
2.2 Technical Challenges Faced 
    1. Location Permission Handling: 
       o Android requires runtime permissions for location access (API 23+). 
       o Had to implement checkSelfPermission() and requestPermissions(). 
    2. API Integration Issues: 
       o OpenWeatherMap API required proper error handling for network failures. 
       o API key security was a concern (initially hardcoded). 
    3. Google Services Dependency: 
      o Initially faced build errors due to missing google-services.json (fixed by 
       removing unnecessary Firebase dependencies). 




✅ Proper permission handling (Android runtime permissions) 
✅ Minimalistic & functional UI 
Future Scope: 
• Add notifications for severe weather alerts. 
• Implement Dark Mode for better usability.
